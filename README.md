# Lab3Web
# Praktikum 3 - Pemrograman Web
```
Fahmi Abdul Muthi
311910463
TI.19.A2
```
# Langkah 1
Membuat sebuah dokumen html dan membuat ordered list :
![101](https://user-images.githubusercontent.com/56380765/114517787-de987f80-9c68-11eb-9b67-d87c0cae3d51.png)
# Langkah 2
kemudian tambahkan kode unorderd list
![102](https://user-images.githubusercontent.com/56380765/114518105-3636eb00-9c69-11eb-8d49-c98556225809.png)
# Langkah 3
setelah pendeklarasian kode unorderd list, kemudian tambahkan kode untuk membuat description list
![103](https://user-images.githubusercontent.com/56380765/114518584-b78e7d80-9c69-11eb-840e-6ff3427a6b2e.png)
# Langkah 4
Membuat dokumen baru html untuk membuat tabel sederhana dengan mengatur margin dan padding
![104](https://user-images.githubusercontent.com/56380765/114518859-00decd00-9c6a-11eb-8b55-04b639b98222.png)
# Langkah 5
kemudian menggabungkan sel data dengan menggunakan atribut ```rowspan dan colspan``` 
![105](https://user-images.githubusercontent.com/56380765/114519399-94180280-9c6a-11eb-92c3-d09069b039e6.png)
# Langkah 6
Membuat dokumen baru html untuk membuat form
![106](https://user-images.githubusercontent.com/56380765/114519722-e2c59c80-9c6a-11eb-97c6-e29eb7efa0ed.png)
# Langkah 7
agar tampilan menu form lebih menarik silahkan tambahkan CSS seperti berikut
![107](https://user-images.githubusercontent.com/56380765/114519980-24eede00-9c6b-11eb-93f8-812e9e3884a4.png)
# Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
![108](https://user-images.githubusercontent.com/56380765/114520320-82832a80-9c6b-11eb-9d78-c167638a4561.png)

syntax untuk Dropdown
```
<!DOCTYPE html>
<html>
<head>
	<title>HTML Lanjutan</title>
</head>
<body>
 
	<style type="text/css">
	html,body{
        background-color: #00ff2a;
		padding: 0;
		margin:0;
		font-family: sans-serif;
	}
 
	.menu{
		background-color: #ff0015;
	}
 
	.menu ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		overflow: hidden;
	}
 
	.menu > ul > li {
		float: left;
	}
 
	
	.menu li a {
		display: inline-block;
		color: rgb(20, 1, 1);
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
	}
 
	.menu li a:hover{
		background-color: #00ff00;
	}
 
	li.dropdown {
		display: inline-block;
	}
 
	.dropdown:hover .isi-dropdown {
		display: block;
	}
 
	.isi-dropdown a:hover {
		color: rgba(22, 2, 2, 0.925) !important;
	}
 
	.isi-dropdown {
		position: absolute;
		display: none;
		box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
		z-index: 1;
		background-color: #1606f7;
	}
 
	.isi-dropdown a {
		color: #3c3c3c !important;
	}
 
	.isi-dropdown a:hover {
		color: #232323 !important;
		background: #07f513 !important;
	}
</style>
 
 
<header class="header">
	<div class="menu">
 
		<ul>
			<li><a href="lab3_Tugas.html">CONTOH DROPDOWN </a></li>
			<li class="dropdown"><a href="#">DAFTAR MENU MINUMAN</a>
				<ul class="isi-dropdown">
					<li><a href=>Kopi Hitam</a></li>
					<li><a href=>Es Teh manis</a></li>
					<li><a href=>Jeruk Panas</a></li>
				</ul>
			</li>
		</ul>
 
	</div>
</header>
<center>
	<h1>Membuat Menu Dropdown dan Listbox</br> Tugas pemrograman web ke 3</h1>
</center>
```
syntax untuk listbox
```
<h4>CONTOH LISTBOX</h4>
<form action="proses.php" method="get">
    <p>Menu Makanan
    <select name='Menu Makanan' multiple='multiple'>
      <option value='Nasi Goreng'>Nasi Goreng</option>
      <option value='Ketoprak' selected='selected'>Ketoprak</option>
      <option value='Mie Goreng'>Mie Goreng</option>
      <option value='Nasi Rames'>Nasi Rames</option>
      <option value='Mie Rebus'>Mie rebus</option>
    </select>
    </p>
    <input type='submit' name='tombol' value='kirim' />
    ```
