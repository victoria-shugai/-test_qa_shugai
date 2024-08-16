![image](https://github.com/user-attachments/assets/c226020f-186e-432a-b50d-ae1b554f1194)# План тестирования №1

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
   
5.	Интеграционное тестирование

6.	Тестирование сайта на продуктивность.

   ### Функциональное тестирование 

Проверяю работоспособность всех опций на сайте.

•	тестирование ссылок и проверка навигации сайта (проверяю ссылки не только на работоспособность, но и корректность перехода).

•	тестирование товаров ( наличие, своевременное обновление данных).

•	тестирование поисковой строки.

•	проверка пользовательских форм  (корректное заполнение и распознавание необходимых символов, выведение ошибок при неправильном заполнении, обязательные/необязательные поля, коментарии) 

Для функционального тестирования сайта я пройду такие вариации проверок как:

1.	Ad-hock проверка - быстрая проверка, ориентированная на быстрое ознакомление с программным обеспечением без первичной подготовки, по принципу использования сайта конечным пользователем, анализ ясности в использовании главных функций и навигации по сайту.

2.	Негативное тестирование - тестирование в котором требуется большое количество тестов на негативный результат и выдачу системой ошибки. В данном тестировании важно найти баги, при которых система не уведомляет об существующей ошибке.

3.	Исследовательское тестирование -  в данном случае система проверяется на ошибки путем ее изучения углубленно. То есть, без начальных требований я изучаю систему, анализирую результаты, которые дает ПО при использовании тех или иных функций, придумываю проверки, при которых система может дать ошибку и снова тестирую. При таком круговом подходе можно за очень короткое время найти баги разной степени тяжести.

### Тестирование безопасности

Проверка конфиденциальности- все личные данные пользователя должны быть ограничены от всеобщего доступа.

### Тестирование на совместимость

Любой сайт должен гармонично смотреться на разных устройствах, будь то компьютер, ноутбук, планшет или мобильная версия сайта для телефона, а также разных операционных системах, поэтому кроссплатформенная проверка будет осоществлятся на OC для ПК: Microsoft (ASUS F553M intel), macOS (MacBook Pro 14 m1); и планшете на ОС Android (Lenovo TB-X505F)	. Кроссбраузерная проверка -  с помощью таких браузеров как: Internet Explorer(Версия 127.0.2651.98), Firefox(v.127.0), Chrome(v. 127.0.6533.119), Safari(16.6)) на предмет функциональности всех элементов, качественного отображения и единого дизайна.
Адаптацию к мобильным версиям я проверю на OC для смартфонов: iOS (iPhone 13 mini v.17.5.1) и ОС: Android(Samsung SM-J510FN v.7.1.1)

### Интеграционное тестирование 

Интеграционное тестирование проводится для того, чтобы убедиться, что наш продукт совместим со сторонними сервисами, в данном случае: Яндекс карты, Почта, Instagram.

### Usability тестирования:

•	Необходимо проверить простоту эксплуатации, оценить практичность структуры, обнаружить лишние элементы на сайте, либо дополнить необходимыми.

•	Следует проверить удобство навигации. Оценить комфортность доступа к меню, понятность обозначения всех кнопок и доступ к ним.

•	А также тестирование контента, в проверки входят: шрифты, маркеры ссылок, расположение абзацев, расположение различных блоков, иконок, фото и др.


### Тестирование сайта на продуктивность

Данный тип тестирования поможет мне определить работоспособность сайта, выносливость, чувствительность при разных нагрузках. Особенно важно тестировать интернет-магазины, на которых может быть одновременно большое количество пользователей. Для таких проверок я использую такой сервис как https://loaddy.com/.

Также можно провести тестирование надежности- проверка работоспособности сайта при большом количестве открытых вкладок на протяжении определенного времени (30мин). 
Проверить сценарий при отключении интернета и имитировать различные интернет соединения в отладчике хрома.

### Тестирование локализации 

Тестирование сайта можно произвести с помощью VPN для изменения местоположений, языка и форматов дат. 



# Чек-лист

