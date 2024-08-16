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
   
5.	Интеграционное тестирование

6.	Тестирование сайта на продуктивность.

   ### Функциональное тестирование 

Проверяю работоспособность всех опций на сайте.

•	тестирование ссылок и проверка навигации сайта (проверяю ссылки не только на работоспособность, но и корректность перехода).

•	тестирование товаров ( наличие, своевременное обновление данных).

•	тестирование поисковой строки.

•	проверка пользовательских форм  (корректное заполнение и распознавание необходимых символов, выведение ошибок при неправильном заполнении, обязательные/необязательные поля, коментарии) 

Для функционального тестирования сайта я пройду такие вариации проверок как:

1.	Ad-hoc проверка - быстрая проверка, ориентированная на быстрое ознакомление с программным обеспечением без первичной подготовки, по принципу использования сайта конечным пользователем, анализ ясности в использовании главных функций и навигации по сайту.

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

**Затем при обнаружении багов необходимо определение степени важности дефектов**

Важность дефекта (Severity) требуется для правильной оценки степени влияния дефекта на корректность выполнения операций конечным пользователем.
Различают следующуе степени важности дефектов:
Наиболее распространена пятиуровневая система критичности:

S1 Блокирующий (Blocker)

S2 Критический (Critical)

S3 Значительный (Major) 

S4 Незначительный (Minor)

S5 Тривиальный (Trivial)

**А также определение приоритета дефектов**

Приоритет дефекта определяется, чтобы правильно оценить, на сколько срочно требуется исправление дефекта.

Приоритет дефекта:

P1 Высокий (High)

P2 Средний (Medium)

P3 Низкий (Low)

# Чек-лист

| Проверка                                                      | Результат         | Комметарии       |
| :---                                                          |     :---:         | :---             |
|  **Функциональное тестирование:**                              |                     |                |
 Сайт корректно открывается и доступен.                        |  ✅           |                |
 Повторное открытие сайта выполняется без сбоев                |  ✅           |                |
 Все кнопки на сайте реагируют на нажатие.                     |  ⛔           |При нажатии на Кнопку "Совместимо с Makita LXT" никак не реагирует   |
 Все ссылки на сайте переходят на соответствующие страницы.    |  ✅                      |                |
 Отсутствуют битые ссылки.                                     |  ⛔           |При нажатии кнопки "Скачать PDF" не происходит перехода по ссылке к каталогу |
 Основные элементы сайта функционируют без нарушений.          |  ⛔           |Поле "Поиск" описано ниже                |
 Проверка функциональности доступных кнопок.                   |  ⛔           |      Описано в других разделах       |
 Навигационное меню работает корректно.                        |  ⛔           |При нажатии на элемент навигационного меню "Новости", не происходит переход , зависание анимации подчеркивания            |
 Загружаемые документы открываются правильно.                  |  ✅           |                |
 Отправка форм происходит без ошибок.                          |  ✅           |                |
 Наличие favicon                                               |  ✅           |                |
 Все данные в списках располагаются хронологически.            |  ✅           |                |
 Проверка почтовой функциональности системы.                   |  ✅           |                |
 ***Поиск:***
 Проверка существующих и не существующих результатов.          |  ✅           |                |
 Поиск с минимальным кол-вом символов                          |  ✅           |                |
Поиск при пустом поле.                                         |  ✅           |                |
 Поиск технической границы ввода                               |  ⛔           | При вводе более 10 000 символов, происходит переход на неизвестную страницу, описано в Баг-репорте             |
 Проверка регистра                                             |  ✅           |                |
