# YouGate
## Проект распознавания автомобильных номеров
Данный проект нацелен на детекцию и распознавание автомобильных номеров. Для наглядности мы обернули нашу технологию в виде Telegram бота.

![1](https://user-images.githubusercontent.com/36695287/98160838-9b3f2580-1f00-11eb-8bf1-986b792cb878.jpg)

## Запуск
1. Необходимо скачать модель детекции по ссылке [здесь](https://drive.google.com/file/d/13qNb-OfK8DmZVhSORy--Jho9tNVRWXgx/view?usp=sharing)
2. Добавить модель детекции в папку `models`
3. Установить зависимости: `pip install -r requirements.txt`
4. Запустить скрипт телеграм бота: `python bot.py`

## Датасеты
* Детекция: более **8000** размеченных автомобильных номеров
* OCR: более **10000** размеченных автомобильных номеров

## Метрики:
* Детекция: **mAP@IoU:0.5 = 0.96-0.98**
* OCR: **Accuracy = 97%**

### TODO:
* Super resolution
* Улучшение точности OCR
