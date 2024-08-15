# План тестирования №1

**Introduction**: Предоставление суммарной оценки качества продукта

**Test items**: Карточка товара https://wortex.by/catalog#shurupoverty

**Responsibilities**: QA - Шугай Виктория

**Schedule**: 16.08.2024

## СТРАТЕГИЯ ТЕСТИРОВАНИЯ

Основным методом проверки данного программного продукта будет ручное функциональное тестирование с использованием метода «черного ящика».

Таким образом в процессе тестирования Карточки товара сайта wortex.by последовательность основных проверок программного продукта будет такой:

1.	Функциональное тестирование.

2.	Тестирование безопасности.

3.	Usability тестирование (UI/UX, удобство пользования).

4.	Тестирование совместимости.

5.	Тестирование сайта на продуктивность.

   ### Функциональное тестирование 

Проверяю работоспособность всех опций на сайте.

•	тестирование ссылок и проверка навигации сайта (проверяю ссылки не только на работоспособность, но и корректность перехода).

•	тестирование товаров ( наличие, своевременное обновление данных, цены/акций если указаны).

•	тестирование файлов cookie .

•	тестирование поисковой строки.

•	проверка пользовательских форм обратной связи при наличии (корректное заполнение и распознавание необходимых символов, выведение ошибок при неправильном заполнении, обязательные/необязательные поля, коментарии) 

Для функционального тестирования сайта я пройду такие вариации проверок как:

1.	Ad-hock проверка - быстрая проверка, ориентированная на быстрое ознакомление с программным обеспечением без первичной подготовки, по принципу использования сайта конечным пользователем, анализ ясности в использовании главных функций и навигации по сайту.

2.	Негативное тестирование - тестирование в котором требуется большое количество тестов на негативный результат и выдачу системой ошибки. В данном тестировании важно найти баги, при которых система не уведомляет об существующей ошибке.

3.	Исследовательское тестирование -  система проверяется на ошибки путем ее изучения углубленно. То есть, без начальных требований я изучаю систему, анализирую результаты, которые дает ПО при использовании тех или иных функций, придумываю проверки, при которых система может дать ошибку и снова тестирую. При таком круговом подходе можно за очень короткое время найти баги разной степени тяжести.

### Тестирование безопасности

Благодаря которому определяется степень уязвимости сайта, защищенность от взлома внешними источниками, общий уровень безопасности.
Три важных принципа работы ПО, которые должны поддаваться тестированию:

•	Конфиденциальность (все личные данные пользователя должны быть ограничены от всеобщего доступа).

•	Целостность (проверка возможности воссоздания утерянной информации при какого-либо рода, а также внешним источником).

•	Доступность (разбивка уровня доступа к конфиденциальным данным на ступени иерархии).

### Тестирование на совместимость

Любой сайт должен гармонично смотреться на разных устройствах, будь то компьютер, ноутбук, планшет или мобильная версия сайта для телефона, а также разных операционных системах.

(iOS Microsoft)

•	Кроссплатформенное - тестирование на разных операционных системах (Windows, Mac, ) и их разных версиях.
•	Кроссбраузерное - тестирование в разных браузерах (Internet Explorer, Firefox, Chrome, Safari, Opera) на предмет функциональности всех элементов, качественного отображения и единого дизайна.
•	Адаптация к мобильным версиям.

### Usability тестирования:

•	Проверка простоты эксплуатации. Дает возможность оценить практичность структуры, убрать лишние элементы с сайта.

•	Проверка удобства навигации. Оценивается комфортность доступа к меню с каждой созданной страницы, понятность обозначения всех кнопок и доступ к ним.

•	Тестирование контента. Изначально проверяется соответствие готового дизайна сайта требуемому. В данные проверки входят: шрифты, цвета каждого элемента должны соответствовать техническому заданию дизайнера, маркеры ссылок, расположение абзацев, расположение различных блоков, иконок, фото и др.


### Тестирование сайта на продуктивность

Данный тип тестирования поможет мне определить работоспособность сайта, выносливость, чувствительность при разных нагрузках. Особенно важно тестировать интернет-магазины, социальные сети, стриминговые платформы, на которых может быть одновременно большое количество пользователей. Для таких проверок используют различные сервисы имитации создания новых пользователей.

