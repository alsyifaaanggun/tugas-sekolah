<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">

    <title>mcdonald's</title>
    <style>
         .jumbotron{
            height: 600px;
            background-color: rgb(255, 196, 0);
            background-repeat: no-repeat;
            background-size: cover;
            background-position:-100%;
            padding-top: 170px;

        }
          
          header h1 {
            float: right;
	          padding:0px 0;	
	          color: red;
          } 
        
        </style>
  </head>
  <body>
    <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <header>
          <div class="container">
              <h1><a>McDonald's</a></h1>
          </div>
      </header>
        <ul class="navbar-nav">
          <li class="nav-hitam active">
            <a class="nav-link" href="#ourmenu">MCDONALD</a>    
          </li>
          <li class="nav-hitam active">
            <a class="nav-link" href="#menu">McCafe'</a>
          </li> 
          <li class="nav-hitam active">
            <a class="nav-link" href="#Form1">Pemesanan</a>
          </li>
          <li class="nav-hitam active">
            <a class="nav-link" href="#Form2">Transaksi</a>
          </li>  
        </ul>
      </div>
    </nav>
    <div class="jumbotron text-center text-white">
  <h1 class="display-4 text-white">MCDONALD'S</h1>
  <p class="lead"></p>
  <hr class="my-4">
  <p> </p>
  <a class="btn btn-outline-primary rounded-pill btn-lg" href="#" role="button">Learn more</a>
</div>



<div class="card-deck">
  <div class="card">
    <img src="https://www.mcdonalds.com/is/image/content/dam/usa/nfl/nutrition/items/regular/desktop/t-mcdonalds-Big-Mac.jpg?$Category_Desktop$" class="card-img-top" alt="..." height="250px">
    <div class="card-body">
      <h5 class="card-title">Big Mac</h5>
      <p class="card-text">15.000</p>
    </div>
  </div>
  <div class="card">
    <img src="https://www.mcdonalds.com/is/image/content/dam/usa/nfl/assets/meal/desktop/h-mcdonalds-Double-Quarter-Pounder-with-Cheese-Extra-Value-Meals.jpg?$Product_Desktop$" class="card-img-top" alt="..." height="150px">
    <div class="card-body">
      <h5 class="card-title">Double Quarter Pounder®* with Cheese Meal</h5>
      <p class="card-text">30.000</p>
    </div>
  </div>
  <div class="card">
    <img src="https://www.mcdonalds.com/is/image/content/dam/usa/nfl/nutrition/items/regular/desktop/t-mcdonalds-Premium-Roast-Iced-Coffee-Medium.jpg?$Category_Desktop$" class="card-img-top" alt="..." height="250px">
    <div class="card-body">
      <h5 class="card-title">Iced t mcdonalds Premium Roast Iced Coffee Medium</h5>
      <p class="card-text">10.000</p>
    </div>
  </div>
  <div class="card">
    <img src="https://www.mcdonalds.com/is/image/content/dam/usa/nfl/nutrition/items/iconic/desktop/t-mcdonalds-fries-small.jpg?$Category_Desktop$" class="card-img-top" alt="..." height="250px">
    <div class="card-body">
      <h5 class="card-title">mcdonalds fries small</h5>
      <p class="card-text">5.000</p>
   </div>
</div>
<div class="card">
  <img src="https://www.mcdonalds.com/is/image/content/dam/usa/nfl/nutrition/items/regular/desktop/h-mcdonalds-Premium-Crispy-Chicken-Classic-Extra-Value-Meals.jpg?$Category_Desktop$" class="card-img-top" alt="..." height="250px">
  <div class="card-body">
    <h5 class="card-title">mcdonalds Premium Crispy Chicken Classic Extra Value Meals</h5>
    <p class="card-text">50.000</p>
  </div>
   
  </div>
</div>
  

    </div>

    
  </div>
     
     
      <!-- BAG INPUT! -->
     <div class="col-sm">
      <div class="card text-white">
          <h5 class="card-header bg-dark"><center>Form Pemesanan</center></h5>
          <div class="card-body">
              <div class="shadow-sm p-3 mb-7 bg-light rounded" style="float: left; margin-left: 5px; width: 500px;">
                  <table class="table table-borderless">

                      <tr>
                          <td>Nama Pembeli:</td>
                          <td><input class="form-control" type="text" name="inputnama" placeholder="Masukkan Nama Anda"></td>
                      </tr>

                      <tr>
                          <td>Pesanan:</td>
                          <td><input class="form-control" type="text" name="inputmenu" placeholder="">
                          </td>
                      </tr>

                      <tr>
                          <td>Harga Produk:</td>
                          <td><input class="form-control" type="text" name="inputharga">
                          </td>
                      </tr>

                      <tr>
                          <td>Jumlah Produk:</td>
                          <td><input class="form-control" type="number" name="inputjumlah" placeholder="Masukkan Angka">
                          </td>
                      </tr>

                      <td colspan="2">
                          <input type="button" class="form-control btn-outline-dark" value="Konfirmasi"
                          onclick="hitungtotal()">
                      </td>

                      <tr>
                          <td>Bayar:</td>
                          <td><input class="form-control" type="text" name="inputbayar" placeholder="Nominal Uang"></td>
                      </tr>

                      <td colspan="2">
                          <input class="form-control btn-outline-dark" type="button" value="Bayar"
                          onclick="hitungsisauang()">
                      </td>

                      <tr>
                          <td><label>Kembali:</label></td>
                          <td><input class="form-control" type="text" name="inputkembali">
                          </td>
                      </tr>

                      <tr>
                          <td colspan="2">
                              <div class="row">
                                  <div class="col-sm">
                                      <input class="form-control btn-outline-success" type="button"
                                          value="Beli" onclick="simpan()"><br>
                                  </div>
                                  <div class="col-sm">
                                      <input class="form-control btn-outline-danger" type="reset"
                                          value="Batal">
                                  </div>
                              </div>
                          </td>
                      </tr>
                  </table>
              </div>
          </div>
      </div>
  </div>
    
  <!-- BAG OUTPUT! -->
  <div class="col-sm">
    <div class="card text-white">
        <h5 class="card-header bg-dark"><center>Form Transaksi</center></h5>
        <div class="card-body">
            <div class="shadow-sm p-2 mb-7 bg-light rounded" style="float: left; margin-left: 45px; width: 400px;">
                <table class="table table-borderless">
                    <tr>
                        <td>Nama Pembeli</td>
                        <td><input class="form-control" type="text" name="onama"></td>
                    </tr>

                    <tr>
                        <td>Menu</td>
                        <td><input class="form-control" type="text" name="omenu"></td>
                    </tr>

                    <tr>
                        <td>Jumlah Pemesanan</td>
                        <td><input class="form-control" type="text" name="ojumlah"></td>
                    </tr>

                    <tr>
                        <td>Total</td>
                        <td><input class="form-control" type="text" name="ototal"></td>
                    </tr>

                    <tr>
                        <td>Dibayar</td>
                        <td><input class="form-control" type="text" name="odibayar"></td>
                    </tr>

                    <tr>
                        <td>Kembali</td>
                        <td><input class="form-control" type="text" name="okembali"></td>
                    </tr>
                </table>
            </div>
        </div>
    </div>
