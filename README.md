# CSS
CSS, sıkça kullanılan ancak gerçekte yeterince açıklanmayan şeylerden biridir. Öncelikle ilk olarak teknik kısımla başlayabiliriz. CSS zamanla web'i daha güzel yapan bir şeyden, kullanıcı deneyimi psikolojisi ve dönüşümü tetikleyen kalıplarla ilham verebilecek bir araca dönüştü. Tüm bunlara ek olarak, tarayıcılar ve ekran boyutu gereksinimlerindeki farklılıklar, CSS'nin potansiyelini biraz daha ileri gereksinimler yoluyla karmaşık olmaya itiyor. CSS'de arka plan renklerini değiştirmekten ve nesnelerin neden olması gerektiği gibi hizalanmadığını merak etmekten daha fazlası vardır. 
JavaScript frameworkleri ve kütüphaneleri gibi diğer şeye zaman ayırdığımız için, CSS genellikle gözden kaçan ve arka planda kalan görsel bir iletişim aracıdır. Genellikle temel çalışma yeterliliğine sahip CSS'yi alırız ve acil hedeflerimize ulaşır ulaşmaz daha derine inmeden bırakrız. Sonuç olarak uygulama genelinde yapı, mimari ve uyum gibi şeyleri göz ardı etme eğilimindeyiz ancak şimdi bu yazımızda bu tabularımı yıkarak en baştan başlayalım.

# CSS(Cascading Style Sheets) Nedir?
CSS (Basamaklanmış Stil Katmanları), web sayfasını şekillendirmek için kullanılan bir kodlama türüdür. CSS kullanarak web sayfasının görünümünü ve düzenini değiştirebiliriz. Bir web sitesinin görünümünün masaüstü bilgisayarlar, tabletler ve mobil cihazlar gibi farklı ekranlarda nasıl değiştiğini de tanımlayabiliriz. CSS, C ++ veya JavaScript gibi bir programlama dili değildir. Bunun nedeni, CSS'nin amacının web tarayıcıları için biçimlendirmeye (HTML'ye) stil vermek olmasıdır. HTML yalnızca içeriği "işaretleyen" bir dildir - yani, belgeye belirli bir görsel ve yapısal biçimlendirme verir.
Hem HTML hem de CSS doğaları gereği bildirimseldir. Bu, yalnızca bir şeyleri açıkladığı ve herhangi bir işlem yapmadığı anlamına gelir.Tarayıcılar CSS'yi görüntüleme için yorumlarken, bunu doğrusal bir şekilde yapar. Bunun nedeni, CSS'nin dosyayı yukarıdan aşağıya okuyan tarayıcıya talimatlar vermesidir. Bir kural belirlendiğinde ve daha sonra dizin aşağıya doğru değiştirildiğinde, tarayıcı ekranda görüntülenecek nihai sonuç olarak en son değerlendirmeyi alır. CSS'deki C'nin ifade ettiği şey budur. CSS'nin kaskad etkisi, tarayıcıyı, kuralın fiziksel olarak ne zaman gerçekleştiğine bağlı olarak, kuralları art arda ve geçersiz kılacak şekilde görüntüleyecek şekilde ayarlar.Cascade(kaskad), öğe için birden çok CSS bildirimi ve birden çok stil sayfasının bir kombinasyonu olduğunda belirli bir öğe için uygulanan stiller arasındaki çakışmayı çözme anlamına gelir. Sonuç olarak, CSS göründüğü kadar kolay değildir. Anlamadan kullanmaya çalışırsanız web geliştirmede zorluk yaşarsınız. Bu nedenle, CSS öğrenmek bir programlama dili öğrenmek kadar önemlidir.
  
# CSS Syntax
İlk CSS kodumuzu yazalım. Örneğin, "h1" etiketinin rengini değiştirmek istiyorum.
  
  ``` <h1>I'm a Header</h1> ```

![png.1](https://miro.medium.com/max/2400/1*XTrm27qwPboOnC35WYUpHQ.png)

Öncelikle, CSS'ye HTML öğesini nasıl bulacağını söylememiz gerekir. Bunu "selector" denen bir özellik ile yapabiliriz. CSS'de bir selector, HTML öğelerini etiket adı, sınıf adı, kimliği ve çok daha fazlasına göre bulmak için kullanılır. O zaman şimdi HTML öğesi için bir selector tanımlayalım ve ardından selector parantezleri arasında her biri noktalı virgülle biten CSS kurallarını bildirelim.

  ``` h1 { color: red;  // CSS rules between brackets}```

![png.2](https://miro.medium.com/max/700/1*YrShrgFIf1Ee3ztba6CI8w.png)

Böylelikle, tanımlı selector'e (h1) bağlı olarak, CSS artık yeni kuralların nereye uygulanacağını anlayabilir.

Bir CSS selector tanımlamanın birçok farklı yolu vardır, aşağıda selector türlerinin bazı örneklerini görebilirsiniz:
-Class Selector: HTML öğelerini sınıf özelliklerine göre bulur
-Id Selector: öğeleri belirli kimliğine göre bulur
-Element Selector: öğeleri etiket adlarına göre bulur


