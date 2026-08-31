# 🏠 Ev Planı Tasarımcısı (Floor Plan Designer)

Modern, kullanımı son derece kolay ve web tabanlı bir 2D oda planlama ve mobilya yerleştirme uygulaması. 

Tarayıcınızda doğrudan çalışır; kurulum, sunucu veya bağımlılık gerektirmez.

![Uygulama Ekran Görüntüsü](index.html) *(Uygulama tek dosya HTML5 Canvas üzerinedir)*

---

## ✨ Özellikler

### 📐 Oda Çizimi & Ölçülendirme
- **Metre / Santimetre Desteği**: Tek tıkla `m` ve `cm` birimleri arasında geçiş yapabilme.
- **Hassas Boyutlandırma**: Genişlik ve yükseklik değerlerini girerek oda ekleme.
- **Oda Tipleri & Renkler**: Salon, Yatak Odası, Mutfak, Banyo, Çalışma Odası, Balkon vb. için özel renk ve ikonlar.
- **Otomatik Ölçü Çizgileri**: Odaların kenarlarında dinamik olarak boyut gösterimi.

### 🪑 Zengin Mobilya Kütüphanesi
- **28+ Hazır Mobilya**: Yataklar, koltuklar, masalar, beyaz eşyalar, banyo elemanları, kapı ve pencereler.
- **Özel Eşya Çizimi**: Kendi istediğiniz isim, renk ve ölçülerde özel eşya oluşturabilme.
- **Sürükle & Bırak**: Mobilyaları odalara kolayca yerleştirme ve taşıma.
- **Döndürme (Rotate)**: Mobilyaları 90° açıyla döndürme (`R` tuşu).

### 📏 Mesafe & Ölçüm Aracı (Ruler Tool)
- **Akıllı Köşe Kilitlenme (Snap-to-point)**: Mobilya ve oda köşelerine/merkezlerine otomatik yapışma.
- **Noktadan Noktaya Ölçüm**: İki nokta arasındaki mesafeyi canlı olarak ölçme.
- **Ölçümleri Saklama**: Yapılan ölçümler tuval üzerinde kalır ve PNG çıktısına dahil edilir.

### 💾 Kaydetme & Dışa Aktarma
- **JSON Kaydetme / Yükleme**: Tasarımlarınızı dosya olarak kaydedip daha sonra tekrar yükleyebilirsiniz.
- **PNG Görsel Çıktısı**: Hazırladığınız planı yüksek çözünürlüklü PNG görseli olarak indirme.
- **Otomatik Kaydetme**: Çalışmanız her 10 saniyede bir tarayıcı hafızasına (`localStorage`) otomatik kaydedilir.

### 🎨 Kullanıcı Deneyimi
- **Göz Yormayan Sıcak Tema**: Krem ve yumuşak gri tonlarında modern tasarım.
- **Geri Al (Undo)**: `Ctrl+Z` veya buton ile son işlemleri geri alma.
- **Zoom & Pan**: Mouse tekerleği ile yakınlaştırma/uzaklaştırma, sağ tık ile tuvali kaydırma.

---

## 🚀 Kullanım / Çalıştırma

1. Projeyi klonlayın veya zip olarak indirin:
   ```bash
   git clone https://github.com/furkanoktay-sevimli/floor-planner.git
   ```
2. `index.html` dosyasını çift tıklayarak herhangi bir modern web tarayıcısında (Chrome, Edge, Firefox, Safari) açın.

---

## ⌨️ Kısayollar

| Kısayol | İşlev |
|---------|-------|
| `Sol Tık + Sürükle` | Eleman seç / taşı |
| `Sağ Tık + Sürükle` | Tuvali kaydır (Pan) |
| `Mouse Tekerleği` | Zoom in / out |
| `M` | Ölçüm modunu aç / kapat |
| `R` | Seçili mobilyayı 90° döndür |
| `Delete` / `Backspace` | Seçili elemanı sil |
| `Ctrl + Z` | Geri al |
| `ESC` | Seçimi kaldır / Ölçümden çık |

---

## 🛠️ Teknolojiler

- **HTML5 Canvas**
- **Vanilla JavaScript (ES6+)**
- **Vanilla CSS3 (Glassmorphism & CSS Variables)**
- **Google Fonts (Inter)**

---

## 📄 Lisans

MIT License
