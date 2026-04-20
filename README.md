# 🚗 CarBook - Araç Kiralama Sistemi

CarBook, kullanıcıların araçları listeleyebileceği, fiyatları inceleyebileceği ve kiralama süreçlerini yönetebileceği bir projedir. Projede modern backend yaklaşımları uygulanarak kurumsal düzeyde bir yapı oluşturulmuştur.

---

## 🧠 Kullanılan Mimari ve Tasarım Desenleri

- 🧅 Onion Architecture
- ⚡ CQRS (Command Query Responsibility Segregation)
- 🧩 Mediator Design Pattern
- 📦 Repository Pattern

---

## 🔐 Kullanılan Teknolojiler

- ASP.NET Core 8.0 Web API
- Entity Framework Core
- MSSQL
- JSON Web Token (JWT)
- SignalR (Gerçek zamanlı veri akışı)
- Fluent Validation
- DTO (Data Transfer Object)

---
## 🧱 Proje Katmanları

- **Core** → Temel arayüzler ve bağımlılıklar
- **Application** → İş kuralları, CQRS işlemleri
- **Infrastructure** → Veritabanı ve dış servisler
- **Presentation** → API ve UI katmanı

---
## ✨ Temel Özellikler

### 🎯 Kullanıcı Deneyimi

- 🚗 **Gelişmiş Araç Listeleme**  
  Kullanıcılar; marka, yakıt tipi, şanzıman ve fiyat gibi kriterlere göre araçları filtreleyebilir.

- 📍 **Lokasyon Bazlı Araç Bulma**  
  Seçilen lokasyona göre müsait araçlar dinamik olarak listelenir.

- 📅 **Kolay Rezervasyon Süreci**  
  Kullanıcı dostu form ile hızlı ve pratik rezervasyon oluşturma imkanı.

- 💰 **Esnek Fiyatlandırma Görüntüleme**  
  Günlük, haftalık ve aylık kiralama seçeneklerini karşılaştırmalı olarak inceleme.

- ⭐ **Yorum ve Değerlendirme Sistemi**  
  Kullanıcılar araçlar hakkında deneyimlerini paylaşabilir.

- 📝 **Blog ve İçerik Yönetimi**  
  Kullanıcılar güncel blog yazılarını okuyabilir ve içeriklere erişebilir.


---

### 🛡️ Yönetim Paneli (Admin)

- 📊 **Gerçek Zamanlı Dashboard**  
  SignalR kullanılarak anlık veri akışı ve canlı istatistik takibi.

- 🚙 **Araç Yönetimi (CRUD)**  
  Araç ekleme, güncelleme, silme ve detaylı yönetim işlemleri.

- ✨ **Dinamik Özellik Atama**  
  Araçlara checkbox yapısı ile özellik ekleme/çıkarma (Many-to-Many yönetimi).

- 🏷️ **Marka ve Kategori Yönetimi**  
  Araç markalarını ve içerik kategorilerini merkezi panelden yönetme.

- 💰 **Fiyatlandırma Yönetimi**  
  Araçlar için dönemsel fiyat tanımlama (günlük, haftalık, aylık).

- 📍 **Lokasyon Yönetimi**  
  Şube bazlı araç ve rezervasyon yönetimi.

- 📋 **Rezervasyon Takibi**  
  Tüm rezervasyonları görüntüleme ve yönetme.

- ✍️ **Blog & İçerik Yönetimi**  
  Blog, kategori, yazar ve yorumların yönetimi.

- 💬 **Yorum Moderasyonu**  
  Kullanıcı yorumlarını onaylama ve kontrol etme.

- 🎨 **Dinamik İçerik Yönetimi**  
  Banner, hizmetler, hakkımızda ve footer alanlarını güncelleme.

- 📈 **Gelişmiş İstatistikler ve Raporlama**  
  Araç, fiyat ve kullanıcı verileri üzerinden analiz ve raporlama.

## 📷 Proje Görselleri

### 🏠 Anasayfa
<img width="1852" height="912" alt="ANASAYFA" src="https://github.com/user-attachments/assets/db744054-d03e-4630-a6b3-214b7fb550a5" />


### 🚘 Araçlar Sayfası
<img width="1626" height="922" alt="ARABALAR" src="https://github.com/user-attachments/assets/9c43f22c-0008-4aa0-865b-d831842c8b64" />

### 🚘 Araç Detay Sayfası
<img width="1230" height="931" alt="arabadetail" src="https://github.com/user-attachments/assets/8c940a22-840a-4fd8-937b-bff608bf98ec" />

### 💰 Araç Kiralama Fiyatları
<img width="1776" height="912" alt="fiyat" src="https://github.com/user-attachments/assets/a3ca4864-38f9-4478-a8e5-dda947da35ec" />


### 📝 Blog Detay Sayfası
<img width="1672" height="918" alt="BLOG" src="https://github.com/user-attachments/assets/d8fad8af-eb48-4908-8c0e-44400e832317" />


### 📞 İletişim Sayfası
<img width="1751" height="870" alt="iletisim" src="https://github.com/user-attachments/assets/eb742349-057f-4398-a81e-63cf34a6aeff" />

### 🔐 Login Sayfası
<img width="1620" height="923" alt="LOGİN" src="https://github.com/user-attachments/assets/4871ba7e-d7f9-439b-8f91-867da9b04dd9" />


## 🛡️ Admin Paneli

### 📊 Dashboard (Gerçek Zamanlı)
<img width="1892" height="926" alt="AdminDashboard" src="https://github.com/user-attachments/assets/431ee99f-5c84-4935-97a7-36be16693d00" />

### 📈 İstatistikler Sayfası
<img width="1887" height="920" alt="İstatistikler" src="https://github.com/user-attachments/assets/4d6bd8e1-a764-45f7-b2cb-4848bd1c8544" />

### 🚗 Araç Yönetimi
<img width="1883" height="892" alt="Arabaişlemleri" src="https://github.com/user-attachments/assets/75b2381a-4e6f-42fa-a475-f645908d8cb0" />

### 🔗 API Yapısı
<img width="1436" height="928" alt="API" src="https://github.com/user-attachments/assets/54678260-8072-4a0e-a6c8-e34632d498cf" />

### 🗄️ Veritabanı Diyagramı
<img width="1375" height="678" alt="veritabani" src="https://github.com/user-attachments/assets/a6db0153-ec52-4583-8791-9a7700477591" />


