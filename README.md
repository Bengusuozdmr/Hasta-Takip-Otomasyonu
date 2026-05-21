# Hasta Takip Otomasyon Sistemi

Bu proje, hastaların muayene süreçlerini, doktor kontrollerini ve randevularını dijital ortamda düzenli bir şekilde takip etmek amacıyla geliştirilmiş bir masaüstü yazılımıdır. Yönetim Bilişim Sistemleri (YBS) yazılım projesi kapsamında geliştirilmiştir.

##  Projenin Amacı ve Ne İş Yaptığı

Sistem; hastane personeli ve doktorların hasta geçmişini, tedavi ve kontrol süreçlerini anlık olarak izlemesini sağlar. Tüm veriler güvenli bir SQL veritabanında kalıcı olarak saklanır.

**Temel Fonksiyonlar:**
* **Kullanıcı Giriş Paneli:** Yetkili personelin sisteme güvenli giriş yapması.
* **Hasta Takip & Kayıt Paneli:** Sisteme yeni hasta kaydetme, telefon ve TC kimlik bilgileriyle sorgulama yapma.
* **Doktor Yönetim Paneli:** Aktif çalışan doktorların branşlarına göre sisteme eklenmesi ve listelenmesi.
* **Randevu & Takip Sistemi:** Hastalara uygun gün ve saatte, istedikleri branş ve doktordan randevu oluşturarak takibini sağlama.

---

##  Kullanılan Teknolojiler

* **Geliştirme Ortamı:** Microsoft Visual Studio
* **Programlama Dili:** C# (C-Sharp)
* **Arayüz Teknolojisi:** Windows Forms App (Visual Programming)
* **Veritabanı:** Microsoft SQL Server (T-SQL)

---

##  Veritabanı Mimarisi (SQL Server)

Projede verilerin kalıcı olması ve kaybolmaması için ilişkisel SQL veritabanı mimarisi kullanılmıştır. Temel tablolar:
* `Tbl_Hastalar` (Hasta Bilgileri ve İletişim Geçmişi)
* `Tbl_Doktorlar` (Doktor Bilgileri ve Branşları)
* `Tbl_Randevular` (Randevu Tarih, Saat ve Takip Durumları)

---

## ⚙️ Kurulum ve Çalıştırma

1. Projeyi bilgisayarınıza indirin (`Clone` veya `Download ZIP`).
2. `SQL Server Management Studio (SSMS)` üzerinde veritabanı tablolarını oluşturun.
3. C# projesindeki `SqlBaglantisi.cs` sınıfındaki (Connection String) SQL Server ismini kendi yerel sunucu adınızla değiştirin.
4. Projeyi `Visual Studio` ile açın ve `Start` butonuna basarak çalıştırın.
