Payment-Calculator
==================

Калькулятор расчета услуг

##Описание

 - 4 основных шага, последовательно появляющихся друг за другом
 - Раскрывающиеся описание для каждой услуги
 - Блок с выбранной услугой отмечается особым цветом
 - Скрипт для выбора только одного чека в первых двух блоках, так же заменены картинки ie9+
 - Проверки на пустой чек, указаны ли кол-во услуг(страниц).Выводятся разные предупреждения для каждого шага
 - Затемнение пройденного шага с уведомлением
 - Прогресс-бар пройденных шагов в процентах и визуальном представлении
 - Подсчет шагов n из 4, после выбора последнего меняется на кнопку "Расчет"
 - Итоговая расчетная таблица выбранных услуг, с типом услуги, ценой, количеством (выбрано страниц), если это возможно, а так же итоговая стоимость
 - Форма заявки, c 3 обязательными полями, поля email и телефон проверяются через регулярные выражения и 1 необязательное
 - Сообщение об успешной отправке с указанием на какой email выслано сообщение
 - Ajax обработка формы, без перезагрузки страницы
 - PHP обработчик формы отправляет два письма: 
	- на указанный email в формате HTML(клиенту); 
	- на email исполнителя с информацией о клиенте

##Кроссбраузерность

 - Все современные браузера
 - В IE8 и ниже не работают некоторые визуальные эффекты, вся логика функционирует

##Пример работы

Можно посмотреть <a href="http://example.web-ulyanov.ru/frontend/Payment-Calculator/">Здесь</a>
