<img src="banner.png" alt="Saldırıyı anla, savunmayı kur." width="100%">

### Merhaba, ben Emir 👋

Bilişim Güvenliği Teknolojisi mezunuyum ve siber güvenlik alanında kariyerime başlıyorum. Hem savunma (Blue Team) hem saldırı (Red Team) tarafını öğreniyor, öğrendiklerimi gerçek projelerde uyguluyorum.

- 🛡️ **Şu an:** OzzAcademy'de Cisco CCNA · CEH Ethical Hacker (Red Team) · Siber Güvenlik Savunma (Blue Team) eğitimleri
- 🔎 **İlgi alanlarım:** SOC ve log analizi · tespit kuralları · sızma testi · ağ güvenliği
- 💼 **Açık olduğum roller:** SOC Analisti · Siber Güvenlik Uzmanı · Sızma Testi · IT Destek (junior)
- 📍 **İstanbul** · hemen başlayabilirim

> **EN:** Information Security Technology graduate starting a career in cybersecurity, learning both the defensive (Blue Team) and offensive (Red Team) side. I built a SIEM from scratch that runs on a real website's logs, and I write Python tools to automate my own work. Open to junior SOC, penetration testing and IT security roles in Istanbul.

## 📌 Projeler

### 🛡️ [Mini-SIEM](https://github.com/emirberatturk/mini-siem): güvenlik izleme sistemi

Gerçek bir web sitesinin 43.000+ log kaydıyla çalışan, sıfırdan geliştirdiğim SIEM.

- **88 alarm → 3 anlamlı alarm:** trafiğin %96'sının hosting firmasının aracı sunucusundan geldiğini log analiziyle bulup kuralları buna göre ayarladım
- **51 gün süren yavaş bir bot taramasını** ("low and slow") kısa pencereli kuralların kaçırdığı yerde yeni bir kuralla yakaladım
- **Üç tespit katmanı:** 7 davranış kuralı + 10 SigmaHQ imza kuralı + öğrenilmiş profille anomali tespiti. Etiketli CSIC 2010 veri setinde imzaların %4,2'lik yakalama oranı anomaliyle %37'ye çıktı (%99,96 doğruluk)
- **SIEM'in kendi güvenliği ve KVKK:** herkese zorunlu iki adımlı doğrulama (TOTP), roller, kişisel veri maskeleme, 90 gün saklama süresi (silinen kayıt dosyada iz bırakmaz)
- SOC arayüzü, olay raporu ve haftalık rapor · MITRE ATT&CK · 268 otomatik test

<table>
  <tr>
    <td><img src="https://github.com/emirberatturk/mini-siem/raw/main/docs/img/overview.png" alt="Mini-SIEM genel bakış ekranı"></td>
    <td><img src="https://github.com/emirberatturk/mini-siem/raw/main/docs/img/weekly.png" alt="Mini-SIEM haftalık rapor (demo verisi)"></td>
  </tr>
</table>

### 🌐 Kurumsal web sitesi ve yönetim paneli (serbest çalışma)

Bir sağlık kliniği için 3 dilli, mobil uyumlu web sitesi ve yönetim paneli (PHP, JavaScript).

- **Panel güvenliği:** şifrelerin hash'lenmesi, brute-force saldırılarına karşı hesap kilidi, formlarda hız sınırı, yüklenen dosyaların sunucuda doğrulanması
- **Gizlilik:** ziyaretçi çerez onayı vermeden harita gibi dış içerikler yüklenmez
- **Performans:** mobilde ağır 3D tedavi önizlemesi yalnızca ziyaretçi dokununca yüklenir

### 🎬 [video-kurgu](https://github.com/emirberatturk/video-kurgu): Python ile video otomasyonu

Türkçe konuşmalı ham çekimleri Instagram Reels için kurgulayan yerel bir araç: konuşmayı yazıya çevirir (faster-whisper), duraksamaları ve tekrarları keser, kelime kelime altyazı ekler, yüze göre dikey kadraj yapar; tanıtım videolarını da doğrudan koddan, 60 fps çizer (Mini-SIEM tanıtım videosu bununla yapıldı). Her şey bilgisayarda çalışır, videolar buluta gönderilmez. MIT lisanslı, açık kaynak.

## 🧰 Araçlar

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square) ![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 📜 Sertifikalar ve kurslar

- Udemy: Sıfırdan Etik Hacker Olma (2026)
- Cisco Networking Academy: Introduction to Cybersecurity (2026)
- Exe-Academy: Sızma Testi, Kablosuz Ağ ve Sosyal Mühendislik (2025)
- BTK Akademi: Siber Güvenliğe Giriş · İşletim Sistemlerine Giriş · Bilgi Teknolojilerine Giriş (2024)

## 📫 İletişim

[![LinkedIn](https://img.shields.io/badge/LinkedIn-emirberatturk-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emirberatturk/)
