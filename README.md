# Blog Sitesi - Bootstrap ile Geliştirilmiş

Modern ve responsive bir blog sitesi projesi. Bootstrap 5.3.2 framework'ü kullanılarak geliştirilmiştir.

## 📋 Proje Hakkında

Bu proje, Bootstrap framework'ünün temel özelliklerini kullanarak oluşturulmuş profesyonel bir blog sitesidir. Responsive tasarım prensiplerine uygun olarak geliştirilmiş olup, tüm cihazlarda mükemmel görünüm sağlar.

## ✨ Özellikler

### Ana Sayfa
- **Koyu Renkli Navbar**: Bootstrap'in navbar-dark ve bg-dark sınıfları kullanılarak oluşturulmuş modern navigasyon menüsü
- **Jumbotron/Hero Bölümü**: Ana sayfada göz alıcı, mavi arka planlı hoş geldiniz bölümü
- **Blog Kartları**: 6 adet responsive blog kartı Bootstrap card yapısı ile tasarlanmıştır
- **Grid Sistemi**: Bootstrap'in güçlü grid sistemi (row, col-md-6, col-lg-4) kullanılarak responsive düzen oluşturulmuştur
- **Eşit Kart Boyutları**: h-100 sınıfı ile tüm kartların aynı yükseklikte olması sağlanmıştır

### Blog Gönderisi Sayfası
- **Detaylı İçerik Düzeni**: Breadcrumb navigasyonu, yazar bilgisi, etiketler ve paylaşım butonları
- **Bootstrap Bileşenleri**: Card, badge, alert ve button bileşenleri etkin kullanılmıştır
- **Okunabilir İçerik**: Justify edilmiş paragraflar ve düzenli başlıklar ile kolay okunabilirlik

### Tasarım ve Stil
- **Hover Efektleri**: Kartlar ve butonlar için smooth animasyonlar
- **Tutarlı Görüntüler**: Tüm card görselleri 250px yüksekliğe sabitlenmiştir
- **Responsive Tasarım**: Mobil, tablet ve masaüstü cihazlar için optimize edilmiş görünüm
- **Custom CSS**: Bootstrap'i tamamlayan özel stiller

## 🛠️ Kullanılan Teknolojiler

- **HTML5**: Semantik ve erişilebilir yapı
- **CSS3**: Modern stil özellikleri
- **Bootstrap 5.3.2**: Responsive framework
- **Unsplash**: Kaliteli görseller için

## 📁 Dosya Yapısı

```
blogsitemboostrap/
│
├── index.html          # Ana sayfa
├── post.html           # Blog gönderisi detay sayfası
├── styles.css          # Özel CSS stilleri
└── README.md           # Proje dokümantasyonu
```

## 🚀 Kurulum ve Kullanım

### Gereksinimler
- Modern bir web tarayıcısı (Chrome, Firefox, Safari, Edge)
- İnternet bağlantısı (Bootstrap CDN için)

### Projeyi Çalıştırma

1. Projeyi klonlayın veya indirin:
```bash
git clone https://github.com/mhmtfthunal/blogsitemboostrap.git
```

2. Proje klasörüne gidin:
```bash
cd blogsitemboostrap
```

3. `index.html` dosyasını bir web tarayıcısında açın:
   - Dosyaya çift tıklayın, veya
   - Sağ tıklayıp "Birlikte Aç" > "Tarayıcı" seçin, veya
   - Live Server (VS Code uzantısı) ile açın

## 📱 Responsive Tasarım

Site aşağıdaki ekran boyutları için optimize edilmiştir:

- **Mobil**: < 768px (tek sütun düzeni)
- **Tablet**: 768px - 992px (iki sütun düzeni)
- **Desktop**: > 992px (üç sütun düzeni)

## 🎨 Bootstrap Bileşenleri

Projede kullanılan başlıca Bootstrap bileşenleri:

- **Navbar**: Responsive navigasyon menüsü
- **Container**: İçerik sarmalayıcı
- **Grid System**: Row ve Column yapısı
- **Cards**: Blog gönderileri için kart yapısı
- **Buttons**: Çeşitli buton stilleri
- **Badges**: Etiket ve kategori gösterimleri
- **Breadcrumb**: Sayfa navigasyonu
- **Alert**: Bilgilendirme mesajları

## 💡 Özelleştirme

### Renkleri Değiştirme
`styles.css` dosyasındaki CSS değişkenlerini düzenleyerek site renklerini özelleştirebilirsiniz.

### İçerik Güncelleme
- `index.html`: Ana sayfa içeriğini düzenleyin
- `post.html`: Blog gönderisi içeriğini düzenleyin

### Yeni Blog Kartı Ekleme
`index.html` dosyasında mevcut card yapısını kopyalayıp düzenleyerek yeni blog kartları ekleyebilirsiniz.

## 📄 Lisans

Bu proje eğitim amaçlı oluşturulmuştur.

## 📝 Notlar

- Tüm görseller Unsplash'tan alınmıştır
- Bootstrap CDN üzerinden yüklenmektedir
- Proje statik HTML sayfalardan oluşmaktadır
- Backend veya veritabanı entegrasyonu bulunmamaktadır
