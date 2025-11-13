### 🔔 Temel Özellikler
- **Otomatik Zil Çalma**: Belirlenen saatlerde otomatik zil çalma
- **Profil Yönetimi**: Farklı gün profilleri oluşturma ve yönetme
- **Marş Sistemi**: Okul marşı başlatma/durdurma
- **Acil Alarm**: Öncelikli alarm sesi çalma
- **Zil Testi**: Manuel zil test etme

### ⚙️ Gelişmiş Özellikler
- **Çift Zil Koruma**: Aynı anda iki zil çalmasını engelleme
- **Marş-Zil Engelleme**: Marş çalarken zil çalmama
- **Checkbox Kontrolü**: Manuel zil devre dışı bırakma
- **Responsive Tasarım**: 1200x710 sabit çözünürlük

### 🎵 Ses Yönetimi
- **Zil Sesleri**: Birden fazla zil sesi desteği
- **Alarm Sesleri**: Özel alarm sesleri
- **Marş Sesleri**: Okul marşı sesleri
- **Ses Testi**: Her ses için test etme özelliği

## 📁 Klasör Yapısı
SSEML_OkulZili/
├── ZilSesleri/ # Zil ses dosyaları (.mp3, .wav)
├── AlarmSesleri/ # Alarm ses dosyaları (.mp3, .wav)
├── Marslar/ # Marş ses dosyaları (.mp3, .wav)
├── Ayarlar.txt # Sistem ayarları
├── Profiller.txt # Zaman profilleri
└── SSEML_OkulZili.exe # Ana uygulama

text


## 🎮 Kullanım Klavuzu

### 1. 💾 Kurulum
1. `SSEML_OkulZili.exe` dosyasını çalıştırın
2. Otomatik olarak gerekli klasörler oluşturulur:
   - `ZilSesleri/`
   - `AlarmSesleri/`
   - `Marslar/`

### 2. 🎵 Ses Dosyaları Ekleme
1. Ses dosyalarınızı ilgili klasörlere kopyalayın:
   - `.mp3` veya `.wav` formatları desteklenir
2. **Yenile** butonuna tıklayarak sesleri yükleyin

### 3. 📅 Profil Yönetimi

#### Varsayılan Profiller:
- **Normal Gün**: Salı, Çarşamba, Cuma
- **Öğle Okulu**: Pazartesi, Perşembe

#### Yeni Profil Oluşturma:
1. **YENİ PROFİL** butonuna tıklayın
2. Profil adını girin
3. Profil zamanlarını ayarlayın

#### Profil Kopyalama:
1. Varolan bir profili seçin
2. **PROFİLİ KOPYALA** butonuna tıklayın
3. Yeni profil adını girin

#### Profil Düzenleme:
1. Profili seçin
2. **PROFİLİ DÜZENLE** butonuna tıklayın
3. Zamanları ve açıklamaları düzenleyin

### 4. ▶️ Fonksiyonlar

#### Zil Çalma:
- Belirlenen saatlerde otomatik çalar
- Aynı saatte sadece bir kez çalar
- Marş çalarken zil çalmaz

#### Marş Başlatma:
- **MARŞ BAŞLAT** butonu ile başlatılır
- Marş çalarken zil çalmaz
- Marş bittikten sonra 5 saniye içinde zil çalmaz

#### Acil Alarm:
- **ACİL ALARM** butonu ile manuel alarm çalma
- Diğer sesleri durdurur ve önceliklidir

#### Zil Testi:
- **ZİLİ TEST ET** butonu ile test sesi çalma
- Sistemdeki zil sesini test eder

### 5. ⚠️ Özel Kontroller

#### Tüm Zilleri Devre Dışı:
- Checkbox işaretliyken zil çalmaz
- İşaret kaldırıldığında normal çalışmaya devam eder

#### Checkbox Kontrolü:
- İşaretliyken gelen zil iptal edilir
- İşaret kaldırıldığında aynı dakikada zil çalmaz

## ⌨️ Kısayollar

| Tuş | İşlev |
|-----|-------|
| F5 | Ses dosyalarını yenile |
| ESC | Açık dialogları kapat |

## 🛠️ Teknik Detaylar

### Gereksinimler
- **Windows**: 7/8/10/11
- **.NET Framework**: 4.0 veya üzeri
- **RAM**: Minimum 512MB
- **Disk Alanı**: 50MB boş alan

### Desteklenen Formatlar
- **Ses Dosyaları**: MP3, WAV
- **Profil Dosyaları**: TXT

### Sistem Bileşenleri
- **Windows Media Player Library**
- **System.Windows.Forms**
- **System.IO**
- **System.Collections.Generic**

## 📊 Performans

### Bellek Kullanımı
- **Boşta**: ~25MB
- **Ses Çalarken**: ~35MB
- **Maksimum**: ~50MB

### CPU Kullanımı
- **Boşta**: %0-1
- **Ses Çalarken**: %2-5
- **Peak**: %10

## 🔧 Sorun Giderme

### Yaygın Sorunlar

#### ❌ Zil Çalmıyor
```bash
Kontrol Edilecekler:
1. Zil sesi dosyası mevcut mu?
2. Ses seviyesi ayarları doğru mu?
3. Ses cihazı çalışıyor mu?
❌ Ses Dosyaları Görünmüyor
Bash

Çözüm Adımları:
1. YENİLE butonuna tıklayın
2. Dosya uzantılarını kontrol edin (.mp3, .wav)
3. Klasör yolunu kontrol edin
❌ Profil Kayıt Edilmiyor
Bash

Kontrol Listesi:
1. Yazma izinleri var mı?
2. Disk alanı yeterli mi?
3. Antivirüs engelliyor mu?
📈 Versiyon Geçmişi
v2.0.0 (Güncel)
Yeni: Profil kopyalama özelliği
Yeni: Checkbox kontrol sistemi
Geliştirme: Marş-zil engelleme sistemi
Geliştirme: Responsive tasarım
v1.0.0 (İlk Sürüm)
Temel zil çalma sistemi
Profil yönetimi
Ses dosyası desteği

👨‍💻 Geliştirici
Yusuf - Baş Geliştirici
