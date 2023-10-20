# **MACHINE LEARNING PREDICT:**
# **E-COMMERCE CUSTOMER CHURN**
**by : Nadya Sarilla Agatha**
---
### **A. Latar Belakang**
Dalam era bisnis modern, retensi pelanggan adalah faktor krusial yang memengaruhi kelangsungan suatu perusahaan dalam persaingan yang semakin ketat. Profitabilitas suatu perusahaan dipengaruhi oleh berbagai faktor, namun retensi pelanggan memiliki peran utama. Kemampuan perusahaan dalam mempertahankan dan memperluas basis pelanggan yang setia merupakan tujuan utama, dan pengembangan metode pembelajaran yang dapat membantu mencegah dan mengurangi pelanggan yang beralih (customer churn) memiliki nilai yang sangat penting.

### **B. Pernyataan Masalah**
Perusahaan e-commerce ingin mengetahui customer churn atau pelanggan yang tidak menggunakan jasa perusahaan lagi, sehingga dapat menimbulkan kerugian bagi perusahaan. Oleh karena itu, perusahaan perlu melakukan prediksi terhadap customer, agar sebelum costumer benar-benar churn, perusahaan dapat menjangkau customer tersebut dengan memberikan layanan yang lebih baik, seperti memberikan promo yang menarik. Namun, sebaiknya promo diberikan kepada orang yang tepat. Dengan demikian, perusahaan dapat menghindari kerugian yang akan terjadi akibat kehilangan pelanggan.

### **C. Tujuan**
Berdasarkan permasalahan diatas, perusahaan perusahaan ingin memiliki kemampuan untuk memprediksi kemungkinan seorang pelanggan akan berhenti menggunakan berlanggan atau tidak, sehingga dapat memfokuskan upaya-upaya retensi pada pelanggan yang terindikasi untuk churn.

### **D. Pendekatan Analitik**
Pendekatan analitik yang dilakukan berupa pembuatan, evaluasi, dan implementasi model machine learning klasifikasi yang dapat memprediksi apabila pelanggan akan *churn* atau tidak berdasarkan riwayat data sebelumnya. 

### **E. Metrik Evaluasi**
Target:   
- 0 (Negatif) : Pelanggan tidak *churn*  
- 1 (Positif) : Pelanggan *churn*

Dalam melakukan prediksi, kesalahan dapat terjadi, yaitu:
- **Type 1 Error** : False Positive
    - Konsekuensi : Perusahaan mengeluarkan biaya pada pelanggan yang kurang tepat.
- **Type 2 Error** : False Negative
    - Konsekuensi : Hilangnya pelanggan loyal

Model yang telah dibuat harus mampu mengurangi kerugian perusahaan akibat kehilangan pelanggan atau mengurangi kesalahan prediksi False Negatif. Namun, perlu juga dijaga agar perusahaan tidak menghabiskan biaya yang tidak diperlukan untuk memberikan promosi kepada pelanggan yang sebenarnya tidak berisiko (False Positive). Oleh karena itu, kita menggunakan metrik utama yaitu **F2 score**.
