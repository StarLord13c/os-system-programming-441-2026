# kusik

Ця директорія містить лабораторні роботи, виконані студентом **Кусік** з дисципліни **«Операційні системи та системне програмування»**.

## Структура

```
kusik/
└── lab_1/
    ├── lab_1.ipynb   # скрипт (Jupyter notebook)
    ├── README.md     # звіт
    └── figures/      # графіки
```

## Середовище

Лабораторні виконуються у **WSL (Windows Subsystem for Linux)** з використанням віртуального середовища `.venv` у корені репозиторію.

## Запуск з нуля

1. Клонувати репозиторій (у WSL):
   ```bash
   git clone https://github.com/StarLord13c/os-system-programming-441-2026
   cd os-system-programming-441-2026
   ```
2. Створити та активувати віртуальне середовище:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
3. Встановити залежності:
   ```bash
   pip install jupyter matplotlib
   ```
4. Запустити notebook:
   ```bash
   jupyter notebook kusik/lab_1/lab_1.ipynb
   ```
