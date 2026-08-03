# 🍲 KolayYemek - Açık Veri API'si

Bu depo, [YemekYarismasi.com](https://yemekyarismasi.com) üzerinde yayınlanan gerçek yemek tariflerinin özet verilerini açık kaynak (Open Data) olarak geliştiricilere sunmaktadır.

Mobil uygulama, web sitesi veya beslenme/kalori takip botu geliştiren yazılımcılar; Türkiye'nin en sevilen tariflerinin temel bilgilerini (besin değerleri dahil) uygulamalarında ücretsiz olarak kullanabilirler.

## 🚀 Otomatik Oluşturulan API'ler

Tüm veriler `yemekyarismasi.com` veritabanından dinamik olarak çekilmektedir:

- 🍽️ **[SALATA TARIFLERI API](./salata-tarifleri.json)**
- 🍽️ **[KURABIYE TARIFLERI API](./kurabiye-tarifleri.json)**
- 🍽️ **[KREP TARIFLERI API](./krep-tarifleri.json)**
- 🍽️ **[BURGER TARIFLERI API](./burger-tarifleri.json)**
- 🍽️ **[KAHVALTILIK TARIFLERI API](./kahvaltilik-tarifleri.json)**
- 🍽️ **[TAVUK TARIFLERI API](./tavuk-tarifleri.json)**
- 🍽️ **[BOREK TARIFLERI API](./borek-tarifleri.json)**
- 🍽️ **[KEK TARIFLERI API](./kek-tarifleri.json)**
- 🍽️ **[ET TARIFLERI API](./et-tarifleri.json)**
- 🍽️ **[PASTA TARIFLERI API](./pasta-tarifleri.json)**
- 🍽️ **[POGACA TARIFLERI API](./pogaca-tarifleri.json)**
- 🍽️ **[TATLI TARIFLERI API](./tatli-tarifleri.json)**
- 🍽️ **[DOLMA TARIFLERI API](./dolma-tarifleri.json)**
- 🍽️ **[BALIK TARIFLERI API](./balik-tarifleri.json)**
- 🍽️ **[MAKARNA TARIFLERI API](./makarna-tarifleri.json)**
- 🍽️ **[KIYMALI TARIFLER API](./kiymali-tarifler.json)**
- 🍽️ **[SEBZE TARIFLERI API](./sebze-tarifleri.json)**
- 🍽️ **[BAKLAVA TARIFLERI API](./baklava-tarifleri.json)**
- 🍽️ **[SOS TARIFLERI API](./sos-tarifleri.json)**
- 🍽️ **[HAMUR ISI TARIFLERI API](./hamur-isi-tarifleri.json)**
- 🍽️ **[MEZE TARIFLERI API](./meze-tarifleri.json)**
- 🍽️ **[DURUM TARIFLERI API](./durum-tarifleri.json)**

### JSON Yapısı Örneği

```json
{
  "id": 25,
  "baslik": "Gerçek Veri Başlığı",
  "hazirlik_suresi": "30 dk",
  "gorsel_url": "https://yemekyarismasi.com/img/foto.jpg",
  "besin_degerleri": {
    "kalori": "320 kcal",
    "protein": "12g",
    "yag": "18g",
    "karbonhidrat": "28g"
  },
  "detayli_tarif_url": "https://yemekyarismasi.com/kategori/tarif-slug"
}
```

## ⚠️ Kullanım Koşulları (ÖNEMLİ)

Geliştiriciler bu veriyi projelerinde özgürce kullanabilirler. Ancak:
1. Uygulamanızda veya sitenizde tarifi listelerken, **tarifin yapılış aşamaları için kullanıcıları mutlaka `detayli_tarif_url` adresine, yani YemekYarismasi.com'a yönlendirmelisiniz.**
2. Verilerin ticari amaçla kopyalanıp satılması yasaktır.

Destek ve iletişim için [sitemizi ziyaret edin](https://yemekyarismasi.com).
