# Term_Deposit_Telemarketing
## Final Project Data Science Rakamin Academy. <br>

### Problem <br> 
Deposito berjangka merupakan salah satu sumber pendapatan utama bagi Bank Unity. Untuk meningkatkan minat nasabah terhadap deposito berjangka, Bank Unity berencana  meningkatkan kampanye pemasaran khusus kepada nasabah melalui telemarketing. Conversion Rate nasabah yang setuju mengikuti deposito berjangka saat ini belum optimal, yaitu sebesar 11.6%. <br>

### Objective : 
1. Mengembangkan model machine learning untuk memprediksi pelanggan yang potensial berlangganan deposito berjangka.
2. Mengidentifikasi faktor kunci yang memengaruhi keputusan nasabah untuk berpartisipasi dalam deposito berjangka.
3. Memberikan rekomendasi untuk meningkatkan dan mengembangkan segmentasi pasar produk deposito berjangka.

### Proses : 
1. Data Collecting.
2. Exploratory Data Analyst.
3. Data Preprocessing.
4. Machine Learning Model.
5. Simulasi Modeling.
6. Rekomendasi Business.

### Machine Learning Model
Project ini menggunakan data binary, sehingga kami menggunakan modeling dengan metode kalsifikasi dengan fokus matrix rou_auc. Kami menggunakan menggunakan 5 Modeling untuk project ini, yaitu : 
1. Decision Tree
2. Random Forest
3. Logistic Regression
4. XGBoost Classifier
5. AdaBosst Classifier 

Setelah melakukan 5 model, kami memilih AdaBoost Classifier sebagai model terbaik untuk project ini. berikut hasil dari model ini : <br>
| Model | Akurasi | Presisi | Recall | Rou_Auc train | Rou_Auc Test | Cross Value | Cross Value|
|----------------------|---------|---------| ----------| ---------| ----------| ----------| ------------|
| Before Tuning   | 0.88 | 0.89  | 0.88 | 0.95 | 0.88 | 0.66 | 0.62 |
| AdaBoost Classifier  | 0.88 | 0.86  | 0.89 | 0.94 | 0.89 | 0.66 | 0.61 |

### Simulasi Model

Jumlah Nasabah Sebelum Model :  1753 <br>
Conversion Rate Sebelum Model :  11.70617696160267 <br>

Jumlah Nasabah Setelah model:  3534 <br>
Conversion Rate Setelah Model :  23.599332220367277

