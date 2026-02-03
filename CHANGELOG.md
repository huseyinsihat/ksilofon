# Değişiklik Günlüğü

Akıllı Ksilofon projesinin tüm önemli değişiklikleri bu dosyada belgelenir.

## [1.0.0] - 2025-12-XX

### ✨ Yeni Özellikler

#### Oyun Modları
- **Serbest Mod**: Kullanıcıların özgürce nota çalabilmesi
- **Refleks Modu**: Tepki hızı ölçümü ve puanlama sistemi
- **Hafıza Modu**: Nota dizilerini tekrarlama oyunu
- **Şarkı Modu**: 4 hazır şarkı melodisi
  - Daha Dün Annemizin
  - Bak Postacı Geliyor
  - İzmir Marşı
  - 23 Nisan

#### Yapay Zeka
- TensorFlow.js entegrasyonu
- Teachable Machine ile eğitilmiş ses tanıma modeli
- 8 farklı notayı %85+ doğrulukla tanıma
- Gerçek zamanlı mikrofon dinleme
- Arka plan gürültü filtreleme

#### Kullanıcı Arayüzü
- Glassmorphism tasarım dili
- Responsive ve mobil uyumlu
- Yatay mod zorunluluğu (oyun sırasında)
- Tam ekran desteği
- Dokunmatik ve fare desteği
- Görsel geri bildirimler (flash efektleri)
- Confetti patlaması (başarı animasyonu)
- Canlı puanlama sistemi

#### Veri Toplama
- Ön test anketi (3 soru)
- Son test anketi (3 soru)
- Her etkileşimin kaydedilmesi
  - Zaman damgası
  - Oyun modu
  - Hedef/çalınan nota
  - Doğruluk durumu
  - Tepki süresi
- Google Sheets entegrasyonu
- Otomatik veri gönderimi

#### Ses Sistemi
- Web Audio API ile gerçek zamanlı ses sentezi
- Polyphonic (çoklu ses) desteği
- 8 farklı nota frekansı
- ADSR zarf (Attack-Decay-Sustain-Release)
- Yumuşak geçişler

### 🔧 Teknik İyileştirmeler

- Modern ES6+ JavaScript kullanımı
- Modüler kod yapısı
- Event handling optimizasyonu
- Touch event performansı
- Canvas animasyon optimizasyonu
- Retina ekran desteği
- Viewport yönetimi (safe-area-inset)
- Pull-to-refresh engelleme
- iOS Safari uyumluluğu

### 📱 Mobil Optimizasyon

- Responsive breakpoints
- Landscape/Portrait mod kontrolü
- Küçük ekran optimizasyonu
- iPhone notch (çentik) desteği
- Android tam ekran desteği
- Dokunmatik scroll engelleme
- Vibrasyon feedback (opsiyonel)

### 🎨 Tasarım

- Özel renk paleti (8 nota rengi)
- Animasyonlu geçişler
- Modern ikonlar
- Emoji kullanımı
- Accessibility düşünülerek tasarlandı

### 📚 Dokümantasyon

- Detaylı README.md
- MIT lisansı eklendi
- Kod içi yorumlar
- Kullanım kılavuzu

### 🐛 Bilinen Sorunlar

- Safari'de mikrofon izni bazen gecikmeli alınabiliyor
- Çok hızlı dokunmalarda bazen nota kaybolabiliyor (optimizasyon yapılacak)
- Bazı eski Android cihazlarda confetti animasyonu yavaş çalışabiliyor

### 🔮 Gelecek Sürümler İçin Planlanan

#### v1.1.0 (Tahmini: Şubat 2026)
- [ ] Öğretmen paneli
- [ ] Detaylı performans grafikleri
- [ ] Öğrenci karşılaştırma
- [ ] Ödev atama sistemi

#### v1.2.0 (Tahmini: Nisan 2026)
- [ ] Çok oyunculu mod (WebSocket)
- [ ] Liderlik tablosu
- [ ] Arkadaş ekleme
- [ ] Başarım sistemi (achievements)

#### v2.0.0 (Tahmini: Haziran 2026)
- [ ] Farklı enstrüman sesleri (piyano, gitar, flüt)
- [ ] Ses kayıt ve paylaşma
- [ ] Özel şarkı oluşturma
- [ ] İngilizce dil desteği
- [ ] Dark/Light tema

---

## Sürüm Numarası Formatı

Projemizde [Semantic Versioning](https://semver.org/lang/tr/) kullanılmaktadır:

- **MAJOR** (1.x.x): Geriye uyumsuz değişiklikler
- **MINOR** (x.1.x): Geriye uyumlu yeni özellikler
- **PATCH** (x.x.1): Geriye uyumlu hata düzeltmeleri

---

## Katkıda Bulunanlar

Bu sürüme katkıda bulunan herkese teşekkürler! 🎉

- [@huseyinsihat](https://github.com/huseyinsihat) - Proje Lideri
- TÜBİTAK 2204B Öğrenci Ekibi - Test ve Geri Bildirim

---

*Not: Tarihler tahminidir ve değişebilir.*
