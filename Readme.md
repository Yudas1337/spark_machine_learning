# Praktikum Minggu 14

Nama : Yudas Malabi

Kelas : TI 3C / 20

NIM : 2041720054

1. Praktikum Slide 30 - Movie Lens Recommendation

    - mount google drive untuk akses dataset / file, kemudian import pyspark, dan buat SparkSession baru.

        ![](img/slide_30/1.png)

    - Selanjutnya, import library pyspark.ml, dan pyspark.sql. Kemudian read file <code>ratings.dat</code> pada google drive. kemudian lakukan RDD mapping.

        ![](img/slide_30/2.png)

     - Membuat model rekomendasi menggunakan ALS pada training data yang telah dibuat sebelumnya.

        ![](img/slide_30/3.png)

    - output :

        ![](img/slide_30/output.png)

2. Praktikum Slide 48

    - Load textFile <code>Ratings.dat</code> kemudian parallelize variable myData dan mapping file yg telah di load. Kemudian train totalRatings menggunakan metode ALS untuk mendapatkan rekomendasi produk.

        ![](img/slide_48/1.png)

3. Praktikum Slide 49

    - Menampilkan statistik summary mulai dari rata", varian, dll dari vectorRdd rating yang telah di proses sebelumnya 

        ![](img/slide_49/1.png)

4. Praktikum Slide 52

    - Import library ml KMeans dan Vectors. kemudian load kmeans_data.txt . Selanjutnya mapping dataset dan konversi menjadi dari RDD menjadi DataFrame

    - masukkan variable parsedData pada method kmeans.fit 

        ![](img/slide_52/1.png)


    - Menampilkan summary dari training cost dan prediksi cluster tiap data. 

        ![](img/slide_52/2.png)

    - output : 

        ![](img/slide_52/output.png)


4. Praktikum Slide 53 - 54

    - Import library Kmeans, Numpy, dan Math. Kemudian membaca file kmeans_data.txt setelah itu melakukan mapping dengan patokan tiap data dipisahkan menggunakan delimiter spasi .

    - kemudian training data dengan Kmeans. dengan jumlah kluster 2 dan maksimal iterasi 10

        ![](img/slide_53/1.png)

    - Menghitung WSSE dari parsedData kemudian melakukan saving model pada folder <code>ml_path_yudas</code>.

        ![](img/slide_53/2.png)

    - Jika dilihat pada sidebar, maka akan terbentuk file clusters yang telah disimpan pada folder <code>ml_path_yudas</code>

        ![](img/slide_53/output.png)