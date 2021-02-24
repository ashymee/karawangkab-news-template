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

### Contoh
```php
<style> .bordering {border: 1px solid #ccc; padding: 5px; border-radius: 10px; margin-bottom: 20px } i.fa {border: 1px solid #ccc; padding: 3px; color: #3f9ae8; height: auto; width: 20px; margin-bottom: 3px; border-radius: 3px; } .theme-default .nivoSlider {box-shadow: none !important} .popup { display: flex; align-items: center; justify-content: center; position: fixed; width: 100vw; height: 100vh; bottom: 0; right: 0; background-color: rgba(0, 0, 0, 0.8); z-index: 2; visibility: hidden; opacity: 0; overflow: hidden; transition: .64s ease-in-out; } </style>

<p class="rtejustify"><strong>Karawang</strong>, - Pelaksana Harian (Plh) Bupati Karawang, Drs. H. Acep Jamhuri M.Si., hadir menghadiri rapat koordinasi persiapan pembayaran kompensasi tiga profesi terdampak tumpahan minyak mentah bersama Pertamina Hulu Energi Offshore North West Java (PHE ONWJ) di Hotel Mercure Karawang, Selasa 23 Februari 2021.<br />
<br />
Rapat koordinasi juga dihadiri tim koordinasi Penanggulangan Dampak Tumpahan Minyak di Kabupaten Karawang, tim Pusat Penelitian Lingkungan Hidup Institut Pertanian Bogor (PPLH IPB) dan BPKP.<br />
<br />
Dalam pembicaraannya, Plh Bupati berharap agar pembayaran kompensasi terhadap warga Karawang yang terdampak, akibat kebocoran minyak mentah agar bisa segera dilaksanakan secepatnya.<br />
<br />
"Lebih cepat lebih bagus. Agar segera direalisasikan dengan mengacu kepada regulasi dan akuntabilitas," ujarnya.<br />
<br />
Ia menuturkan, dalam pembayaran kompensasi itu harus mengutamakan aspek keamanan dan kondusifitas.<br />
<br />
Sementara, dalam menentukan jumlah hari, area dan profesi terdampak serta perhitungan nilai kompensasi PHE ONWJ menggandeng tim peneliti dari PPLH IPB.<br />
<br />
PPLH IPB dalam menentukan jumlah hari, area serta perhitungan nilai kompensasi melakukan survey ke lapangan dengan melakukan komunikasi dengan warga terdampak.&nbsp;</p>

<hr>
<center>
	<div class="bordering">
		<img src="https://scontent-cgk1-1.cdninstagram.com/v/t51.2885-15/e35/152476443_182067827047467_6339058443064689209_n.jpg?_nc_ht=scontent-cgk1-1.cdninstagram.com&_nc_cat=103&_nc_ohc=ojojfd1bmpAAX8G6xxm&tp=1&oh=2fd2aa94f50f3c4be5a7ef6241a7d543&oe=605E8778" style="width: 99%">
		<img src="https://scontent-cgk1-1.cdninstagram.com/v/t51.2885-15/e35/152662368_5071270742944366_1878520493734339486_n.jpg?_nc_ht=scontent-cgk1-1.cdninstagram.com&_nc_cat=110&_nc_ohc=7o_v545ypPsAX-6YW0B&tp=1&oh=a5bfb8ffd85af3c3a1e52340ca9feac0&oe=605F80F5" style="width: 49%">
		<img src="https://scontent-cgk1-1.cdninstagram.com/v/t51.2885-15/e35/153107611_152671543338382_3697700762863043129_n.jpg?_nc_ht=scontent-cgk1-1.cdninstagram.com&_nc_cat=110&_nc_ohc=k5CtrxovELIAX8eDaS4&tp=1&oh=b2da94984e7aa4d35d8b876c317a0703&oe=605DB0AB" style="width: 49%">
		<img src="https://scontent-cgk1-1.cdninstagram.com/v/t51.2885-15/e35/152397496_280729603468469_668652600429539739_n.jpg?_nc_ht=scontent-cgk1-1.cdninstagram.com&_nc_cat=105&_nc_ohc=xgu4v2LaZNwAX_yEFCI&tp=1&oh=07a9a52d781c02ae0b940335ea3740b0&oe=60601B6F" style="width: 49%">
		<img src="https://scontent-cgk1-1.cdninstagram.com/v/t51.2885-15/e35/152481598_441202917099748_622950447650737405_n.jpg?_nc_ht=scontent-cgk1-1.cdninstagram.com&_nc_cat=104&_nc_ohc=SxVLYY4mO9EAX-Xk03B&tp=1&oh=67ae80cb1df6f284dbd561fcd8d3502b&oe=605ED0A7" style="width: 49%">
	</div>
</center>

<hr><center class="banner-covid"><a href="https://covid19.karawangkab.go.id" target="_blank"><img src="https://www.karawangkab.go.id/sites/default/files/SpandukCovid19.png" /></a></center> <br> <p class="rtejustify"> Halo wargi Karawang, untuk informasi lebih lengkap. Wargi bisa akses melalui web berikut :<br> <a href="https://covid19.karawangkab.go.id" target="_blank">covid19.karawangkab.go.id</a><br> <br> Data tersebut silakan digunakan wargi untuk proaktif agar saling mengingatkan untuk menjaga diri dan mengurangi interaksi sosial di zona merah dan hitam, tanpa reaksi sosial berlebihan.<br> <br> KITA HARUS TETAP TENANG, TINGKATKAN KEWASPADAAN, DAN SELALU TERAPKAN PROTOKOL KESEHATAN 3M:<br> - MENJAGA JARAK<br> - MENCUCI TANGAN<br> - MEMAKAI MASKER<br> </p>	
<hr><strong>Follow Kominfo Official Media at</strong> <br> <i class="fa fa-facebook"></i> <a href="https://web.facebook.com/Diskominfokrwkab" target="_blank">Diskominfokrwkab</a><br> <i class="fa fa-instagram"></i> <a href="https://www.instagram.com/diskominfokrwkab/" target="_blank">@Diskominfokrwkab</a><br> <i class="fa fa-twitter"></i> <a href="https://twitter.com/Diskominfokrwkab" target="_blank">@Diskominfokrwkab</a><br> <i class="fa fa-globe"></i> <a href="https://www.karawangkab.go.id" target="_blank">www.karawangkab.go.id</a>, <a href="http://www.diskominfo.karawangkab.go.id" target="_blank">www.diskominfo.karawangkab.go.id</a>
```

## Design Image Upload

Untuk keperluan upload image, graphic editor / tools yang digunakan adalah [Affinity Designer](https://affinity.serif.com/en-gb/designer/)

Untuk upload 1 gambar, gunakan template ini: [Master 1](https://github.com/ashymee/karawangkab-news-template/blob/main/assets/Master%201.afdesign)

Untuk upload > 1 gambar, gunakan template ini: [Master 2] (https://github.com/ashymee/karawangkab-news-template/blob/main/assets/Master%203.afdesign)
