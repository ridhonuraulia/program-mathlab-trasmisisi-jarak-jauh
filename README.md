# program-mathlab-trasmisisi-jarak-jauh
pengguanan program mathalab dalam implemeterasi trasmisi jarak jauh.dalam progrma ini saya memecahakan sub program ayng ada untuk mudah di kresasikan

## **program sub mathalab ini**
program ini terdiri dari 8 program yaitu
1.main_transmisi.m: Script utama tempat Anda melakukan deklarasi parameter sistem tenaga listrik (pembangkit, trafo, saluran, dan beban) serta menghitung efisiensi daya keseluruhan.
2.ac_source.m: Modul pembangkit tegangan AC sinus sesaat.
3.transformer_step_up.m & transformer_step_down.m: Modul simulasi trafo penaik dan penurun tegangan ideal.
4.transmisi_line.m: Modul kawat transmisi yang menghitung jatuh tegangan induktif-resistif sesaat (
<img width="195" height="40" alt="Screenshot 2026-08-08 152152" src="https://github.com/user-attachments/assets/da5c77b4-b731-4b7e-b6a8-621a5c7c0f9d" /> ) serta rugi daya aktif kawat.
5.load_system.m: Modul simulasi beban konsumen R-L.
6.calculate_rms.m: Fungsi khusus yang menghitung nilai RMS secara numerik menggunakan integrasi Aturan Trapesium (trapz) selama satu periode gelombang penuh [20.5, 540].
7.plot_scope.m: Modul visualisasi grafik hitam gelap menyerupai layar Oscilloscope Scope fisik.

**## PENGGUNAAN SOFWARE**
saya saat test ini menggunakan sofware mathlab R2024b

# tujuan
tujaun dari program ini hanya semata-mata untuk memeberikan implementasi pengguannaan mathlab dalam analisis sitem tenaga listrik.juga disini saya masih belajar,inilah hasil simulasi saya trimakasih

# cara pengguanaan
kalian tinggal dowlaod filw ini dan langsung drag ke file mathlabnya.lanjtu setalh itu kalain tinggal jalankan file main_transmisi.m 
kamu juga bisa ganti varibel yang ada diddlam program ini
