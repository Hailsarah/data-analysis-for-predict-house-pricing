# Predict House Pricing in Tangerang
Bertujuan untuk membuat model prediksi harga rumah di Tangerang berdasarkan luas tanah, luas bangunan serta kedekatan lokasi dengan pusat kota.

## Dataset yang digunakan dengan format .txt:

https://storage.googleapis.com/dqlab-dataset/harga_rumah.txt

## Transformasi Data

Transformasi data dilakukan dengan mengurangi setiap nilai atribut dalam data dengan nilai atribut minimum dan membaginya dengan nilai atribut maksimum yang dikurangi dengan nilai atribut minimum, seperti ini:

- Untuk atribut tanah, nilai maksimum adalah 150 dan nilai minimum adalah 70.
- Saat nilai atribut tanah 100, proses transformasi akan mengubah nilai atribut ini menjadi 0,375
- nilai_transformasi = 100 - 70 / (150 - 70) 
- Variable yang digunakan yaitu:
data = {'tanah': 110, 'bangunan': 80, 'jarak_ke_pusat': 35}
 
