<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Preparatoria Oficial Anexa a la Normal de Naucalpan</title>

<style>

:root{
--guinda:#6A0D25;
--guinda2:#8B1E3F;
--blanco:#ffffff;
--negro:#111111;
--gris:#f5f5f5;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
scroll-behavior:smooth;
}

body{
background:var(--gris);
color:var(--negro);
}

header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.65),
rgba(0,0,0,.65)),
url("escuela.jpg");
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}

.hero h1{
font-size:4rem;
margin-bottom:20px;
}

.hero p{
font-size:1.3rem;
max-width:800px;
margin:auto;
}

.btn{
display:inline-block;
margin-top:25px;
padding:15px 35px;
background:var(--guinda);
color:white;
text-decoration:none;
border-radius:30px;
}

nav{
position:sticky;
top:0;
z-index:999;
background:var(--guinda);
padding:15px;
box-shadow:0 2px 10px rgba(0,0,0,.3);
}

nav ul{
display:flex;
justify-content:center;
gap:30px;
list-style:none;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

section{
padding:80px 10%;
}

.titulo{
text-align:center;
margin-bottom:50px;
color:var(--guinda);
font-size:2.3rem;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.card h3{
color:var(--guinda);
margin-bottom:15px;
}

.estadisticas{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.stat{
background:var(--guinda);
color:white;
padding:30px;
text-align:center;
border-radius:15px;
}

.stat h2{
font-size:3rem;
}

.tabla{
width:100%;
border-collapse:collapse;
margin-top:25px;
background:white;
}

.tabla th{
background:var(--guinda);
color:white;
padding:15px;
}

.tabla td{
padding:15px;
border:1px solid #ddd;
}

footer{
background:black;
color:white;
text-align:center;
padding:40px;
}

</style>
</head>

<body>

<header>

<div class="hero">

<img src="logo.png" width="180">

<h1>Preparatoria Oficial Anexa a la Normal de Naucalpan</h1>

<p>
Institución pública comprometida con la formación académica,
científica, tecnológica y humanística de los jóvenes del
Estado de México.
</p>

<a href="#escuela" class="btn">
Conocer más
</a>

</div>

</header>

<nav>

<ul>
<li><a href="#escuela">Escuela</a></li>
<li><a href="#instalaciones">Instalaciones</a></li>
<li><a href="#docentes">Docentes</a></li>
<li><a href="#ubicacion">Ubicación</a></li>
<li><a href="#gorra">Gorra Institucional</a></li>
</ul>

</nav>

<section id="escuela">

<h2 class="titulo">Nuestra Institución</h2>

<div class="grid">

<div class="card">
<h3>Historia</h3>
<p>
La Preparatoria Oficial Anexa a la Normal de Naucalpan forma parte
de una de las comunidades educativas con mayor tradición de la región.
Su objetivo es preparar estudiantes para ingresar exitosamente a la
educación superior.
</p>
</div>

<div class="card">
<h3>Misión</h3>
<p>
Brindar educación media superior de calidad desarrollando competencias,
valores y habilidades para la vida profesional y ciudadana.
</p>
</div>

<div class="card">
<h3>Visión</h3>
<p>
Ser una institución líder en formación académica,
reconocida por la excelencia de sus estudiantes.
</p>
</div>

</div>

</section>

<section>

<h2 class="titulo">Estadísticas Institucionales</h2>

<div class="estadisticas">

<div class="stat">
<h2>400</h2>
<p>Alumnos</p>
</div>

<div class="stat">
<h2>34</h2>
<p>Docentes</p>
</div>

<div class="stat">
<h2>2</h2>
<p>Turnos</p>
</div>

<div class="stat">
<h2>40+</h2>
<p>Años de Historia</p>
</div>

</div>

</section>

<section id="instalaciones">

<h2 class="titulo">Instalaciones</h2>

<div class="grid">

<div class="card">
<h3>Aulas</h3>
<p>Espacios equipados para el aprendizaje.</p>
</div>

<div class="card">
<h3>Laboratorios</h3>
<p>Prácticas de biología, química y física.</p>
</div>

<div class="card">
<h3>Biblioteca</h3>
<p>Material de consulta y apoyo académico.</p>
</div>

<div class="card">
<h3>Áreas Deportivas</h3>
<p>Desarrollo físico y competencias deportivas.</p>
</div>

</div>

</section>

<section id="docentes">

<h2 class="titulo">Personal Docente</h2>

<div class="card">

<p>
La institución cuenta con aproximadamente 34 docentes especializados
en áreas científicas, humanísticas y tecnológicas.
</p>

<ul>
<li>Capacitación continua.</li>
<li>Experiencia en educación media superior.</li>
<li>Participación en proyectos académicos.</li>
<li>Acompañamiento estudiantil.</li>
</ul>

</div>

</section>

<section id="ubicacion">

<h2 class="titulo">Ubicación</h2>

<div class="card">

<p>
Camino Real a San Mateo No. 179,
San Mateo Nopala,
Naucalpan de Juárez,
Estado de México.
</p>

<iframe
src="https://maps.google.com/maps?q=Naucalpan&t=&z=13&ie=UTF8&iwloc=&output=embed"
width="100%"
height="400"
style="border:0;">
</iframe>

</div>

</section>

<section id="gorra">

<h2 class="titulo">Proyecto de Gorra Institucional</h2>

<div class="grid">

<div class="card">

<h3>Descripción</h3>

<p>
Gorra oficial diseñada para fortalecer la identidad institucional,
promover el sentido de pertenencia y representar a la comunidad escolar
en eventos académicos, culturales y deportivos.
</p>

</div>

<div class="card">

<h3>Características Técnicas</h3>

<ul>
<li>6 paneles.</li>
<li>Costura recta industrial doble.</li>
<li>Overlock de 4 hilos.</li>
<li>Visera reforzada.</li>
<li>Algodón premium.</li>
<li>Bordado computarizado.</li>
<li>Broche Snapback.</li>
</ul>

</div>

</div>

<table class="tabla">

<tr>
<th>Concepto</th>
<th>Información</th>
</tr>

<tr>
<td>Producción</td>
<td>400 gorras</td>
</tr>

<tr>
<td>Costo Unitario</td>
<td>$83 MXN</td>
</tr>

<tr>
<td>Costo Total</td>
<td>$33,200 MXN</td>
</tr>

<tr>
<td>Precio de Venta</td>
<td>$150 MXN</td>
</tr>

<tr>
<td>Ingresos</td>
<td>$60,000 MXN</td>
</tr>

<tr>
<td>Ganancia Estimada</td>
<td>$26,800 MXN</td>
</tr>

<tr>
<td>ISR Estimado</td>
<td>$8,040 MXN</td>
</tr>

</table>

</section>

<footer>

<h3>Preparatoria Oficial Anexa a la Normal de Naucalpan</h3>

<p>
Proyecto académico de identidad institucional.
</p>

</footer>

</body>
</html>
