# parkingProject
 
**Техническое задание на разработку приложения для аренды парковочных мест**

# **1. Введение**

## **1.1. Описание проекта**

Приложение предназначено для аренды частных парковочных мест, предоставляя пользователям удобную платформу для поиска, бронирования и оплаты парковки. Оно включает три модуля:

- **Клиентское приложение** – для поиска и бронирования парковок.
- **Приложение арендодателя** – для управления парковочными местами.
- **Административный модуль** – для управления платформой, обеспечения безопасности, контроля со стороны администрации подземных и публичных парковок а также праграмма для генерации одноразовых ключей доступа QR кодов для получения доступа на паковку.

## **1.2. Цели проекта**

- Обеспечение удобного поиска и бронирования парковочных мест.
- Автоматизация процесса аренды.
- Обеспечение безопасных и прозрачных расчетов.
- Монетизация через комиссию с аренды.

# **2. Функциональные требования**

## **2.1. Функции клиентского приложения**

### **Регистрация и аутентификация**

- Регистрация по email/номеру телефона.
- Авторизация с помощью логина и пароля.
- Альтернативная авторизация с помощью входа через портнерскую платформу или сеть (Google account, apple ID, Yandex account).
- Подтверждение учетной записи через SMS/почту.
- Привязка одного либо несколько автомобилей к профилю.
- Создание учетной записи.
- Подтверждение легального возраста в 18 лет.
- Проверка водительских прав для получения 

### **Поиск и бронирование**

- Карта с отмеченными парковками.
- Поиск вариантор через поисковик локации и фильтр по дате и времяни.
- Возможность сохранить понравившиеся варианты в закладки
- Фильтрация по цене, расстоянию, доступности, наличию зарядки для электромобилей.
- Выбор парковки и бронирование.
- Оплата через встроенную платежную систему.

### **Управление бронированием**

- Просмотр текущих и завершенных бронирований.
- Продление аренды.
- Отмена бронирования (по условиям аренды).
- Генерация QR-кода для въезда/выезда на парковки доступные толко с ключа.

### **Отзывы и поддержка**

- Оценка парковки.
- Оставление комментариев.
- Чат с арендодателем.
- Поддержка через чат-бота или операторов.

## **2.2. Функции приложения арендодателя**

### **Регистрация и управление парковочными местами**

- Регистрация арендодателя.
- Подтверждение возроста через проверки прав.
- Размещение информации (адрес, фото, цена, доступность, описание).
- Подтвердение наличие камер видео наблюлдения если это частная парковка.
- Управление бронированиями и изменениями.
- Возможность в отказе бронирования.
- Возможность в вызове эвакуатора за счет клиента если то нарушил договор.

### **Финансовые операции/инструменты**

- Настройка цен, скидок и минимального/максимального срока аренды.
- Гибкие тарифные планы (например, разные цены на выходные и будни).
- Возможность предложить дополнительные услуги (зарядка авто, мойка авто собственно ручно).
- Календарь для управления доступностью порковки.
- Получение платежей и финансовая аналитика.
- Настройки выплат.
- Настройки и доступ к личной информации о налогах - поддержка налоговых требований.
- Автоматическое получение выплат на банковский счет или PayPal.
- Автоматические уведомления на телефон о пополнение или сниятиясо сщета.

### **Связь с клиентами**

- Обмен сообщениями с потенциальными арендаторами через встроенный чат.
- Просмотр отзывов и рейтингов гостей перед подтверждением бронирования.
- Автоматизированные сообщения (например, инструкции по заезду).
- Уведомления о бронированиях.

### **Управление ронированиями**

- Возможность устанавливать правила отмены бронирования.
- Опция мгновенного бронирования (без необходимости одобрения хостом).
- Фильтр гостей (можно установить ограничения, например, принимать только гостей с хорошими отзывами).

### **Защита и поддержка**

- Гарантия AirCover: преложение предоставляет страховое покрытие на случай повреждения имущества или экстренных ситуаций.
- Поддержка 24/7: служба поддержки помогает решать проблемы с гостями и бронированиями.
- Проверка гостей: система безопасности приложения анализирует бронирования и может предупреждать о возможных рисках.

## **2.3. Функции административного модуля**

### **Управление пользователями (гостями и хостами)**

- Мониторинг активности пользователей.
- Верификация личностей пользователей (сканирование документов, подтверждение номера телефона и электронной почты).
- Проверка и модерация аккаунтов (например, блокировка или временное приостановление учетных записей при нарушениях).
- Управление спорными ситуациями - обзор жалоб и споров между пользователями.
- Безопасность и контроль (сканирование QR-кодов, мониторинг отзывов и жалоб).
- Управление комиссией сервиса.

### **Управление объявлениями и контентом**

- Модерация новых объявлений (проверка соответствия стандартам приложения).
- Удаление или скрытие объявлений, нарушающих правила (например, мошеннические или небезопасные объекты).
- Обзор фотографий и описаний, предложенных хостами, с возможностью их редактирования или удаления.
- Автоматизированные и ручные уведомления пользователям (предупреждения, рекомендации, изменения в политике).

### **Финансовый контроль и платежи**

- Мониторинг транзакций (выплаты хостам, списания с гостей, возвраты средств).
- Управление налогами и комиссиями.
- Обзор финансовых отчетов и движение средств по платформе.

### **Безопасность и разрешение споров**

- Обзор жалоб на гостей и хостов.
- Управление случаями мошенничества и подозрительных действий (например, несколько учетных записей, попытки обхода комиссии).
- Вмешательство в конфликты (например, споры о возмещении ущерба, отмены бронирований по форс-мажорным причинам).

### **Аналитика и бизнес-управление**

- Сбор статистики по бронированиям, доходам, активности пользователей.
- Анализ спроса в различных регионах (популярность определенных мест, сезонные колебания).
- Оптимизация рекламных кампаний и партнерских программ.
- Управление блогом и разделом помощи (статьи с советами для хостов и гостей).

### **Безопасность платформы**

- Мониторинг подозрительных действий (подозрительные IP-адреса, массовые создания аккаунтов).
- Защита от DDoS-атак и киберугроз.
- Внедрение и управление алгоритмами AI для выявления подозрительной активности.

### *весь этот модуль работает за кулисами и обеспечивает бесперебойную работу всей платформы, предотвращая мошенничество, управляя платежами и обеспечивая комфортное взаимодействие между гостями и хостами.*



# **3. Технические требования**

## **3.1. Платформы**

- iOS (Swift, SwiftUI).
- Android (Java/Kotlin).
- Backend (Flask/Python).
- База данных (MongoDB).

## **3.2. Безопасность**

- Шифрование пользовательских данных.
- Защита платежных транзакций.
- Двухфакторная аутентификация.

# **4. Интерфейс и дизайн**

- Разработка удобного UI/UX по макетам из Figma.
- Адаптация под мобильные устройства.
- Поддержка тёмной и светлой темы.

# **5. Развитие проекта**

- Внедрение системы динамического ценообразования.
- Интеграция с картами (Google Maps, Apple Maps).
- Разработка web-версии.
- Расширение географии работы сервиса.

