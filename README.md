# Audit Metrologi & Stabilitas Sensor Suhu (AWS, AWOS, SYNOP) 2018–2026
### Stasiun Meteorologi Kelas III Rahadi Oesman Ketapang (WMO ID: 96685)
Badan Meteorologi, Klimatologi, dan Geofisika (BMKG)

🌐 **Live Web Report (GitHub Pages):** [https://ariffu.github.io/awos-ketapang-audit/](https://ariffu.github.io/awos-ketapang-audit/)

---

## 📌 Ringkasan Eksekutif
Repositori ini memuat laporan interaktif dan hasil analisis audit metrologi komprehensif terhadap kinerja sensor suhu udara otomatis (AWS Sutron), sensor cuaca bandara (AWOS Campbell Scientific), dan pengamatan konvensional (SYNOP termometer gelas bola kering) selama periode **8 tahun (2018–2025)** serta verifikasi kalibrasi komparasi lapangan (*on-site standard*) tahun **2023, 2024, 2025, dan 2026**.

### Temuan Utama:
1. **Laju Degradasi Fisik (*Sensor Drift*):** Mendekati $0.00^\circ\text{C}/\text{tahun}$. Median perbedaan suhu AWOS terhadap AWS berada sangat stabil pada $+0.16^\circ\text{C}$ hingga $+0.19^\circ\text{C}$ sepanjang 66.309 jam observasi.
2. **Kepatuhan WMO No. 8:** Seluruh deviasi sensor otomatis berada jauh di dalam batas toleransi operasional WMO ($\pm 0.3^\circ\text{C}$).
3. **Verifikasi Adjustment:** Tidak ditemukan modifikasi parameter *offset* internal pada *data logger* sejak Juli 2019. Kestabilan ini merupakan sifat alami material resistor kawat Platinum (Pt100 DIN IEC 60751 Class A).
4. **Rekomendasi Operasional:** Efisiensi anggaran perjalanan dinas dapat dilakukan dengan mengalihkan kalibrasi komparasi tahunan menjadi **Condition-Based Maintenance (CBM)** berbasis *automated cross-system alerting*.

---

## 📊 Struktur Repositori
- `index.html` : Halaman dashboard web interaktif lengkap dengan ringkasan, tabel data kalibrasi, grafik komparasi, analisis metrologi, dan transkrip tanya-jawab teknis.
- `assets/` : Grafik audit resolusi tinggi:
  - `plot_pemetaan_kalibrasi_standar_aws_awos_synop_2023_2026.png`
  - `plot_audit_boxplot_deviasi_standar_aws_awos_synop.png`
  - `plot_audit_boxplot_degradasi_sensor_2018_2025.png`
  - `plot_karakteristik_peluruhan_drift_aws_awos_tanpa_synop.png`
  - `plot_combined_calibration_verdict.png`

---
© 2018–2026 Stasiun Meteorologi Kelas III Rahadi Oesman Ketapang - BMKG.
