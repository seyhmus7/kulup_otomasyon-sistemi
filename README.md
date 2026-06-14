# Üniversite Kulüp Otomasyon Sistemi 🎓

Bu proje, üniversitelerdeki öğrenci kulüplerinin yönetimini dijitalleştirmek ve kolaylaştırmak amacıyla geliştirilmiş kapsamlı bir **Girişimcilik Ödevi** projesidir.

## 🚀 Projenin Amacı
Kulüp yöneticilerinin, üyelerin ve etkinliklerin tek bir platform üzerinden takip edilmesini sağlamaktır. Sistem sayesinde karmaşık excel dosyalarına veya kağıt evraklara gerek kalmadan, tüm veriler güvenli bir veritabanında tutulur ve kullanıcı dostu bir arayüzle sunulur.

## 🛠️ Kullanılan Teknolojiler
- **Backend:** Python, Flask
- **Frontend:** HTML5, CSS3, Jinja2 (Şablon Motoru)
- **Veritabanı:** SQLite (`club_system.db`)
- **Stil & Tasarım:** Özel CSS (`style.css`), Responsive Arayüz

## 🌟 Temel Özellikler
1. **Kulüp Yönetimi:** Yeni kulüp ekleme, mevcut kulüplerin bilgilerini güncelleme veya silme.
2. **Öğrenci / Üye Kaydı:** Kulüplere üye öğrencilerin sisteme kaydedilmesi ve takibi.
3. **Etkinlik Planlama:** Kulüplerin düzenleyeceği etkinliklerin sisteme girilmesi ve duyurulması.
4. **Görev Yönetimi:** Kulüp içerisindeki görev dağılımlarının ve yöneticilerin belirlenmesi.
5. **Kullanıcı Girişi:** Sisteme güvenli giriş (Login) ekranı.

## ⚙️ Kurulum ve Çalıştırma

Projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. **Depoyu Klonlayın:**
   ```bash
   git clone https://github.com/seyhmus7/kulup_otomasyon-sistemi.git
   cd kulup_otomasyon-sistemi
   ```

2. **Gerekli Paketleri Yükleyin:**
   Python yüklü olduğundan emin olduktan sonra bağımlılıkları kurun:
   ```bash
   pip install -r requirements.txt
   ```

3. **Uygulamayı Başlatın:**
   ```bash
   python app.py
   ```

4. **Tarayıcıda Görüntüleyin:**
   Web tarayıcınızı açın ve `http://localhost:5000` veya komut satırında belirtilen adrese gidin.

## 📝 Lisans
Bu proje girişimcilik dersi ödevi kapsamında geliştirilmiştir.
