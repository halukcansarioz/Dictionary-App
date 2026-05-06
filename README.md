# 📖 Dictionary-App
### (C Dili ile Yazılmış Basit Bir İngilizce-Türkçe Sözlük Uygulaması)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)](#)
[![Console App](https://img.shields.io/badge/Console%20App-4D4D4D?style=flat&logo=windowsterminal&logoColor=white)](#)
[![Made with Learning](https://img.shields.io/badge/Made%20with-Learning-1f425f.svg)](#)

Bu proje, C programlama dili ile geliştirilmiş, konsol tabanlı basit bir İngilizce-Türkçe / Türkçe-İngilizce sözlük uygulamasıdır. Temel dosya okuma ve dize işleme becerilerini geliştirmek amacıyla hazırlanmıştır.

## 📚 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum ve Kullanım](#kurulum-ve-kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Geliştirme Süreci](#geliştirme-süreci)
- [Katkıda Bulunma](#katkıda-bulunma)
- [İletişim](#iletisim)
- [Lisans](#lisans)

---

## Proje Hakkında
Bu uygulama, `ingilizce.txt` ve `turkce.txt` dosyalarında saklanan kelime listelerini okuyarak kullanıcıya hem İngilizce'den Türkçe'ye hem de Türkçe'den İngilizce'ye çeviri yapma imkânı sunar. Konsol üzerinde çalışan bu uygulama, C dilinde dosya işleme, dize yönetimi ve kullanıcı etkileşimi konularını pekiştirmek için yazılmıştır.

* **Geliştirici:** Haluk Can SARIÖZ
* **Tür:** Konsol Sözlük Uygulaması
* **Amaç:** C programlama pratiği ve algoritma geliştirme

---

## Özellikler
* **Çift Yönlü Çeviri:** İngilizce'den Türkçe'ye ve Türkçe'den İngilizce'ye kelime arama.
* **Harici Kelime Listesi:** Sözlük verileri ayrı `.txt` dosyalarında tutulur, kolayca genişletilebilir.
* **Basit ve Temiz Kod:** Başlangıç seviyesi C programcıları için anlaşılır kod yapısı.
* **Hızlı Çalışma:** Konsol tabanlı olduğu için oldukça hızlı ve düşük kaynak tüketimlidir.

---

## Kullanılan Teknolojiler
* **C Programlama Dili:** Uygulamanın geliştirildiği ana dil.
* **GCC / G++:** Derleme işlemleri için kullanılan araç.
* **VS Code / Dev-C++:** Geliştirme ortamı olarak kullanılan editörler.

---

## Kurulum ve Kullanım

### 1. Depoyu Klonlayın
```bash
git clone https://github.com/halukcansarioz/Dictionary-App.git
```

### 2. Proje Dizinine Gidin
```bash
cd Dictionary-App
```

### 3. Uygulamayı Derleyin

* **Linux / macOS için:**
```bash
gcc sozluk.c -o sozluk
```

* **Windows için (MinGW / GCC kurulu olmalı):**
```bash
gcc sozluk.c -o sozluk.exe
```

### 4. Uygulamayı Çalıştırın
```bash
# Linux / macOS
./sozluk

# Windows
sozluk.exe
```

> ⚠️ **Not:** `ingilizce.txt` ve `turkce.txt` dosyaları, uygulama ile aynı dizinde bulunmalıdır.

---

## Proje Yapısı
```text
Dictionary-App/
├── sozluk.c               # Ana uygulama kaynak kodu
├── sozluk.exe             # Derlenmiş Windows yürütülebilir dosyası
├── ingilizce.txt          # İngilizce kelime listesi
├── turkce.txt             # Türkçe kelime listesi
├── .gitattributes         # Git yapılandırma dosyası
└── README.md              # Proje dökümantasyonu
```

---

## Geliştirme Süreci

### 1. Forklama
Kendi özelliklerinizi eklemek veya kelime listesini genişletmek için depoyu fork'layabilirsiniz.

### 2. Yeni Dal (Branch) Oluşturma
```bash
git checkout -b ozellik/yeni-kelime-ekleme
```

### 3. Kodları Gönderme (Push)
```bash
git push origin ozellik/yeni-kelime-ekleme
```

---

## Katkıda Bulunma
1. Bu depoyu **Fork**'layın.
2. Bir **Branch** oluşturun (`git checkout -b feature/YeniOzellik`).
3. Yeni kelimeler ekleyin veya kodu iyileştirin.
4. Değişikliklerinizi **Commit** edin (`git commit -m 'Ekleme: Yeni kelimeler'`).
5. Kodlarınızı **Push**'layın (`git push origin feature/YeniOzellik`).
6. Bir **Pull Request** açın.

> 💡 **Öneri:** Kelime eklerken `ingilizce.txt` ve `turkce.txt` dosyalarındaki sıralamanın aynı olmasına dikkat ediniz.

---

<a name="iletisim"></a>
## İletişim
**Haluk Can Sarıöz** - [GitHub Profilim](https://github.com/halukcansarioz)  
**Proje Linki:** [https://github.com/halukcansarioz/Dictionary-App](https://github.com/halukcansarioz/Dictionary-App)

---

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
