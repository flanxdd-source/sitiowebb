<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Marimba Chapina</title>

<style>

body{
    font-family: Arial;
    margin:0;
    background:#f0f0f0;
}

header{
    background:rgb(103, 141, 188);
    color:white;
    text-align:center;
    padding:20px;
}

nav{
    background:rgb(58, 87, 121);
    text-align:center;
    padding:10px;
}

nav a{
    color:white;
    margin:10px;
    text-decoration:none;
}

.banner{
    background-image:url('https://i.pinimg.com/1200x/24/24/7f/24247f7a879a6838c50b5a04e0f14efc.jpg');
    background-size:cover;
    background-position:center;
    height:300px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
}

.banner h1{
    background:rgba(0,0,0,0.5);
    padding:20px;
}

.contenedor{
    width:90%;
    margin:auto;
}

.volcan{
    background:rgb(197, 168, 134);
    margin:20px 0;
    padding:15px;
    border-radius:10px;
}

.volcan img{
    width:100%;
    max-width:400px;
    border-radius:10px;
}

h2{
    color:rgb(10, 1, 49);
}

.links a{
    display:block;
    margin:10px;
    color:rgb(31, 31, 136);
}

.video{
    text-align:center;
    margin:20px;
}

footer{
    background:rgb(31, 69, 102);
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}

</style>
</head>

<body>

<header>
    <h1>Marimba chapina</h1>
    <p>música de marimba guatemalteca por el mundo</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">marimbas</a>
    <a href="#">Galería</a>
    <a href="#">Contacto</a>
</nav>

<!-- Banner -->
<div class="banner">
    <h1>¡Aprende más sobre las marimbas!</h1>
</div>

<div class="contenedor">

    <h2>Imagenes de la marimba</h2>

    

    <div class="volcan">
        <h3>1.</h3>
        <img src="https://i.pinimg.com/1200x/24/da/55/24da556eaefedef5378b6bb15035e98a.jpg">
    </div>

    <div class="volcan">
        <h3>2.</h3>
        <img src="https://i.pinimg.com/1200x/1a/58/c0/1a58c00adbc1ee6cc90fb67fdca4d72a.jpg">
    </div>

    <div class="volcan">
        <h3>3.</h3>
        <img src="https://i.pinimg.com/1200x/6a/e4/ea/6ae4ea9e49a0f218784a4853ba54943e.jpg">
    </div>

    <div class="volcan">
        <h3>4.</h3>
        <img src="https://i.pinimg.com/1200x/1a/2d/d9/1a2dd96dce6a2f38752b138b9e29e0f2.jpg">
    </div>

    <h2>Mis Hipervínculos</h2>

    <div class="links">
        <a href="https://www.google.com" target="_blank">Google</a>
        <a href="https://www.youtube.com" target="_blank">YouTube</a>
    </div>

    <h2>Mi Video</h2>

    <div class="video">
        <iframe width="560" height="315"
        src="https://youtu.be/GG4iOf6QWk8"
        frameborder="0"
        allowfullscreen>
        </iframe>
    </div>

    <section>

<h2>MI FORMULARIO</h2>

<form>

<input type="text" placeholder="Ingrese su nombre">

<input type="email" placeholder="Ingrese su correo">

<select>
<option>Guatemala</option>
<option>México</option>
<option>El Salvador</option>
<option>Honduras</option>
</select>

<input type="text" placeholder="Pasatiempos">

<textarea placeholder="Comentarios"></textarea>

<button type="submit">
Enviar Información
</button>

</form>

</section>



    
</body>
</html>
