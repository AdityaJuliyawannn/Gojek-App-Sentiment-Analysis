# Gojek App Sentiment Analysis

Deskripsi Proyek
Analisis Sentimen Pengguna Aplikasi Gojek Menggunakan Model LSTM (Long Short-Term Memory)

Proyek ini bertujuan untuk mengekstrak, mengolah, dan menganalisis opini serta umpan balik pengguna aplikasi Gojek yang diperoleh dari ulasan digital. Melalui pendekatan Natural Language Processing (NLP) dan Deep Learning, ulasan teks yang bersifat tidak terstruktur diklasifikasikan ke dalam tiga kategori sentimen, yaitu: Positif, Negatif, dan Netral.

Proses pemodelan menggunakan arsitektur LSTM (Long Short-Term Memory), sebuah variasi dari Recurrent Neural Network (RNN) yang sangat efektif dalam menangani data teks berurutan (sequential data). Model LSTM dipilih karena kemampuannya dalam menangani ketergantungan jangka panjang (long-term dependencies) dan memahami konteks kata dalam kalimat ulasan yang sering kali kompleks dan bervariasi.

Alur Kerja Teknis:
Data Preprocessing: Melakukan pembersihan data teks bahasa Indonesia yang kotor (cleaning), mengubah teks menjadi huruf kecil (lowercasing), pembuangan tanda baca, filtering/stopword removal, serta proses tokenization.

Text Embedding: Mengubah representasi teks ulasan menjadi bentuk vektor numerik yang siap diproses oleh lapisan Deep Learning.

Modelling & Klasifikasi: Melatih arsitektur LSTM untuk mengenali pola bahasa yang merepresentasikan rasa puas (Positif), keluhan/eror (Negatif), atau informasi standar (Netral).
