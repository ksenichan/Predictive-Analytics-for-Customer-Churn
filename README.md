# Прогнозирование оттока клиентов для сервисов, работающих по подписке
Проект по прогнозированию оттока клиентов для сервисов, работающих по подписке, решает задачу предсказания вероятности того, что клиент прекратит использование сервиса. Это важная задача для бизнеса, так как отток клиентов может повлиять на доходы компании.
Для решения этой задачи будут использоваться модели классификации в основном решающие деревья и ансамблевые методы: такие как Random Forest, CatBoost,XGBoost,LightGBM. Помимо этого для отбора признаков использовалась модель логистической регрессии.
Так как классы целевой переменной имеют большой дисбаланс, то также используются различные методы для повышения качества модели, обученной на таких данных.
Для оценки качества модели будут использоваться метрики: F1-score, ROC-AUC, так как нам важно минимизировать, как ложноположительные, так и ложноотрицательные ошибки. Также для оценки качества модели используется кросс-валидация. 
