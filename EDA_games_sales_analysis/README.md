## Постановка задачи
*Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.*  
*Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.*

#### Описание данных
- Name — название игры
- Platform — платформа
- Year_of_Release — год выпуска
- Genre — жанр игры
- NA_sales — продажи в Северной Америке (миллионы проданных копий)
- EU_sales — продажи в Европе (миллионы проданных копий)
- JP_sales — продажи в Японии (миллионы проданных копий)
- Other_sales — продажи в других странах (миллионы проданных копий)
- Critic_Score — оценка критиков (максимум 100)
- User_Score — оценка пользователей (максимум 10)
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.  
*Данные за 2016 год могут быть неполными.*

## Детали проекта
Провёл предобрабоку: исправил типы данных в столбцах, часть пропусков заполнил очевидным решением, часть данных с критическими пропусками удалил.
Произвёл расчёт продаж по регионам. Определил актуальный для исследования период.

## Вывод
Был проведён разведочный анализ с предобработкой. Сделана визуализация данных, даны ответы на ключевые вопросы, а также были проверены гипотезы.

Итоги исследования:
- нужно закупать игры для PS4, Xbox One в достаточном количестве, в значительно меньшем - PS3 и Xbox 360 (т.к. платформы устаревают, и люди активно перепродают диски с рук, ато и прошивают приставки);
- в закупке нужно сделать упор на экшены, шутеры, РПГ, спортивные игры и гончые симуляторы, причём в подборке должны преобладать игры с рейтингами M и E;
- одну игру можно закупать сразу под несколько разных платформ, если она популярна на любой из платформ (и если эта игра не эксклюзив для одной из них, конечно же);
- время отказываться совсем от дисков для PC, кроме коробочных изданий: "Ведьмак" только набирает обороты популярности, кому-то наверняка захочется поставить красивую коробочку на полку;
- при подборе игр лучше ориентироваться на рейтинги критиков, чем на пользвательские - самые высокие оценки пользователи ставят играм, которые почему-то никто не берёт.