# 🎧 Touchless Music & SFX Trigger

Proyek web prototype berbasis Artificial Intelligence (Computer Vision) yang dapat memicu efek suara/instrumen musik secara *hands-free* menggunakan gestur tangan diam melalui webcam secara *real-time*.

 live Demo: [https://hafizh0205.github.io/Touchless-music-trigger/](https://hafizh0205.github.io/Touchless-music-trigger/)

---

## 🎯 Fitur & Konsep Utama

Aplikasi ini menggunakan model klasifikasi gambar dari **Teachable Machine** dan **TensorFlow.js** dengan ambang batas kepastian (*confidence threshold*) **≥ 90%** untuk memicu suara:

- 🥁 **Pose 1 Jari (`DRUM LOOP`)** -> Memicu tampilan visual drum & efek suara drum.
- 🎸 **Pose 2 Jari / Peace (`GUITAR CHORD`)** -> Memicu tampilan visual gitar & sampel petikan gitar.
- 🎵 **Pose Metal / Rock (`BASS DROP / SFX`)** -> Memicu tampilan visual bass & efek suara bass synth.
- ⏸️ **Background / Posisi Kosong (`IDLE`)** -> Mode standby, visual bersih, dan menghentikan seluruh audio.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & CSS3** (Responsive & Modern UI)
- **JavaScript (ES6+)**
- **[TensorFlow.js](https://www.tensorflow.org/js)** & **[Teachable Machine Library](https://github.com/googlecreativelab/teachablemachine-community)**
- **Web Audio API & AudioContext** (Fallback synthesizer jika autoplay browser diblokir)

---

## 🚀 Cara Menjalankan Secara Lokal

1. Clone repository ini:
   ```bash
   git clone [https://github.com/Hafizh0205/Touchless-music-trigger.git](https://github.com/Hafizh0205/Touchless-music-trigger.git)
