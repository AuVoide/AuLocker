# 🛡️ AuVoide | Sentinel Locker
### Ultimate Client-Side File Encryption Engine

<p align="center">
  <img src="https://img.shields.io/badge/Versiyon-2.0.0-f43f5e?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/Güvenlik-AES--256-a855f7?style=for-the-badge" alt="Security">
  <img src="https://img.shields.io/badge/Lisans-MIT-10b981?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Marka-AuVoide-06b6d4?style=for-the-badge" alt="Brand">
</p>

---

## 🔐 Proje Özeti
**AuVoide Sentinel Locker**, hassas dosyalarınızı askeri düzeyde şifreleme algoritmalarıyla koruma altına alan tarayıcı tabanlı bir güvenlik aracıdır. Dosyalarınız hiçbir zaman bir sunucuya yüklenmez; tüm şifreleme ve deşifreleme işlemleri bilgisayarınızın RAM'i üzerinde (Client-Side) gerçekleşir.

> "Verileriniz size aittir. Onları kırılmaz yapın."

---

## ✨ Kriptografik Özellikler

### 🛡️ 3 Katmanlı Zırh Mimarisi (3-Layer Armor)
Sıradan şifreleyicilerin aksine AuVoide Sentinel, veriyi üç farklı işlemden geçirerek kırılmasını imkansız hale getirir:
1. **L1 (Scramble):** Dosyanın ham verisi (Base64) tersine çevrilir.
2. **L2 (AES Encryption):** Tersine çevrilmiş veri, kullanıcının belirlediği şifre ile `CryptoJS` kullanılarak **AES** algoritmasıyla şifrelenir.
3. **L3 (Wrapper):** Şifrelenmiş veri, özel bir başlık (HEADER) ve JSON formatı ile sarmalanarak dışa aktarılır.

### 📁 Özel '.au' Formatı
Şifrelenen her dosya, AuVoide ekosistemine özel **.au** uzantısına dönüştürülür. Bu dosyalar yalnızca Sentinel Locker arayüzü ve doğru şifre ile orijinal haline getirilebilir.

### 🎨 Premium Hacker/Studio Arayüzü
* **Glassmorphism:** Rose (`#f43f5e`) ve Mor (`#a855f7`) vurgularla zenginleştirilmiş koyu, şeffaf tasarım.
* **JetBrains Mono:** Terminal hissiyatını artırmak için özel tipografi entegrasyonu.
* **Sürükle-Bırak Desteği:** Dosyalarınızı kilitlemek veya açmak için ekrana bırakmanız yeterlidir.

---

## 🚀 Teknik Altyapı

| Teknoloji | Görev |
| :--- | :--- |
| **Vanilla JS (ES6)** | Sıfır framework, maksimum işleme hızı. |
| **CryptoJS** | Askeri standartlarda AES şifreleme/deşifreleme. |
| **HTML5 File API** | Tarayıcı içi Blob ve FileReader yönetimi. |
| **Lucide Icons** | Yüksek çözünürlüklü vektörel arayüz ikonları. |

---

## 🛠️ Kurulum & Kullanım

Bu sistem **Zero-Knowledge (Sıfır Bilgi)** prensibiyle çalışır. Kurulum gerektirmez.

1. **Repoyu İndirin:**
   ```bash
   git clone [https://github.com/AuVoide/sentinel-locker.git](https://github.com/AuVoide/sentinel-locker.git)
