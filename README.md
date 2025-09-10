📊 Analisis Data Eksplorasi (EDA) pada Dataset Titanic
Deskripsi Proyek
Proyek ini berisi skrip Python untuk melakukan Analisis Data Eksplorasi (Exploratory Data Analysis - EDA) pada dataset Titanic. Tujuannya adalah untuk memahami karakteristik data, menemukan pola, mengidentifikasi anomali, dan mendapatkan wawasan awal melalui statistik deskriptif dan visualisasi data.

Dataset Titanic adalah salah satu dataset klasik dalam ilmu data yang berisi informasi demografis dan perjalanan dari para penumpang kapal Titanic. Analisis ini mencoba mengungkap faktor-faktor yang memengaruhi tingkat kelangsungan hidup penumpang.

💾 Dataset
Nama: Titanic

Sumber: Dimuat langsung dari library Seaborn (sns.load_dataset('titanic')).

Isi: Data berisi variabel seperti kelas penumpang, usia, jenis kelamin, jumlah keluarga, tarif tiket, dan status kelangsungan hidup (survived).

🛠️ Langkah-langkah Analisis
Skrip ini melakukan analisis dalam beberapa tahapan utama:

Pemuatan Data: Mengimpor library yang diperlukan (Pandas, Seaborn, Matplotlib) dan memuat dataset.

Pemeriksaan Awal:

Menampilkan beberapa baris pertama dan terakhir data (.head(), .tail()).

Melihat informasi umum dataset seperti tipe data dan nilai non-null (.info()).

Menghitung statistik deskriptif untuk kolom numerik (.describe()).

Penanganan Nilai Hilang (Missing Values): Mengidentifikasi dan menghitung jumlah nilai yang hilang di setiap kolom.

Analisis Univariat: Menganalisis setiap variabel secara individual.

Distribusi Usia: Histogram untuk melihat sebaran usia penumpang.

Distribusi Tarif: Histogram untuk sebaran tarif tiket.

Jumlah Penumpang per Kelas: Bar plot untuk melihat komposisi penumpang di setiap pclass.

Analisis Bivariat: Menganalisis hubungan antara dua variabel.

Kelangsungan Hidup vs. Jenis Kelamin: Bar plot untuk membandingkan tingkat survival antara pria dan wanita.

Kelangsungan Hidup vs. Kelas Penumpang: Bar plot untuk melihat pengaruh kelas sosial terhadap survival.

Usia vs. Tarif: Scatter plot untuk melihat korelasi antara usia dan tarif tiket, dibedakan berdasarkan status survival.

Analisis Multivariat:

Matriks Korelasi: Heatmap untuk menunjukkan korelasi antar variabel numerik.

Pairplot: Melihat hubungan berpasangan antara beberapa variabel kunci, dibedakan berdasarkan status survival.
