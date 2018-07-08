# Panduan MSC dan SC Olimpiade Sains Nasional bidang Informatika

1. [Singkatan](#singkatan)
1. [Main Scientific Committee (MSC)](#main-scientific-committe-msc)
1. [Scientific Committee (SC)](#scientific-committee-sc)


## Singkatan

Untuk kemudahan dokumen ini, segala frase Olimpiade Sains Nasional atau singkatan OSN mulai dari halaman ini sampai akhir dokumen menunjuk pada Olimpiade Sains Nasional khusus bidang Informatika.

<table border="1">
<thead><td>Singkatan</td><td>Kepanjagan</td></thead>
<tr><td>IA TOKI</td><td>Ikatan Alumni TOKI</td></tr>
<tr><td>IOI</td><td>International Olympiad in Informatics</td></tr>
<tr><td>IOI’n+1</td><td>IOI tahun n+1</td></tr>
<tr><td>PJJ</td><td>Pelatihan Jarak Jauh</td></tr>
<tr><td>MSC</td><td>Main Scientific Committee</td></tr>
<tr><td>MTC</td><td>Main Technical Committee</td></tr>
<tr><td>OSN</td><td>Olimpiade Sains Nasional</td></tr>
<tr><td>OSN’n-1</td><td>OSN tahun n-1</td></tr>
<tr><td>OSN’n</td><td>OSN tahun n</td></tr>
<tr><td>OSN’n+1</td><td>OSN tahun n+1</td></tr>
<tr><td>OSN’n+2</td><td>OSN tahun n+2</td></tr>
<tr><td>POOC</td><td>PJJ and Open OSN Coordinator</td></tr>
<tr><td>SC</td><td>Scientific Committee</td></tr>
<tr><td>TC</td><td>Technical Committee</td></tr>
<tr><td>TOKI</td><td>Tim Olimpiade Komputer Indonesia</td></tr>
</table>

## Main Scientific Committee (MSC)

* **MSC1.** MSC OSN’n diharuskan untuk menghadiri OSN’n.

* **MSC2.** MSC OSN’n diharuskan untuk merancang silabus kompetisi OSN’n.

* **MSC3.** MSC OSN’n diharuskan untuk merancang peraturan kompetisi OSN’n.

* **MSC4.** MSC OSN’n diharuskan untuk memastikan bahwa OSN’n adalah kompetisi yang sesuai sebagai tahap awal untuk seleksi TOKI menuju IOI’n+1.

## Scientific Committee (SC)

* **SC1.** Seluruh anggota sementara SC OSN’n sangat disarankan untuk menghadiri OSN’n.

* **SC2.** Ketua SC OSN’n diharuskan untuk mengumumkan silabus OSN’n pada situs resmi OSN’n paling lambat dua bulan sebelum OSN’n.

* **SC3.** Ketua SC OSN’n diharuskan untuk mengirimkan pemanggilan pengumpulan ide soal
untuk OSN’n paling lambat dua bulan sebelum OSN’n.
    * **SC3.1.** Pemanggilan pengumpulan ide soal setidaknya ditujukan kepada Google Groups [Penulis Soal Tim Olimpiade Komputer Indonesia](https://groups.google.com/forum/#!forum/toki-problem-authors).
    * **SC3.2.** Pemanggilan pengumpulan ide soal OSN’n ditutup paling lambat satu bulan sebelum OSN’n.
    * **SC3.3.** Penulis calon soal OSN’n harus memenuhi syarat-syarat berikut:
        * Telah menyelesaikan pendidikan SMA/sederajat pada tahun n-1.
        * Dikenal oleh setidaknya satu anggota SC, atau merupakan anggota IA TOKI.
        * Tidak melatih calon kontestan, institusi, ataupun sekolah untuk OSN’n, ataupun melakukan kegiatan apapun yang dapat menyebabkan bocornya kandidat soal OSN’n.

* **SC4.** Anggota SC OSN’n, setelah membaca kandidat soal OSN’n, tidak diperbolehkan untuk melatih calon kontestan, institusi, ataupun sekolah untuk OSN’n, ataupun melakukan kegiatan apapun yang dapat menyebabkan bocornya kandidat soal OSN’n.

* **SC5.** SC OSN’n diharuskan untuk mengumumkan peraturan kompetisi pada situs resmi OSN’n paling lambat satu bulan sebelum OSN’n.
    * **SC5.1.** Peraturan kompetisi OSN’n setidaknya mencakup hal-hal berikut ini:
        * Banyaknya soal dan durasi waktu kompetisi
        * Bahasa yang diperbolehkan sebagai kode peserta dalam pengumpulan
        * Banyaknya pengumpulan yang diperbolehkan

* **SC6.** SC OSN’n diharuskan untuk melakukan finalisasi soal OSN’n dan melaporkannya kepada Pembina TOKI paling lambat tiga minggu sebelum OSN’n.
    * **SC6.1.** Soal yang difinalisasi dan dilaporkan mencakup soal untuk kedua hari kompetisi, satu hari pemanasan/latihan, dan setidaknya dua soal cadangan.
    * **SC6.2.** Soal yang dipilih untuk OSN’n harus mengikuti silabus kompetisi OSN’n.

* **SC7.** SC OSN’n diharuskan untuk menyelesaikan kelengkapan soal OSN’n paling lambat satu minggu sebelum OSN’n.
    * **SC7.1.** Kelengkapan soal setidaknya mengandung:
        * Solusi resmi
            * Solusi ini adalah solusi yang digunakan untuk menghasilkan keluaran juri dari setiap masukan yang ada.
        * Solusi kedua
            * Solusi ini adalah solusi yang digunakan untuk menguji bahwa seluruh keluaran juri benar.
            * Solusi ini harus dibuat secara independen dengan solusi resmi.
        * Generator kasus uji
            * Generator kasus uji harus menggunakan [tcframe](https://github.com/tcframe/tcframe).
        * Deskripsi soal
            * Jika soal bertipe batch atau output only, deskripsi soal harus mengandung format input, format output, contoh input, contoh output, batasan untuk setiap subsoal, dan nilai untuk setiap subsoal.
            * Jika soal bertipe interaktif, deskripsi soal harus mengandung format interaksi, contoh interaksi, batasan untuk setiap subsoal, dan nilai untuk setiap subsoal.
        * Solusi untuk setiap subsoal.
            * Solusi ini digunakan untuk menguji bahwa solusi suboptimal akan mendapatkan nilai yang diharapkan.
        * Scorer, jika dibutuhkan.
            * Jika mungkin saja terdapat lebih dari satu keluaran yang benar untuk setiap masukan, maka scorer soal harus disiapkan. Scorer adalah program yang digunakan untuk menguji apakah sebuah keluaran yang diberikan benar. Scorer harus mengikuti format [scorer tcframe](http://docs.tcframe.org/en/stable/topic-guides/styles.html?highlight=scorer#scorer).

* **SC8.** MSC OSN’n diharuskan untuk mengunggah seluruh soal OSN’n ke sistem online judge OSN’n paling lambat satu minggu sebelum OSN’n.

* **SC9.** SC OSN’n diharuskan untuk menguji (testing) seluruh soal OSN’n di sistem online judge paling lambat satu hari sebelum OSN’n.
    * **SC9.1.** SC diharuskan untuk meminta bantuan dua penguji (tester) soal OSN’n.
        * **SC9.1.1.** Penguji soal OSN’n merupakan penguji independen yang belum membaca soal OSN’n sebelum sesi testing.
        * **SC9.1.2.** Penguji soal OSN’n harus memenuhi syarat-syarat berikut:
            * Telah menyelesaikan pendidikan SMA/sederajat pada tahun n-1.
            * Dikenal oleh setidaknya satu anggota SC, atau merupakan anggota IA TOKI.
            * Tidak melatih calon kontestan, institusi, ataupun sekolah untuk OSN’n, ataupun melakukan kegiatan apapun yang dapat menyebabkan bocornya soal OSN’n.
        * **SC9.1.3.** Salah satu penguji harus mengerjakan soal OSN’n dengan waktu dan kondisi yang sama dengan OSN’n. Hal ini digunakan untuk memperkirakan kesulitan soal dari OSN’n dan dapat digunakan untuk pengaturan nilai.
        * **SC9.1.4.** Setidaknya satu penguji harus mengerjakan soal OSN’n dengan menguji semua kebenaran seluruh kasus uji, kekokohan seluruh kasus uji, dan kejelasan deskripsi soal.

* **SC10.** SC OSN’n diharuskan untuk menjawab seluruh klarifikasi soal pada saat OSN’n berlangsung.

* **SC11.** SC OSN’n diharuskan untuk memasang soal pada kontes OSN’n setiap sebelum hari kompetisi paling lambat 1 jam sebelum hari kompetisi tersebut.

* **SC12.** SC OSN’n diharuskan untuk mengembalikan seluruh ide soal yang tidak digunakan untuk OSN’n kepada penulisnya paling lambat satu minggu setelah OSN’n.
    * **SC12.1.** SC OSN’n disarankan untuk memberitahukan seluruh penulis yang soalnya digunakan untuk OSN’n.

* **SC13.** SC OSN’n diharuskan untuk mengumumkan pembahasan soal OSN’n pada situs resmi OSN’n paling lambat satu bulan setelah OSN’n.

* **SC14.** SC OSN’n diharuskan untuk mengumumkan kelengkapan soal OSN’n pada situs resmi OSN’n paling lambat satu bulan setelah OSN’n.

* **SC15.** SC OSN’n diharuskan untuk mengumumkan hasil akhir OSN’n pada situs resmi OSN’n paling lambat satu bulan setelah OSN’n.
