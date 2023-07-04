# Predict Clicked Ads Customer Classification by Using Machine Learning
Sebuah perusahaan di Indonesia ingin mengetahui efektifitas sebuah iklan yang mereka tayangkan, hal ini penting bagi perusahaan agar dapat mengetahui seberapa besar ketercapainnya iklan yang dipasarkan sehingga dapat menarik customers untuk melihat iklan. <br/>
Dengan mengolah data historical advertisement serta menemukan insight serta pola yang terjadi, maka dapat membantu perusahaan dalam menentukan target marketing. Fokus case ini adalah membuat model machine learning classification yang berfungsi menentukan target customers yang tepat,yang kemungkinan akan mengklik iklan yang ditampilkan oleh tim marketing.  

### Dataset Overview
<hr>
Data terdiri dari 1000 baris dengan 10 fitur dengan 1 fitur target yaitu clicked on ad. <br/> 
Terminologi tiap fitur: <br/>  
- Daily time spent on site: waktu customer browsing dalam sehari <br/>
- Age: umur  <br/>
- Area income: penghasilan  <br/>
- Daily internet usage: kuota internet yang digunakan dalam sehari  <br/>
- Male: jenis kelamin  <br/>
- Timestamp: waktu browsing terakhir yang tercatat  <br/>
- Clicked on ad: klik ads atau tidak <br/>  
- City: kota  <br/>
- Province: provinsi  <br/>
- Category: kategori yang dilihat oleh customer  <br/>

## Exploratory Data Analysis<br/>
1. Statistical Descriptive <br/>
2. Univariate Analysis <br/>
3. Bivariate Analysis <br/>

## Data Preprocessing and Modelling</br>
1. Feature Engineering: Menentukan target dan merubah kolom timestamp mnejadi dayofweek
2. Hypotesis Testing: ANOVA dan chi square
3. Split test dan train
4. Pipeline: Simpleimputer untuk mengisi missing value dan algoritma machine learning

## Result
- Mencoba menggunakan 3 algoritma yaitu: Random Forest, XGBoost, dan Gradient Boosting.
- Scoring: Accuracy karena target balance, dan Precision untuk meminimalisir false positive
- Hasil: Algoritma terbaik XGBoost dengan nilai Accuracy 0.95, Precision 0.96
- Most Important Feature: Daily internet usage

Hasil simulasi bisnis dengan menggunakan CLICK PER IMPRESSION sebagai acuan menunjukkan adanya potensi keuntungan hingga **44%**
