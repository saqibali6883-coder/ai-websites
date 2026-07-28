<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Firestick IPS | Premium Streaming Experience</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">


<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Inter',sans-serif;
}

body{
background:#020617;
color:white;
overflow-x:hidden;
}

html{
scroll-behavior:smooth;
}


/* HEADER */

header{

position:fixed;
top:0;
width:100%;

padding:20px 6%;

display:flex;
justify-content:space-between;
align-items:center;

background:rgba(2,6,23,.9);

backdrop-filter:blur(10px);

z-index:1000;

}


.logo{

font-size:30px;
font-weight:800;

}

.logo span{

color:#2563eb;

}


nav a{

color:white;
text-decoration:none;
margin-left:25px;
font-weight:600;

}


.btn{

background:#2563eb;

padding:14px 28px;

border-radius:30px;

color:white;

text-decoration:none;

font-weight:700;

display:inline-block;

}


/* HERO */


.hero{

min-height:100vh;

display:flex;

align-items:center;

justify-content:space-between;

padding:120px 6% 60px;

background:

linear-gradient(
90deg,
rgba(2,6,23,.95),
rgba(2,6,23,.5)
),

url("https://images.unsplash.com/photo-1593784991095-a205069470b6");

background-size:cover;

background-position:center;

}


.hero-text{

width:50%;

}


.hero-text h1{

font-size:60px;

line-height:1.1;

}


.hero-text p{

font-size:20px;

color:#cbd5e1;

margin:25px 0;

}



/* DEVICE AREA */


.device-showcase{

width:45%;

position:relative;

height:500px;

}



/* TV */


.tv{

position:absolute;

right:0;

top:60px;

width:420px;

height:250px;

background:#111827;

border:12px solid #334155;

border-radius:15px;

box-shadow:0 20px 60px #000;

}


.tv-screen{

width:100%;

height:100%;

background:

url("https://images.unsplash.com/photo-1593359677879-a4bb92f829d1");

background-size:cover;

background-position:center;

}


.tv-stand{

width:80px;

height:40px;

background:#334155;

margin:auto;

}



/* LAPTOP */


.laptop{

position:absolute;

left:20px;

bottom:40px;

width:250px;

height:160px;

background:#111827;

border:8px solid #64748b;

border-radius:10px;

}


.laptop-screen{

height:100%;

background:url("https://images.unsplash.com/photo-1517336714731-489689fd1ca8");

background-size:cover;

}



/* MOBILE */


.mobile{

position:absolute;

right:50px;

bottom:20px;

width:90px;

height:180px;

background:#020617;

border:5px solid #64748b;

border-radius:20px;

}


.mobile-screen{

height:100%;

background:url("https://images.unsplash.com/photo-1511707171634-5f897ff02aa9");

background-size:cover;

border-radius:15px;

}





/* SECTION */


.section{

padding:90px 6%;

}


.title{

text-align:center;

margin-bottom:50px;

}


.title h2{

font-size:40px;

}





/* TRUST */


.cards{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(280px,1fr));

gap:30px;

}


.card{

background:#1e293b;

padding:35px;

border-radius:20px;

text-align:center;

border:1px solid #334155;

}


.card h3{

margin:20px 0;

}


.card p{

color:#94a3b8;

}


.icon{

font-size:45px;

}




/* RESPONSIVE */


@media(max-width:900px){


.hero{

flex-direction:column;

text-align:center;

}


.hero-text{

width:100%;

}


.hero-text h1{

font-size:40px;

}


.device-showcase{

width:100%;

height:400px;

margin-top:40px;

}


.tv{

width:280px;

height:170px;

}


nav{

display:none;

}


}


</style>

</head>


<body>


<header>

<div class="logo">
FIRESTICK<span>IPS</span>
</div>


<nav>

<a href="#">Home</a>
<a href="#">Devices</a>
<a href="#">Reviews</a>
<a href="#">Contact</a>

<a class="btn" href="https://wa.me/447436763956">
WhatsApp
</a>

</nav>


</header>



<section class="hero">


<div class="hero-text">


<h1>
Premium Streaming Experience On Every Device
</h1>


<p>
Enjoy entertainment on Smart TV, Computer, Laptop and Mobile with professional setup support.
</p>


<a class="btn" href="https://wa.me/447436763956">
Get Started
</a>


</div>



<div class="device-showcase">


<div class="tv">

<div class="tv-screen"></div>

<div class="tv-stand"></div>

</div>



<div class="laptop">

<div class="laptop-screen"></div>

</div>



<div class="mobile">

<div class="mobile-screen"></div>

</div>


</div>


</section>



<section class="section">


<div class="title">

<h2>
Why Customers Trust Us
</h2>

</div>



<div class="cards">


<div class="card">

<div class="icon">🏆</div>

<h3>
Trusted Streaming Support Team
</h3>

<p>
Professional customer assistance and setup guidance.
</p>

</div>



<div class="card">

<div class="icon">⭐</div>

<h3>
Thousands Of Satisfied Customers
</h3>

<p>
A growing community worldwide.
</p>

</div>



<div class="card">

<div class="icon">🌍</div>

<h3>
Worldwide Community
</h3>

<p>
Quality support across different devices.
</p>

</div>


</div>


</section>
