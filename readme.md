# Lab22_Web

<h3> Praktikum 7 - PHP DASAR </h3>
<h3> Mata Kuliah : Pemrograman Web </h3>
<h3> Dosen        : Agung Nugroho,S.Kom.,M.Kom </h3>

<h3> Nama : Achmad Syarifudin </h3>
<h3> Nim  : 312110598 </h3> 
<h3> Kelas : TI.21.B1 </h3>



 ###Langkah 1
 Membuat dokumen HTML
 
 Pertama kita install XAMMP
 https://www.apachefriends.org/download.html

 <h1> Run Web Server </h1>
 habis itu buat folder lab77_dasar_php

 ![step-1](https://imgur.com/LaxbkNb.png )
![step-2]( https://imgur.com/voSwv7c.png)



<h1> Membuat Hello world </h1>
![step-3]( https://imgur.com/Nafivfr.png)


<h1> Membuat Variable harus menyertaka $ didepanya seperti ini</h1>
![step-4]( https://imgur.com/zDA3rBe.png)


<h1> Membuat Predefine Variable get</h1>
![step-5]( https://imgur.com/9qcOmnJ.png)

<h1> Membuat Create form input</h1>
![step-6]( https://imgur.com/6Vi8gUe.png)

<h1> Membuat Operator</h1>
![step-7]( https://imgur.com/zZzAONK.png)

Contoh conditional if adalah seperti ini
<?php
    $nama_hari = date("l");
    if ($nama_hari == "Sunday") {
    echo "Minggu";
    } elseif ($nama_hari == "Monday") {
    echo "Senin";
    } else {
    echo "Selasa";
    }
?>


Contoh Conditional Switch
<?php
    $nama_hari = date("l");
    switch ($nama_hari) {
        case "Sunday":
        echo "Minggu";
        break;
        case "Monday":
        echo "Senin";
        break;
        case "Tuesday":
        echo "Selasa";
        break;
        default:
        echo "Sabtu";
    }
?>


Contoh Perulangan Loop
<?php
    echo "Perulangan 1 sampai 10 <br />";
    for ($i=1; $i<=10; $i++) {
        echo "Perulangan ke: " . $i . '<br />';
    }
    echo "Perulangan Menurun dari 10 ke 1 <br />";
    for ($i=10; $i>=1; $i--) {
        echo "Perulangan ke: " . $i . '<br />';
    }
?>

Contoh While Loop
<?php
    echo "Perulangan 1 sampai 10 <br />";
    $i=1;
    while ($i<=10) {
        echo "Perulangan ke: " . $i . '<br />';
        $i++;
    }
?>

Contoh Do while Lop
<?php
    echo "Perulangan 1 sampai 10 <br />";
    $i=1;
    do {
        echo "Perulangan ke: " . $i . '<br />';
        $i++;
    }
    while ($i<=10);
?>