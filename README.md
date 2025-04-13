
# 📊 Финансовый скрининг: AAPL, MSFT, TSLA

В этом проекте выполнен сравнительный анализ трёх компаний на основе данных Yahoo Finance:

- Apple (AAPL)
- Microsoft (MSFT)
- Tesla (TSLA)

## 🔍 Цель проекта

Рассчитать ключевые метрики эффективности и ликвидности:
- **ROS (Return on Sales)**
- **Current Ratio**
- **Quick Ratio**
- **Absolute Ratio**

## 📈 Выводы

- **Microsoft** — лидер по ROS (~44%) и ликвидности (до 14.8), стабильна и устойчива
- **Apple** — эффективна (~30% ROS), но работает с пониженной ликвидностью (<1.0)
- **Tesla** — слабый ROS, но поддерживает ликвидность кэшем

## 📊 Визуализации
- Графики ROS и ликвидности по годам
- Таблица `final_comparison.csv` с итоговыми метриками

## 📁 Структура
- `data/` — входные и итоговые CSV
- `notebooks/` — расчёты и графики
- `README.md` — описание
- `requirements.txt` — библиотеки (`pandas`, `matplotlib`, `yfinance`)

## 🚀 Как запустить

```
pip install -r requirements.txt
jupyter notebook notebooks/liquidity_ros_analysis.ipynb
```
