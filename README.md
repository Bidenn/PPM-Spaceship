# PPM Spaceship Titanic - Kelompok Lima

Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

Help save them and change history!

## Anggota Kelompok

- Azizi Novan Maulana (235150209111003)
- Muhammad Haris Firmansyah (235150209111006)
- Roziqul Abidin (235150209111010)
- Diagne Alya Fidian (235150209111009)
- Nurul Annisa Murnastiti (235150209111008)
- Hana Tiara Fadhilah (235150209111001)

## Komparasi Hasil Evaluasi Sebelum dan Sesudah SMOTE

### Sebelum SMOTE
| Algorithm      | Class | F1-Score | Recall | Precision | Accuracy          |
|----------------|-------|----------|--------|-----------|-------------------|
| SVM            | False | 0.76     | 0.69   | 0.86      | 0.7849338700402531|
| SVM            | True  | 0.80     | 0.89   | 0.73      | 0.7849338700402531|
| Decision Tree  | False | 0.75     | 0.73   | 0.77      | 0.7475560667050029|
| Decision Tree  | True  | 0.76     | 0.78   | 0.74      | 0.7475560667050029|
| Naive Bayes    | False | 0.70     | 0.59   | 0.84      | 0.7625071880391029|
| Naive Bayes    | True  | 0.77     | 0.89   | 0.68      | 0.7625071880391029|
| KNN            | False | 0.75     | 0.73   | 0.77      | 0.7291546866014951|
| KNN            | True  | 0.76     | 0.78   | 0.74      | 0.7291546866014951|
| Random Forest  | False | 0.80     | 0.81   | 0.79      | 0.7906843013225991|
| Random Forest  | True  | 0.79     | 0.78   | 0.80      | 0.7906843013225991|
| CatBoost       | False | 0.70     | 0.59   | 0.84      | 0.74              |
| CatBoost       | True  | 0.77     | 0.89   | 0.68      | 0.74              |


### Sesudah SMOTE
| Algorithm      | Class | F1-Score | Recall | Precision | Accuracy          |
|----------------|-------|----------|--------|-----------|-------------------|
| SVM            | False | 0.78     | 0.71   | 0.85      | 0.7924094307073031|
| SVM            | True  | 0.81     | 0.87   | 0.75      | 0.7924094307073031|
| Decision Tree  | False | 1.00     | 1.00   | 1.00      | 0.7567567567567568|
| Decision Tree  | True  | 1.00     | 1.00   | 1.00      | 0.7567567567567568|
| Naive Bayes    | False | 0.73     | 0.64   | 0.84      | 0.8441633122484187|
| Naive Bayes    | True  | 0.78     | 0.87   | 0.71      | 0.8441633122484187|
| KNN            | False | 0.84     | 0.82   | 0.86      | 0.9976998274870615|
| KNN            | True  | 0.85     | 0.87   | 0.83      | 0.9976998274870615|
| Random Forest  | False | 1.00     | 1.00   | 1.00      | 0.9994249568717654|
| Random Forest  | True  | 1.00     | 1.00   | 1.00      | 0.9994249568717654|
| CatBoost       | False | 0.73     | 0.64   | 0.84      | 0.8493387004025302|
| CatBoost       | True  | 0.78     | 0.87   | 0.71      | 0.8493387004025302|
