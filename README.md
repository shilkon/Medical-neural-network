# Medical neural network
## Раннее выявление рака легких с помощью нейронной сети
***
### Участники:
#### Бендрышев Сергей Александрович, группа 5130904/10103
#### Шульгин Илья Константинович, группа 5130904/10103
#### Бурычкин Матвей Олегович, группа 5130904/10103

### Описание проекта

1) Целью проекта является разработка модели нейронной сети для раннего выявление рака легких с использованием снимков компьютерной томографии.
2) Выработка требований
    1. Объединение источников данных (снимки компьютерной томографии LUNA) - часть 1 доступна по ссылке https://zenodo.org/records/3723295, часть 2 по ссылке https://zenodo.org/records/4121926
    2. Обучение модели классификации обнаружению потенциальных опухолей
    3. Улучшение процесса обучения с помощью метрик и дополнений (аугментация)
3) Разработка архитектуры и детальное проектирование доступна по ссылке
4) Распределение обязанностей
    1. Сергей - обучение модели классификации
    2. Илья - объединение источников данных
    3. Матвей - запуск процесса обучения модели и предоставление результатов тестов
5) Визуализация данных доступна в ноутбуках explore_data и augmented_explore_data
6) В качестве демонстрации интеграционного тестирования предлагаются скриншоты из Tensorboard
7) Сборка проекта есть в двух вариантах
   1) Docker
   2) Makefile

***
