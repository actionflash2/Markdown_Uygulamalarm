# Bu bir başlık
## Bu bir alt başlık



![](https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1453&q=80)

Markdown Kullanım Rehberi
Markdown, web’de metinlerin daha iyi görünmesi için kullanılan bir söz dizimidir. Bu yazımda pratik örnekler ile markdown kullanımını anlatacağım.


Photo by Victória Kubiaki on Unsplash
Web’de yazdığımız yazıların veya blogların dikkat çekmesini isteriz. Yazılara resim eklemek veya bazı yerleri vurgulamak okuyucunun dikkatini daha çok çeker. Metinlerin daha kolay okunması için 2004 yılında John Gruber ve Aaron Swartz tarafından markdown formatı geliştirildi.

Bu yazıda özetle;

Markdown nedir?
Başlık oluşturma
Vurgulama
Listeler
Resim ekleme
Editör
gibi konuları anlatacağım.

Markdown Nedir?
Markdown, web’de metinleri biçimlendirmek için kullanılan bir formattır. Markdown ile dökünmalarınızı daha görsel hale getirebilirsiniz. Örneğin metninize resim ekleyebilir, kelimelerinizi kalın ya da italik yapabilir veya yazınızda listeler oluşturabilirsiniz.

Şimdi örnekler ile önemli markdown söz dizimlerini görelim.

Başlıklar
Bazen dökümanınızda farklı büyüklükte başlıklar kullanmak isteyebilirsiniz. Başlık oluşturmak için ‘#’ sembolü kullanılır. Çoklu ‘#’ kullanımı daha küçük başlıklar oluşturur.

# bir <h1> tag’ıdır.
## bir <h2> tag’ıdır.
##### bir <h5> tag’ıdır.

Eğer bir kişiden alıntı almak isterseniz > karakteri kullanılır.

> “Two things are infinite: the universe and human stupidity; and I’m not sure about the universe.” Albert Einstein

Vurgular
Bir kelimeyi veya cümleyi kalın yapmak için **kalın**, italik yapmak için *italik* sembolleri kullanılır. İsterseniz bunları beraber kullanabilirsiniz.

*Bu formatları *beraber* kullanabilirsiniz.**

Link Ekleme
Metin içinde link verebilirsiniz. Örneğin Google kelimesinin üzerine basıldığında Google ana sayfaya gitmek isteyelim.

[Google link](http://google.com)

Listeler
Bazen sayılar kullanarak listeler oluşturmak isteyebilirsiniz.

1. Bir
2. İki
3. Üç

Ya da maddeleri nokta ile göstermek isteyebilirsiniz.

* Bir yıldız ile başla
* Harika

Maddeleri nokta ile görmek için tire sembolünü de kullanabilirsiniz.

- Tire kullanımı
- Süper

Alt başlıklar için yıldız veya tireden önce iki boşluk bırakılır.

- Tire kullanımı
- Süper
  - Bunun gibi
  - Ve böyle

Görevleri listelemek ve yapılanları işaretlemek isteyebilirsiniz. Bunun için köşeli parantezler kullanılır.

- [x] Tamamlanmış görev
- [] Tamamlanmamış görev

Resim Ekleme
Dökümanınıza resim eklemek metni daha ilgi çekici yapabilir. Metne aşağıdaki gibi kolayca resim ekleyebilirsiniz.

![Teknoloji](https://images.unsplash.com/photo-1575755049931-8338ad979f7c?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=667&q=80)

Kod Yazma
Metne kod ekleyebilirsiniz. Metin içine kod yazmak için backticks (`) sembolü kullanılır.

Örneğin `x=[1,2,3]` şeklinde bir değişken oluşturalım.

Eğer daha uzun kod satırlar yazmak isterseniz kodlardan önce dört boşluk bırakılır.

    a = 33
    b = 33
    if b > a:
        print("b is greater than a")
    elif a == b:
        print("a and b are equal")

Kod yazmak için fencing (```) de kullanabilirsiniz.

```
if (super){
 return true
 }
```

Renkli sözdizimi kullanmak isterseniz kullanacağınız programlama dilini üst kısma yazmanız yeterli olur.

``` python
if (super){
 return true
 }
```

Tablo Oluşturma
Metinde kelimeleri ayıracak tablolar oluşturmak isteyebilirsiniz. Bunun için tire ve pipe sembolleri kullanılır.

İlk Başlık | İkinci Başlık
 — — — — — — | — — — — — — -
Birinci hücre içeriği | İkinci hücre içeriği
Birinci sütun içeriği | İkinci sütun içeriği

Markdown Editör
Markdown dosyaları genellikle .md veya .markdown uzantılıdır. Markdown dosyalarınız ile çalışmak için bir editöre ihtiyacınız olabilir. Yazdığınız markdown söz dizimlerini görmek için buradaki ücretsiz editörü kullanabilirsiniz.

Ayrıca markdown dosyası içinde emoji kullanabilirsiniz. Kullanabileceğiniz emojilere buradan ulaşabilirsiniz.
