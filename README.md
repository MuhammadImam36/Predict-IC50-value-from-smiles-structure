# Predict-IC50-value-from-smiles-structure

Deployment:
Hasil deployment berupa web prediksi menggunakan microframework flask, dimana flask mendukung bahasa pemrograman HTML untuk keperluan front end, dan bagian backend menggunakan bahasa pemrograman python.

Struktur projek:
- Folder (folder utama)
    - model (subfolder untuk model machine learning berupa file pkl)
        - project4.pkl
          
    - static (subfolder untuk file css/styling front end)
        - style.css
          
    - templates (subfolder untuk file html/front end)
        - index.html
          
    - app.py (file backend untuk inisialisasi flask, model dan memproses inputan pengguna yang kemudian hasil prediksi akan dikirim ke front end)
      
