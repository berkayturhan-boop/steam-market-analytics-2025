# 🎮 Steam Market Analytics & Price Prediction 2025

![Project Banner](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python) ![BigQuery](https://img.shields.io/badge/Google_Cloud-BigQuery-yellow?style=for-the-badge&logo=googlecloud)

<p align="center">
  <img src="header_image.png" alt="Steam Fiyat Tahmin AI Arayüzü" width="100%">
</p>

Bu proje, **Team 6** tarafından Steam 2025 veri seti (240.000+ oyun) kullanılarak gerçekleştirilen uçtan uca (End-to-End) bir veri bilimi ve veri mühendisliği çalışmasıdır.

## 🔗 Hızlı Erişim (Canlı Demo & Dokümantasyon)

Projenin interaktif çıktılarına ve veri mimarisine aşağıdaki butonlardan doğrudan ulaşabilirsiniz:

| Platform | İçerik | Link |
|----------|--------|------|
| 📊 **Dashboard** | Canlı Rapor (Looker Studio) | [👉 Raporu Görüntüle](https://lookerstudio.google.com/reporting/cb3b8cb6-710c-40ad-aeac-3e0244427d2b) |
| 📝 **Notion** | Task Yönetimi & Süreç | [👉 Notion Sayfasına Git](https://www.notion.so) |
| 🗺️ **Şema** | Veri Mimarisi (tldraw) | [👉 Mimariyi Görüntüle](https://www.tldraw.com/f/A1G0ucpf2pwONYo6cEshK?d=v-660.343.2143.1220.page) |

---

## 📌 Proje Hakkında

**Temel Hedef:** Oyun sektöründeki fiyatlandırma dinamiklerini çözmek, pazar trendlerini analiz etmek ve oyunların teknik/kategorik özelliklerini kullanarak ideal piyasa fiyatını tahmin eden Makine Öğrenmesi modelleri geliştirmektir.

### 🛠️ Tech Stack (Kullanılan Teknolojiler)
Proje, "Modern Data Stack" prensiplerine uygun olarak bulut tabanlı bir mimaride geliştirilmiştir.

* **Veri Mühendisliği & Depolama:**
    * 🔵 **Google BigQuery:** Veri Ambarı (Data Warehouse).
    * 🛠 **dbt Cloud:** Veri Modelleme (Staging → Intermediate → Mart).
* **Veri Bilimi & Analitik:**
    * 🐍 **Python & SQL:** EDA, Veri Temizleme, Dönüşümler.
    * 📓 **Google Colab:** Kodlama ve model geliştirme ortamı.
* **Görselleştirme & Yönetim:**
    * 📊 **Looker Studio:** Dinamik dashboard.
    * 📅 **Notion & Slack:** Agile proje yönetimi.

---

## 💻 Geliştirme Ortamı (Colab Notebooks)

Geliştirme aşamasındaki kodlara ve analiz geçmişine aşağıdaki orijinal çalışma dosyalarından erişebilirsiniz:

* [📍 Veri Analizi ve Temizleme (Colab - Atakan)](https://colab.research.google.com/drive/1Npm3eXjAuRlqyh1xjXoa5TEUOHXBZpt2?usp=sharing)
* [📍 ML Fiyat Tahmin Modeli (Colab)](https://colab.research.google.com/drive/14pPPDY8fjeyvG1WMxdwVITJl8HpaOktB?usp=sharing)

---

## 📊 Veriye Dayalı Temel İçgörüler (Key Insights)

240.000'den fazla oyun verisi üzerinde yapılan EDA ve ML çalışmaları sonucu:

1.  **💰 Enflasyonist Baskı:** 2021-2025 arasında oyun fiyatlarında **%22'nin üzerinde artış** gözlemlendi.
2.  **🖥️ Donanım Maliyeti:** "High" sistem gereksinimi olan oyunlar, ortalamadan **%60 daha yüksek** fiyata sahip.
3.  **📉 Fiyat-Kalite Paradoksu:** Fiyat ile Metacritic puanı arasında sadece **0.23 (Zayıf Pozitif)** korelasyon var. Pahalı oyun her zaman kaliteli demek değil.
4.  **🚀 Üstel Büyüme:** Pazar doygunluğu artıyor, Indie geliştiriciler için "görünürlük" en büyük sorun.

---

## 👥 Takım (Team 6)

Bu proje **Workintech Data Science Bootcamp** kapsamında aşağıdaki ekip tarafından geliştirilmiştir:

* **Atakan Can** (Veri Analizi, BigQuery Entegrasyonu, ML Modelleme)
* **Tümay Turhan**
* **Berkay Turhan**
* **D. Hazal Tuncay**

---
