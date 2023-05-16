# A/B тестирование маркетинговых кампаний
Применение A/B тестирования с использованием Python для выявления самой эффективной маркетинговой кампании

## Суть задачи
Компания, специализирующаяся на одежде, запускает новый продукт для своего каталога. Но менеджер так и не смог определиться с тем, какой вариант из трех имеющихся выбрать для продвижения.
Поэтому компания решила запустить разные варианты стратегий для нескольких своих магазинов, чтобы изучить влияние каждой стратегии, и выявить самый лучший и прибыльный вариант.
Итоговое решение компании - использовать разные стратегии для каждого магазина, где результат будет оцениваться путем замера еженедельных продаж в текущем месяце (4 полные недели).


## Описание имеющихся данных
Всего имеется 548 наблюдений, содержащих в себе:
- OutletID: Уникальный код магазина. Общее число таких точек - 137.
- AgeofOutlets: Сколько лет магазину.
- Campaigns: Одна из трех тестирующихся кампаний (1, 2, 3).
- Sales in Thousands: Сумма продаж для определенного OutletID, Campaigns и недели. Среднее число продаж = 53.5 тысячи долларов.
- Market size: Магазины поделены на три типа по размеру (small, medium and large).
- Week: Текущая неделя (1–4).


## Используемые библиотеки
1. Pandas
2. Matplotlib
3. Seaborn
4. Scipy
