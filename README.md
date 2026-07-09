# 🤖 Мои учебные проекты по машинному обучению

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-educational-brightgreen.svg)]()

**Русский** | **[English (below)](#english-version)**

---

## 📚 Оглавление
1. [📖 Описание проекта](#-описание-проекта)
2. [🛠 Используемые технологии](#-используемые-технологии)
3. [🚀 Быстрый старт](#-быстрый-старт)
4. [📁 Структура проекта](#-структура-проекта)
5. [📓 Обзор лабораторных](#-обзор-лабораторных)
6. [💡 Примеры использования](#-примеры-использования)

---

## 📖 Описание проекта

Привет! 👋 Это мой проект по машинному обучению. Здесь я собрал все свои работы, которые делал в Google Colab во время обучения.

Это коллекция Jupyter Notebooks, посвящённая фундаментальным алгоритмам машинного обучения. Каждый блокнот содержит теоретическую базу, реализацию с нуля и примеры применения на реальных данных.

### 🎯 Основные темы
- **📈 Линейная регрессия** — теория, реализация и применение к реальным данным
- **🎯 Логистическая регрессия** — задачи классификации
- **🧠 Перцептрон** — базовая реализация нейронной сети с нуля
- **🔮 Нейронные сети** — реализация с различными функциями потерь

### 🎓 Для кого этот проект
- **Студентам**, изучающим основы машинного обучения
- **Практикующим Data Scientist'ам**, ищущим наглядные примеры
- **Разработчикам**, реализующим алгоритмы ML с нуля

---

## 🛠 Используемые технологии

### 🔧 Основные технологии

| Технология | Версия | Назначение |
|:---|:---|:---|
| **Python** | 3.8+ | Основной язык программирования |
| **Jupyter Notebook** | Последняя | Интерактивная среда разработки |
| **NumPy** | 1.21+ | Численные вычисления |
| **Pandas** | 1.3+ | Манипуляция и анализ данных |
| **Matplotlib** | 3.4+ | Визуализация данных |
| **scikit-learn** | 1.0+ | Алгоритмы машинного обучения |

### 📊 Алгоритмы машинного обучения
- **Линейные модели**: Линейная регрессия
- **Классификация**: Логистическая регрессия, Перцептрон
- **Нейронные сети**: Пользовательские реализации с различными активациями
- **Метрики оценки**: MSE, Accuracy

---

## 🚀 Быстрый старт

### ⚡ Предварительные требования
- Python 3.7 или выше
- Менеджер пакетов pip
- Git (для клонирования репозитория)

### 📥 Шаги установки

**1. Клонируйте репозиторий**

```bash
git clone https://github.com/interiys/Machine-learning.git
cd Machine-learning
```

**2. Создайте и активируйте виртуальное окружение**

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/MacOS
python3 -m venv venv
source venv/bin/activate
```

**3. Установите зависимости**

```bash
pip install -r requirements.txt
```

**4. Запустите Jupyter Notebook**

```bash
jupyter notebook
```

**5. Изучайте лабораторные по порядку:**
- `Linear_Regression.ipynb`
- `Logistic_Regression.ipynb`
- `practice_perceptron.ipynb`
- `practice_neuron.ipynb`
- `practice_neuron_logloss.ipynb`

### 🧪 Проверка установки

```python
# Проверьте установку
import numpy as np
import pandas as pd
import sklearn
print("Все пакеты успешно установлены! 🎉")
```

---

## 📁 Структура проекта

```
Machine-learning/
│
├── 📓 Лабораторные/
│   ├── Linear_Regression.ipynb
│   ├── Logistic_Regression.ipynb
│   ├── practice_perceptron.ipynb
│   ├── practice_neuron.ipynb
│   └── practice_neuron_logloss.ipynb
│
├── 📁 Данные/
│   ├── apples_pears.csv
│   └── voice.csv
│
└── 📖 README.md
```

---

## ✨ Возможности

### 🔧 Основные возможности

| Возможность | Описание | Иконка |
|:---:|:---:|:---:|
| **Комплексная теория** | Математические основы с подробными объяснениями | 📚 |
| **Реализации с нуля** | Пользовательские реализации алгоритмов ML | 🛠️ |
| **Приложения на реальных данных** | Практические примеры с реальными данными | 🌍 |
| **Продвинутая визуализация** | Обширное построение графиков и визуализация | 📊 |
| **Оценка моделей** | Множественные метрики и анализ производительности | ✅ |

---

## 📓 Обзор лабораторных

### 1. 📈 Линейная регрессия

| Тема | Описание | Навыки |
|:---|:---|:---|
| **Теория** | Математические основы | Математика |
| **Синтетические данные** | Генерация и визуализация | NumPy, Matplotlib |
| **Обучение модели** | Реализация и оценка | scikit-learn |
| **Реальное применение** | Работа с данными | Pandas, Анализ данных |

### 2. 🎯 Логистическая регрессия
- Теория бинарной классификации с вероятностной интерпретацией
- Техники предобработки данных и one-hot кодирования
- Оценка модели с точностью и метриками

### 3. 🧠 Реализация перцептрона
- Алгоритм перцептрона с первых принципов
- Пользовательская реализация класса
- Тестирование на реальных данных (голос)
- Сравнение производительности с scikit-learn

### 4. 🔮 Нейронные сети
- Реализация нейронной сети с сигмоидальной активацией
- Техники оптимизации градиентным спуском
- Реализация функции потерь LogLoss
- Сравнение MSE vs LogLoss

---

## 💡 Примеры использования

### 📈 Пример линейной регрессии
```python
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

# Создание и обучение модели
model = LinearRegression()
model.fit(X_train, y_train)

# Прогнозирование
predictions = model.predict(X_test)

# Оценка производительности
mse = mean_squared_error(y_test, predictions)
print(f'Test MSE: {mse:.4f}')

# Визуализация результатов
plt.figure(figsize=(10, 6))
plt.scatter(y_test, predictions, alpha=0.7)
plt.plot([y_test.min(), y_test.max()], [y_test.min(), y_test.max()], 'r--')
plt.xlabel('Фактические значения')
plt.ylabel('Предсказанные значения')
plt.title('Линейная регрессия: Фактические vs Предсказанные')
plt.show()
```

### 🎯 Пример логистической регрессии
```python
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, classification_report

# Инициализация и обучение модели
model = LogisticRegression(random_state=42)
model.fit(X_train, y_train)

# Предсказание и оценка
y_pred = model.predict(X_test)
accuracy = accuracy_score(y_test, y_pred)
print(f'Точность: {accuracy:.4f}')
print(classification_report(y_test, y_pred))
```

### 🧠 Пример пользовательского перцептрона
```python
from sklearn.metrics import accuracy_score

# Инициализация пользовательского перцептрона
perceptron = Perceptron()
losses = perceptron.fit(X_train, y_train, num_epochs=300)

# Прогнозирование
predictions = perceptron.forward_pass(X_test)

# Расчет точности
accuracy = accuracy_score(y_test, predictions)
print(f'Точность перцептрона: {accuracy:.4f}')

# График процесса обучения
plt.plot(losses)
plt.title('Потери при обучении перцептрона')
plt.xlabel('Эпоха')
plt.ylabel('Потери')
plt.show()
```

<a name="english-version"></a>
## 🇬🇧 English Version

### 📖 Project Description
Hello! 👋 This is my machine learning project. Here I collected all my works from Google Colab.

This is a collection of Jupyter Notebooks covering fundamental machine learning algorithms and their implementations.

### 🎯 Main Topics
- **📈 Linear Regression** — theory, implementation, real data applications
- **🎯 Logistic Regression** — classification problems
- **🧠 Perceptron Algorithm** — basic neural network from scratch
- **🔮 Neural Networks** — implementation with different loss functions

### 🛠 Technologies Used

| Technology | Version | Purpose |
|:---|:---|:---|
| **Python** | 3.8+ | Core programming language |
| **Jupyter Notebook** | Latest | Interactive development environment |
| **NumPy** | 1.21+ | Numerical computations |
| **Pandas** | 1.3+ | Data manipulation and analysis |
| **Matplotlib** | 3.4+ | Data visualization |
| **scikit-learn** | 1.0+ | Machine learning algorithms |

### 🚀 Quick Start

```bash
git clone https://github.com/interiys/Machine-learning.git
cd Machine-learning
pip install -r requirements.txt
jupyter notebook
```

### 📁 Project Structure

```
Machine-learning/
│
├── 📓 Laboratory Works/
│   ├── Linear_Regression.ipynb
│   ├── Logistic_Regression.ipynb
│   ├── practice_perceptron.ipynb
│   ├── practice_neuron.ipynb
│   └── practice_neuron_logloss.ipynb
│
├── 📁 Data/
│   ├── apples_pears.csv
│   └── voice.csv
│
└── 📖 README.md
```

### 📓 Laboratory Works Overview

| File | Description |
|:---|:---|
| `Linear_Regression.ipynb` | 📈 Linear Regression |
| `Logistic_Regression.ipynb` | 🎯 Logistic Regression |
| `practice_perceptron.ipynb` | 🧠 Perceptron from scratch |
| `practice_neuron.ipynb` | 🔮 Neuron with MSE |
| `practice_neuron_logloss.ipynb` | 🔮 Neuron with LogLoss |

---

### 💡 Usage Examples

#### 📈 Linear Regression Example

```python
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

# Create and train model
model = LinearRegression()
model.fit(X_train, y_train)

# Make predictions
predictions = model.predict(X_test)

# Evaluate performance
mse = mean_squared_error(y_test, predictions)
print(f'Test MSE: {mse:.4f}')

# Visualize results
plt.figure(figsize=(10, 6))
plt.scatter(y_test, predictions, alpha=0.7)
plt.plot([y_test.min(), y_test.max()], [y_test.min(), y_test.max()], 'r--')
plt.xlabel('Actual Values')
plt.ylabel('Predicted Values')
plt.title('Linear Regression: Actual vs Predicted')
plt.show()
```

#### 🎯 Logistic Regression Example

```python
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, classification_report

# Initialize and train model
model = LogisticRegression(random_state=42)
model.fit(X_train, y_train)

# Predict and evaluate
y_pred = model.predict(X_test)
accuracy = accuracy_score(y_test, y_pred)
print(f'Accuracy: {accuracy:.4f}')
print(classification_report(y_test, y_pred))
```

#### 🧠 Custom Perceptron Example

```python
from sklearn.metrics import accuracy_score

# Initialize custom perceptron
perceptron = Perceptron()
losses = perceptron.fit(X_train, y_train, num_epochs=300)

# Make predictions
predictions = perceptron.forward_pass(X_test)

# Calculate accuracy
accuracy = accuracy_score(y_test, predictions)
print(f'Perceptron Accuracy: {accuracy:.4f}')

# Plot training progress
plt.plot(losses)
plt.title('Perceptron Training Loss')
plt.xlabel('Epoch')
plt.ylabel('Loss')
plt.show()
```

#### 🔮 Neural Network with LogLoss

```python
# Initialize neural network with LogLoss
neuron = Neuron()
J_values = neuron.fit(X, y, num_epochs=5000)

# Generate predictions
predictions = neuron.forward_pass(X_test)
binary_predictions = (predictions > 0.5).astype(int)

# Evaluate performance
accuracy = accuracy_score(y_test, binary_predictions)
print(f'Neural Network Accuracy: {accuracy:.4f}')

# Visualize learning curve
plt.figure(figsize=(10, 6))
plt.plot(J_values)
plt.title('Neural Network Training (LogLoss)')
plt.xlabel('Iteration')
plt.ylabel('LogLoss')
plt.grid(True)
plt.show()
```

---

## 📌 О проекте / About the Project

**Status**: 🟢 Laboratory project

**Author**: The author loves ferrets ;3

<p align="center">
  <img src="https://github.com/user-attachments/assets/b02d24de-8dd5-41c5-9229-2060730c03e2" width="400" alt="ferret" />
</p>
