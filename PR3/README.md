### **Краткий конспект лекции "Метод анализа иерархий"**

**1. Основные понятия МАИ**  
- **Автор**: Томас Саати (1970-е гг.).  
- **Цель**: Решение многокритериальных задач (МКО) с качественными и количественными факторами.  
- **Ключевые особенности**:  
  - Декомпозиция задачи на иерархическую структуру.  
  - Использование парных сравнений для оценки критериев и альтернатив.  
  - Проверка согласованности суждений.  

---

**2. Этапы МАИ**  
  1. **Построение иерархии**:  
     - **Уровень 1**: Главная цель (напр., "Выбор смесителя для умного дома").  
     - **Уровень 2**: Критерии (напр., интеграция, экономия воды, бесконтактность).  
     - **Уровень 3**: Альтернативы (напр., виды смесителей).  

  2. **Парные сравнения**:  
     - Критерии и альтернативы сравниваются попарно по шкале относительной важности (от 1 до 9).  
     - Пример шкалы:  
       - 1 — равная важность,  
       - 9 — абсолютное превосходство.  

  3. **Расчёт приоритетов**:  
     - Для каждой матрицы сравнений вычисляется:  
       - **Геометрическое среднее** строк.  
       - **Нормализованный вектор приоритетов** (веса критериев/альтернатив).  
     - Проверка согласованности:  
       - **Индекс согласованности (ИС)** и **отношение согласованности (ОС)**.  
       - ОС ≤ 0.10 — приемлемо.  

---

**3. Пример: Выбор смесителя**  
  - **Критерии**:  
    1. Интеграция в "умный дом" (вес 0.45).  
    2. Экономия воды (0.235).  
    3. Бесконтактность (0.17).  
    4. Вандалоустойчивость (0.1).  
    5. Стоимость (0.04).  

  - **Альтернативы**:  
    - A1: Смеситель с раздельными кранами.  
    - A2: Однорычажный.  
    - A3: Со встроенным термостатом.  
    - A4: Бесконтактный + термостат.  
    - A5: Электронный сенсорный.  

  - **Результаты**:  
    - **Лучшая альтернатива**: A4 (приоритет 0.437).  
    - **Вторая**: A5 (0.326).  

---

**4. Проверка согласованности**  
  - **Расчёт для критериев**:  
    - λmax = 5.43, ИС = 0.1075, ОС = 0.096 (приемлемо).  
  - **Для альтернатив**: ОС всех матриц < 0.10.  

---

**5. Преимущества и проблемы МАИ**  
  - **Плюсы**:  
    - Учёт качественных и количественных факторов.  
    - Гибкость (добавление/удаление элементов иерархии).  
  - **Проблемы**:  
    - Субъективность парных сравнений.  
    - Трудоёмкость при большом числе критериев.
