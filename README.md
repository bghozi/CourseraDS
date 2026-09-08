### 📊 Extracting and Visualizing Stock Data

**Project Overview**
Proyek ini bertujuan untuk mengekstrak data historis saham dan pendapatan kuartalan dari perusahaan publik (Tesla dan GameStop), membersihkan data tersebut, lalu memvisualisasikannya ke dalam bentuk dasbor interaktif. Proyek ini merupakan bagian dari **IBM Data Science Professional Certificate** di Coursera.

**Key Objectives**
Proyek ini mendemonstrasikan penguasaan pada tahapan awal siklus *Data Science*, yaitu:
* **Data Extraction via API:** Menggunakan library `yfinance` untuk menarik data historis harga saham secara otomatis.
* **Web Scraping:** Menggunakan `requests` dan `BeautifulSoup` untuk mengekstrak data pendapatan perusahaan langsung dari tabel HTML di halaman web.
* **Data Cleaning & Manipulation:** Menggunakan `pandas` untuk membersihkan data mentah (menghapus karakter string seperti `$` dan `,`, menangani *null values*, dan mereset indeks).
* **Data Visualization:** Menggunakan `plotly` untuk membuat grafik *subplot* interaktif yang membandingkan tren harga saham dan pendapatan dari waktu ke waktu.

**Tech Stack & Libraries**
* **Language:** Python
* **Data Manipulation:** Pandas
* **Data Extraction:** YFinance, Requests, BeautifulSoup (bs4)
* **Visualization:** Plotly
