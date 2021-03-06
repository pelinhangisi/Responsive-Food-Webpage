* Öncelikle HTML-CSS ve JS dosyalarımızı oluşturuyoruz.

* HTML dosyası içerisine kullanacağımız dosyaların tanımlamasını yapıyoruz. (CSS-Fontawesome-Bootstrap-Google Fonts-JS vb.)

* HTML dosyası içerisinde Tasarlanılacak olan sayfayı bölümlere ayırıyoruz.

<h4>Section 1 >> </h4>

* HTML >> <br>
* Başlık kısmı oluşturma. <br>
* Fontawesome ile ikon oluşturma. <br>
<img src="ReadMeImages/r1.jpg">


* Oluşturulan kısımların CSS parçasını hazırlama. <br>
* CSS >> <br>
    * Kullanılacak olan yazı tipi google fonts aracılığı ile css dosyasına import edildi.  <br>
    * Bütün sayfa genelinde kullanılacak olan CSS özellikleri tanımlandı. <br>
    * Section 1 bölümü için CSS özellikleri tanımlandı. (Başta genel section-1 özellikleri tanımlanırken akabinde başlık ve ikonlar ile alakalı css özellikleri tanımlandı.) <br>
<img src="ReadMeImages/r2.JPG">

* Section-1 kısmı ile alakalı ikonların geçişini sağlamak için JS parçası oluşturuldu. <br>
* JS >> <br> 
    * İlk olarak bütün ikonları içeren bir "icons" değişkeni tanımlandı ve 4 saniye aralıklar ile ikonların sırası ile ekranda görünüp kaybolması adına method yazıldı. Son ikondan sonra sırası gelecek bir ikon olmadığı için başa dönmesini sağlayacak koşul eklendi. <br>
<img src="ReadMeImages/r3.JPG"> <br><br> 
<hr>
<h4>Section 2 >> </h4> 

* HTML >>
    * "heading" için css te düzenlenen özellik buradaki başlık içinde aynı olacağı için aynı class tanımlaması yapıldı ve ".heading / css" kısmı genel ortak kullanım için hazırlanan kısıma eklendi. (Common Style) <br>
    * 3 adet İsim, Resim ve Sipariş verme butonu içeren kart oluşturuldu. <br>
<img src="ReadMeImages/rr4.JPG">

* CSS >>
    * Section 2 bölümü için CSS özellikleri tanımlandı. Öncelikle oluşturulan kartların özelliği verilirken aynı zamanda kart içerisinde yer alan resimlerin, isimlerin ve sipariş ver butonunun css özellikleri tanımlandı.
    * box-shadow, transform, transition, before, after ve hover özellikleri ile hareketli ve üç boyutlu kart tasarımı ortaya çıkarıldı. <br>
<img src="ReadMeImages/r5.JPG">
<img src="ReadMeImages/r6.JPG">
<img src="ReadMeImages/r7.JPG"> <br>
<hr>
<h4>Section 3 >> </h4>

* HTML >>
    *  "heading" için css te düzenlenen özellik buradaki başlık içinde aynı olacağı için aynı class tanımlaması yapıldı.
    * 6 adet ürün fotoğraflarının, isimlerinin ve açıklamalarının yer alacağı link elementleri oluşturuldu.
<img src="ReadMeImages/r8.JPG">
<img src="ReadMeImages/r9.JPG">

* CSS >>
    * Section 3 bölümü için CSS özellikleri tanımlandı. Öncelikle oluşturulan kartların özelliği verilirken aynı zamanda kart içerisinde yer alan resimlerin, isimlerin ve sipariş ver butonunun css özellikleri tanımlandı.
    * box-shadow, transition, before-after, hover, filter ve opacity özellikleri ile hareketli ve üç boyutlu görsel çalışmalar ortaya çıkarıldı. <br>
<img src="ReadMeImages/r10.JPG">
<img src="ReadMeImages/r11.JPG">
<img src="ReadMeImages/r12.JPG">
<img src="ReadMeImages/r13.JPG"> <br>
<hr>

* HTML >>
    * Footer kısmı"heading" için css te düzenlenen özellik buradaki başlık içinde aynı olacağı için aynı class tanımlaması yapıldı.
    * Footer kısmı olarak belirlenen bu bölümde, "submit" ile giriş yapılacağı buton ayarlandı. Email adresini girebileceği bölüm ve "Bütün hakları saklıdır" bölümü ayarlandı. İkon tanımlaması yapıldı. <br>
<img src="ReadMeImages/rr14.JPG"> <br>

* CSS >>
    * Section 4 bölümü için CSS özellikleri tanımlandı.Buradaki heading kısmı farklı özellikte olacağı için farklı bir class ismi atandı. <br>
    * Footer kısmında olması gereken yerleşimler belirlenip css özellikleri tanımlandı. <br>
<img src="ReadMeImages/r15.JPG">
<img src="ReadMeImages/r16.JPG">
<img src="ReadMeImages/r17.JPG"> <br>
<hr>

* HTML >>
    * Navbar Html kısmı Home-Meals-Burger-Pizza-Contact içerecek şekilde link kısımları ve ikon kısımları oluşturuldu. <br>
    * Css kısmında şekillendirilmek üzere bir div içerisinde menu tanımlaması yapıldı. <br>
<img src="ReadMeImages/rr18.JPG"> <br>

* CSS >>
    * Navbar içerisinde yer alan linkler ve ikonlar before, hover, box-shadow gibi özellikler ile tanımlanıp JS de event eklenebilmesi için hazır hale getirildi. <br>
    * Navbar kısmı açıldığı anda içerisinde yer alan ikonların sırası ile ekrana gelmesi için .change .navbar-link:nth-child() özelliği kullanıldı. <br>
<img src="ReadMeImages/r19.JPG">
<img src="ReadMeImages/r20.JPG">
<img src="ReadMeImages/r21.JPG">


* JS >>
    * Navbar kısmında yer alan isimler ve ikonların gizlenip tekrar görüntülenebilmesi için event eklemeleri yapıldı. <br>
    * menu içerisinde click eventi tanımlandıktan sonra arrow function ile bütün .target sınıfına sahip olanlar seçildi ve forEach metodu kullanılırken, toggle kullanımı ile aynı anda hareket edebilme özelliği sağlandı. <br>
<img src="ReadMeImages/r22.JPG"> <br><br>
<hr>

* PROJEYİ RESPONSIVE YAPMAK.
    * Responsive yapıya ulaşabilmek için CSS dosyamızın içerisinde media querie kullanımı yapıyoruz. Responsive yapıya ulaşabilmek için belli breakpoint noktaları yani max-width dediğimiz ekran ölçüleri belirleyip özelliklerimi şekillendiriyoruz. <br>
<img src="ReadMeImages/r23.JPG">
<img src="ReadMeImages/r24.JPG">
<img src="ReadMeImages/r25.JPG">







