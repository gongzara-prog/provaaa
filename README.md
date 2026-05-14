

<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Linea Arredi</title>

<style>

body{
margin:0;
font-family:Arial,sans-serif;
background:linear-gradient(to bottom, #efe7dc, #e5dbcf);
color:#222;
}

/* HERO */

.hero{
height:100vh;
background:url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1600&auto=format&fit=crop') center/cover;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}

.hero-box{
background:rgba(0,0,0,0.5);
padding:40px;
}

.hero h1{
font-size:70px;
margin:0;
letter-spacing:6px;
}

.hero p{
font-size:20px;
margin-top:15px;
}

/* SECTION */

.section{
padding:60px 10%;
}

.section h2{
text-align:center;
margin-bottom:30px;
font-size:35px;
font-weight:normal;
}

/* STILI E STANZE */

.boxes{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:15px;
margin-bottom:50px;
}

.box{
background:#f7f1e8;
padding:15px 25px;
border:1px solid #d8cfc3;
}

/* CARD */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#f7f1e8;
border:1px solid #d8cfc3;
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card h3{
padding:15px 15px 5px;
font-weight:normal;
}

.card p{
padding:0 15px 20px;
color:#666;
line-height:1.5;
}

/* MOBILE */

@media(max-width:768px){

.hero h1{
font-size:45px;
}

.hero p{
font-size:16px;
}

}

</style>
</head>

<body>

<section class="hero">

<div class="hero-box">
<h1>LINEA ARREDI</h1>
<p>Trova lo stile perfetto per la tua casa</p>
</div>

</section>

<section class="section">

<h2>Stili Disponibili</h2>

<div class="boxes">
<div class="box">Moderno</div>
<div class="box">Minimal</div>
<div class="box">Scandinavo</div>
<div class="box">Industriale</div>
<div class="box">Japandi</div>
<div class="box">Boho</div>
</div>

<h2>Stanze</h2>

<div class="boxes">
<div class="box">Bagno</div>
<div class="box">Camera Adulti</div>
<div class="box">Camera Singola</div>
<div class="box">Cucina</div>
<div class="box">Soggiorno</div>
<div class="box">Ufficio</div>
</div>

<h2>Ispirazioni Arredo</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1620626011761-996317b8d101?q=80&w=1200&auto=format&fit=crop">
<h3>Bagno Moderno</h3>
<p>Mobile bagno elegante con design moderno.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1494526585095-c41746248156?q=80&w=1200&auto=format&fit=crop">
<h3>Soggiorno Scandinavo</h3>
<p>Ambiente luminoso e accogliente in stile nordico.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1484154218962-a197022b5858?q=80&w=1200&auto=format&fit=crop">
<h3>Cucina Industriale</h3>
<p>Cucina moderna con dettagli in metallo nero.</p>
</div>

</div>

</section>

</body>
</html>
