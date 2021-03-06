**Источник данных**: исторические данные компании из золотодобывающей отрасли с параметрами добычи и очистки золота. \
Данные предоставлены компанией «Цифра» (https://www.zyfra.com)

**Стек**: Pandas, NumPy, Math, SciPy, Seaborn, MatPlotLib, sklearn, предобработка данных, исследовательский анализ данных, визуализация, linear regression, decision tree, random forest.

**Цель проекта**: разработать модель, предсказывающую коэффициент восстановления золота из золотосодержащей руды.

**Целевая метрика**: sMAPE (итоговое) = 0.25 * sMAPE (1 этап) + 0.75 * sMAPE (2 этап)

**Состав проекта**:
- Общие данные
- Предобработка и подготовка данных
- Анализ данных
- Обучение и анализ моделей ML
- Подбор гиперпараметров
- Тестирование моделей
- Выводы

**Полученные результаты**:
- Проведено сравнение 6 сочетаний моделей ML (линейная регрессия, решающее дерево, случайный лес) и сконструированных датасетов;
- Наилучшие результаты получены для модели линейной регрессии:
  - sMAPE = 8.7
- Сформулированы рекомендации относительно корректировки технологического процесса с целью получения концентрата с повышенным содержанием золота.
