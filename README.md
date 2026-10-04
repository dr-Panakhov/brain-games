# Brain Games («Игры разума») 🧠

[![Actions Status](https://github.com/dr-Panakhov/python-project-49/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/dr-Panakhov/python-project-49/actions)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=dr-Panakhov_python-project-49&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=dr-Panakhov_python-project-49)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=dr-Panakhov_python-project-49&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=dr-Panakhov_python-project-49)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=dr-Panakhov_python-project-49&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=dr-Panakhov_python-project-49)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=dr-Panakhov_python-project-49&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=dr-Panakhov_python-project-49)

Набор из пяти консольных интеллектуальных мини-игр, построенных по принципу популярных тренажеров для мозга. 

Проект спроектирован с упором на **чистую архитектуру**: единый движок управления игровым циклом, строгая изоляция побочных эффектов (I/O) и независимые модули бизнес-логики для каждой игры.

---

### 🛠 Стек технологий

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![uv](https://img.shields.io/badge/uv-Package_Manager-DE5FE9?style=flat-square)
![Ruff](https://img.shields.io/badge/Linter-Ruff-orange?style=flat-square)
![SonarCloud](https://img.shields.io/badge/QA-SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

* **Язык:** Python 3.10+
* **Менеджер пакетов и окружения:** `uv`
* **Линтер и форматирование кода:** `ruff`
* **Архитектурный паттерн:** Game Engine / CLI Routing, чистые функции без сайд-эффектов

---

### 🎮 Список игр

1. **brain-even** — Определение чётности случайного числа.
2. **brain-calc** — Вычисление случайных арифметических выражений (+, -, *).
3. **brain-gcd** — Нахождение наибольшего общего делителя (НОД) двух чисел.
4. **brain-progression** — Восстановление пропущенного числа в арифметической прогрессии.
5. **brain-prime** — Определение, является ли число простым.

---

### 🚀 Установка и запуск

Для работы требуется установленный менеджер пакетов [uv](https://github.com/astral-sh/uv).

```bash
# 1. Клонировать репозиторий
git clone [https://github.com/dr-Panakhov/python-project-49.git](https://github.com/dr-Panakhov/python-project-49.git)
cd python-project-49

# 2. Установить зависимости и собрать виртуальное окружение
uv sync

# 3. Установить пакет в систему (опционально, для запуска по имени команды)
uv pip install -e .
