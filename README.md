# DL Lab 1: Влияние Dropout и BatchNorm на нелинейную регрессию

## Задача

Сгенерировать 3 случайные нелинейные регрессии, обучить модель на 4 конфигурациях:
1. Без Dropout, без BatchNorm
2. Только BatchNorm
3. Только Dropout
4. BatchNorm + Dropout

Сравнить результаты: loss curves, предсказания, переобучение, время обучения.

## Структура

- `notebooks/dl_lab1_regression.ipynb` — основной ноутбук
- `results/` — графики
- `report.md` — отчёт
- `requirements.txt` — зависимости

## Запуск

```bash
pip install -r requirements.txt
jupyter notebook notebooks/dl_lab1_regression.ipynb

## Ссылки

GitHub: https://github.com/1rizhik/dl_lab1