</div>

<div class="col-sm">
  <div class="card text-white">
      <h5 class="card-header bg-dark"><center>Form Konfirmasi</center></h5>
      <div class="card-body">
          <div class="shadow-sm p-2 mb-7 bg-light rounded" style="float: left; margin-left: 45px; width: 980px;">
              <table class="table table-borderless">
                  <div class="form-group row ">
                      <label for="namaa" class="col-sm-2 col-form-label">Nama Pembeli</label>
                      <div class="col-sm-4">
                        <input type="text" class="form-control" id="nama" placeholder="Masukkan Nama Pembeli" style="width: 350px;">
                      </div>
                  </div>
                  <div class="form-group row">
                      <label for="modell" class="col-sm-2 col-form-label">Pesanan</label>
                      <div class="col-sm-3">
                        <select class="form-control mb-4" id="model">
                          <option selected>Pilih Menu</option>
                          <option value="Big Mac">Big Mac</option>
                          <option value="Double Quarter Pounder®* with Cheese Meal">Double Quarter Pounder®* with Cheese Meal</option>
                          <option value="Iced t mcdonalds Premium Roast Iced Coffee Medium">Iced t mcdonalds Premium Roast Iced Coffee Medium</option>
                          <option value="mcdonalds fries small">mcdonalds fries small</option>
                          <option value="mcdonalds Premium Crispy Chicken Classic Extra Value Meals">mcdonalds Premium Crispy Chicken Classic Extra Value Meals</option>
                        </select>
                      </div>
                </div>
                  <div class="form-group row ">
                      <label for="jumlahh" class="col-sm-2 col-form-label">Jumlah Pelanggan</label>
                      <div class="col-sm-4">
                        <input type="number" class="form-control" id="jumlah" placeholder="Masukkan Jumlah Pemesanan" style="width: 350px;">
                      </div>
                  </div>
                  <form name="hitung diskon" method="POST">
                  <div class="form-group row ">
                      <label for="totall" class="col-sm-2 col-form-label">Total</label>
                      <div class="col-sm-4">
                        <input type="number" class="form-control" id="total" name="total" placeholder="Masukkan Total" style="width: 350px;">
                      </div>
                  </div>
                  <div class="form-group row ">
                      <label for="dibayarr" class="col-sm-2 col-form-label">Dibayar</label>
                      <div class="col-sm-4">
                        <input type="number" class="form-control" id="dibayar" name="dibayar" placeholder="Masukkan Nominal Uang" style="width: 350px;">
                      </div>
                  </div>
                  
                  <div class="form-group row mt-3">
                      <label for="tanggall" class="col-sm-2 col-form-label">Tanggal Pembelian</label>
                      <div class="col-sm-4">
                        <input type="date" class="form-control" id="tanggal" name="tanggal" style="width: 350px;">
                      </div>
                  </div>
                  </form>
                  <button type="button" class="btn btn-outline-success" style="margin-left: 125px; margin-top: 20px;" onclick="add()">Pesan</button>
                </div>
              </table>
          </div>
        </div>
      </div><br><br>
      <br id="Form2">

<br id="Hasil">
<div class="container rounded" style="width: 100%; text-align: center;" > 
  <table class="table table-bordered mt-4" >
    <thead class="table-dark">
      <tr class="bg-dark text-white">
        <th scope="col">Nama Pembeli</th>
        <th scope="col">Pesanan</th>
        <th scope="col">Harga Produk</th>
        <th scope="col">Jumlah Produk</th>
        <th scope="col">Diskon</th>
        <th scope="col">Total Harga</th>
        <th scope="col">Jumlah Bayar</th>
        <th scope="col">Kembali</th>
      </tr>
    </thead>
    <tbody id="tampildata">
     
    </tbody>
  </table>
</div>


      


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  
 </form>



    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </body>
</html>
