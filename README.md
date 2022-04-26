<!DOCTYPE html>

<head>

<meta charset="utf-8">
<meta name="viewport" content="width=device-width">
<title>Actividad practica 1</title>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

</head>

<body>
<header>
    <nav class="navbar navbar-expand-sm bg-light navbar-light">
        <div class="container-fluid">
            <span class="navbar-brand">Codo a Codo</span>
            <ul class="navbar-nav me-auto">
            <li class="nav-item">
              <a class="nav-link active" href="#">Inicio</a>
            </li>
           <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" href="#">Desactivado</a>
            </li>
          </ul>
         <form class="d-flex">
          <input class="form-control me-2" type="text" placeholder="Buscar">
    <button class="btn btn-primary bg-light text-success border-success" type="button">Buscar</button>
         </form>
        </div>
    </nav>


</header>

<main>
<div class="card-group mt-2">
    <div class="card" style="width:400px">
        <img class="card-img-top" src="logo html.png" alt="Card image" style="width:50%">
        <div class="card-body">
          <h4 class="card-title">Titulo 1</h4>
          <p class="card-text">Contenido de card</p>
          <a class="nav-link disabled" href="#">Ultima actualizacion 1</a>
        </div>
      </div>

      <div class="card" style="width:400px">
        <img class="card-img-top" src="logo css.png" alt="Card image" style="width:50%">
        <div class="card-body">
          <h4 class="card-title">Titulo 2</h4>
          <p class="card-text">Contenido de card</p>
          <a class="nav-link disabled" href="#">Ultima actualizacion 2</a>
        </div>
      </div>

      <div class="card" style="width:400px">
        <img class="card-img-top" src="logo bootstrap.png" alt="Card image" style="width:50%">
        <div class="card-body">
          <h4 class="card-title">Titulo 3</h4>
          <p class="card-text">Contenido de card</p>
          <a class="nav-link disabled" href="#">Ultima actualizacion 3</a>
        </div>
      </div>
      </div>

      <form action="/action_page.php">
        <div class="mb-3 mt-3">
          <label for="email" class="form-label">Mail</label>
          <input type="email" class="form-control" id="email" name="email">
          <input type="text" class="form-control-plaintext" placeholder="Nunca completa su email">
        </div>
        <div class="mb-3">
          <label for="pwd" class="form-label">Contraseña</label>
          <input type="password" class="form-control" id="pwd" name="pswd">
        </div>
        <div class="form-check mb-3">
          <label class="form-check-label">
            <input class="form-check-input" type="checkbox" name="remember"> Verificar
          </label>
        </div>
        <button type="submit" class="btn btn-primary">Enviar</button>
      </form>



</main>
</body>
</html>
