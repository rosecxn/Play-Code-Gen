### Google Play Hediye Kartları - Kod Üretici

#### Hakkında

---

**CPA Landing Pages** – "Cost Per Action" pazarlamasıyla para kazanmanız için yalnızca en iyi açılış sayfalarını bulup sizlere sunuyoruz. Açılış sayfasındaki tüm dosyalar küçültülmüş (minify) olacaktır (görseller, scriptler, stiller), ancak düzenlemek veya geliştirmek isterseniz bunları her zaman güzelleştirebilirsiniz.

> HTML, CSS, JS dosyalarını güzelleştirmek veya yeniden küçültmek için [Minify Code](http://minifycode.com/) kullanabilirsiniz.

#### Önizleme

---

![Landing Page Preview](https://github.com/cpa-landing-pages/google-play-cards/blob/master/preview.png)

#### İndir

---

[<img src="http://svgshare.com/i/28_.svg" width="40%" alt="Download" />](https://github.com/cpa-landing-pages/google-play-cards/archive/master.zip)

#### Nasıl Kullanılır

---

##### Başlamadan önce

* Bir kod düzenleyicisine ihtiyacınız olacak. Eğer yoksa, şu düzenleyicilerden birini öneriyoruz:
  [Notepad++](https://notepad-plus-plus.org/download/v7.4.2.html)
  [Sublime Text](https://www.sublimetext.com/3)

> Adım 1

* Yukarıdaki butonla açılış sayfasını indirin.

> Adım 2

* Dosyaları çıkarın ve çıkan klasörü açın.

> Adım 3

* Ana site içeriğini değiştirmek için `generator.php` dosyasını açın ve istediğiniz değişiklikleri yapın.

> Adım 4

* İçerik kilidi (content locker) eklemek için favori CPA ağınıza gidin ve talimatlarını izleyin. Her durumda `<head>` etiketi içine eklemeniz gereken bir `<script>` olacaktır ve ardından içerik kilidi çağrısını bir butona eklemeniz gerekir. `generator.php` içinde `locker` kelimesini arayın; içinde `alert('demo')` içeren bir fonksiyon göreceksiniz. Bu fonksiyon butona tıklandığında `demo` mesajını gösterir. Sadece `alert('demo')` bölümünü kendi içerik kilidi çağrınızla değiştirin (örneğin: `call_locker()`).

> Adım 5 (isteğe bağlı)

* CSS'i değiştirmek için `css/main.min.css` dosyasını açın ve güzelleştirin. "CSS Beautify" diye aratabilir veya bahsettiğimiz araçları kullanabilirsiniz. İşiniz bittiğinde dosyayı tekrar küçültmeyi unutmayın; bu daha hızlı sayfa yüklenmesini sağlar.

> Adım 6 (isteğe bağlı)

* JS'i değiştirmek için `js/script.min.js` dosyasını açın ve güzelleştirin. "JS Beautify" diye aratabilir veya bahsettiğimiz araçları kullanabilirsiniz. Düzenlemeler tamamlanınca dosyayı yeniden küçültün.

> Adım 7 (isteğe bağlı)

* Açılış sayfası bir "konsol" içeriyorsa ve bu konsol "üretici" mesajlarını gösteriyorsa, `generator.php` dosyasında `consoleMessages` araması yaparak bu mesajları düzenleyebilirsiniz.
