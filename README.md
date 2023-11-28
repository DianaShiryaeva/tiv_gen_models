# Датасет диаграм, сгенерированных нейронными сетями

### Описание
Данный проект состоит из нескольких этапов:
- Поиск различных диаграмм объектно-ориентированого, структурного, предметно-ориентированного проектирования, сгенерированных другими людьми и выложеными в сеть
- Анализ полученных результатов и промтов пользователей
- Составление собственных промптов
- Генерация диаграмм

### Нейронные сети
В данном проекте используются следующие нейронные сети
- Kandinsky 2.2
- Шедеврум
- OCTAVE
- Dream
- Bing Image Creator

### Датасет
Датасет включает в себя:
- изображения, которые удалось найти в сети. К этим изображениям прилагается csv файл "images_search.csv". Папка - images_search
- 200 изображений, сгенерированных с помощью нейронной сети Kandinski 2.2, которые отображают 4 вида диаграмм: диаграмма классов, use-case, DFD, IDEF0. Для каждого вида диаграмм - 50 изображений.
- 200 изображений, сгенерированных с помощью нейронной сети Шедеврум, которые отображают 4 вида диаграмм: диаграмма классов, use-case, DFD, IDEF0. Для каждого вида диаграмм - 50 изображений.
- 200 изображений, сгенерированных с помощью нейронной сети OCTAVE, которые отображают 4 вида диаграмм: диаграмма классов, use-case, DFD, IDEF0. Для каждого вида диаграмм - 50 изображений
- 200 изображений, сгенерированных с помощью нейронной сети Dream, которые отображают 4 вида диаграмм: диаграмма классов, use-case, DFD, IDEF0. Для каждого вида диаграмм - 50 изображений
- 200 изображений, сгенерированных с помощью нейронной сети Bing Image Creator, которые отображают 4 вида диаграмм: диаграмма классов, use-case, DFD, IDEF0. Для каждого вида диаграмм - 50 изображений

### Промпты
Таблицу с промптами можно найти в файле "list_prompts.xlsx".

