# TF2-ANN-Regression-Interpolation-Ekstrapolation-
TF2 ANN Regression (Interpolation, Ekstrapolation)

Tujuan dari tulisan ini adalah untuk mengetahui nilai yang kosong atau tidak ada di dalam nilai range yang sudah dibuat

Langkah - langkah penggunaan dan keterangan:

1. Import library tensorflow dan muat data publik mnist serta bagi menjadi data train dan data test
2. Buat model

![image](https://user-images.githubusercontent.com/87703066/180631570-78b8fdec-502a-436d-a36c-a47043d44423.png)

3. Visualisasi data yang sudah dibuat menggunakan fungsi tadi

![image](https://user-images.githubusercontent.com/87703066/180631666-627c69e6-c313-4102-8992-9e04b20c3df6.png)

4. Membuat Model 
- ReLu

Aktivasi ReLU (Rectified Linear Unit) merupakan lapisan aktivasi pada model CNN yang mengaplikasikan fungsi f(x)=max(0,x) yang berarti fungsi ini melakukan thresholding dengan nilai nol terhadap nilai piksel pada input citra. Aktivasi ini membuat seluruh nilai piksel yang bernilai kurang dari nol pada suatu citra akan dijadikan 0.

![image](https://user-images.githubusercontent.com/87703066/180631601-2aa1fd62-762a-4407-9a24-815f23f22a3d.png)

(source : Ilahiyah dan Nilogiri 2018)

5. Training data dengan optimizer adam

- adam

Adam adalah algoritma optimasi pengganti untuk stochastic gradient descent untuk training model deep learning. Adam menggabungkan sifat-sifat terbaik dari algoritma AdaGrad dan RMSProp untuk memberikan optimization algorithm yang dapat menangani sparse gradients pada noisy problem. (https://lms.onnocenter.or.id)

![image](https://user-images.githubusercontent.com/87703066/180631640-77123ccf-34ef-4903-9619-56ede3d314b1.png)

6. Visualisasi training loss

7. Menggunakan model untuk interpolasi dan ekstrapolasi

Interpolasi merupakan teknik mencari harga suatu fungsi pada suatu titik di antara 2 titik yang nilai fungsi pada ke-2 titik tersebut sudah diketahui

![image](https://user-images.githubusercontent.com/87703066/180631662-2a81f21f-a8d6-493a-95d0-5cc95215b274.png)

Ekstrapolasi adalah perluasan data di luar data yang tersedia, tetapi tetap mengikuti pola kecenderungan data yang tersedia itu

![image](https://user-images.githubusercontent.com/87703066/180631708-89dff53b-3aa2-4698-9d86-5b892a850129.png)


