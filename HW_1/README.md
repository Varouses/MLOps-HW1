# MLOps HW1

## Описание
Этот проект реализует базовый MLOps сервис с использованием Flask. Сервис позволяет создавать, обучать, хранить и удалять модели машинного обучения.

## Функциональность
Создание и обучение модели: Пользователь может создать модель и обучить её на предоставленных данных.
Просмотр обученных моделей: Сервис предоставляет список всех обученных моделей.
Удаление модели: Пользователь может удалить модель из хранилища.

## Установка и запуск
Требования
Python 3.8
Пакеты Python, перечисленные в requirements.txt.

Создание и обучение модели
Отправьте POST запрос на /create с параметрами модели.

Получение списка моделей
Отправьте GET запрос на /models для получения списка всех обученных моделей.

Получение доступных классов
Отправьте GET запрос на /classes для получения списка всех классов для обучения.

Удаление модели
Отправьте DELETE запрос на /delete с именем модели, чтобы удалить её.