# Ödev 2

## Bootstrap ile Instagram Clone

![instagram](https://github.com/Kodluyoruz/taskforce/raw/main/bootstrap/odev2/figures/instagram.gif)

Yukarıda görmüş olduğunuz şahane yapıyı Kodluyoruz mühendisleri üstün dil CSS ile 6 yıl boyunca Ağrı Dağı eteklerinde geliştirdiler. Büyük acılar, büyük zorluklar sonrası bu muhteşem yapıyı oluşturdular desek tabii ki doğru olmaz. Bootstrap ile sizin için böyle bir yapı geliştirdik ve geliştirme sırası şimdi sizde. Bütün vicdansızlığımızı kullanarak yukarıdaki yapıyı aşağıdakine dönüştürdük ve gerekli düzenlemeleri yaparak bu yapı üzerinde çalışıp bu clone'u tekrar yazmanızı istiyoruz.

![brokeninstagram](https://github.com/Kodluyoruz/taskforce/raw/main/bootstrap/odev2/figures/instagrambroken.gif)

**Hazırlamış olduğumuz Instagram clone'una** [**buradan**](https://drive.google.com/drive/folders/1hRWmpYpuax4Aqsf_BRKdpDoNUowTpzKe?usp=sharing) **ulaşabilirsiniz.**

### Sizden Beklediklerimiz

-   Navbar'ı yukarı  **sabitleyip**  sayfayı aşağı kaydırdığınızda hala yukarıda durmasını sağlayın. İçerik ile birleşmemesi için body'e  `padding`  veriniz.
-   Navbarın  `height`'ı  **54 px**  olmalı ve arkaplan rengi  **beyaz**  olmalı.
-   Navbar'daki elementlerin doğru yerde olmadığını fark ettiniz mi? Öncelikle navbar'ın başındaki logo class'ının içine  **192px soldan**  `margin`  verin.
-   Arama kısmını  `d-flex`  ile ortay alıp  **soldan 5 birim**  `margin`  verin.
-   CSS dosyası içindeki  `::placeholder`  kısmının arkaplanına assets klasörü içinde bulunan arama simgesini ekleyin. Ve resmin  **tekrar etmemesini**  sağlayın.

**_Clone ödevimizdeki ikonları_** [**_FontAwesome_**](https://fontawesome.com/) **_sitesinden aldık. Daha detaylı bilgi için web sitesini ziyaret edin ve nasıl çalıştığını öğrenin._**

-   Sağ üstte yer alan menü kısmına  **soldan 5 birim üstten 2 birim**  `margin`  verin.
-   Sağ üstte yer alan menü kısmına sayfa  **sm**  boyutunda olunca kaybolacak şekilde  `display`  verin. Bunun için  [Bootstrap Display property](https://getbootstrap.com/docs/4.5/utilities/display/)  sayfasını inceleyebilirsiniz.
-   İçerik alanı(ortadaki gönderilerin olduğu alan)  `offset`  **4**  olmalı ve  **üstten 2**  birim  `margin`  almalı.
-   Class'da belirttiğimiz  `middlearea`  içinde maksimum yükseklik  **200px**  olmalı ve bunu  `important`  ile yazmalısınız.  _(_`_important_`_'ın ne olduğunu, ne işe yaradığını henüz bilmiyorsanız bir "Css important nedir?" şeklinde aramanızı ve ne işe yaradığını öğrenmenizi öneririz. Unutmayın parametre vermek bazen istemediğiniz durumlara yol açabilir bilinçli kullanmak gerekir.)_
-   Bu alanın  `col`'unun default değerini  **12**, diğer tüm ölçekleri ise  **6**  olarak ayarlayın. Yani normal boyutta 12, sayfa küçülüp büyüdükçe, boyutuyla oynadıkça 6 ölçek olacak şekilde ayarlayın.  _(_`_Grid_` _sistemin 12'lik olduğunu hatırlayın)_
-   Hikayeler kısmında isimler nasıl resimlerin altına gelecek?  _(İpucu: Arama kısmında kullandığımız özellik)_
-   İçerik kısmında üç nokta sağda olmalı.
-   Beğenme, yorum yapma, paylaşma kısmında  `border`  **olmamalı.**
-   Bookmark ikonunun  `offset`'i  **7**  birim olmalı.
-   Card header ve card footer'lar  **beyaz**  renk olmalı.
-   Yorum paylaş metnini  **sağa**  alın.
-   Sağ panele verilen alan sizce yeterli mi? Değilse düzeltin.
-   Sağ panel için  `stickysidebar`  ve  `rightpanel`  diye iki class verdiğimizi fark etmişsiniz.  `Stickysidebar`  bu panelin sayfayı aşağı kaydırdıkça onun da gelmesini sağlıyor. Bunu sağlamak için için CSS'in  [position property](https://www.w3schools.com/css/css_positioning.asp)'sini kullanabilirsiniz.  `Rightpanel`'de de arkaplan rengi  **beyaz**  olup  **kenarlık olmamalı**.
-   Tümünü gör ve takip et yazılarını  **sağa**  alınız.
-   Bütün sayfanın arkaplan rengini Instagram'dan alıp uygulayın.

Burada belirtmediğimiz ama gözünüze takılan bir yer olursa orayı da düzeltin. Bu ödev için bol bol Instagram sitesini  **inspect/incele**  etmeniz gerekecek.

Buradaki ana amacımız Bootstrap elementlerini kullanarak ve özellikle deneyip yanılarak doğru yöntemi bulmanız. Mükemmel olmasına gerek yok. Unutmayın efektif olması mükemmel olmasından daha önemlidir.

![arog](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/bootstrap/odev2/figures/arog.jpg)

Hepinize başarılar, kolay gelsin!

![index](https://github.com/Mua12/frontend-web-dev-101/blob/main/BOOTSTRAP/000_BOOTSTRAP_ODEVLER/Odev_2/assets/md.png)
