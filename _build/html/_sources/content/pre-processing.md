# Pre-Processing

erdasarkan eksplorasi data yang sudah dilakukan menggunakan 3 model deteksi anomaly berbeda yaitu `abod`, `knn`, dan `lof`. Masing-masing model memprediksi 8 buah data anomali. Pada tahap pre-processing, data tersebut perlu dibersihkan dari dataset agar hasil prediksi model nantinya bisa lebih akurat. Untuk menghilangkan data anomaly, kita perlu memfilter data anomaly tersebut sebagai pengecualian untuk digunakan sebagai dataset. Berikut adalah script python yang digunakan untuk memfilter data anomaly:

```
import pandas as pd
from pycaret.anomaly import *

data = dataset.copy()
abod_data = setup(data, session_id=123)
abod = create_model('lof')
abod_predictions = assign_model(abod)

data_anomaly = abod_predictions[abod_predictions['Anomaly'] == 1]
data_anomaly

normal_data = abod_predictions[abod_predictions['Anomaly'] == 0]
```

varibel `normal_data` digunakan untuk menyimpan data yang sudah bersih dari.
