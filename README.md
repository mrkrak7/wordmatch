# 🎮 WordMatch - İngilizce Kelime Öğrenme Oyunu

WordMatch, İngilizce kelimeleri eğlenceli bir şekilde öğrenmenizi sağlayan, Mobile Legends tarzı rank sistemiyle donatılmış bir kelime eşleştirme oyunudur.

![WordMatch Banner](https://img.shields.io/badge/WordMatch-v1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Language](https://img.shields.io/badge/language-Turkish-red)

## ✨ Özellikler

### 🏆 Rank Sistemi (Mobile Legends Tarzı)
- **Bronze** (A1) → **Silver** (A2) → **Gold** (B1) → **Platinum** (B2) → **Emerald** (C1)
- Her rank'te 4 tier: IV → III → II → I
- Her tier için 4 yıldız toplanması gerekiyor

### 📚 Kelime Veritabanı
- **Toplam 4.876 kelime** (A1-C1 seviyeleri)
- CEFR standartlarına uygun seviye dağılımı:
  - A1: 1.479 kelime
  - A2: 310 kelime
  - B1: 556 kelime
  - B2: 1.280 kelime
  - C1: 1.251 kelime

### 🎯 Oyun Mekanikleri
- İngilizce-Türkçe kelime eşleştirme
- Doğru/yanlış animasyonlar
- Streak (seri) takibi
- İngilizce kelimelere tıklayınca sesli telaffuz (TTS)
- İlerleme kaydetme (localStorage)

### 🎨 Görsel Özellikler
- Modern, profesyonel tasarım
- Rank'e göre değişen renk teması
- Kalkan şeklinde rank rozetleri
- Glow efektleri ve animasyonlar
- Yıldız kazanma/tier atlama kutlamaları

## 🚀 Kurulum

### Basit Kullanım
1. Repoyu klonlayın:
```bash
git clone https://github.com/YOUR_USERNAME/wordmatch.git
```

2. `index.html` dosyasını tarayıcınızda açın.

### GitHub Pages ile Yayınlama
1. Repository ayarlarına gidin
2. Pages → Source: Deploy from a branch
3. Branch: main, Folder: / (root)
4. Save'e tıklayın
5. Birkaç dakika sonra siteniz yayında!

## 📱 Ekran Görüntüleri

### Ana Oyun Ekranı
- Rank rozeti ve yıldızlar
- İlerleme çubuğu
- Kelime eşleştirme kartları

### Kutlama Animasyonları
- Yıldız kazanma
- Tier atlama
- Rank yükseltme

## 🛠️ Teknolojiler

- **HTML5** - Yapı
- **CSS3** - Modern tasarım, animasyonlar
- **JavaScript** - Oyun mantığı
- **Web Speech API** - Sesli telaffuz
- **LocalStorage** - İlerleme kaydetme

## 📂 Dosya Yapısı

```
wordmatch/
├── index.html      # Ana uygulama
├── words.js        # Kelime veritabanı
├── README.md       # Dokümantasyon
└── LICENSE         # MIT Lisansı
```

## 🎮 Nasıl Oynanır?

1. **Başla** butonuna tıklayın
2. Sol taraftaki İngilizce kelimelerden birine tıklayın
3. Sağ taraftaki Türkçe karşılığını bulun ve tıklayın
4. Doğru eşleşmelerde yeşil, yanlışlarda kırmızı animasyon görünür
5. Tüm kelimeleri eşleştirince yeni kelimeler gelir
6. Yıldız toplayarak tier ve rank atlayın!

## 🌟 Yıldız ve Rank Sistemi

| Öğrenilen Kelime | Kazanılan Yıldız |
|------------------|------------------|
| Her %25 ilerleme | 1 ⭐ |
| 4 Yıldız | 1 Tier Atlama |
| Rank %100 | Sonraki Rank |

## 🔊 Ses Özellikleri

- **Doğru cevap**: Başarı melodisi
- **Yanlış cevap**: Hata sesi
- **Kelime tıklama**: İngilizce telaffuz (TTS)
- Sağ üstteki 🔊 butonu ile ses açılıp kapatılabilir

## 📊 İstatistikler

Uygulama şu istatistikleri takip eder:
- Öğrenilen toplam kelime
- Doğruluk yüzdesi
- En iyi seri (streak)
- Mevcut seri

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/YeniOzellik`)
3. Commit yapın (`git commit -m 'Yeni özellik eklendi'`)
4. Push yapın (`git push origin feature/YeniOzellik`)
5. Pull Request açın

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👨‍💻 Geliştirici

**Aizen** - *Tüm geliştirme*

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!

## 🔮 Gelecek Özellikler

- [ ] Çoktan seçmeli mod
- [ ] Zamanlı challenge modu
- [ ] Günlük görevler
- [ ] Başarımlar sistemi
- [ ] Çoklu dil desteği
- [ ] Sesli kelime sözlüğü
- [ ] Özel kelime listeleri
- [ ] Sosyal paylaşım

---

Made with ❤️ for learning English
