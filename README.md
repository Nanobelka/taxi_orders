# [Прогнозирование количества заказов такси](https://nbviewer.jupyter.org/github/Nanobelka/taxi_orders/blob/main/taxi_orders.ipynb)
Project for [Yandex.Praktikum](https://github.com/Nanobelka/Yandex_Praktikum)

### **Входные данные**

Исторические данные о заказах такси в аэропортах.

### **Цель**

Чтобы привлекать больше водителей в период пиковой нагрузки, необходимо построить модель для прогнозирования количества заказов такси на следующий час.

### **Задачи:**  

- загрузить данные и выполнить их ресемплирование по одному часу;
- проанализировать данные;
- подготовить данные для обучения и тестирования модели, под тестовую выборку выделить 10% данных;
- обучить несколько моделей;
- выбрать лучшую модель;
- проанализировать выбранную модель, значение метрики RMSE на тестовой выборке должно быть менее 48.

### Примеры визуализаций

EDA
![hourly_orders)](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_1_hourly_orders.png)
![trend_seasonal](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_2_trend_seasonal.png)
![daily_seasonal](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_3_daily_seasonal.png)
![difference_hourly](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_4a_difference_hourly.png)
![difference_daily](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_4b_difference_daily.png)
![difference_weekly](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_4c_difference_weekly.png)
![autocorrelation](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_5_autocorrelation.png)
![autocorrelation_partly](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_6_autocorrelation_partly.png)

Анализ модели
![permutation_importance](https://github.com/Nanobelka/taxi_orders/blob/main/images/example_7_permutation_importance.png)
