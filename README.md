# Data BMKG

Snapshot prakiraan cuaca publik BMKG untuk 35 kabupaten/kota di Jawa Tengah,
dikumpulkan otomatis setiap 3 jam oleh workflow `collect-bmkg.yml` di branch `main`.

- Struktur: `bmkg/YYYY/MM/DD/HHMM.csv.gz` (waktu pengambilan, UTC)
- Sumber: BMKG (Badan Meteorologi, Klimatologi, dan Geofisika), https://data.bmkg.go.id
- Dipakai sebagai pembanding dalam penelitian; bukan data observasi.
