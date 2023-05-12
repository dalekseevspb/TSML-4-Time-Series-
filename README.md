# TSML-4 (Time Series, ВременнЫе ряды)

# (#1) Знакомство с временными рядами:
1. Построение графиков следующих рядов:
 - "Monthly sales of company X",
 - "Monthly Boston armed robberies",
 - "International airline passengers: monthly totals in thousands",
 - "Mean monthly air temperature (Deg. F) Nottingham Castle",
 - "Weekly closings of the Dow-Jones industrial average",
 - "Daily total female births in California".
2.  Приведение рядов к стационарному виду:
- Проверка каждого ряда на стационарность (проведение теста Дики-Фуллера). 
- Построение и анализ коррелограмм. 
- В случае нестационарности ряда: дифференцирование, преобразование Бокса-Кокса.
- Повторная проверка (проведение теста Дики-Фуллера, анализ коррелограмм).

# (#2) Элементарные методы обработки временных рядов (MA, WMA, EMA, TEMA):
- скользящее среднее (Moving Average), 
- взвешенное скользящее среднее (Weighted Moving Average);
- экспоненциальное скользящее среднее (Exponential Moving Average);
- тройное экспоненциальное сглаживание (Triple Exponential Moving Average, или метод Хольта-Винтерса).
1.Взять из (#1) ряд (в двух вариантах - стационарный и нет) и приблизить оба эти варианта моделями из класса MA. 
2.Оценить качество и прислать соображения, почему была выбрана та или иная модель.

# (#3) Модель ARIMA + Предсказание "классическим" ML(лин.регрессия)

# (#4) Модель GARCH

# (#5) SSA (сингулярный спектральный анализ)

# (#6) Случайные марковские процессы, HMM