| Проверка                                                      | Результат         | Комметарии       |
| :---                                                          |     :---:         | :---             |
|  **Функциональное тестирование:**                              |                     |                |
 Сайт корректно открывается и доступен.                        |  ✅           |                |
 Повторное открытие сайта выполняется без сбоев                |  ✅           |                |
 Все кнопки на сайте реагируют на нажатие.                     |  ⛔           |При нажатии на Кнопку "Совместимо с Makita LXT" никак не реагирует   |
 Все ссылки на сайте переходят на соответствующие страницы.    |  ✅                      |                |
 Отсутствуют битые ссылки.                                     |  ⛔           |При нажатии кнопки "Скачать PDF" не происходит перехода по ссылке к каталогу |
 Основные элементы сайта функционируют без нарушений.          |  ⛔           |Поле "Поиск"                |
 Проверка функциональности доступных кнопок.                   |  ⛔           |             |
 Навигационное меню работает корректно.                        |  ⛔           |При нажатии на элемент навигационного меню "Новости", нет перехода            |
 Загружаемые документы открываются правильно.                  |  ✅           |                |
 Отправка форм происходит без ошибок.                          |  ✅           |                |
 Наличие favicon                                               |  ✅           |                |
 Все данные в списках располагаются хронологически.            |  ✅           |                |
 Проверка почтовой функциональности системы.                   |  ✅           |                |
 ***Поиск:***
 Проверка существующих и не существующих результатов.          |  ✅           |                |
 Поиск с минимальным кол-вом символов                          |  ✅           |                |
Поиск при пустом поле.                                         |  ✅           |                |
 Поиск технической границы ввода                               |  ⛔           | При вводе более 10 000 символовпереход на неизвестную страницу             |
 Проверка регистра                                             |  ✅           |                |
Поиск по полному совпадению                                    |  ✅           |                |
Поиск по частичному совпадению                                 |  ✅           |                |
Поиск похожих значений (или предложение исправить опечатку, как в google)   |  ⛔           |Отсутствует                |
Ввод в поле поиска спецсимволов и отображение соответствующих результатов |  ✅           |                |
Ввод в поле поиска эмоджи и отображение соответствующих результатов |  ✅           |                |
Ввод пробела до/после параметра поиска                             |  ✅           |                |
Поиск по 1 слову/ по 2 словам                                        |  ✅           |                |
По двум словам в обратном порядке                                     |  ⛔           |Не ищет                |
Удаление параметров поиска через кнопку Очистить                   |  ✅           |                |
Удаление параметров поиска через клавишу Backspace                   |  ✅           |                |
Удаление параметров поиска через клавишу Delete                       |  ⛔           |Не удаляет                |
Проверить наличие плейсхолдера                                       |  ⛔           |Отсутствует                |
Ввести параметр поиска с неверной раскладкой клавиатуры             |  ⛔           |Отсутствует                |
  ***Поля формы "Регистрации гарантии"***
  Проверка максимальной и минимальной длины.                 |  ✅           |                |
  Диапазон допустимых символов/спецсимволов.                 |  ✅           |                |
  Обязательность к заполнению.                               | ✅           |                |
  Астериск (знак звездочки) отображается у всех обязательных полей.|  ⛔           | Отсутствует               |
  Система отображает окно ошибки при незаполненных необязательных полях.|  ✅           |                |
***Всплывающие сообщения***
Проверка всплывающего сообщения «Минимально допустимое количество символов в поле:3» в поле "Поиск", когда запрос менее 3-х символов |  ✅           |                |
 Корректное сообщение-предупреждение при пустом запросе        |  ⛔           | Отсутствует               |
 Разрешение на использование геопозиции                         |  ✅           |                |
Сообщения об ошибках ввода                                     |  ⛔           | Отсутствуют               |
 ***DevTools***
 Отсутствие ошибок в Console.    |  ⛔           | Отсутствует атрибут alt в элементе img             |
 Все стили загружаются.          |  ✅           |                |
 Картинки загружаются.           |  ⛔           | Отсутствует               |
