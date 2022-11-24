


<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>Form lap_harian</title>
  <!-- plugins:css -->
  <link rel="stylesheet" href="../makeup/vendors/feather/feather.css">
  <link rel="stylesheet" href="../makeup/vendors/ti-icons/css/themify-icons.css">
  <link rel="stylesheet" href="../makeup/vendors/css/vendor.bundle.base.css">
  <!-- endinject -->
  <!-- Plugin css for this page -->
  <link rel="stylesheet" href="../makeup/vendors/ti-icons/css/themify-icons.css">
  <!-- End plugin css for this page -->
  <!-- inject:css -->
  <link rel="stylesheet" href="../makeup/css/vertical-layout-light/style.css">
  <!-- endinject -->
  <link rel="shortcut icon" href="images/favicon.png" />
</head>
<body>
  <div class="container-scroller">
    <!-- partial:partials/_navbar.html -->
    <!-- partial:partials/_navbar.html -->
<nav class="navbar col-lg-12 col-12 p-0 fixed-top d-flex flex-row">
  <div class="text-center navbar-brand-wrapper d-flex align-items-center justify-content-center">
    <a class="navbar-brand brand-logo mr-5" href="../index.php"> Teknomedika</a>
  </div>
  <div class="navbar-menu-wrapper d-flex align-items-center justify-content-end">
    <button class="navbar-toggler navbar-toggler align-self-center" type="button" data-toggle="minimize">
      <span class="icon-menu"></span>
    </button>
    
    <ul class="navbar-nav navbar-nav-right">
      
    </ul>
    <button class="navbar-toggler navbar-toggler-right d-lg-none align-self-center" type="button" data-toggle="offcanvas">
      <span class="icon-menu"></span>
    </button>
  </div>
