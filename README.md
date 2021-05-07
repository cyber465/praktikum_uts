# praktikum_uts

Setelah anda membuat desain web pada tutorial sebelumnya, kali ini kita akan meng-konversi desain web yang telah kita buat menjadi baris-baris kode HTML. Jika anda ingin mengetahui bagaimana proses pembuatan desain web silahkan baca tutorial Membuat Desain Web Minimalis Dengan Photoshop.

Persiapan Yang harus anda persiapkan pertama kali adalah konsentrasi, Jika anda kurang mengerti akan apa yang saya jelaskan, harap untuk membacanya berulangkali karena tutorial ini merupakan dasar dan bisa disebut fundamental untuk proses markup/pembuatan kode HTML.

Untuk memudahkan proses konversi desain, saya selalu membuat wireframe untuk desain yang dibuat, hal ini ditujukan untuk memudahkan anda dalam membuat layout web sesuai dengan desain juga untuk memudahkan kita dalam penamaan masing-masing elemen. Berikut ini adalah wireframe/kerangka desain web yang telah kita buat pada tutorial sebelumnya.

![Untitled](https://user-images.githubusercontent.com/37741274/117404273-d7952200-af33-11eb-9644-362240b0ebc4.png)

# Sekilas

Sedikit mengingatkan kembali, bahwa tugas HTML adalah untuk membuat markup/formatting dari desain web. Bukan untuk membuat penampilan yang sesuai dengan desain. Jadi jangan dulu memikirkan bagaimana agar markup HTML yang kita buat sesuai dengan desain, karena ini adalah tugas CSS untuk membuat markup HTML menjadi sesuai dengan Desain Web.

# kode html

'''

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Mint - PSD Estate Landing Page</title>
    <link rel="stylesheet" href="assets/style.css">
</head>
<body>
	<div class="container">
		<div class="side">
			<div class="info">
				<a href="http://www.graphberry.com"><img src="assets/logo.png"></a>
				<p><b>CREATED: </b> 09.05.2020</p>
				<p><b>BY: </b><a href="http://www.graphberry.com"> Graphberry</a></p>
				<p><b>CONTACT: </b><a href="http://www.graphberry.com/pages/contact"> Contact Us</a></p>
			</div>
			<div class="menu">
				<li>
					<a href="#1">Introduction</a>
				</li>
				<li>
					<a href="#2">Fonts</a>
				</li>
				<li>
					<a href="#3">Template</a>
				</li>
				<li>
					<a href="#4">Credits</a>
				</li>
			</div>
		</div>
		<div class="content">
			<div id="1">
			    <p class="title">Introduction</p>
				<div class="intro-info">
					<p>Welcome to Mint PSD template documentation.If you have any question,please fill free to <a href="http://www.graphberry.com/pages/contact">Contact Us</a></p>
				<p><b>FEATURES: </b>
					<li>Single Page Design</li>
					<li>Fully Layered Adobe Photoshop PSD file</li>
					<li>1140 pix Grid Style</li>
					<li>Modern And Clean Design</li>
					<li>Free Google <a href="https://fonts.google.com/specimen/Montserrat">Monteserat</a></li>
					<li>Easy To Use And Customize</li>
				</p>
				</div>
		    </div>

			<div id="2">
			    <p class="title">Fonts</p>
				<div class="intro-info">
					<p>Please make sure to download and instal google font <a href="https://fonts.google.com/specimen/Montserrat">Monteserat</a> or you will have problem to edit text</p>
				</div>
		    </div>

			<div id="3">
			    <p class="title">Template</p>
				<div class="intro-info">
					<p>Mint is fully layered PSD template,every element is on one layer,gruped and organized</p>
					<p>Make sure to select layer for element you wish to edit</p>
          <p>Images not included,links can be found in credits section</p>
          <p>Template width is 1140pix. Compatible with Bootstrap 4</p>
				</div>
		    </div>

			<div id="4">
			    <p class="title">Credits</p>
				<div class="intro-info">
					<p><b>CREDITS:</b>
						<li>Free Google font <a href="https://fonts.google.com/specimen/Montserrat">Monteserat</a></li>
                        <li>Images <a href="https://unsplash.com">Unsplash</a></li>
                    </p>
				</div>
		    </div>

			<div>
				<p class="title"></p>
				<div class="footer">
					<p>© Copyright 2020 <a href="http://www.graphberry.com">Graphberry</a>.All Rights Reserved.</p>
				</div>
			</div>
		</div>
	</div>






</body>
</html>

'''

# css


'''
.info a {
	text-decoration:none;
	font-family:Arial;
	color:#26D381;
	font-size:15px;
}
a:hover {
	color:#00E1FF;
}
b {
	color:#2B3C47;
	font-family:Arial;
	font-size:13px;
}
p {
	color:#545B6B;
	font-family:Arial;
	font-size:15px;
	padding:10px 5px;
}
.container {
	width:960px;
	margin:0 auto;
}
.side {
	float:left;
	width:250px;
	border-right:1px solid #E6E6E6;
	position:fixed;
}
.content {
	float:right;
	width:709px;
}
.side img {
	width:150px;
	height:60px;
	border-bottom:1px solid #E6E6E6;
	padding:7px 100px 10px 0px;
}
.info {
	border-bottom:1px solid #E6E6E6;
}
li {
	list-style:none;
	padding-top:20px;
	color:#545B6B;
	font-family:Arial;
}
li a {
	font-size:17px;
	text-decoration:none;
	color:#26D381;
}
li a:hover {
	color:#00E1FF;
}	
.title {
	color:#26D381;
	text-align:center;
	font-size:27px;
	border-bottom:1px solid #E6E6E6;
	padding-bottom:7px;
}
.intro-info {
	text-align:center;
	padding-top:5px;
}
.intro-info a {
	color:#26D381;
	text-decoration:none;
}
.intro-info a:hover {
	color:#00E1FF;
}	
.intro-info li {
	font-size:17px;
}	
.footer p {
	font-size:12px;
	color:#545B6B;
	text-align:center;
}
.footer a {
	color:#26D381;
	text-decoration:none;
}
.footer a:hover {
	color:#00E1FF;
}
'''

# hasil

![yyy](https://user-images.githubusercontent.com/37741274/117405114-47f07300-af35-11eb-9075-8050c878968f.png)
