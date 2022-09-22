<style>

  nav ul {
    list-style: none;
    overflow: hidden; /* Limpiamos errores de float */
  }
  
  nav ul li {
    float: left;
    font-family: Arial, sans-serif;
    font-size: 16px;
  }
  
  nav ul li a {
    display: block; /* Convertimos los elementos a en elementos bloque para manipular el padding */
    padding: 20px;
    color: black;
    text-decoration: none;
  }
  
  
  h1{
    text-align: center;
  }

  /* footer */
  
  .footer-style {
      padding-top: 50px;
      background-color: #2C3E50;
  }
  footer {
    color: white;
  }
  footer h3 {
    margin-bottom: 30px;
      font-weight: 800;
  }
  footer .footer-above {
    padding-top: 50px;
    background-color: #2C3E50;
  }
  footer .footer-col {
    margin-bottom: 50px;
  }
  footer .footer-below {
    padding: 25px 0;
    background-color: #233140;
  }
  
  </style>
  
<template>
  <!-- Required meta tags -->
  <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <link rel="stylesheet" href="assets/base.css">

  <head>
      <!-- Required meta tags -->
    

  </head>
  <body>
  <div>
    <header>
      <nav>
          <ul class="nav justify-content-center">
            <li><a href="https://pide.burgerking.com.mx">FASTFOOD</a></li>
            <li><a href="#">Citlally Itel Carrrera Sanchez 4A</a></li>
            <li><a href="#">Bebidas</a></li>
            <li><a href="#">Hamburguesas</a></li>
            <li><a href="#">Tacos</a></li>
          </ul>
        </nav>
    </header>
  </div>
  <hr>
  <div>
    <h1>COMIDA RAPIDA</h1><br><br>
    
  </div>
  <div>
    
    <div class="card-deck">
  <div class="card">
    <card url="https://img.freepik.com/foto-gratis/papa-fresca-frita-salsa_144627-5503.jpg?size=626&ext=jpg&ga=GA1.2.1370031169.1661046267" nombre="Papas" />
    <div class="card-body">
      <h5 class="card-title">Descripcion</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    </div>
   
  </div>
  <div class="card">
    <card url="https://assets.stickpng.com/images/580b57fcd9996e24bc43c1b7.png" nombre="Hot Dogs" />
    <div class="card-body">
      <h5 class="card-title">Descripcion</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
    </div>
    
  </div>
  <div class="card">
    <card url="https://img.freepik.com/foto-gratis/pizza-hawaiana_1203-2455.jpg?size=626&ext=jpg&ga=GA1.2.1370031169.1661046267" nombre="Pizza hawaiana" /> 
    
    
    <div class="card-body">
      <h5 class="card-title">Descripcion</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>  
  </div>
  <br><br><hr><br><br><br><br><br><br>
  
  <div class="card-deck">
  <div class="card">
    <card url="https://img.freepik.com/vector-gratis/dibujado-mano-ilustracion-michelada-fresca_23-2149205755.jpg?size=338&ext=jpg&ga=GA1.2.1370031169.1661046267" nombre="Bebidas" />
    <div class="card-body">
      <h5 class="card-title">Descripcion</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    </div>
   
  </div>
  <div class="card">
    <card url="https://i.pinimg.com/originals/ef/4a/4a/ef4a4a551b83ee26dbfe2bafe3e34699.png" nombre="Hamburguesas" />
    <div class="card-body">
      <h5 class="card-title">Descripcion</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
    </div>
    
  </div>
  <div class="card">
    <card url="https://img.freepik.com/vector-gratis/acuarela-deliciosa-ilustracion-pozole_23-2149189983.jpg?w=740&t=st=1663642195~exp=1663642795~hmac=dc2f7801238bde0bb3c4345abf8a27f58d4167640d75fdf6b1d4eabdc91e6eba" nombre="Pozole" />
    
    <div class="card-body">
      <h5 class="card-title">Descripcion</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>
    
  </div>
</div>
</div>
    
     
    
    
    
   
    
    
  
    
    
  </div>

</body><br><br>

    <footer class="text-center footer-style">
    <div class="container">
        <div class="row">
            <div class="col-md-4 footer-col">
                <h3>Dirección</h3>
                <p>
                    Universidad Tecnologica de Tehuacan  <br />
                    San Pablo 
                </p>
            </div>
            <div class="col-md-4 footer-col">
                <h3>Mis redes</h3>
                <ul class="list-inline">
                    <li>
                        <a  target="_blank" href="#" class="btn-social btn-outline"><i class="fa fa-fw fa-facebook"></i></a>
                    </li>
                    <li>
                        <a  target="_blank" href="#" class="btn-social btn-outline"><i class="fa fa-fw fa-google-plus"></i></a>
                    </li>
                    <li>
                        <a  target="_blank" href="#" class="btn-social btn-outline"><i class="fa fa-fw fa-twitter"></i></a>
                    </li>
                    <li>
                        <a  target="_blank" href="#" class="btn-social btn-outline"><i class="fa fa-fw fa-linkedin"></i></a>
                    </li>
                    <li>
                        <a  target="_blank" href="#" class="btn-social btn-outline"><i class="fa fa-fw fa-dribbble"></i></a>
                    </li>
                </ul>
            </div>
            <div class="col-md-4 footer-col">
                <h3>Agradecimientos</h3>
                <p>Gracias por ver :D</p>
                <p>Citlally Itzel Carrera Sanchez 4°A</p>
            </div>
        </div>
    </div>
</footer>

</template>


<script>
  import Card from "./components/Card.vue"
  
  export default {
    components:{
      Card,
    },
  };
</script>