Поиск по полному совпадению                                    |  ✅           |                |
Поиск по частичному совпадению                                 |  ✅           |                |
Поиск похожих значений (или предложение исправить опечатку, как в google)   |  ⛔           |Отсутствует                |
Ввод в поле поиска спецсимволов и отображение соответствующих результатов |  ✅           |                |
Ввод в поле поиска эмоджи и отображение соответствующих результатов |  ✅           |                |
Ввод пробела до/после параметра поиска                             |  ✅           |                |
Поиск по 1 слову/ по 2 словам                                        |  ✅           |                |
Поиск по двум словам в обратном порядке                              |  ⛔           |Поиск не осуществляется                |
Удаление параметров поиска через кнопку Очистить                     |  ✅           |                |
Удаление параметров поиска через клавишу Backspace                   |  ✅           |                |
Удаление параметров поиска через клавишу Delete                       |  ⛔           |Удаление не происходит                |
Проверить наличие плейсхолдера                                       |  ⛔           |Отсутствует                |
Поиск при неверной раскладке клавиатуры                            |  ⛔           |Отсутствует                |
  ***Поля формы "Регистрации гарантии"***
  Проверка максимальной и минимальной длины.                 |  ✅           |                |
  Диапазон допустимых символов/спецсимволов.                 |  ✅           |                |
  Обязательность к заполнению.                               | ✅           |                |
  Астериск (знак звездочки) отображается у всех обязательных полей.|  ⛔           | Отсутствует               |
  Система отображает окно ошибки при незаполненных необязательных полях.|  ✅           |                |
***Всплывающие сообщения***
Проверка всплывающего сообщения «Минимально допустимое количество символов в поле:3» в поле "Поиск", когда запрос менее 3-х символов |  ✅           |                |
 Корректное сообщение-предупреждение при пустом запросе        |  ⛔           | При поиске пустого запроса, сообщение не появляется                |
 Разрешение на использование геопозиции                         |  ✅           |                |
Сообщения об ошибках ввода                                     |  ⛔           | Отсутствуют               |
 ***DevTools***
 Отсутствие ошибок в Console.    |  ⛔           |    Отсутствует путь к некоторым изображениям       |
 Все стили загружаются.          |  ✅           |                |
 Картинки загружаются.           |  ⛔           | Отсутствует               |
**Тестирование безопасности**
Ссылки на пользовательские соглашения                             |  ⛔           | Отсутствуют               |
Страницы, содержащие важные данные открываются через HTTPS (SSL). |  ✅           |                |
Cookie должны храниться в зашифрованном виде.                     |  ✅           |                |
У пользователя не должно быть доступа к директориям и файлам проекта |  ✅           |                |
Перейти с https на http (не защищенное соединение)       |  ⛔      | Должно появиться сообщение с предупреждением, что пользователь переходит на незащищенное соединение   |
**Интеграционное тестирование**
Проверка работы сторонних модулей, таких как карты   |  ✅           |                |
Проверка перехода на соцсети (Instagram)             |  ✅           |                |
Проверка перехода на Почту                           |  ✅           |                |
**Тестирование на совместимость**
Функциональность всех элементов, качественное отображения и единый дизайн на OC для ПК: Microsoft (ASUS F553M intel)  |  ✅           |                |
Функциональность всех элементов, качественное отображения и единый дизайн на macOS (MacBook Pro 14 m1);  |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн напланшете на ОС Android (Lenovo TB-X505F)     |  ⛔            |      Всплывающее окно раздела "Продукции" меню навигации не открывается при нажатии на галочку, а сразу переходит к Каталогу          |
Адаптацию к мобильным версиям на iOS (iPhone 13 mini v.17.5.1)  |  ⛔            |      Всплывающее окно раздела "Продукции" меню навигации не открывается при нажатии на галочку, а сразу переходит к Каталогу          |
Адаптацию к мобильным версиям на ОС: Android(Samsung SM-J510FN v.7.1.1)  |  ⛔    |   Всплывающее окно раздела "Продукции" меню навигации не открывается при нажатии на галочку, а сразу переходит к Каталогу  |
Функциональность всех элементов, качественное отображения и единый дизайн в Internet Explorer(Версия 127.0.2651.98) |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн в Firefox(v.127.0)  |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн в Chrome(v. 127.0.6533.119)  |  ✅           |                |
 Функциональность всех элементов, качественное отображения и единый дизайн в Safari(16.6))  |  ✅           |                |
