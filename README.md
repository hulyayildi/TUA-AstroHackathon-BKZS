# BKZS | GNSS Sinyal Doğrulama ve Anti-Spoofing Arayüzü 🛰️🛡️

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Bu proje, **TUA AstroHackathon** kapsamında geliştirilmiş bir GNSS (Küresel Navigasyon Uydu Sistemi) sinyal doğrulama ve siber tehdit anomali tespiti sistemidir.

Tamamen bağımsız bir **SIEM (Güvenlik Bilgi ve Olay Yönetimi)** tarzı web paneline (Dashboard) sahip olan bu uygulama, GPS sinyallerine yapılan Spoofing (Yanıltma) ve Jamming (Karıştırma) saldırılarını tespit edip otomatik olarak önlemler alır (Firewall simülasyonu).

---

## 🌐 Canlı Demo
Projeyi bilgisayarınıza kurmadan, doğrudan web tarayıcınız üzerinden test etmek için aşağıdaki bağlantıya tıklayabilirsiniz:

👉 **[Uygulamayı Canlı Olarak Test Etmek İçin Tıklayın]([https://tua-astrohackathon.streamlit.app/](https://tua-astrohackathon-bkzs-8qcnnkff2slgtpdbgz9hgp.streamlit.app/))** *(Not: Linki kendi Streamlit Cloud adresinizle güncelleyebilirsiniz)*

---

## 🚀 Özellikler
- **Modern Web Arayüzü (Streamlit):** İnteraktif, hareketli ve anlık siber olay güncelleyici kontrol paneli (Dashboard/C2 Center).
- **🤖 Gelişmiş Otopilot (Unified INS):** 
  - Hem **Işınlanma (Teleport)** hem de **Sürüklenme (Drag)** spoofing saldırılarında devreye girer.
  - Sinyal kaybı veya saldırı anında son bilinen ivme ve vektörlerle rotayı otonom korur.
- **Anomali ve Saldırı Tespiti:**
  - **Spoofing Tespiti:** Konum sıçramaları (Teleport) ve ani ivme değişimlerinin aerodinamik analizi.
  - **Jamming Tespiti:** SNR düşüşü üzerinden sinyal boğma tespiti ve akıllı filtreleme.
- **Otomatik Simülasyon Senaryoları:** Jüri sunumları için tek tuşla rastgele ataklar üreten akıllı simülasyon motoru.
- **Otomatik Simülasyon Senaryoları:** Jüri sunumları için tek tuşla rastgele ataklar üreten akıllı "Otomatik Simülasyon" motoru.
- **📋 Adli Bilişim (Forensics):** Siber olayların detaylı dökümünü CSV formatında dışa aktarma.

---

## 🛠️ Kurulum
Projenin çalışması için bilgisayarınızda **Python 3.8+** yüklü olmalıdır. İndirdikten sonra terminalinizde şu komut ile kütüphaneleri yükleyin:

```bash
pip install -r requirements.txt
```

---

## 💻 Kullanım
Uygulamayı ve web panelini ayağa kaldırmak için dizin içerisinde sadece şu komutu çalıştırmanız yeterlidir:

```bash
streamlit run guvenlik_arayuz.py
```

Bu komut, varsayılan web tarayıcınızda (`http://localhost:8501`) interaktif güvenlik panelini açacaktır.

---

## ⚖️ Lisans
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

---
*🌌 Hackathon ruhuyla kodlanmıştır!*
