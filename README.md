
## Cara menambahkan user di website laporan teknomedika
pertama buka visual studio code dan arahkan folder ke folder testo yang 
ada di folder C:/Xampp/Htdocs/testo

1.buka file datalap_op.php yang ada di folder component

```html
		  $status_ardif = mysqli_query($conn,"SELECT * FROM daily_report_op where DAYOFYEAR(timestamp)=$dayofyear && user_name='Ardif' ");
		  if (mysqli_num_rows($status_ardif) > 0) {
			// output data of each row
			$stat_ardif = '<label class="badge badge-success">Sudah Melapor</label>';
		   } else {
			$stat_ardif = '<label class="badge badge-danger">Belum Melapor</label>';
		   }

``` 

ini ada di baris 138

tinggal ganti nama contoh disini menggunakan nama ardif tinggal copy paste code diatas lalu ganti nama sesuai 
nama operator baru.di bawah code yang sudah ada.jangan lupa perhatikan huruf besar,pastikan sama dengan yang ada di atas !

```html
	["15", "Ardif", $stat_ardif, "<a href='form.html'>kirim laporan</a>"],
```
lalu tambah code disini ganti no urutnya dan namanya 

ini ada di baris 166

2.buka form.html yang ada di folder conn 

lalu copy paste kan code ini dan ganti namanya 

``` 
<option value="Ardif">Ardif

```

ini ada di baris 100

