<h1 align="center">
  Simulation of Two-Dimensional MoS<sub>2</sub> for Gas Sensing Applications
</h1>

![Status](https://img.shields.io/badge/Status-Completed-success)
![Method](https://img.shields.io/badge/Method-DFT)
![Engine](https://img.shields.io/badge/Engine-Quantum_ESPRESSO-orange)

> *Laporan Akhir Kerja Praktik (Magang) MBKM Mandiri*
>  *Lokasi:* Pusat Riset Fisika Kuantum, Badan Riset dan Inovasi Nasional (BRIN)
>  *Periode:* 12 Januari 2026 – 12 Februari 2026

---

##  Ringkasan Proyek
Repositori ini mendokumentasikan riset komputasi mengenai potensi material dua dimensi *Molybdenum Disulfide ($MoS_2$)* sebagai sensor gas generasi baru. Melalui pendekatan First-Principles (DFT), proyek ini menganalisis interaksi atomik antara permukaan $MoS_2$ dengan berbagai molekul gas atmosfer dan polutan.

*Fokus Gas Target:*
Simulasi mencakup enam molekul uji: $NO_2$, $NO$, $O_2$, $H_2O$, $H_2$, dan $CO$.

###  Tujuan Riset
Menjawab tantangan deteksi gas beracun dengan mengevaluasi *selektivitas* (kemampuan membedakan gas) dan *sensitivitas* (respon elektronik) dari $MoS_2$, khususnya terhadap gas berbahaya Nitrogen Dioksida ($NO_2$).

---

##  Metodologi & Alur Kerja
Simulasi dijalankan pada klaster High Performance Computing (HPC) BRIN dengan tahapan sebagai berikut:

1.  *Pemodelan Sistem ($Modeling$):*
    Konstruksi supercell $4\times4$ monolayer $MoS_2$ (total 48 atom) dengan penambahan ruang vakum 20 Å untuk mengisolasi lapisan 2D.
2.  *Optimasi Geometri ($Relaxation$):*
    Pencarian konfigurasi adsorpsi paling stabil pada situs Hollow, Top-Mo, Top-S, dan Bridge.
3.  *Analisis Energi ($Energetics$):*
    Perhitungan Energi Adsorpsi ($E_{ads}$) untuk menentukan jenis interaksi (Fisisorpsi vs Kemisorpsi).
4.  *Struktur Elektronik ($Electronic Properties$):*
    Analisis perubahan Density of States (DOS) dan Band Structure untuk mendeteksi impurity states di celah pita energi.

---

##  Temuan Kunci (Key Findings)
> Material $MoS_2$ terbukti memiliki *selektivitas tinggi terhadap $NO$, ditandai dengan energi adsorpsi yang signifikan dan munculnya *state elektronik baru di area band gap, berbeda dengan respon lemah terhadap gas lain seperti $CO$ atau $H_2$.

---

##  Stack Teknologi
| Kategori | Tools / Software |
| :--- | :--- |
| *Metode Komputasi* | Density Functional Theory (DFT) |
| *Simulation Engine* | Quantum ESPRESSO |
| *Visualisasi Struktur* | XCrySDen |
| *Sistem Operasi* | Linux Debian (Dual Boot) & WSL |
| *Infrastruktur* | HPC Cluster (Slurm Workload Manager) |

---

##  Dokumen Hasil Riset
Berikut adalah luaran utama dari kegiatan magang ini:

*  *[Laporan_Magang_BRIN_Shafira.pdf](Laporan_Magang_BRIN_Shafira.pdf)*
    Dokumen teknis lengkap mencakup teori dasar DFT, detail parameter simulasi, data mentah, hingga analisis mendalam.
*  *[Presentasi_Komputasi_2D_Nanosensor.pdf](Presentasi_Komputasi_2D_Nanosensor.pdf)*
    Salindia presentasi akhir yang memvisualisasikan grafik perbandingan DOS dan kesimpulan performa sensor.

---

## Penulis
*Shafira Zaujatina Nasution* (NIM: 101042300006)
Program Studi Teknik Fisika
*Telkom University*
