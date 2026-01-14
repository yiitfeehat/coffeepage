# Noir Roast Kahve Websitesi ☕

![Noir Roast](./img/coffeePage.gif)

Bu proje, sofistike ve modern bir kullanıcı deneyimi sunmak için tasarlanmış **Premium Kahve Dükkanı Websitesi**dir. **Noir Roast** marka kimliğini etkili bir şekilde yansıtmak için tamamen duyarlı (responsive) bir tasarım, zengin koyu kahve & altın estetiği ve etkileşimli öğeler içerir.

## 🌟 Özellikler

*   **Premium Estetik:** Üst düzey bir kahve evi hissi uyandıran uyumlu bir "Dark Roast & Gold" renk paleti (`#2C1A1D`, `#D4A373`).
*   **Responsive (Duyarlı) Tasarım:** **Bootstrap 5** ile oluşturulmuş, mobil, tablet ve masaüstü cihazlarda kusursuz görünüm.
*   **Hero Carousel:** Markanın atmosferini ve öne çıkan ürünlerini vurgulayan sürükleyici bir kaydırıcı.
*   **Etkileşimli Menü:** Yüksek kaliteli görsel önizlemeleri için **fslightbox** entegre edilmiş sekmeli menü sistemi (Kahve, Yemek, Tatlı).
*   **Ekip Tanıtımı:** Uzman baristaları ve şefleri tanıtan, hover (üzerine gelince) efektli kartlara sahip özel bir bölüm.
*   **İletişim Bölümü:** Şık bir iletişim formu ve özel olarak filtrelenmiş Google Haritalar entegrasyonu.
*   **Akıcı Animasyonlar:** Dinamik bir kullanıcı deneyimi için CSS geçişleri ve hover efektleri.

## 🛠 Kullanılan Teknolojiler

### Frontend
*   **Çekirdek:** HTML5, CSS3, JavaScript (Vanilla)
*   **Framework:** Bootstrap 5.3
*   **Stil:** Özel CSS Değişkenleri, Flexbox, Grid, Google Fonts (Plus Jakarta Sans)
*   **Kütüphaneler:** `fslightbox.js` (Resim Galerisi), `Bootstrap Icons`

## 📂 Proje Yapısı

```
/
├── css/                
│   └── style.css       # Ana stil dosyası (Özel stiller ve overridelar)
├── img/                # Proje görselleri
│   ├── menu/           # Menü ürün görselleri (kahve, yemek, tatlı)
│   ├── team/           # Ekip fotoğrafları
│   └── ...             # Slider ve statik görseller
├── lib/
│   └── fslightbox.js   # Görsel galerileri için Lightbox kütüphanesi
└── index.html          # Ana uygulama giriş noktası
```

## 🚀 Kurulum ve Kullanım

Bu statik bir websitesidir, bu nedenle karmaşık bir backend kurulumu gerektirmez.

1.  **Repository'i klonlayın:**
    ```bash
    git clone https://github.com/kullaniciadiniz/noir-roast.git
    ```
2.  **Proje dizinine gidin:**
    ```bash
    cd noir-roast
    ```
3.  **Projeyi çalıştırın:**
    *   `index.html` dosyasını herhangi bir modern web tarayıcısında açmanız yeterlidir.
    *   Alternatif olarak, daha iyi bir geliştirme deneyimi için bir canlı sunucu eklentisi (VS Code Live Server gibi) kullanabilirsiniz.

## 🎨 Tasarım Felsefesi

Tasarım, **"Noir" (Siyah/Koyu)** ve **"Roast" (Sıcaklık/Altın)** kavramlarına odaklanır.
*   **Birincil:** Dark Espresso (`#2C1A1D`)
*   **İkincil:** Latte Gold (`#D4A373`)
*   **Vurgu:** Light Crema (`#FAF9F6`)

Butonlardan form girişlerine kadar tüm bileşenler, varsayılan Bootstrap görünümünden sıyrılarak benzersiz bir "Noir Roast" kimliği sunacak şekilde özelleştirilmiştir.
