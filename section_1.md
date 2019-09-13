### Section 1 (HTML + CSS)

1. (BEM) Untuk penamaan class css-nya masih belum ada standar. coba pelajari methode BEM (<http://getbem.com/>). Methode ini pada inti-nya mengstandarkan gaya koding untuk penulisan nama class css-nya. Kita bisa ambil contoh penamaan kelas pada bootstrap .

   contoh:

   ```
   <style>
   	.box {
           // CSS CODE
   	}
   	
   	.box > .box__heading {
           // CSS CODE
   	}
   
   	.box > .box__heading > .box__heading--title {
           // CSS CODE
   	}
   	
   	// More CSS CODE
   </style>
   
   <div class="box">
   	<div class="box__heading">
   		<h3 class="box__heading--title">Hello World</h3>
   	<div>
   	<div class="box__body">
   		<p>Your content is here.</p>
   	</div>
   </div>
   ```

   

2. Penggunakaan CSS selector masih kurang efficient. seperti attribut id dan beberapa pemakaian css selector pada css-nya. berikut link referensi-nya: 

   1. <https://css-tricks.com/almanac/selectors/>
   2. <https://dev.to/willamesoares/css-selectors-reviewed-with-examples-3f29>
   3. <https://learn.shayhowe.com/advanced-html-css/complex-selectors/>

3. Untuk font-nya bisa menggunakan font google, agar bisa lebih rapih. (<https://fonts.google.com/>)

4. Sebisa mungkin attribut id hanya di pake ketika kita menggunakan javasript, dan digunakan sebagai selector unique di javascript-nya.

5. Untuk padding dan margin sebisa mungkin konstant, termasuk penggunaan warna, font-size dan font.

6. Jangan terlalu menggunakan tag `</br>`.

7. Gunakan selector h1-h6 untuk penulisan title atau judul.

8. Gunakan html tag sesuai standar SEO.