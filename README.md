- 👋 Hi, I'm Aira Althafeliq Nurfirly @AAN007
- ⚙️ My NIM is 2401439
- 👀 I'm interested in Biomedic Engineer
- 🌱 I'm currently learning Mechatronic
- 😄 Pronouns: Aira/AAN
- ⚡ Fun fact: I'm Rhotascim

JUDUL : Biomedical Question Answering Datasets
# Rangkuman BioASQ dan Dataset Terkait

## BioASQ Task B
**BioASQ Task B** adalah "Pertanyaan Jawab Semantik Biomedis" yang terdiri dari dua fase:
1. **Fase A (IR)**: Sistem mengambil dokumen relevan untuk pertanyaan yang diberikan.
2. **Fase B (MRC)**: Sistem menggunakan dokumen relevan dan data ontologis untuk menjawab pertanyaan.

### Fase A
Peserta harus mengembalikan:
- Konsep dari ontologi tertentu (misalnya MeSH)
- Artikel dari PubMed dan potongan teks dalam artikel tersebut
- RDF triples dari Linked Life Data

**Metrik Evaluasi**: Mean Average Precision (MAP) untuk pengambilan, dengan modifikasi untuk potongan teks.

### Fase B
- Dataset MRC BQA yang paling besar dan banyak digunakan, dengan 500 contoh QA uji setiap tahun.
- **Contoh QA**: Faktual, daftar, ya/tidak, dan ringkasan.
- **Jawaban**: 
  - **Tepat**: Jawaban singkat (misalnya entitas biomedis).
  - **Ideal**: Jawaban tepat dalam kalimat lengkap.
  
**Metrik Evaluasi**:
- Akurasi
- Mean Reciprocal Rank (MRR)
- Mean F-score
- Skor manual

## Dataset Lainnya
### BiQA
Dataset IR BQA dengan 7.4k pertanyaan dan 14.2k artikel relevan dari PubMed.

### EPIC-QA
Tantangan QA Epidemi dengan pertanyaan tentang COVID-19.

### HealthQA
7.5k pertanyaan yang dianotasi secara manual.

### TREC Genomics
Pendekatan IR BQA dengan 28 dan 36 pertanyaan pada 2006 dan 2007.

### Biomed-Cloze
Dataset cloze dari makalah akademis PubMed, terdiri dari 1 juta cloze.

### BioRead
Dataset pemahaman membaca mesin biomedis dengan 16.4 juta contoh passage-pertanyaan.

### BioMRC
Dataset baru untuk MRC biomedis, versi ditingkatkan dari BioREAD.

### BMKC
Dataset gaya cloze dengan Judul dan Kalimat Terakhir Pemahaman Pengetahuan Biomedis.

### CliCR
Dataset pemahaman mesin di domain medis dengan 100.000 kueri.

### COVIDQA
Dataset QA khusus COVID-19 dengan 124 pasangan pertanyaan-artikel.

### COVID-QA
Dataset QA COVID-19 dengan 2k pasangan pertanyaan-jawaban yang dianotasi oleh ahli biomedis.

### EBMSummariser
Dataset ringkasan dari 456 contoh untuk EBM.

### emrQA
Dataset QA berskala besar spesifik domain dengan lebih dari 1 juta pasangan bukti kueri-jawaban.

### MASH-QA
Dirancang untuk mengekstrak informasi dari teks panjang.

### MEDHOP
Dataset MRC BQA multi-hop dengan kueri subjek dan predikat.

### MEDIQA-QA
Sub-tugas QA MEDIQA 2019 dengan 400 pertanyaan dan 3k jawaban.

### ProcessBank
Pertanyaan pilihan ganda dengan paragraf biologis relevan.

### PubMedQA
Dataset dari artikel PubMed menggunakan pertanyaan biner sebagai judul.

### QA4MRE-Alz
Sub-tugas tentang pembacaan mesin teks biomedis tentang penyakit Alzheimer dengan 40 contoh QA.

### Bioinformatics
Kueri biomedis dengan kompleksitas berbeda.

### QALD-4 Tugas 2
50 pertanyaan biomedis dalam bahasa alami yang meminta kueri SPARQL untuk mengambil jawaban.
