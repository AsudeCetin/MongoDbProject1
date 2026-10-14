# 🌍 Travelio - MongoDB & ASP.NET Core MVC Seyahat Platformu

Travelio, modern web mimarisi standartlarına uygun olarak, NoSQL veri tabanı esnekliğiyle geliştirilmiş tam kapsamlı bir seyahat, tur ve rezervasyon yönetim platformudur. Proje, hem son kullanıcı deneyimini (UI) hem de kurumsal yönetim mekanizmalarını (Admin Panel) uçtan uca simüle etmektedir.

## 🛠️ Kullanılan Teknolojiler & Mimari
* **Backend:** C# & ASP.NET Core 8.0 MVC (Modüler Katmanlı Mimari)
* **Veri Tabanı:** MongoDB (NoSQL esnek veri şeması yönetimi)
* **Güvenlik & Oturum:** Cookie Authentication, Güvenli LogOut Mekanizması ve TempData Yönetimi
* **Frontend:** Bootstrap 5, HTML5, CSS3, JavaScript, jQuery
* **Veri Görselleştirme:** Chart.js (Dinamik Admin Grafik Analitiği)
* **Raporlama Modülleri:** EPPlus (Excel Export) ve iTextSharp (PDF Export)
* **Dil Desteği:** ASP.NET Core Localization (İngilizce & Türkçe Çoklu Dil Altyapısı)

## 📌 Öne Çıkan Modüller ve Özellikler
* **Dinamik Banner Slider:** Web sitesinin ana sayfa banner alanı, admin panelinden yüklenen aktif görsel, başlık ve slogan kombinasyonlarıyla Bootstrap Carousel mimarisinde otomatik ve kesintisiz akmaktadır.
* **Akıllı Yorum Yönetimi:** Kullanıcı yorumları MongoDB'den asenkron çekilir; sisteme üye olmayan telefon müşterilerinin isimleri akıllı string algoritmalarıyla içerikten ayıklanarak başlığa otomatik yansıtılır.
* **Gelişmiş Admin Dashboard:** İstatistik verilerini, son rezervasyonları, yorumları ve gelen soruları anlık özetleyen analitik yönetim paneli.
* **İçerik & Tur Yönetimi:** Turlar, kategoriler, lokasyonlar ve banner alanları için tam kapsamlı CRUD yönetim mekanizması.

## 🚀 Proje Kurulumu
1. Bilgisayarınıza **MongoDB Compass** kurun ve yerel bir veri tabanı bağlantısı oluşturun.
2. `appsettings.json` dosyasındaki `ConnectionString` alanını kendi MongoDB adresinize göre güncelleyin.
3. Projeyi Visual Studio ile açıp `Build` ettikten sonra çalıştırabilirsiniz.
