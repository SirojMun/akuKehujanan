# Data Realtime

Diperbarui otomatis tiap jam oleh workflow `predict.yml` di branch `main`.

| File | Isi |
|---|---|
| `latest_predictions.csv` | Prediksi 24 jam terbaru untuk 35 kabupaten/kota |
| `latest_observations.csv` | Data 48 jam terakhir |
| `predictions/YYYY/MM/DD/HH.csv.gz` | Arsip prediksi (waktu terbit, UTC) |
| `observations/YYYY/MM/DD/HH.csv.gz` | Arsip data jam terbit |
| `models/current/` | Model yang sedang dipakai (`config.json`, `model.pt`, `scaler.npz`). Jika kosong, dipakai persistence. |

Sumber data: Open-Meteo (ECMWF IFS), lisensi CC-BY 4.0.