</nav>
<!-- partial -->
<div class="container-fluid page-body-wrapper">
  <!-- partial:partials/_settings-panel.html -->
        <!-- partial:partials/_sidebar.html -->
  <nav class="sidebar sidebar-offcanvas" id="sidebar">
    <ul class="nav">
      <li class="nav-item">
        <a class="nav-link" href="../index.php">
          <i class="icon-grid menu-icon"></i>
          <span class="menu-title">Dashboard</span>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="../lap_op.php">
        <i class="ti-comment-alt menu-icon"></i>
        <span class="menu-title">Laporan harian OP</span>
        </a>
      </li>
      
      </nav>
         
      

          
      <div class="main-panel">
        <div class="content-wrapper">
          <div class="row">
            <div class="col-12 grid-margin stretch-card">
                <div class="card">
                  <div class="card-body">
                    <h4 class="card-title">Form laporan real produksi</h4>
                    <p class="card-description">
                      form laporan real produksi
                    </p>
                    <form class="forms-sample" action="kirim_lap_harian_op.php" method="POST" name="form-input-data">
                      <div class="form-group">
                        <div class="form-group">
                            <label for="exampleSelectGender">Nama operator</label>
                              <select  name="nama" class="form-control">
                                <option value="">- Pilih nama -
                                    <option value="Aditya">Aditya
                                    <option value="Annisa">Annisa
                                    <option value="Arya">Arya
                                    <option value="Dayat">Dayat
                                    <option value="Ichsan">Ichsan
                                    <option value="Alfian">Alfian
                                    <option value="Brians">Brians

                                      <option value="Prima">Prima
                                        <option value="Fajar">Fajar
                                        <option value="Sendy">Sendy
                                        <option value="Sandi">Sandi
                                          <option value="Baron">Baron
                                            <option value="Erico">Erico
                                            <option value="Gathan">Gathan
                                            <option value="Ardif">Ardif


                
                              </select>
                            </div>
                      </div>
                      <div class="form-group">
                        <div class="form-group">
                            <label for="exampleSelectGender">stasiun/mesin</label>
                              <select class="form-control"  name="machine_id">
                                <option value="">- Pilih sta/msn -
                                    <option value="Mesin 1a">Mesin 1a
                                    <option value="Mesin 2a">Mesin 2a
                                    <option value="Station 3a">Station 3a
                                    <option value="Mesin 3b">Mesin 3b
                                    <option value="Mesin 4a">Mesin 4a
                                    <option value="Mesin 4b">Mesin 4b
                                    <option value="Mesin 5a">Mesin 5a
                                    <option value="Mesin 5b">Mesin 5b
                                    <option value="Mesin 5c">Mesin 5c
                                    <option value="Mesin 5d">Mesin 5d
                                    <option value="Mesin 6a">Mesin 6a
                                    <option value="Mesin 7">Mesin 7					
                                    <option value="Mesin 10">Mesin 10	
                                    <option value="Lain-lain">Lain-lain
                              </select>
                            </div>
                      </div>

                      <div class="alert alert-warning alert-dismissible fade show" role="alert">
                        Untuk<strong> Jenis produk</strong> Bisa di kosongi untuk Mesin 1
                        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                          <span aria-hidden="true">&times;</span>
                        </button>
                      </div>


                      <div class="form-group">
                        <p>Jenis Produk</p>
                        <td>
                          <input type="radio" id="N_95" name="product_type" value="N95">
                          <label for="N_95">N95</label><br>
                          <input type="radio" id="FFP_2" name="product_type" value="FFP2">
                          <label for="FFP_2">FFP2</label><br>
                          <input type="radio" id="putih" name="product_type" value="tali putih">
                          <label for="putih">Tali putih</label><br>
                          <input type="radio" id="biru" name="product_type" value="tali biru">
                          <label for="biru">Tali biru</label><br>
                              </td>

                      </div>
                      <div class="form-group">
                        <label for="exampleInputPassword4">jumlah produk ok</label>
                        <input  class="form-control" name="product_ok">
                      </div>
                      
                      <div class="form-group">
                        <label for="exampleInputPassword4">jumlah produk reject</label>
                        <input  class="form-control" name="product_reject">
                      </div>
                      <div class="form-group">
                        <label for="exampleTextarea1">keterangan</label>
                        <textarea class="form-control" name="remark" rows="4"></textarea>
                      </div>

                        <input type="submit" class="btn btn-primary" name="Submit" value="Submit">
                      <button class="btn btn-light">Cancel</button>
                    </form>
                  </div>
                </div>
              </div>
            
          </div>
        </div>
        <!-- content-wrapper ends -->
        <!-- partial:../../partials/_footer.html -->
        <footer class="footer">
          <div class="d-sm-flex justify-content-center justify-content-sm-between">
            <span class="text-muted text-center text-sm-left d-block d-sm-inline-block"><a href="https://www.teknomedika.com/" target="_blank">Teknomedika.</span>
            <span class="float-none float-sm-right d-block mt-1 mt-sm-0 text-center">made by @aditrachman23<i class="ti-heart text-danger ml-1"></i></span>
          </div>
        </footer>
        <!-- partial -->
      </div>
      <!-- main-panel ends -->
    </div>   
    <!-- page-body-wrapper ends -->
  </div>
  <!-- container-scroller -->

    <!-- plugins:js -->
    <script src="../makeup/vendors/js/vendor.bundle.base.js"></script>
  <!-- endinject -->
  <!-- Plugin js for this page -->
  <script src="../makeup/vendors/chart.js/Chart.min.js"></script>
  <script src="../makeup/vendors/datatables.net/jquery.dataTables.js"></script>
  <script src="../makeup/vendors/datatables.net-bs4/dataTables.bootstrap4.js"></script>
  <script src="../makeup/js/off-canvas.js"></script>
  <script src="../makeup/js/hoverable-collapse.js"></script>
  <script src="../makeup/js/template.js"></script>
  <script src="../makeup/js/settings.js"></script>
  <script src="../makeup/js/todolist.js"></script>
</body>

</html>
