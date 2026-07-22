# Alwyy
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>WELCOME TO CLASS ANANDA ALWY FAWWAZY</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:linear-gradient(135deg,#001f3f,#0074D9,#00c6ff);
    color:white;
    min-height:100vh;
    overflow-x:hidden;
}

/* Animasi background */
body::before{
    content:"";
    position:fixed;
    width:300px;
    height:300px;
    background:white;
    opacity:.15;
    border-radius:50%;
    top:50px;
    left:-100px;
    animation:gerak 8s infinite alternate;
}

@keyframes gerak{
    from{
        transform:translateY(0);
    }
    to{
        transform:translateY(300px);
    }
}


/* Header */

header{
    text-align:center;
    padding:50px 20px;
    animation:turun 1.5s;
}

header h1{
    font-size:35px;
    text-shadow:0 0 20px cyan;
}

header p{
    margin-top:15px;
    font-size:18px;
}


@keyframes turun{
    from{
        opacity:0;
        transform:translateY(-50px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}



/* Card */

.container{
    width:90%;
    max-width:1000px;
    margin:auto;
}


.card{
    background:rgba(255,255,255,.15);
    backdrop-filter:blur(10px);
    padding:25px;
    border-radius:20px;
    margin:25px 0;
    box-shadow:0 0 25px rgba(0,0,0,.3);
    animation:muncul 1.5s;
}


@keyframes muncul{
    from{
        opacity:0;
        transform:scale(.8);
    }
    to{
        opacity:1;
        transform:scale(1);
    }
}


h2{
    color:#00ffff;
    margin-bottom:15px;
}


p{
    line-height:1.7;
}


/* Code */

.code{
    background:#050505;
    padding:20px;
    border-radius:15px;
    margin-top:15px;
    overflow:auto;
    color:#00ff9d;
    font-family:monospace;
}



/* Button */

button{
    padding:12px 25px;
    border:none;
    border-radius:30px;
    background:#00ffff;
    color:#003;
    font-weight:bold;
    cursor:pointer;
    margin-top:15px;
    transition:.3s;
}


button:hover{
    transform:scale(1.1);
    box-shadow:0 0 20px cyan;
}


/* Footer */

footer{
    text-align:center;
    padding:30px;
    opacity:.8;
}


</style>

</head>


<body>


<header>

<h1>
WELCOME TO CLASS<br>
ANANDA ALWY FAWWAZY
</h1>

<p>
Tempat belajar HTML, CSS, dan Web Development
</p>

<button>
Mulai Belajar
</button>

</header>



<div class="container">


<div class="card">

<h2>Apa Itu HTML?</h2>

<p>
HTML (HyperText Markup Language) adalah bahasa markup yang digunakan untuk membuat struktur sebuah website.
HTML digunakan untuk mengatur teks, gambar, link, tabel, formulir, dan berbagai elemen halaman web.
</p>

</div>




<div class="card">

<h2>Struktur Dasar HTML</h2>

<p>
Setiap website HTML memiliki struktur utama yaitu html, head, dan body.
Bagian head berisi informasi website, sedangkan body berisi tampilan yang dilihat pengguna.
</p>


<div class="code">

&lt;!DOCTYPE html&gt;<br>
&lt;html&gt;<br>
&nbsp;&nbsp;&lt;head&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;title&gt;Website Saya&lt;/title&gt;<br>
&nbsp;&nbsp;&lt;/head&gt;<br>

&nbsp;&nbsp;&lt;body&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;h1&gt;Halo Dunia&lt;/h1&gt;<br>
&nbsp;&nbsp;&lt;/body&gt;<br>

&lt;/html&gt;

</div>


</div>




<div class="card">

<h2>Heading dan Paragraf</h2>

<p>
Heading digunakan sebagai judul mulai dari h1 sampai h6.
Sedangkan paragraf menggunakan tag p untuk membuat tulisan.
</p>


<div class="code">

&lt;h1&gt;Judul Website&lt;/h1&gt;

<br>

&lt;p&gt;
Ini adalah contoh paragraf website.
&lt;/p&gt;

</div>


</div>





<div class="card">

<h2>Memasukkan Gambar</h2>

<p>
HTML dapat menampilkan gambar menggunakan tag img.
Atribut src digunakan untuk lokasi gambar.
</p>


<div class="code">

&lt;img src="gambar.jpg" 
alt="gambar saya"&gt;

</div>


</div>





<div class="card">

<h2>Membuat Link</h2>

<p>
Link digunakan untuk berpindah ke halaman lain atau website lain.
</p>


<div class="code">

&lt;a href="https://google.com"&gt;
Klik Disini
&lt;/a&gt;

</div>


</div>






<div class="card">

<h2>Membuat Formulir</h2>

<p>
Form digunakan untuk menerima input dari pengguna seperti nama, email, dan password.
</p>


<div class="code">

&lt;form&gt;

&lt;input type="text"
placeholder="Nama"&gt;

&lt;button&gt;
Kirim
&lt;/button&gt;

&lt;/form&gt;

</div>


</div>





<div class="card">

<h2>Kesimpulan</h2>

<p>
HTML adalah langkah pertama untuk menjadi Web Developer.
Setelah menguasai HTML, kamu dapat mempelajari CSS untuk mempercantik tampilan dan JavaScript untuk membuat website lebih interaktif.
</p>

</div>



</div>



<footer>

© 2026 WELCOME TO CLASS ANANDA ALWY FAWWAZY

</footer>



</body>
</html>
