🛡️ CheckText AI — Plagiarism & AI Content Detector

CheckText AI adalah aplikasi web interaktif berbasis Client-Side JavaScript yang dirancang untuk menganalisis indikasi plagiarisme (kemiripan teks) dan pola penulisan AI (Kecerdasan Buatan) secara cepat, transparan, dan aman tanpa mengirimkan data ke server eksternal.

✨ Fitur Utama

🔍 Pemeriksan Kemiripan (Plagiarism Detector)

Menggunakan algoritma gabungan TF-IDF Vectorizer (Cosine Similarity) dan N-Gram Jaccard Index untuk mengukur kemiripan antar teks.

Mampu membandingkan 1 teks utama dengan banyak dokumen referensi secara sekaligus (Batch Analysis).

🤖 Deteksi Konten AI (AI Content Predictor)

Analisis berbasis indikator heuristik NLP:

Burstiness (Variasi standar deviasi panjang kalimat).

Type-Token Ratio (TTR) (Keberagaman kosakata / Lexical Diversity).

AI Transition Phrase Density (Kerapatan frasa konjungsi khas LLM).

🎨 Penanda Visual Teks (Highlighted Text Viewer)

Menandai secara langsung (real-time) kalimat yang terindikasi plagiat, berpola AI, maupun kombinasi keduanya.

📁 Manajemen Koleksi & Upload File Pembanding

Mendukung penambahan dokumen referensi manual serta pengunggahan berkas .txt, .md, dan .json.

🔒 100% Aman & Privat (Client-Side Only)

Seluruh pemrosesan data dilakukan penuh di dalam browser pengguna. Teks yang kamu periksa tidak pernah diunggah atau disimpan ke server mana pun.

📊 Ekspor Laporan Ringkas

Menyediakan fitur salin laporan ke clipboard dan pengunduhan ringkasan analisis dalam format teks (.txt).

🛠️ Teknologi yang Digunakan

Frontend Framework / UI: HTML5, Tailwind CSS CDN

Icons: Lucide Icons

Core Engine (JavaScript):

Custom TF-IDF (Term Frequency-Inverse Document Frequency)

Cosine Similarity & Jaccard Index Evaluator

Heuristic Syntactic Variance & Pattern Matching

🚀 Cara Menjalankan Secara Lokal

Aplikasi ini didesain sebagai aplikasi Single-Page Application (SPA) berbasis satu file HTML tanpa ketergantungan build tool (Zero Node.js dependency):

Clone Repository Ini

git clone https://github.com/USERNAME-KAMU/plagiarism-ai-detector.git


Buka File HTML
Cukup klik dua kali atau buka berkas index.html menggunakan browser pilihan kamu (Chrome, Firefox, Edge, Safari).

🌐 Deploy ke GitHub Pages

Aplikasi ini dapat langsung diakses publik secara gratis lewat GitHub Pages:

Push berkas index.html dan README.md ini ke repository GitHub kamu.

Buka tab Settings -> Pages pada repository kamu.

Pada opsi Source, pilih branch main dan folder / (root).

Klik Save. Tunggu beberapa saat hingga URL publik muncul (contoh: https://username.github.io/plagiarism-ai-detector/).

📖 Cara Penggunaan

Masukkan Teks Utama: Tempelkan atau ketik artikel/tulisan yang ingin kamu periksa di area teks utama.

Kelola Dokumen Pembanding (Opsional): Tambahkan teks lama/arsip sendiri di menu pustaka referensi untuk pengujian kemiripan plagiarisme.

Jalankan Analisis: Klik tombol "Jalankan Analisis Plagiarisme & AI".

Tinjau Laporan: Lihat skor persentase, grafik indikator heuristik, dan kalimat mana saja yang terdeteksi pada panel hasil.

📜 Lisensi

Proyek ini dirilis di bawah lisensi MIT License. Kamu bebas mengutip, memodifikasi, atau membagikannya kembali secara terbuka.