** Тестирование удобства использования**
Отсутствие орфографических и грамматических ошибок, опечатки, все страницы имеют корректные заголовки. |  ⛔           | В разделе Эксцентриковые шлифмашины в обоих вариантах карточек товара находится опечатка "шлифмаши"             |
Дублирование текста  |  ⛔           | В разделе Аккумуляторы и зарядные устройства в карточке Зарядное устройство FC 2120-1 дублируюется "Параметры сети"            |
Корректное отображение иконок  |  ⛔           | Отсутствуют иконки разделов: Эксцентриковые шлифмашины, Пылесосы, Клеевые пистолеты, Гвоздезабивные пистолеты  (Приложение №1)       |
Корректное отображение изображений |  ⛔           | Отсутствуют некоторые изображения карточек товара, описано в Баг-репорте              |
Выравнивание картинок, шрифтов, текстов. |  ⛔           | Разная высота ячеек (Приложение № 2)             |
Корректное отображение иконок и изображений при увеличении экрана  |  ⛔        |При увеличении на 200% 2 изображения в "шапке" накладываются друг на друга (Приложение № 3)        |
Информативные ошибки, подсказки.|  ✅           |                |
Отступы между полями, колонками, рядами и сообщениями об ошибках. |  ✅           |                |
Кнопки имеют стандартный размер, цвет. |  ✅           |                |
Проверка изображения сайта при разных разрешениях экрана. |  ✅           |                |
Скролл должен появляться только тогда, когда он требуется. |  ✅           |                |
Отображение выпадающего списка.|  ⛔           | Обрезает, если "футер" находится слишком близко , описано в Баг-репорте               |
Корректное отображение деталей при наведении на них  |  ⛔           | В поле поиска, после введения запроса и при многократном наведении на "Крестик" от "Крестика" остается 2 точки  (Приложение №4 )          |
Длинный текст скрывается под многоточие.|  ✅           |                |
Корректный выбор даты. |  ✅           |                |
Логотип ведет на главную страницу сайта. |  ✅           |                |
Наиболее подходящий под параметры поиска результат должен отображаться в самом начале  |  ⛔           | При частичном вводе, результатыотображаются все и лишь вразнобой по всей странице подсвечиваются нужные              |
**Тестирование продуктивности** 
Нагрузочное  с помощью сервиса https://loaddy.com/. |  ⛔          |       Приложение №5         |
Тестирование при большом количестве открытых вкладок на протяжении  (30мин). |  ✅           |                |
Проверка сценариев при отключении интернета и имитировать различные интернет соединения в отладчике хрома. |  ✅           |                |
**Тестирование локализации**
Отображение времени, даты в соответствии с часовым поясом пользователя.  |  ✅           |                |
Смена языка и проверка перевода всех элементов WEB приложения исходя из выбранного языка.  |  ✅           |                |
Определение местоположения пользователя и отображение соответствующего пермишена ГЕО.  |  ✅           |                |


# Баг-репорт

