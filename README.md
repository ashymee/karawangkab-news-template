# Karawangkab News Template

> hanya digunakan untuk keperluan update **Headline** dan **Berita** di situs (official) [Pemerintah Kabupaten Karawang](https://karawangkab.go.id "Situs Official Pemerintah Kabupaten Karawang"

* diletakkan di atas konten berita:

```html
<style> .bordering {border: 1px solid #ccc; padding: 5px; border-radius: 10px; margin-bottom: 20px } i.fa {border: 1px solid #ccc; padding: 3px; color: #3f9ae8; height: auto; width: 20px; margin-bottom: 3px; border-radius: 3px; } .theme-default .nivoSlider {box-shadow: none !important} .popup { display: flex; align-items: center; justify-content: center; position: fixed; width: 100vw; height: 100vh; bottom: 0; right: 0; background-color: rgba(0, 0, 0, 0.8); z-index: 2; visibility: hidden; opacity: 0; overflow: hidden; transition: .64s ease-in-out; } </style>
```

* diletakkan di setelah konten berita:
```html
<hr>
<center>
	<div class="bordering">
		<img src="" style="width: 49%">
	</div>
</center>

<hr><center class="banner-covid"><a href="https://covid19.karawangkab.go.id" target="_blank"><img src="https://www.karawangkab.go.id/sites/default/files/SpandukCovid19.png" /></a></center> <br> <p class="rtejustify"> Halo wargi Karawang, untuk informasi lebih lengkap. Wargi bisa akses melalui web berikut :<br> <a href="https://covid19.karawangkab.go.id" target="_blank">covid19.karawangkab.go.id</a><br> <br> Data tersebut silakan digunakan wargi untuk proaktif agar saling mengingatkan untuk menjaga diri dan mengurangi interaksi sosial di zona merah dan hitam, tanpa reaksi sosial berlebihan.<br> <br> KITA HARUS TETAP TENANG, TINGKATKAN KEWASPADAAN, DAN SELALU TERAPKAN PROTOKOL KESEHATAN 3M:<br> - MENJAGA JARAK<br> - MENCUCI TANGAN<br> - MEMAKAI MASKER<br> </p>	
<hr><strong>Follow Kominfo Official Media at</strong> <br> <i class="fa fa-facebook"></i> <a href="https://web.facebook.com/Diskominfokrwkab" target="_blank">Diskominfokrwkab</a><br> <i class="fa fa-instagram"></i> <a href="https://www.instagram.com/diskominfokrwkab/" target="_blank">@Diskominfokrwkab</a><br> <i class="fa fa-twitter"></i> <a href="https://twitter.com/Diskominfokrwkab" target="_blank">@Diskominfokrwkab</a><br> <i class="fa fa-globe"></i> <a href="https://www.karawangkab.go.id" target="_blank">www.karawangkab.go.id</a>, <a href="http://www.diskominfo.karawangkab.go.id" target="_blank">www.diskominfo.karawangkab.go.id</a>
```

> tag <img src="" style="width: 49%"> disesuaikan dengan jumlah image yang akan diupload. Width / lebar gambar cukup diubah menjadi 49% atau 99%. 49% untuk layout setengah laman, sedangkan 99% untuk layout full laman.

> src / source diisi link url sumber pengutipan gambar

### pengaturan width, jika jumlah gambar = ganjil
- jika jumlah gambar yang akan diupload = 1, maka __width: 99%__.
```html
<center>
	<div class="bordering">
		<img src="" style="width: 99%">
	</div>
</center>
```
- jika jumlah gambar = 3, dst. Maka, pengaturannya adalah 
```html
<center>
	<div class="bordering">
		<img src="" style="width: 99%">
    <img src="" style="width: 49%">
    <img src="" style="width: 49%">
	</div>
</center>
```

### pengaturan width, jika jumlah gambar = genap
```html
<center>
	<div class="bordering">
    <img src="" style="width: 49%">
    <img src="" style="width: 49%">
	</div>
</center>
```
