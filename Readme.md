🏥 Medical Cost Personal Dataset Analizi

📊 Veri Seti Genel Bakış

- Bu veri seti, bireylerin kişisel özellikleri ve yaşam tarzı seçimlerine bağlı olarak sağlık harcamalarını içermektedir. Yaş, cinsiyet, vücut kitle indeksi (BMI), çocuk sayısı, sigara içme durumu, yaşanılan bölge ve sağlık harcamaları gibi çeşitli özellikler yer almaktadır. Bu veri seti, sağlık harcamalarına etki eden faktörlerin analiz edilmesi ve bireylerin tıbbi masraflarının genel etkilerinin anlaşılması amacıyla kullanılır.

🔎 Sütunlar:

- yaş: Bireyin yaşı (sayısal).
- cinsiyet: Bireyin cinsiyeti (kategorik: 'erkek', 'kadın').
- bmi: Vücut Kitle İndeksi (sayısal), bireyin vücut ağırlığının boyla olan oranını gösteren değer.
- çocuklar: Sigorta kapsamında olan çocuk ya da bağımlı sayısı (sayısal).
- sigara: Bireyin sigara içip içmediği (kategorik: 'evet', 'hayır').
- bölge: Bireyin yaşadığı coğrafi bölge (kategorik: 'güneybatı', 'güneydoğu', 'kuzeybatı', 'kuzeydoğu').
- harcamalar: Bireyin sağlık harcamaları (sayısal, USD cinsinden).

- 🎯 Amaç

- Bu analizdeki ana hedef, sağlık harcamalarına etki eden temel faktörleri keşfetmektir. Analiz amacıyla şunlar yapılacaktır:

- Yaş, cinsiyet, bmi ve diğer faktörlerin harcamalar ile ilişkisi keşfedilecektir.
- Bölge ve sigara içme durumuna göre sağlık harcamalarıyla ilgili eğilimler belirlenecektir.
- Çocuk sayısı ve bmi’nin sağlık harcamalarına etkisi anlaşılacaktır.

- 🛠️ Yöntem

- Veri Temizleme: Eksik değerler, aykırı değerler ve format hataları giderilecektir.
- Tanımlayıcı İstatistikler: İlişkilerin daha iyi anlaşılması için özet istatistikler ve görselleştirmeler yapılacaktır.
- Korelasyon Analizi: Sağlık harcamaları ile hangi faktörlerin güçlü korelasyona sahip olduğu belirlenecektir.

- 📚 Kullanılan Araçlar ve Kütüphaneler

- Python: Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook: Analiz ve görselleştirme

## 🛠 Tools & Technologies
| Pandas | Numpy | Matplotlib | Seaborn |
|-------|--------|------------|---------|
| <p align="center"><a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" title="Pandas" width="45" height="45"/> </a></p> |<p align="center"><img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="Numpy" alt="Numpy" width="65" height="65"/></p> | <img src="https://github.com/devicons/devicon/blob/master/icons/matplotlib/matplotlib-original.svg" alt="mpl" title="Matplotlib" width="40" height="40"/></p> | <p align="center"><a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" title="Seaborn" width="45" height="45"/> </a></p>

                            - ENG - 

🏥 Medical Cost Personal Dataset Analysis

📊 Dataset Overview

- This dataset includes health expenditures of individuals depending on their personal characteristics and lifestyle choices. Various characteristics such as age, gender, body mass index (BMI), number of children, smoking status, region of residence and health expenditures are included. This dataset is used to analyze the factors affecting health expenditures and to understand the general effects of individuals' medical expenses.

🔎 Columns:

- age: The age of the individual (numerical).
- gender: The gender of the individual (categorical: 'male', 'female').
- bmi: Body Mass Index (numerical), the value indicating the ratio of the individual's body weight to height.
- children: The number of children or dependents covered by insurance (numerical).
- cigarettes: Whether the individual smokes (categorical: 'yes', 'no').
- region: The geographical region where the individual lives (categorical: 'southwest', 'southeast', 'northwest', 'northeast').

- expenditures: The individual's healthcare expenditures (numerical, in USD).

- 🎯 Purpose

- The main goal of this analysis is to explore the main factors affecting healthcare expenditures. For the purpose of the analysis, the following will be done:

- The relationship between age, gender, bmi and other factors and expenditures will be explored.
- Trends in healthcare expenditures by region and smoking status will be determined.
- The effect of the number of children and bmi on healthcare expenditures will be understood.

- 🛠️ Method

- Data Cleaning: Missing values, outliers and formatting errors will be removed.
- Descriptive Statistics: Summary statistics and visualizations will be made to better understand the relationships.
- Correlation Analysis: Which factors have a strong correlation with healthcare expenditures will be determined.

- 📚 Tools and Libraries Used

- Python: Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook: Analysis and visualization
