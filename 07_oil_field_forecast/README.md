# Выбор региона для разработки новых нефтяных месторождений
### Задача
Решить в каком регионе добывать нефть. Построить модель машинного обучения, которая поможет определить регион, где добыча принесет наибольшую прибыль с наименьшим риском убытков

### Результат
Проведено исследование скважин для бурения нефти в трех различных регионах. Подготовлена и обучена модель, предсказывающая запасы нефти в скважинах. Вычислены пороги рентабельности для каждого региона. Средний результат по скважинам везде оказался ниже требуемого, что определяет необходимость отбора скважин перед началом добычи на них.
В последнем шаге методом бутстреп вычислили показатели средней прибыли с доверительным интервалом 95%, а также риск убытков для каждого региона.

### Используемые библиотеки:
- pandas
- NumPy
- seaborn
- matplotlib
- scikit-learn

### Статус проекта
Завершен
