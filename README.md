# Latihan-SKLearn-Train-Test-Split

Tahapan Latihan
Untuk latihan membagi dataset terdiri dari tahapan-tahapan sebagai berikut:

Persiapkan dataset ke dalam Notebook.

- Impor library SKLearn.

- Buat variabel untuk menampung data training dan data testing.

- Panggil fungsi train_test_split().

**Codelab**

Pada Google Colab, import library yang dibutuhkan.

![4](https://github.com/brnabidin/Latihan-SKLearn-Train-Test-Split/assets/67081096/1a5c8e31-1550-4762-8216-e2f3a1107091)

Library sklearn menyediakan **dataset iris** yakni sebuah dataset yang umum digunakan untuk masalah klasifikasi. Dataset ini memiliki jumlah 150 sampel. Untuk mendapatkan dataset, kita bisa menulis kode berikut pada cell baru.

![5](https://github.com/brnabidin/Latihan-SKLearn-Train-Test-Split/assets/67081096/9bf98982-31f5-48f7-a74b-316621bd1bdb)

Dataset iris dari library sklearn belum dapat langsung dipakai oleh sebuah model ML. Sesuai dengan yang telah dibahas pada modul terdahulu, kita harus memisahkan antara atribut dan label pada dataset.

![6](https://github.com/brnabidin/Latihan-SKLearn-Train-Test-Split/assets/67081096/401f5592-eab2-441c-bef9-468a48814d23)

Untuk membuat train set dan test set kita tinggal memanggil fungsi train_test_split. Train_test_split memiliki parameter x yaitu atribut dari dataset, y yaitu target dari dataset, dan test_size yaitu persentase test set dari dataset utuh. Train_test_split mengembalikan 4 nilai yaitu, atribut dari train set, atribut dari test set, target dari train set, dan target dari test set.

![7](https://github.com/brnabidin/Latihan-SKLearn-Train-Test-Split/assets/67081096/7c24625b-a4ab-4b79-bf63-dd505a38350c)

Ketika kita print panjang dari x_test, kita bisa melihat bahwa panjang dari atribut test set adalah 30 sampel, sesuai dengan parameter yang kita masukkan pada fungsi train_test_split yaitu 0.2 atau 20% dari 150 sampel. Kode untuk print panjang dari x_test seperti di bawah ini.

![8](https://github.com/brnabidin/Latihan-SKLearn-Train-Test-Split/assets/67081096/0db76b86-0f64-472c-9962-da1c2239bb1e)


![9](https://github.com/brnabidin/Latihan-SKLearn-Train-Test-Split/assets/67081096/3528eedf-128d-4825-b621-d2c2d31dce2a)

Pada tahap ini dataset kita telah siap dipakai untuk pelatihan model machine learning.
