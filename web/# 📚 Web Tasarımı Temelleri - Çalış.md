&#x09;								# 📚 Web Tasarımı Temelleri - Çalışma Notları # 

&#x09;			###temel iskelet yapısı###





\* <html> ve </html>

&#x20; - Ne işe yarar? Tüm HTML kodlarının yazıldığı ana kök etiketidir. Başlangıcı ve bitişidir.

\* <head> ve </head>

&#x20; - Ne işe yarar? Kullanıcının ekranda doğrudan görmediği; sayfa başlığı, karakter kodlaması ve CSS (stil) kodlarının tutulduğu "arka plan" alanıdır.

\* <title> ve </title>

&#x20; - Ne işe yarar? Tarayıcı sekmesinde görünen sayfa başlığını belirler.

\* <body> ve </body>

&#x20; - Ne işe yarar? Web sitesine giren kullanıcıların ekranda gördüğü metinlerin, resimlerin, butonların ve tabloların yazıldığı ana gövde alandır.



&#x09;			## 2. Başlık ve Metin Etiketleri





\* <h1> ile <h6> arası (Örn: <h1>Başlık</h1>)

&#x20; - Ne işe yarar? Başlık (Heading) oluşturur. <h1> en büyük ve en önemli başlıktır, <h6> en küçüğüdür.

\* <p> ve </p>

&#x20; - Ne işe yarar? Paragraf oluşturur. Yazıların arasında otomatik boşluk bırakarak alt alta, düzenli durmasını sağlar.

\* <br>

&#x20; - Ne işe yarar? Satır atlama (Break). Aynı paragraf içinde hemen bir alt satıra geçmek için kullanılır. Kapanış etiketi yoktur.



&#x09;			## 3. Metin Biçimlendirme Etiketleri





\* <b> veya <strong>

&#x20; - Ne işe yarar? Yazıyı kalın yapar. strong etiketi ek olarak metnin anlamsal olarak önemli olduğunu belirtir.

\* <i> veya <em>

&#x20; - Ne işe yarar? Yazıyı italik (eğik) yapar. em etiketi vurgu yapmak için kullanılır.

\* <u>

&#x20; - Ne işe yarar? Yazının altını çizer (Underline).





&#x09;			## 4. Bağlantı (Link) ve Görsel Etiketleri





\* <a href="adres" target="\_blank">Tıklanacak Metin</a>

&#x20; - Ne işe yarar? Başka bir web sayfasına veya dosyaya bağlantı (link) verir. href gideceği adresi söyler; target="\_blank" ise linkin yeni sekmede açılmasını sağlar.

\* <img src="dosya\_adi.jpg" alt="Açıklama" width="300">

&#x20; - Ne işe yarar? Sayfaya görsel ekler. src resmin kaynağını (dosya adı veya URL), alt resim yüklenemezse çıkacak yazıyı belirtir. Kapanış etiketi yoktur.



&#x09;			## 5. Tablo Etiketleri (<table>)





Verileri satır ve sütunlar halinde düzenli göstermek için kullanılır:

\* <table> ve </table>: Tabloyu başlatır ve bitirir.

\* <tr> ve </tr>: Tablo satırı (Table Row) oluşturur. Her yeni yatay sıra için açılır.

\* <th> ve </th>: Tablo sütun başlığı (Table Header) oluşturur. Yazıları otomatik kalın ve ortalanmış yapar.

\* <td> ve </td>: Tablo hücresi (Table Data) oluşturur. Normal verileri içine yazarsın.



&#x09;			## 6. CSS (Stil ve Tasarım) Komutları





Tasarım ve renkleri <head> içindeki <style> etiketi arasına yazarız:



\* background-color: renk;

&#x20; - Ne işe yarar? Arka plan rengini değiştirir (Örn: background-color: #2c3e50;).

\* color: renk;

&#x20; - Ne işe yarar? Yazı rengini değiştirir (Örn: color: white;).

\* text-align: center;

&#x20; - Ne işe yarar? Yazıları veya içeriği yatay olarak ortalar. (left sola, right sağa yaslar).

\* font-family: Arial, sans-serif;

&#x20; - Ne işe yarar? Yazı tipini (fontunu) değiştirir.

\* display: flex; justify-content: center; align-items: center;

&#x20; - Ne işe yarar? İçerikleri ekranın tam ortasına (hem yatay hem dikey) sabitlemek için kullanılır.

\* border-radius: 15px;

&#x20; - Ne işe yarar? Kutuların veya butonların köşelerini yumuşatır, ovalleştirir.

\* :hover (Örn: .btn:hover)

&#x20; - Ne işe yarar? Fareyle bir elementin (butonun vb.) üzerine gelindiğinde ne olacağını belirler (örneğin renk değişimi veya yukarı kalkma efekti).

