# Дашборд предсказания стоимости недвижимости (King County House Price Predictor)

Интерактивный веб-дашборд, предназначенный для разведочного анализа данных (EDA) и инференса ансамбля моделей машинного обучения для оценки рыночной стоимости жилья.

* **Деплой приложения:** (https://appmlrgr-xqncudgp3r35bk9hvgk6ud.streamlit.app/)

* **Инфраструктура:** Python, Streamlit;
* **Анализ данных и визуализация:** Pandas, NumPy, Seaborn, Matplotlib;
* **Машинное обучение (Scikit-learn):** Полиномиальная регрессия, Random Forest, Bagging & Stacking Regressors;
* **Градиентный бустинг:** LightGBM, Gradient Boosting;
* **Глубокое обучение:** TensorFlow / Keras .


| Идентификатор | Архитектура модели | Ожидаемый $R^2$ | Формат сериализации |
| :--- | :--- | :--- | :--- |
| **ML1** | Полиномиальная регрессия | 0.81 | `.pkl` |
| **ML2** | Gradient Boosting Regressor | 0.89 | `.pkl` |
| **ML3** | LightGBM Regressor | 0.90 | `.pkl` |
| **ML4** | Bagging Regressor | 0.86 | `.pkl` |
| **ML5** | Stacking Regressor | 0.91 | `.pkl` |
| **ML6** | Глубокая нейронная сеть (FCNN) | 0.87 | `.keras` |

