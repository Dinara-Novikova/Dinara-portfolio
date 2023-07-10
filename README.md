## ПОРТФОЛИО: Аналитик данных
Привет! 

Меня зовут Динара, я начинающий аналитик данных. В этом репозитории вы сможете найти некоторые из моих проектов, выполненных во время обучения и практики. 

## Навыки и технологии
Инструменты анализа данных: SQL, Excel, google-sheets

Системы управления базами данных: PostgreSQL

Инструменты хранения, визуализации данных - регламентов, инструкций: база данных wiki, google-sheets

Инструменты для бизнеса: crm-системы ramex, bitrix24, платформа коммуникаций UIS-телефония, 1С Предприятие - настройка, а также внесение, проверка и аналитика данных. 

Онлайн-системы управления проектами: trello, notion, miro.com, zoom. 

Командная работа и наставничество в сферах розничной торговли, финансов. 

Опыт организации и контроля процессов. 

## Проекты

### Проект 1: Калькулятор юнит-экономики онлайн-школы

Что нужно было сделать:

Задача №1.

Создать калькулятор юнит-экономики для онлайн школы с возможностью изменения входных параментров и автоматическим расчетом бизнес-показателей. Настроить динамический расчёт количества новых студентов за указанный период с учетом поправочного коэффициента. Найти с помощью калькулятора новое расчётное количество студентов на 04.2022 г.
   
Как решала:
1) Создала калькулятор с возможностью изменения входных параментров и добавила в список параметров калькулятора показатель "Поправочный коэф-т на привлечение";			
2) Установила значение этого показателя по умолчанию как 100% и добавила возможность изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение";							
3) Настроила динамический расчёт количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. Если для 05.21-04.22 он равен 120%, то в каждый месяц этого периода рассчётное значение количества новых студентов должно быть больше на 20%;				
4) Просчитала сценарий, при котором планы маркетинга будут увеличены на 12% (при сохранении настроек остальных показателей).							
				
Итог:
- калькулятор юнит-экономики для онлайн школы с возможностью изменения входных параментров и автоматическим расчетом бизнес-показателей;
- динамический расчёт количества новых студентов за указанный период с учетом поправочного коэффициента


Задача №2.

Составить обновлённый план по найму преподавателей с количеством новых преподавателей по месяцам за указанный период.
Сделать калькулятор найма преподавателей с возможностью изменения входных параметров: Пропускной способности преподавателей и Retention преподавателей.

Как решала:
1) Создала калькулятор найма преподавателей с возможностью изменять входные параметры: Пропускную способность преподавателей и Retention преподавателей - с помощью дополнительного столбца "изменения" с процентными изменениями.
2) По запросу сделала поправку в расчёте общей пропускной способности, с учетом того, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя, задаваемой параметром.
3) Обновила прогнозное количество уроков, добавив новые значения, полученные после решения задачи №1 - расчета поправки на планы маркетинга.
4) По запросу просчитала сценарий, при котором Пропускная способность преподавателей увеличится на 15%, а Retention преподавателей упадёт на 2%
5) С помощью Поиска решений составила новый план найма преподавателей с ограничением: за месяц нельзя нанять более 70 преподавателей

Итог:
- калькулятор найма преподавателей с возможностью изменять входные параметры - Пропускную способность преподавателей и Retention преподавателей;
- обновленный план по найму преподавателей с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022.

### Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра

Что нужно было сделать:

Определить эффективность системы через расчет юнит-экономики продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность и собрать наглядную визуализацию, где будет показано - кто, где и в каком объеме смотрит фильмы на платформе. Также собрать калькулятор юнит-экономики продукта, чтобы была автоматизированная система для быстрого принятия решений. 

Задачи:

1. Определить, что является юнитом в нашей экономике.
2. Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.
3. Выбрать оптимальный вариант расчета Retention. 
4. Собрать визуализации основных бизнес-показателей.
5. Исследовать данные о пользователях и их поведении
