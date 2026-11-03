# ☕ kahvelerce

**Bir kahve, kaç karar?**

Sabah kahveni söylerken aslında kaç karar verdiğini hiç saydın mı? Sıcak mı soğuk mu, hangi demleme, süt olacak mı, olacaksa hangisi, yanına ne... Bu site o küçük kararları tek tek görünür kılmak için yapıldı.

👉 **Dene ve kendi sayını gör → [kahvelerce.com](https://kahvelerce.com)**

---

## Sitede neler var

| Sayfa | Ne yapıyor |
|---|---|
| [Bir kahve, kaç karar?](https://kahvelerce.com) | Kahveni adım adım seçiyorsun, üstte sayaç dönüyor. Başta kaç karar vereceğini tahmin ediyorsun, sonda gerçek sayıyla karşılaştırıyorsun. |
| [138 milyon kahve](https://kahvelerce.com/olasiliklar.html) | Uygulamadaki seçeneklerle **138.269.568** farklı kahve yapılabiliyor. Bu sayfa o sayıyı somutlaştırıyor. Rastgele kahve üretici, sıra numarasıyla kahve bulma ve hesabın açık dökümü burada. |
| [Günde kaç karar veriyoruz?](https://kahvelerce.com/blog/gunluk-kararlar.html) | Çok paylaşılan "günde 35.000 karar" iddiasının peşine düşen, araştırmaların gerçekte ne dediğine bakan blog yazısı. |

## Nasıl yapıldı

Bilerek sade tutuldu.

- **Statik site.** Sadece HTML, CSS ve vanilla JavaScript. Framework yok, build adımı yok, sunucu tarafı kod yok.
- **Her sayfa tek dosya.** CSS ve JS dosyanın içinde, illüstrasyonlar satır içi SVG.
- **Harici bağımlılık yok.** Kütüphane, CDN, Google Fonts kullanılmıyor.
- **Çerez, analitik, form yok.** Ziyaretçiden hiçbir veri toplanmıyor, bu yüzden çerez bandı da yok.
- **Mobil öncelikli.** Ziyaretçilerin çoğu telefondan geliyor, her ekran önce telefona göre tasarlandı.
- **Barındırma** GitHub Pages üzerinde, alan adı GoDaddy'de.

## Dosyalar

```
/
├── index.html               ← "Bir kahve, kaç karar?" uygulaması
├── olasiliklar.html         ← 138 milyon kahve sayfası
├── 404.html                 ← bulunamayan sayfa
├── LICENSE                  ← kodun MIT lisansı
├── README.md                ← bu dosya
└── blog/
    └── gunluk-kararlar.html ← blog yazısı
```

## Kendi bilgisayarında açmak

Kurulacak bir şey yok. Depoyu indir ve `index.html` dosyasını tarayıcıda aç, o kadar.

## Kaynaklar hakkında

Blog yazısındaki ve 138 milyon sayfasındaki rakamlar kaynaklarıyla birlikte verildi. Doğrulanamayan popüler iddialar gerçekmiş gibi değil, "çok paylaşılan ama kaynağı belirsiz" diye ele alındı.

## Lisans ve telif

- **Kod** (HTML, CSS ve JavaScript) [MIT lisansı](LICENSE) ile paylaşılıyor. Kullanabilir, değiştirebilir, kendi projende kullanabilirsin. Tek şart lisans metninin ve telif satırının korunması.
- **Yazılar, sayfa metinleri ve illüstrasyonlar** MIT lisansına dahil değil. © 2026 Halil İbrahim Erdoğan, tüm hakları saklıdır. Alıntı yapmak istersen kaynak göstermen ve bağlantı vermen yeterli. Metnin tamamını ya da büyük bir bölümünü kopyalamak için izin gerekiyor.

Blog yazısı [Substack](https://hierdogan.substack.com) sayfamda da yayımlanıyor.

---

*Yarınki kahven için kaç karar vereceksin? [Dene →](https://kahvelerce.com)*
