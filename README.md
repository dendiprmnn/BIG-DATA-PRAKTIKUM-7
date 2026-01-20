# BIG-DATA-PRAKTIKUM-7

# 🚀 Streaming Analytics dengan Kafka & Spark di Google Colab

![Streaming Analytics](https://img.shields.io/badge/Streaming-Analytics-blue)
![Apache Kafka](https://img.shields.io/badge/Apache-Kafka-orange)
![Apache Spark](https://img.shields.io/badge/Apache-Spark-yellow)
![Google Colab](https://img.shields.io/badge/Google-Colab-gold)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)

**Praktikum Lengkap: Real-time Data Processing dengan Apache Kafka dan Spark Structured Streaming**

## 📋 Daftar Isi
- [🎯 Tujuan Praktikum](#-tujuan-praktikum)
- [🏗️ Arsitektur Sistem](#️-arsitektur-sistem)
- [🚀 Cara Menggunakan di Google Colab](#-cara-menggunakan-di-google-colab)
- [📁 Struktur Kode](#-struktur-kode)
- [🔧 Instalasi & Setup](#-instalasi--setup)
- [📊 Analisis yang Dihasilkan](#-analisis-yang-dihasilkan)
- [🧪 Tugas Praktikum](#-tugas-praktikum)
- [❓ Troubleshooting](#-troubleshooting)
- [📚 Referensi](#-referensi)

## 🎯 Tujuan Praktikum

1. **Menyiapkan lingkungan Big Data** (Spark & Kafka) di Google Colab
2. **Memahami cara mengirim data streaming** ke Kafka (Producer)
3. **Mampu memproses data real-time** menggunakan Spark Structured Streaming (Consumer)
4. **Melakukan analisis agregasi** pada data streaming
5. **Mengimplementasikan filter dan transformasi** data

## 🏗️ Arsitektur Sistem

```mermaid
graph LR
    A[Data Generator<br/>Python Producer] --> B[Apache Kafka<br/>Message Broker]
    B --> C[Spark Structured<br/>Streaming Consumer]
    C --> D{Analisis &<br/>Agregasi}
    D --> E[Hasil Analisis<br/>Memory Table]
    D --> F[Visualisasi<br/>Real-time]

```
