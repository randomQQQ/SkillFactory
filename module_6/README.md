# Проект 6. Парсинг auto.ru и прогнозирование цен на авто

### Задачи проекта:

 - сбор данных для тренировочного набора с помощью web-scraping
 - анализ и обработка этих данных
 - обучение и подбор гиперпараметров регрессионых моделей

### Цель:
 - добиться лучшего показателя метрики MAPE

### Notebook
 - [парсинг](https://github.com/randomQQQ/SkillFactory/blob/master/module_6/parsing.ipynb)
 - [EDA + ml](https://github.com/randomQQQ/SkillFactory/blob/master/module_6/project.ipynb)


### MAPE
 - StackingRegressor (из моделей ниже, кроме RandomForestRegressor,  финальная модель Ridge) - 11.73
 - CatBoostRegressor- 12.05
 - LGBMRegressor - 12.16
 - XGBRegressor - 12.27
 - ExtraTreesRegressor - 12.48
 - RandomForestRegressor - 12.73

 #### [Профиль Kaggle](https://www.kaggle.com/phxphxphx)