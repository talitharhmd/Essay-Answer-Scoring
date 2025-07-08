# Comparing Word2Vec and FastText in Automatic Scoring of Student Reflections

Repositori ini berisi proyek Automated Essay Scoring (AES) menggunakan pendekatan semantic similarity dengan Word2Vec dan FastText pada data refleksi mahasiswa terkait penggunaan Artificial Intelligence (AI) dalam dunia akademik.

## 📄 Deskripsi Proyek:
Penelitian ini bertujuan untuk mengevaluasi kemampuan model word embedding (Word2Vec dan FastText) dalam memberikan penilaian otomatis terhadap esai singkat berbahasa Indonesia. Data berupa 41 jawaban reflektif mahasiswa dianalisis dan dibandingkan dengan kunci jawaban menggunakan teknik cosine similarity. Hasil menunjukkan bahwa FastText lebih konsisten dan akurat dibanding Word2Vec dalam memahami konteks semantik, khususnya pada bahasa Indonesia yang kaya morfologi.

## Code Colab
https://colab.research.google.com/drive/1uSmybyqBwXzGTzrKNOjBj5RAWVwvDpuS?usp=sharing

## 📌 Overview Dataset
| Kolom              | Tipe Data                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Timestamp                 | Date Time                                                         |
| Lebih adil mana: tugas manual atau dengan bantuan AI?         | Object                                                 |
| kalimat yang paling sering diucapkan ke AI saat mengerjakan tugas?          | Object                                              |
| Kapan waktu paling bermanfaat menggunakan AI?     | Object                                               |
| Risiko utama jika mahasiswa terlalu bergantung pada AI?             | Object                                 |
| AI bisa bikin lulus cepat tapi nggak ngerti apa-apa. Tetap pakai atau tidak? Kenapa?             | Object                                 |

### 🔍 Tema dan Jenis Data
- Tema: "Refleksi Singkat: Pengaruh AI dalam Mengerjakan Tugas Kuliah"
- Jenis Data: Jawaban berbentuk narasi bebas, digunakan untuk evaluasi semantik dan pemahaman reflektif melalui sistem Automated Essay Scoring (AES).
