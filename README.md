<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Latest compiled and minified CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Codo a Codo</a>
        <button class="navbar-toggler" type="button" dagitta-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Inicio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">

              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Desactivado</a>
            </li>
          </ul>
          <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Buscar</button>
          </form>
        </div>
      </div>
    </nav>
  </header>
  <main class="container-fluid">
    <section>
        <div class="row">
            <!-- CARDS -->
                <div class="card px-2 col-4">
                    <img src= "img\imgHTML.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">titulo 1</h5>
                      <p class="card-text">Contenido de card</p>
                      <p class="card-text"><small class="text-muted">Ultima actualizacion 1</small></p>
                    </div>
                  </div>
                  <div class="card p-0 col-4">
                    <img src="img\imgCSS.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">titulo 2</h5>
                      <p class="card-text">Contenido de card</p>
                      <p class="card-text"><small class="text-muted">Ultima actualizacion 1</small></p>
                    </div>
                  </div>
                  <div class="card p-0 col-4">
                    <img src="img\imgBOOTSTRAP.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">titulo 3</h5>
                      <p class="card-text">Contenido de card</p>
                      <p class="card-text"><small class="text-muted">Ultima actualizacion 1</small></p>
                    </div>
                  
            </div>
            <!-- FORM -->
            <form>
                <div class="mb-3">
                  <label for="exampleInputEmail1" class="form-label">Email</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                  <div id="emailHelp" class="form-text">Nunca comparta su email.</div>
                </div>
                <div class="mb-3">
                  <label for="exampleInputPassword1" class="form-label">Contraseña</label>
                  <input type="password" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="mb-3 form-check">
                  <input type="checkbox" class="form-check-input" id="exampleCheck1">
                  <label class="form-check-label" for="exampleCheck1">Verificar</label>
                </div>
                <button type="submit" class="btn btn-primary">Enviar</button>
              </form>
        
    </div></section>


</main>
<!-- Latest compiled JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>