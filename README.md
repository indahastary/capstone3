# capstone3

### BACKGROUND

Di pasar terdapat banyak pesaing yang mana berlomba-lomba menawarkan berbagai keuntungan menyebabkan pelanggan mudah beralih dari satu e-commerce ke e-commerce lainnya.

Churn merupakan sebuh business metrics yang sangat penting karena dapat mengindikasikan kemampuan bisnis mempertahankan pelanggan serta mencerminkan kualitas layanan dan manfaat produk bagi pelanggan. Apabila pelanggan merasa tidak nyaman atau menganggap manfaat yang diberikan kurang atau tidak cocok untuk mereka maka otomatis mereka akan berhenti menggunakan produk kita. Bisa dikatakan ini merupakan bentuk feedback customer yang paling jujur.

Semakin tinggi churn rate maka semakin kecil revenue yang akan perusahaan raih di masa mendatang. Babu dan Ananthanarayanan (2014) menyatakan bahwa biaya untuk mendapatkan pelanggan baru jauh lebih besar dibandingkan mempertahankan pelanggan lama dengan jumlah revenue yang sama. Oleh karena itu, akan lebih efektif untuk perusahaan mencegah pelanggan yang sudah ada saat ini melakukan churn. Salah satunya dapat dilakukan Churn Prediction yang bertujuan untuk memprediksi potensi seorang pelanggan untuk churn sebelum pelanggan tersebut benar-benar melakukannya, dengan demikian dapat dilakukan strategi-strategi untuk meminimalisir kemungkinan churn.

Data yang akan diproses adalah data milik sebuah perusahaan E-Commerce. Perusahaan retail online (E-Commerce) ini ingin membuat Model churn prediction yang mampu memisahkan antara pengguna yang akan churn dan tidak churn di masa mendatang. Dengan mengetahui jenis dan pelanggan mana saja yang berpotensi Churn akan sangat membantu perusahaan bergerak lebih cepat, memberikan treatment seperti promosi, diskon, layanan lainnya secara tepat ke pelanggan tersebut.

Tujuan: membuat model yang dapat memisahkan antara pelanggan yang akan churn dan yang tidak


Note:
- Target dalam dataset tidak seimbang.
- Feature dalam dataset terbagi menjadi data numerikal dan kategorikal.
- Setiap baris data merepresentasikan data customer dan transaksinya dalam sebuah platform e-commerce.
<br>

**Attribute Information**

| Attribute | Data Type, Length | Description |
| --- | --- | --- |
| Tenure | Float | Tenure of a customer in the company |
| WarehouseToHome | Float | Distance between the warehouse to the customer’s home |
| NumberOfDeviceRegistered | Integer | Total number of deceives is registered on a particular customer |
| PreferedOrderCat | Object | Preferred order category of a customer in the last month |
| SatisfactionScore | Integer | Satisfactory score of a customer on service |
| MaritalStatus | Object | Marital status of a customer |
| NumberOfAddress | Integer | Total number of added on a particular customer |
| Complain | Integer | Any complaint has been raised in the last month |
| DaySinceLastOrder | Float | Day since last order by customer |
| CashbackAmount | Float | Average cashback in last month |
| Churn | Integer | Churn flag |