| Номер  | Промпт | Диаграмма |
| ------------- | ------------- | ------------- |
| 1  | Сгенерируй диаграмму классов  | Диаграмма классов  |
| 2  | Сгенерируй class diagram  | Диаграмма классов  |
| 3  | Сгенерируй диаграмму классов на языке UML  | Диаграмма классов  |
| 4  | Сгенерируй диаграмму классов на языке UML. Классы в объектно-ориентированном моделировании представлены с тремя компонентами: в верхней части имя класса. Поля (атрибуты) класса располагаются в центральной части. Методы класса пишутся в нижней части.  | Диаграмма классов  |
| 5  | Сгенерируй диаграмму классов для информационной системы "Онлайн-магазин одежды"  | Диаграмма классов  |
| 6  | Сгенерируй диаграмму классов для информационной системы "Ветеринарная клиника"  | Диаграмма классов  |
| 7  | Сгенерируй диаграмму классов для информационной системы "Онлайн-магазин одежды". 1. Класс - Продукт. Атрибуты: название, стоимость, размер, цвет, описание 2. Класс - Заказ. Атрибуты: дата заказа, статус, общая стоимость 3. Класс - Пользователь. Атрибуты: имя, адрес доставки, контактная информация 4. Класс - Корзина. Атрибуты: список продуктов, сумма заказа 5. Класс - Оплата. Атрибуты: способ оплаты, информация о платеже 6. Класс - Доставка. Атрибуты: адрес доставки, статус доставки 7. Класс - Категория. Атрибуты: имя категории, описание 8. Класс - Производитель. Атрибуты: название, страна, специализация 9. Класс - Отзывы. Атрибуты: оценка, комментарий, дата 10. Класс - Акции и скидки. Атрибуты: описание акции, сроки, условия  | Диаграмма классов  |
| 8  | Сгенерируй диаграмму классов для информационной системы "Ветеринарная клиника". 1. Класс - Животное. Атрибуты: кличка, вид, возраст, владелец. 2. Класс - Врач. Атрибуты: имя, специализация, график работы 3. Класс - Пациент. Атрибуты: животное, дата приема, диагноз  4. Класс - Специализация. Атрибуты: название специализации, описание 5. Класс - Процедуры и услуги. Атрибуты: название, описание, стоимость.  6. Класс - Запись. Атрибуты: пациент, врач, дата, вид процедуры. 7. Класс - Лечение. Атрибуты: название лечения, рецепт, дозировка. 8. Класс - Отзывы и рейтинг. Атрибуты: оценка, отзыв, дата.  | Диаграмма классов  |
| 9  | Создайте диаграмму классов для информационной системы "Онлайн-магазин одежды". Включите основные классы: продукты, заказы, пользователи. Покажите связь между классами заказов и пользователями, учитывая, что каждый пользователь может иметь несколько заказов. Укажите основные атрибуты каждого класса, такие как название товара, стоимость, дата заказа и другие соответствующие атрибуты. Дополнительно укажите, что каждый заказ может содержать один или несколько продуктов.  | Диаграмма классов  |
| 10  | Сгенерируй диаграмму классов для информационной системы "Ветеринарная клиника". Создайте диаграмму классов для информационной системы "Ветеринарная клиника". Опишите основные классы: 'Животные', 'Врачи и персонал', 'Услуги и процедуры'. Укажите основные атрибуты и методы для каждого класса. Опишите особенности, такие как специфические характеристики каждого класса, общие особенности между классами, их взаимосвязи, а также другие особенности, которые следует учесть при генерации диаграммы классов для данной информационной системы.  | Диаграмма классов  |
| 11  | Сгенерируй диаграмму use-case | Диаграмма use-case |
| 12  | Сгенерируй диаграмму вариантов использования | Диаграмма use-case |
| 13  | Сгенерируй диаграмму use-case на языке UML  | Диаграмма use-case |
| 14  | Сгенерируй диаграмму use-case на языке UML. Для отражения use-case на диаграмме используются: рамки системы — прямоугольник с названием в верхней части и эллипсами (прецедентами) внутри. актёр — стилизованный человечек, обозначающий набор ролей пользователя. прецедент — эллипс с надписью, обозначающий выполняемые системой действия. Имя прецедента связано с непрерывным (атомарным) сценарием — конкретной последовательностью действий, иллюстрирующей поведение.  | Диаграмма use-case |
| 15  | Сгенерируй диаграмму use-case для информационной системы "Онлайн-магазин одежды"  | Диаграмма use-case |
| 16  | Сгенерируй диаграмму use-case для информационной системы "Ветеринарная клиника"  | Диаграмма use-case |
| 17  | Сгенерируй диаграмму use-case для информационной системы "Онлайн-магазин одежды". Система должна включать основные функции, такие как просмотр каталога товаров, добавление товаров в корзину, оформление заказа, аутентификация пользователей, управление аккаунтом и обработка платежей. Определите основных актеров системы и их взаимодействие с функциональными блоками. Учтите различные сценарии использования, такие как поиск товаров, оформление заказа как гость или зарегистрированный пользователь, отслеживание статуса заказа и возврат товаров. Опишите ключевые шаги и потоки данных в каждом сценарии использования.  | Диаграмма use-case |
| 18  | Сгенерируй диаграмму use-case для информационной системы "Ветеринарная клиника". Система должна поддерживать основные функции, такие как запись на прием, учет медицинских карт пациентов, выписка рецептов, администрирование расписания врачей и финансовый учет. Представьте основные актеры системы и их взаимодействие с основными функциональными блоками. Учтите основные сценарии использования, такие как прием пациента, выписка рецепта, и формирование отчетов для администрирования. Опишите основные шаги и потоки данных в каждом случае использования.  | Диаграмма use-case |
| 19  | Сгенерируй диаграмму use-case для информационной системы "Онлайн-магазин одежды", которая будет включать следующие сценарии использования: 1. Регистрация нового пользователя: включает ввод имени, адреса, контактных данных и создание пароля. 2. Вход в аккаунт: пользователь вводит свои данные для авторизации. 3. Поиск товаров: пользователь может искать товары по названию, категории, бренду или другим параметрам. 4. Просмотр товара: после поиска товара пользователь может просмотреть детальную информацию о нем, включая фотографии, описание, размер, цвет и стоимость. 5. Добавление товара в корзину: пользователь добавляет выбранный товар в корзину для дальнейшего оформления заказа. 6. Оформление заказа: пользователь выбирает способ доставки и оплаты, вводит контактные данные и подтверждает заказ. 7. Изменение или удаление товаров из корзины: пользователь может изменять количество товаров или удалять их из корзины. 8. История заказов: пользователь может просматривать историю своих заказов. 9. Личный кабинет пользователя: в личном кабинете пользователь может редактировать свои данные, управлять своими заказами, просматривать историю заказов и оставлять отзывы о товарах. 10. Обратная связь: пользователь может оставлять отзывы о приобретенных товарах и задавать вопросы службе поддержки. 11. Подписка на рассылку: пользователь подписывается на рассылку новостей и акций магазина.  | Диаграмма use-case |
| 20  | Сгенерируй диаграмму use-case для информационной системы "Ветеринарная клиника". Диаграмма должна охватывать все основные сценарии использования системы, включая: 1. Регистрацию новых клиентов и животных. 2. Запись на прием к ветеринару. 3. Управление информацией о пациентах (история болезни, назначения, результаты анализов). 4. Ведение базы данных о животных (идентификационные данные, информация о владельце, медицинские данные). 5. Формирование отчетов о работе клиники (статистика посещений, финансовые отчеты, анализ эффективности работы сотрудников). 6. Обеспечение безопасности данных и конфиденциальности информации о клиентах. 7. Возможность удаленного доступа к системе для сотрудников клиники с разных устройств и в разных браузерах. 8. Интеграцию с другими системами и сервисами (например, с системами оплаты или электронной почтой). 9. Возможность обновления и расширения функционала системы в будущем.  | Диаграмма use-case |
| 21 | Сгенерируй диаграмму потоков данных | Диаграмма DFD |
| 22 | Сгенерируй диаграмму DFD | Диаграмма DFD |
| 23 | Сгенерируй диаграмму DFD на основе методологии SADT | Диаграмма DFD |
| 24 | Сгенерируй диаграмму DFD. В DFD входят процессы: круги или прямоугольники, представляющие операции в системе; потоков данных: стрелки, показывающие перемещение данных между процессами, хранилищами и внешними сущностями; хранилища данных: параллелограммы, отображающие места хранения данных в системе; внешние сущности: прямоугольники, представляющие внешние источники/назначения данных для систем | Диаграмма DFD |
| 25 | Сгенерируй диаграмму DFD для информационной системы "Онлайн-магазин одежды" | Диаграмма DFD |
| 26 | Сгенерируй диаграмму DFD для информационной системы "Ветеринарная клиника" | Диаграмма DFD |
| 27 | Создайте DFD для информационной системы "Онлайн-магазин одежды". Включите в диаграмму функциональные блоки, описывающие процессы системы, а также укажите стрелки (потоки данных) между этими функциями. Также необходимо указать взаимодействие системы с внешними сущностями | Диаграмма DFD |
| 28 | Создайте DFD для информационной системы "Ветеринарная клиника". Включите в диаграмму функциональные блоки, описывающие процессы системы, а также укажите стрелки (потоки данных) между этими функциями. Также необходимо указать взаимодействие системы с внешними сущностями | Диаграмма DFD |
| 29 | Создайте диаграмму DFD для информационной системы "Онлайн-магазин одежды". Необходимо включить основные функции системы: оформление заказа, управление складом, обработка платежей, учет клиентской информации и взаимодействие с поставщиками. Укажите потоки данных между этими функциями, включая информацию о заказах, товарах, клиентах и финансовых транзакциях. Также укажите на взаимодействие системы с внешними сущностями: клиенты и поставщики, и на потоки данных между ними и системой | Диаграмма DFD |
| 30 | Создайте диаграмму потоков данных (DFD) для информационной системы "Ветеринарная клиника". Включите основные функции системы: запись на прием, ведение медицинских карт, назначение лечения, управление запасами лекарств и оборудования, обработка платежей. Опишите потоки данных между этими функциями, включая информацию о пациентах, медицинских услугах, лекарствах, финансовых транзакциях и связи с внешними сторонами, такими как клиенты и поставщики | Диаграмма DFD |
| 31 | Сгенерируй диаграмму "как есть" и "как будет" на основе методологии функциональнного моделирования | Диаграмма IDEF0 |
| 32 | Сгенерируй диаграмму IDEF0 | Диаграмма IDEF0 |
| 33 | Сгенерируй диаграмму IDEF0 на основе методологии SADT | Диаграмма IDEF0 |
| 34 | Сгенерируй диаграмму IDEF0. В IDEF0 входят блоки функций: прямоугольники, отображающие функциональные элементы системы; стрелки и потоки: обозначают потоки данных или управления между блоками функций. У каждого функционального блока есть входящие стрелки, которые ставят задачу, исходящие, которые показывают результат деятельности, стрелки контроля, показывают управляющие ресурсы, и стрелки механизмов, показывают, что необходимо для работы. | Диаграмма IDEF0 |
| 35 | Сгенерируй диаграмму IDEF0 для информационной системы "Онлайн-магазин одежды" | Диаграмма IDEF0 |
| 36 | Сгенерируй диаграмму IDEF0 для инфомрационной системы "Ветеринарная клиника" | Диаграмма IDEF0 |
| 37 | Сгенерируй IDEF0 для информационной системы "Онлайн-магазин одежды". Опишите основные функции системы, укажите иерархию этих функций, а также связи между ними, чтобы полноценно отразить структуру и функциональность системы. Опишите что необходимо для управления и выполнения каждой функции системы | Диаграмма IDEF0 |
| 38 | Сгенерируй IDEF0 для информационной системы "Ветеринарная клиника". Опишите основные функции системы, укажите иерархию этих функций, а также связи между ними, чтобы полноценно отразить структуру и функциональность системы. Опишите что необходимо для управления и выполнения каждой функции системы | Диаграмма IDEF0 |
| 39 | Создайте диаграмму IDEF0 для информационной системы "Онлайн-магазин одежды". Отобразите основные функциональные блоки: управление каталогом товаров, обработка заказов, обработка платежей, управление складом, обратная связь с клиентами и обновление информации о товарах. Покажите взаимодействие между этими функциям. Укажите стрелки для выполнения процессов: клиенты, менеджеры, продавцы. Также укажите стрелки для управления процессами: закон о защите прав потребителей, закон купли-продажи | Диаграмма IDEF0 |
| 40 | Создайте диаграмму IDEF0 для информационной системы "Ветеринарная клиника". Отобразите на диаграмме основные функциональные блоки: запись на прием, регистрация пациентов, медицинский осмотр, диагностическое тестирование, планирование лечения и обновление медицинских данных. Отобразите взаимодействие между этими функциями. Укажите необходимые стрелки для выполнения процессов: клиент, ветеринар. Также укажите стрелки для управления процессов: протокол медицинского обслуживания, санитарные стандарты. | Диаграмма IDEF0 |

