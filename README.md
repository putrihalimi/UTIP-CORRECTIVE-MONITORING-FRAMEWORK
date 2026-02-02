# UTIP-CORRECTIVE-MONITORING-FRAMEWORK
(Intern-Level | Data Analytics Support | Link PPT Portofolio: (https://www.canva.com/design/DAHAJJY1zSc/IRngIgO79rCj-mxoYd_FqA/edit?utm_content=DAHAJJY1zSc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

📌 Objective
> Membangun workflow monitoring UTIP corrective action untuk membantu unit internal dalam:
1. tracking progres temuan
2. identifikasi flagging & non-flagging
3. penyusunan laporan berkala berbasis data

🧠 1️⃣ Problem Understanding
Dalam proses audit internal (UTIP), sering ditemukan:
1. corrective action yang terlambat
2. status yang tidak ter-update
3. kurangnya ringkasan progres untuk manajemen
➡️ Dibutuhkan sistem monitoring sederhana berbasis data untuk memastikan corrective action berjalan sesuai target.

📥 2️⃣ Data Collection
Sumber data (simulasi):
1. File Excel / Google Sheets
2. Laporan temuan UTIP
3. Update status dari PIC unit kerja
Struktur data utama:
1. Unit Kerja
2. Kode Temuan
3. Deskripsi Temuan
4. Risiko (High / Medium / Low)
5. Corrective Action
6. PIC
7. Target Date
8. Status

🧹 3️⃣ Data Preparation & Cleaning
Langkah-langkah:
1. Standarisasi format tanggal
2. Validasi status (Not Started / On Progress / Done / Overdue)
3. Cek missing value pada PIC & target date
4. Konsistensi penamaan unit kerja
Tools:
1. Microsoft Excel
2. Google Sheets

🚩 4️⃣ Flagging Logic
> Menerapkan aturan sederhana untuk flagging:
Flagging jika:
1. Status = Overdue
2. Risiko = High & Status ≠ Done
Non-Flagging jika:
1. Status = Done
2. On Progress & masih dalam target waktu
➡️ Hasil flagging digunakan untuk prioritas monitoring.

📊 5️⃣ Data Processing & Analysis
Analisis yang dilakukan:
1. Total temuan UTIP
2. Jumlah temuan flagging vs non-flagging
3. Distribusi status corrective action
4. Unit dengan temuan overdue terbanyak
Teknik:
1. Pivot Table
2. COUNTIF / SUMIF
3. Filter & conditional formatting
4. Data Entry
5. Data Validation

📈 6️⃣ Reporting & Visualization
Output laporan:
1. Tabel ringkasan progres
2. Grafik status corrective action
3. Persentase penyelesaian
Laporan digunakan untuk:
1. Monitoring mingguan
2. Bahan koordinasi lintas unit
3. Update ke stakeholder internal

🔁 7️⃣ Monitoring & Update Cycle
Workflow bersifat iteratif:
1. Update status dari unit
2. Refresh data & flagging
3. Generate summary report
4. Identifikasi follow-up
➡️ Dilakukan secara mingguan / berkala

🛠️ Tools Used
Microsoft Excel (Pivot Table, Formula, Visualization)
Google Sheets
GitHub (Documentation & Versioning)

🎯 Key Learning Outcomes
1. Memahami proses UTIP corrective action
2. Mengelola data monitoring berbasis status
3. Melakukan flagging untuk prioritas risiko
4. Menyusun laporan analitis sederhana

Nama: Salsabila Putri Halimi | Data Science/Analyst | Universitas Terbuka Bogor
