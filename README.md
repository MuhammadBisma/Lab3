# Lab3Web

## Nama     : Muhammad Bisma Putra H
## NIM      : 312010443
## Kelas    : TI.20.A.1

## <b>Membuat Ordered List</b>
<img width="191" alt="gambar1" src="https://user-images.githubusercontent.com/101621068/160338838-73f32398-69e1-41a6-b5f2-c4ad76ae83d4.png">

Ini adalah hasil dari Membuat Ordered List <p>

## Contoh Coding
html
<section id="order-list">
<h2>Ordered List</h2>
<ol>
<li>Pemrograman Web</li>
<li>Sistem Informasi</li>
<li>Basis Data 2</li>
</ol>
</section>

## <b>Membuat Nonordered List</b>
<img width="215" alt="gambar2" src="https://user-images.githubusercontent.com/101621068/160339902-b0e02440-5a33-4ab7-81b8-34dd137c04da.png">

Ini adalah hasil dari Membuat Nonordered <p>

## Contoh Coding
html
<section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>

## <b>Membuat Description List</b>
<img width="182" alt="gambar3" src="https://user-images.githubusercontent.com/101621068/160340782-d48d5175-fc94-4924-b006-2bba1c4d7b52.png">

Ini adalah hasil dari Membuat Description List <p>

## Contoh Codingan
html
<section id="unorder-list">
<h2>Description List</h2>
<dl>
<dt>Fakultas Teknik</dt>
<dd>Teknik Industri</dd>
<dd>Teknik Informatika</dd>
<dd>Teknik Lingkungan</dd>
<dt>Fakultas Ekonomi dan Bisnis</dt>
<dd>Akuntansi</dd>
<dd>Manajemen</dd>
<dd>Bisnis Digital</dd>
</dl>
</section>


## <b>Membuat Tabel</b>
<img width="224" alt="gambar4" src="https://user-images.githubusercontent.com/101621068/160341079-6fb9d0f0-88f2-4d89-879d-fae1a6dd4332.png">

Ini adalah hasil dari Membuat Tabel <p>

## Contoh Codingan
html
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
</header>
</body>
</html>


<b>Mengatur Margin dan Padding</b>
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan
cellspacing pada tag table.
<br><img width="213" alt="gambar5" src="https://user-images.githubusercontent.com/101621068/160341476-caec25d2-8cdd-4471-b291-febc87cb2032.png"> </br>

Ini adalah hasil dari Mengatur Margin dan Padding<p>

## Contoh Codingan
html
<table border="1" cellpadding="4" cellspacing="0">


## <b>Menggabungkan Sel Data</b>
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara
horizontal).
<br><img width="223" alt="gambar6" src="https://user-images.githubusercontent.com/101621068/160341839-35564111-d88f-4ea3-ad3b-eabd727c1fda.png"> </br>

Ini adalah hasil dari Menggabungkan Sel Data<p>

## Contoh Codingan
html
<table border="1" cellpadding="6" cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program Studi</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.</td>
<td rowspan="3">Teknik</td>
<td>Teknik Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik Lingkungan</td>
</tr>
</tbody>
</table>


## <b>Membuat Form</b>
<img width="959" alt="gambar7" src="https://user-images.githubusercontent.com/101621068/160342395-f739cba6-8862-416b-8e98-36a88235fb35.png">

Ini adalah hasil dari Membuat Form <p>

## Contoh Codingan
html
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Form</h1>
</header>
</body>
</html>

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:

<form action="proses.php" method="post">
<fieldset>
<legend>Data Pelanggan</legend>
<p>
<label for="nama">Nama</label>
<input type="text" id="nama" name="nama">
</p>
<p>
<label for="alamat">Alamat</label>
<textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
</p>
<p>
<label>Jenis Kelamin</label>
<input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
<input id="jk_p" type="radio" name="kelamin" value="P" /><label
for="jk_p">Perempuan</label>
</p>
<p><input type="submit" value="Login"></p>
</fieldset>
</form>

## <b>Menambahkan Style pada Form</b>
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
<img width="957" alt="gambar8" src="https://user-images.githubusercontent.com/101621068/160342997-5ff975e8-23a8-45fb-a464-bff41c07184e.png">

Ini adalah hasil dari Menambahkan Style pada Form <p>

## Contoh Codingan
html
<style>
form p > label {
display: inline-block;
width: 100px;
}
form input[type="text"], form textarea {
border: 1px solid #197a43;
}
form input[type="submit"] {
border: 1px solid #197a43;
background-color: #197a43;
color: #ffffff;
font-weight: bold;
padding: 5px 15px;
}
</style>


## TERIMA KASIH