<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">

    <title>Virus Covid-19!</title>
  </head>
  <body>

    <div class="jumbotron jumbotron-fluid bg-dark text-white">
      <div class="container text center">
        <div class="dropdown">
          <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
             Menu
             </button>
              <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <li><a class="dropdown-item" href="index.php">DKI Jakarta</a></li>
              <li><a class="dropdown-item" href="jabar.php">Jawa Barat</a></li>
              <li><a class="dropdown-item" href="banten.php">Banten</a></li>
              <li><a class="dropdown-item" href="jateng.php">Jawa Tengah</a></li>
               </ul>

        <h1 class="display-4">Data Pemantaun Covid19 Wilayah Banten</h1>

        </p>
        <p>Tanggal/Waktu: <span id="tanggalwaktu"></span></p>
          <script>
           var dt = new Date();
             document.getElementById("tanggalwaktu").innerHTML = dt.toLocaleString();
          </script>

          <p class="lead">
               <br>Imam Sholikhin
               <br>181011402902
          </p>


          </div>
      </div>
    </div>

    <table class="table table-dark table-striped">
  <thead>
    <tr>
      <th scope="col">No</th>
      <th scope="col">Positif</th>
      <th scope="col">Di rawat</th>
      <th scope="col">Sembuh</th>
      <th scope="col">Meninggal</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>47.491</td>
      <td>1.478</td>
      <td>44.800</td>
      <td>1.213</td>
    </tr>

  </tbody>
</table>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>

  </body>
</html>
