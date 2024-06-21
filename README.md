# Predict-IC50-value-from-smiles-structure

## Deployment:
Proyek ini dideploy sebagai aplikasi web prediksi menggunakan microframework Flask. Flask mendukung penggunaan bahasa pemrograman HTML dan CSS untuk kebutuhan front end, sementara bagian backend menggunakan bahasa pemrograman Python.

## Struktur projek:
- Folder (folder utama)
    - model (subfolder untuk model machine learning berupa file pkl)
        - project4.pkl
          
    - static (subfolder untuk file css/styling front end)
        - style.css
          
    - templates (subfolder untuk file html/front end)
        - index.html
          
    - app.py (file backend untuk inisialisasi flask, model dan memproses inputan pengguna yang kemudian hasil prediksi akan dikirim ke front end)

