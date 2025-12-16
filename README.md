# Analisis_Churn

# 📉 Analisis Customer Churn – Portfolio Data Analyst

## 📌 Projecct Overview

Proyek ini bertujuan untuk menganalisis **perilaku customer churn** menggunakan dataset bisnis pelanggan. Fokus utama analisis adalah mengidentifikasi **user yang berpotensi churn** serta menemukan **faktor-faktor utama** yang memengaruhi churn, seperti tingkat engagement, signup channel, jenis kontrak, dan feedback pelanggan.

Repository ini disusun sebagai **portfolio Data Analyst**, yang menunjukkan kemampuan dalam:

* Business understanding
* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature engineering
* Visualisasi data
* Penyampaian insight bisnis berbasis data

---

## 🧠 Permasalahan Bisnis

Customer churn dapat berdampak serius pada bisnis, antara lain:

* Penurunan pendapatan
* Turunnya Customer Lifetime Value (CLV)
* Meningkatnya biaya akuisisi pelanggan baru

**Tujuan Analisis:**

> Mengidentifikasi segmen pelanggan yang berpotensi churn dan memberikan rekomendasi berbasis data untuk meningkatkan retensi pelanggan.

---

## 📊 Informasi Dataset

* **Sumber**: Dataset bisnis pelanggan (simulasi)
* **Jumlah data**: 10.000 pelanggan
* **Jumlah fitur**: 32 kolom
* **Target variabel**: `churn`

  * `0` → Pelanggan bertahan
  * `1` → Pelanggan churn

### Kolom Penting yang Digunakan

| Kategori           | Kolom                                                     |
| ------------------ | --------------------------------------------------------- |
| Engagement         | `monthly_logins`, `weekly_active_days`, `last_login_days` |
| Feedback Pelanggan | `survey_response`, `csat_score`, `nps_score`              |
| Faktor Bisnis      | `signup_channel`, `contract_type`, `customer_segment`     |

---