**Тестирование безопасности**
Ссылки на пользовательские соглашения                             |  ⛔           | Отсутствует               |
Страницы, содержащие важные данные открываются через HTTPS (SSL). |  ✅           |                |
Cookie должны храниться в зашифрованном виде.                     |  ✅           |                |
У пользователя не должно быть доступа к директориям и файлам проекта |  ✅           |                |
Перейти с https на http (не защищенное соединение)       |  ⛔           | Должно появиться сообщение с предупреждением, что пользователь переходит на незащищенное соединение               |
**Интеграционное тестирование**
Проверка работы сторонних модулей, таких как карты   |  ✅           |                |
Проверка перехода на соцсети (Instagram)             |  ✅           |                |
Проверка перехода на Почту                           |  ✅           |                |
**Тестирование на совместимость**
Функциональность всех элементов, качественное отображения и единый дизайн на OC для ПК: Microsoft (ASUS F553M intel)  |  ✅           |                |
Функциональность всех элементов, качественное отображения и единый дизайн на macOS (MacBook Pro 14 m1);  |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн напланшете на ОС Android (Lenovo TB-X505F)  |  ✅           |                |	
Адаптацию к мобильным версиям на iOS (iPhone 13 mini v.17.5.1)  |  ✅           |                |
Адаптацию к мобильным версиям на ОС: Android(Samsung SM-J510FN v.7.1.1)  |  ✅           |                |
Функциональность всех элементов, качественное отображения и единый дизайн в Internet Explorer(Версия 127.0.2651.98) |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн в Firefox(v.127.0)  |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн в Chrome(v. 127.0.6533.119)  |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн в Safari(16.6))  |  ✅           |                |
**Usability тестирования**
Отсутствие орфографических и грамматических ошибок, опечатки, все страницы имеют корректные заголовки. |  ⛔           | В разделе Эксцентриковые шлифмашины "шлифмаши "             |
Дублирование текста  |  ⛔           | В разделе Зарядные ус-ва 2 раа "Параметры сети"            |
Корректное отображение иконок и изображений |  ⛔           | Отсутствуют некоторые иконки и изображения               |
Выравнивание картинок, шрифтов, текстов. |  ⛔           | Разная высота ячеек            |
Корректное отображение иконок и изображений при увеличении экрана  |  ⛔        |При увеличении на 200% 2 изображения в "шапке" накладываютсядруг на друга         |
Информативные ошибки, подсказки.|  ✅           |                |
Отступы между полями, колонками, рядами и сообщениями об ошибках. |  ⛔           | Отсутствует               |
Кнопки имеют стандартный размер, цвет. |  ✅           |                |
На сайте нет битых ссылок и изображений. |  ⛔           | Отсутствует               |
Изображение сайта при разных разрешениях экрана. |  ✅           |                |
Скролл должен появляться только тогда, когда он требуется. |  ✅           |                |
Отображение выпадающего списка.|  ⛔           | Обрезает, если "футер" находится слишком близко                |
Корректное отображение деталей при наведении на них  |  ⛔           | В поле поиска от "Крестика" остается 2 точки             |
Длинный текст скрывается под многоточие.|  ✅           |                |
Корректный выбор даты. |  ✅           |                |
Логотип ведет на главную страницу сайта. |  ✅           |                |
Наиболее подходящий под параметры поиска результат должен отображаться в самом начале  |  ⛔           | Вразнобой по всей странице подсвечивается               |
**Тестирование локализации**
Отображение времени, даты в соответствии с часовым поясом пользователя.  |  ✅           |                |
Смена языка и проверка перевода всех элементов WEB приложения исходя из выбранного языка.  |  ✅           |                |
Определение местоположения пользователя и отображение соответствующего пермишена ГЕО.  |  ✅           |                |


Баг-репорт

| **Summary**  | Second Header |
|**Project** | Content Cell  |
| **Version** | Content Cell  |
|**Priority**  | Content Cell  |
| **Description:**  | Content Cell  |
| ***Steps***  | Content Cell  |
|***Actual result***  | Content Cell  |
|***Expected result***  | Content Cell  |
| **Attachment**  | Content Cell  |