| **Summary**  | Отсутствие на странице Каталога некоторых изображений продукции магазина  |
| ------------- | ------------- |
|**Project** | https://wortex.by/  |
| **Environment** | Microsoft (ASUS F553M intel) Chrome (v. 127.0.6533.119)|
|**Severity**  | Major  |
|**Priority**  | Medium |
| **Description:**  |   |
| ***Steps***  | 1. Открыть сайт 2. Перейти в навигационном меню в Раздел "Продукция"|
|***Actual result***  | На данных моделях отсутствует изображение: Аккум. дрель-шуруповерт BD 2030-1 DLi/Аккум. воздуходувка BB 2536 D/Аккум. секатор CBS 2535-1/Аккум. цепная пила CEC 3018/Аккум. газонокосилка CLM 3336/Аккум. газонокосилка CLM 3836/Аккум. краскораспылитель CPS 1808/Аккум. краскораспылитель CPS 1810/Аккум. культиватор CRC 3036/Аккум. опрыскиватель KS 1680-1 Li/Аккум. триммер TB 3018/Аккум. триммер TB 3018 AT/Аккум. триммер TB 3018-1/Аккум. триммер TB 3036/Аккум. пылесос CVC 1860/ Аккум. Лобзик CJS 8030 |
|***Expected result***  | Рядом с каждым описанием продукта отображается его изображение |
| **Attachment**  | ![np-4](https://github.com/user-attachments/assets/84dc92ff-3ba6-42d1-97a4-7be37c437f07)|


| **Summary**  | Обрезание списка продукции каталога всплывающего окна, когда футер находится в середине сайта и закрывает его   |
| ------------- | ------------- |
|**Project** | https://wortex.by/  |
| **Environment** | Microsoft (ASUS F553M intel) Chrome (v. 127.0.6533.119)|
|**Severity**  | Minor  |
|**Priority**  | Medium |
| **Description:**  |   |
| ***Steps***  | 1. Открыть сайт 2.Ввести в поле "Поиск" 2 любых символа 3.Навести курсор на всплывающее навигационное меню "Продукции" |
|***Actual result***  | Меню  обрезается футером, не все элементы списка видны |
|***Expected result***  |Меню открывается полностью, все элементы списка видны |
| **Attachment**  |  ![np-6](https://github.com/user-attachments/assets/3817da46-368b-4aec-934a-969f8639b1ec) |


| **Summary**  | Переход на неизвестную страницу при наборе символов более 10000 в поле поиска  |
| ------------- | ------------- |
|**Project** | https://wortex.by/  |
| **Environment** | Microsoft (ASUS F553M intel) Chrome (v. 127.0.6533.119)|
|**Severity**  | Trivial  |
|**Priority**  | Medium |
| **Description:**  |   |
| ***Steps***  | 1. Открыть сайт 2. Ввести в поле поиска более 10000 символов|
|***Actual result***  | Отображение сообщения на странице сайта "Ничего не нашли. Попробуйте найти через Каталог или ввести другой поисковой запрос" |
|***Expected result***  | Переход на неизвесную страницу с другим сообщением. |
| **Attachment**  |   ![np-2](https://github.com/user-attachments/assets/caea1f99-826d-41ad-9f37-791dd373b1ca)|


  ## Приложения
**Приложение № 1**
![ТЗ-1](https://github.com/user-attachments/assets/c4cecf9d-3580-427c-8449-f3bc6067e50f)

**Приложение № 2**
![прил 2](https://github.com/user-attachments/assets/bb545ee7-fb31-4530-8056-5b10f24ab1c5)

**Приложение № 3**
![прил3](https://github.com/user-attachments/assets/e32cde30-a5c0-4c82-aa3b-c4458f765ad3)

**Приложение № 4**
![прил4](https://github.com/user-attachments/assets/5fffe1c4-eada-49b8-9801-1d5b01455fc9)

**Приложение № 5**
![img png](https://github.com/user-attachments/assets/64b19c58-17c6-4f5e-a90f-5228b2b1c5ae)

## Дополнительно:

- При просмотре кода была обнаружена Форма обратной связи, но она была задизейблена. При проверке выяснилось, что форма не отправляет запрос на сервер.
- Для оптимизации Seo , а именно для высокого ранжирования сайта интернет-магазина в поисковой выдаче, для формирования развернутого сниппета, для повышения кликабельности сайта в поисковиках нужно правильно сформировать теги и метатеги сайта https://wortex.by/, так как метатеги отсутствуют и некоторых тегов не хватает, как например alt в элементе img
