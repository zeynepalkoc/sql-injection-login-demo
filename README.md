# SQL Injection Açığına Sahip ve Güvenli Giriş Sistemi

Bu projede, SQL Injection zafiyeti barındıran basit bir kullanıcı girişi sistemi geliştirilmiş ve ardından bu açık güvenli hale getirilmiştir. Amaç, web uygulamalarındaki temel güvenlik zafiyetlerini göstermek ve bu zafiyetleri nasıl kapatabileceğimizi pratik olarak uygulamaktır.

## 🚀 Proje İçeriği

### 1. `insecure-version/`
Bu klasörde, doğrudan kullanıcıdan alınan verilerle SQL sorgusu oluşturarak çalışan, SQL Injection'a açık bir login sistemi bulunmaktadır.

### 2. `secure-version/`
Bu klasörde, **Prepared Statements (Hazırlanmış İfadeler)** kullanılarak SQL Injection açığı giderilmiş güvenli sürüm bulunmaktadır.

### 3. `database/setup.sql`
Veritabanı ve kullanıcı tablosunu oluşturmak için kullanılan SQL dosyasıdır.

---

## 💻 Gereksinimler

- PHP 7.x veya üstü
- MySQL/MariaDB
- Web sunucusu (XAMPP/WAMP/Laragon önerilir)

---

## 🛠 Kurulum

1. Veritabanını oluşturmak için `database/setup.sql` dosyasını çalıştırın.
2. `db.php` dosyasında veritabanı bağlantı ayarlarını kendinize göre güncelleyin.
3. `insecure-version/` veya `secure-version/` klasörünü local sunucunuzda çalıştırarak test edin.

---

## 📸 Ekran Görüntüleri

`/screenshots` klasöründe hem açık sürümün hem güvenli sürümün ekran görüntüleri yer alacaktır.

---

## 📌 Amaç

Bu proje, aşağıdaki konularda farkındalık oluşturmak için hazırlanmıştır:

- SQL Injection nedir ve nasıl yapılır?
- Web uygulamalarında nasıl güvenlik açıkları oluşur?
- Bu tür açıklar nasıl giderilir?
- Prepared statements neden önemlidir?

---

## 👤 Geliştirici

**Zeynep Rabia Alkoç**  
Tek kişilik bir proje olarak gerçekleştirilmiştir.

---

## 📝 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.
