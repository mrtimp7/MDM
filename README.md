<div align="center">

  <!-- Logo / Başlık -->
  <h1>⚡ MRT Download Manager (MDM)</h1>
  <p><strong>Yüksek Performanslı, Çok Kanallı ve Yeni Nesil Masaüstü İndirme Yöneticisi</strong></p>

  <!-- Rozetler (Badges) -->
  <p>
    <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Version" />
    <img src="https://img.shields.io/badge/GUI-PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6" />
    <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Platform Windows" />
    <img src="https://img.shields.io/badge/Status-Aktif%20Geli%C5%9Ftirme-00d2ff?style=for-the-badge" alt="Status" />
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
  </p>

  <p>
    <a href="#-temel-özellikler">Özellikler</a> •
    <a href="#-proje-mimarisi">Mimari</a> •
    <a href="#-kurulum-ve-çalıştırma">Kurulum</a> •
    <a href="#-tarayıcı-eklentisi-entegrasyonu">Tarayıcı Entegrasyonu</a> •
    <a href="#-yol-haritası">Yol Haritası</a>
  </p>
</div>

---

## 📖 Genel Bakış

**MRT Download Manager (MDM)**; geleneksel indirme yöneticilerinin hantallığını geride bırakan, **Python** ve **PyQt6** gücüyle geliştirilmiş açık ve modüler bir masaüstü indirme çözümüdür. 

Dosyaları eşzamanlı soket parçalarına bölerek bant genişliğinizi tam kapasiteyle kullanan segmentli motoru, yerleşik **Torrent (P2P)** desteği, **YouTube medya ayrıştırıcısı** ve tek tıkla indirme yakalayan **tarayıcı köprüsü (Browser Bridge)** ile eksiksiz bir indirme ekosistemi sunar.

---

## ⚡ Temel Özellikler

| Özellik | Açıklama |
| :--- | :--- |
| **🚀 Dinamik Çok Kanallı İndirme** | Dosyaları eşzamanlı parçalara böler (`segment_worker`). Bant genişliğini son baytına kadar kullanarak indirme sürelerini minimuma indirir. |
| **🌐 Kesintisiz Tarayıcı Köprüsü** | Chrome, Edge ve Chromium tarayıcılarla yerel soket köprüsü (**Port 28765**) ve Native Host protokolü üzerinden doğrudan konuşur; linkleri otomatik yakalar. |
| **🧲 Dahili Torrent & Magnet** | Harici istemciye gerek duymadan `.torrent` dosyalarını ve magnet linklerini doğrudan `libtorrent` motoruyla indirir. |
| **🎬 Gelişmiş Medya Yakalama** | YouTube ve benzeri video ağlarından doğrudan ses (MP3) veya 4K kalitesine kadar video akışlarını ayıklar ve birleştirir. |
| **📊 Kuyruk & Hız Sınırlayıcı** | İndirmeleri önceliklendirin, duraklatıp devam ettirin (`Pause/Resume`) ve ağınızı boğmamak için dinamik hız sınırı (KB/s) belirleyin. |
| **🌙 Modern Karanlık Arayüz (QSS)** | Yüksek DPI ekranlar için optimize edilmiş, göz yormayan, modern neon dokunuşlara sahip PyQt6 donanım hızlandırmalı UI. |
