# Kolay Yemek Tarifleri API - Geliştirici Kuralları (Contributing)

Bu açık kaynaklı JSON veri deposunu (Kolay Yemek Tarifleri API) projelerinizde kullandığınız için teşekkür ederiz!

Bu depo, **YemekYarismasi.com** veritabanında yer alan gerçek, denenmiş ve besin değerleri hesaplanmış yemek tariflerinin herkese açık (Open Data) bir yansımasıdır.

## Veri Güncellemeleri Hakkında

Bu depodaki tüm `.json` dosyaları ve `README.md` dosyası, ana sunucularımızdan otomatik bir yazılım (Bot) aracılığıyla senkronize edilmektedir. Bu nedenle:

- 🚫 Lütfen doğrudan JSON dosyaları veya README üzerinde değişiklik yaparak Pull Request (PR) **GÖNDERMEYİN**. Otomatik sistem bu değişiklikleri bir sonraki senkronizasyonda ezeceği için PR'lar maalesef kabul edilememektedir.
- 💡 Eğer verilerde bir eksiklik, besin değerlerinde bir hata veya API yapısında bir bozukluk tespit ederseniz, lütfen doğrudan **Issues** sekmesi üzerinden bize bir hata kaydı açın. Yazılım ekibimiz ana veritabanında düzeltme yaptığında, buradaki JSON'lar da otomatik olarak güncellenecektir.

## Uygulamalarınızda Kullanım Şartı 🤝

Verilerimiz tamamen ücretsiz olup, ticari veya hobi amaçlı projelerinizde özgürce kullanabilirsiniz (Mobil uygulamalar, web siteleri, yapay zeka eğitim setleri vb.).

Açık kaynak kültürünü yaşatmak ve sunucu maliyetlerimizi karşılayabilmek için **tek bir şartımız** bulunmaktadır:
> API'den çektiğiniz veriyi (tarifi) kendi uygulamanızda veya sitenizde son kullanıcıya gösterirken, **mutlaka** tarifin asıl kaynağı olan [YemekYarismasi.com](https://yemekyarismasi.com)'a veya tarifin spesifik URL'sine (JSON içindeki `detayli_tarif_url` alanında bulunur) tıklanabilir bir referans linki (Backlink) vermelisiniz.

Örnek Kullanım:
*Tarifin tüm adımları ve ipuçları için kaynak: [YemekYarismasi.com](https://yemekyarismasi.com)*

Bizi desteklediğiniz için teşekkür ederiz, afiyet olsun! 👨‍🍳👩‍💻