•	Нагрузочное тестирование. Проводится проверка работоспособности сайта как при обычных нагрузках, так и при пиковых, получая различные данные и сопоставляя показатели.

•	Стресс-тестирование. Анализируется работоспособность системы при условии работы на экстремально высоких нагрузках, продолжительность корректной работы без аварийных отключений, определяется допустимое граничное значение пиковой нагрузки.

•	Объемное тестирование. Проводится для определения продуктивности сайта при увеличении объема баз данных (загрузка файлов большого объема, создание большого количество пользователей, добавление в корзину интернет-магазина большого количества товара).

•	Тестирование надежности. Проверка работоспособности сайта при определенных условиях на протяжении определенного времени (например, длительное использование при интенсивной нагрузке).
При завершении проекта используется также регрессионное тестирование. То есть повторное тестирование осуществляется для всех элементов, в которых вносились изменения кода.

### Тестирование локализации и глобализации

Тестирование интернационализации/глобализации WEB приложения включает тестирование приложения для различных местоположений, форматов дат, чисел и валют. Тестирование локализации включает тестирование WEB приложения с локализованными строками, изображениями и рабочими процессами для определенного региона.




# Чек-лист

| Проверка                                                      | Результат         | Комметарии       |
| :---                                                          |     :---:         | :---             |
|  *Функциональное тестирование:*                              |                     |                |
 Сайт корректно открывается и доступен.                        | passed ☑           |                |
 Повторное открытие сайта выполняется без сбоев                | passed ☑           |                |
 Все кнопки на сайте реагируют на нажатие.                     | failed ⛔           |Кнопка "Совместимо с Makita LXT"  |
 Все ссылки на сайте переходят на соответствующие страницы.    | failed ⛔           |                |
 Отсутствуют битые ссылки.                                     | failed ⛔           |                |
 Основные элементы сайта функционируют без нарушений.          | failed ⛔           |                |
 Навигационное меню работает корректно.                        | failed ⛔           |                |
 Загружаемые документы открываются правильно.                  | failed ⛔           |                |
 Отправка форм происходит без ошибок.                          | passed ☑           |                |
 Все данные в списках располагаются хронологически.            | passed ☑           |                |
 *Поиск:*
 Проверка существующих и не существующих результатов          | passed ☑           |                |
 Поиск с минимальным кол-вом и отображение корректного сообщения,когда запрос менее N символов| passed ☑           |                |
Поиск при пустом поле.                                         | passed ☑           |                |
 Корректное сообщение при пустом запросе                       | failed ⛔           |                |
 Диапазон допустимых символов                                  | failed ⛔           |                |
 Проверка регистра                                               | passed ☑           |                |
Если поиск по полному совпадению - проверить, что работает именно так, как надо  | passed ☑           |                |
Если поиск по частичному - проверить, что ищет неполное совпадение | passed ☑           |                |
Поиск похожих значений (или предложение исправить опечатку, как в google)   | failed ⛔           |                |
Ввод в поле поиска спецсимволов и отображение соответствующих результатов | passed ☑           |                |
Ввод в поле поиска эмоджи и отображение соответствующих результатов | passed ☑           |                |
Ввод пробела до/после параметра поиска                             | passed ☑           |                |
СИМВОЛОВ
Поиск с максимальным кол-вом символов (если такой параметр указан в требованиях)
Поиск технической границы ввода (например, 10 тыс символов)
Результаты поиска - отображается то, что мы ищем
Наиболее подходящий под параметры поиска результат - в самом начале
  *Валидация всех полей Регистрации гарантии*
  Проверка максимальной и минимальной длины.                 | passed ☑           |                |
  Диапазон допустимых символов/спецсимволов.                 | passed ☑           |                |
  Обязательность к заполнению.                               | passed ☑           |                |
  Астериск (знак звездочки) отображается у всех обязательных полей.| failed ⛔           |                |
  Система не отображает окно ошибки при незаполненных необязательных полях.| passed ☑           |                |
   Необязательные поля также проходят валидацию.             | passed ☑           |                |
   


