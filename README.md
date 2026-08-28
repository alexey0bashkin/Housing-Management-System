<div align="center">
  <h1>🏢 Информационная система для управляющей компании</h1>
  <p><strong>Курсовая работа по дисциплине «Проектный практикум»</strong></p>
  
  [![Course](https://img.shields.io/badge/Курс-4_курс-blue.svg)](https://github.com/alexey0bashkin/housing-management-system)
  [![University](https://img.shields.io/badge/РГГУ-Российский_государственный_гуманитарный_университет-red.svg)](https://rsuh.ru)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
  [![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/alexey0bashkin)
  
  <img src="docs/screenshots/main_page.png" alt="Главная страница" width="800"/>
</div>

---

## 📋 О проекте

**Разработка информационной системы для управляющей компании** — это курсовая работа, выполненная в рамках дисциплины «Проектный практикум» на 4 курсе РГГУ.

Система предназначена для автоматизации ключевых процессов управления многоквартирными домами, включая:

- 📊 Учет объектов недвижимости
- 💰 Расчет и начисление коммунальных платежей
- 🔧 Обработка заявок на ремонт и обслуживание
- 👥 Взаимодействие с жильцами через личный кабинет
- 📈 Генерация отчетности и аналитика

---

## 🎯 Цель работы

Создание информационной системы, которая будет способствовать улучшению и упрощению процессов управления объектами недвижимости, учета заявок на ремонт и контроля коммунальных платежей.

---

## 📚 Структура работы

| Глава | Содержание |
|-------|------------|
| **Глава 1** | Анализ предметной области, описание подходов к проектированию ИС, определение требований, обзор технологий и аналогов |
| **Глава 2** | Изучение и выбор инструментов CASE, проектирование БД на инфологическом и даталогическом уровнях, создание модели TO-BE |
| **Глава 3** | Разработка информационной системы: написание кода, создание интерфейса, интеграция с БД |

---

## 🛠️ Технологический стек

<div align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</div>

### Выбранные технологии

| Компонент | Технология | Обоснование |
|-----------|------------|-------------|
| **СУБД** | MySQL | Производительность, масштабируемость, безопасность |
| **Платформа** | WordPress | Гибкость, большое количество плагинов, удобство настройки |
| **Язык запросов** | SQL | Стандарт для реляционных БД, поддержка сложных запросов |

---

## 📊 Моделирование бизнес-процессов

### Модель AS-IS (как есть)

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="diagrams/as_is_context.png" width="400" alt="Контекстная диаграмма AS-IS"/>
        <p><em>Контекстная диаграмма (IDEF0) — первый уровень</em></p>
      </td>
      <td align="center">
        <img src="diagrams/as_is_decomposition.png" width="400" alt="Декомпозиция AS-IS"/>
        <p><em>Диаграмма декомпозиции (IDEF0) — второй уровень</em></p>
      </td>
    </tr>
  </table>
</div>

### Модель TO-BE (как должно быть)

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="diagrams/to_be_context.png" width="400" alt="Контекстная диаграмма TO-BE"/>
        <p><em>Модель TO-BE</em></p>
      </td>
      <td align="center">
        <img src="diagrams/to_be_decomposition.png" width="400" alt="Декомпозиция TO-BE"/>
        <p><em>Декомпозиция процессов TO-BE</em></p>
      </td>
    </tr>
  </table>
</div>

---

## 🗄️ База данных

### Инфологическая модель

<div align="center">
  <img src="diagrams/er_diagram.png" alt="ER-диаграмма" width="700"/>
</div>

### Основные сущности

| Сущность | Описание |
|----------|----------|
| `Streets` | Улицы города |
| `Houses` | Многоквартирные дома |
| `Apartments` | Квартиры |
| `Residents` | Проживающие/владельцы |
| `PrivateMeters` | Индивидуальные счетчики |
| `CommonMeters` | Общедомовые счетчики |
| `Services` | Виды коммунальных услуг |
| `Invoices` | Квитанции на оплату |
| `InvoiceDetails` | Детализация квитанций |

### UML-диаграммы

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="diagrams/class_diagram.png" width="300" alt="Диаграмма классов"/>
        <p><em>Диаграмма классов</em></p>
      </td>
      <td align="center">
        <img src="diagrams/sequence_diagram.png" width="300" alt="Диаграмма последовательности"/>
        <p><em>Диаграмма последовательности</em></p>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="diagrams/component_diagram.png" width="300" alt="Диаграмма компонентов"/>
        <p><em>Диаграмма компонентов</em></p>
      </td>
      <td align="center">
        <img src="diagrams/state_diagram.png" width="300" alt="Диаграмма состояний"/>
        <p><em>Диаграмма состояний</em></p>
      </td>
    </tr>
  </table>
</div>

---

## 💻 Функциональность системы

### Основные разделы сайта

<div align="center">
  <table>
    <tr>
      <td width="25%" align="center">
        <img src="docs/screenshots/main_page.png" width="150" alt="Главная"/>
        <p><strong>Главная</strong></p>
      </td>
      <td width="25%" align="center">
        <img src="docs/screenshots/about_page.png" width="150" alt="О компании"/>
        <p><strong>О компании</strong></p>
      </td>
      <td width="25%" align="center">
        <img src="docs/screenshots/services_page.png" width="150" alt="Услуги"/>
        <p><strong>Услуги</strong></p>
      </td>
      <td width="25%" align="center">
        <img src="docs/screenshots/news_page.png" width="150" alt="Новости"/>
        <p><strong>Новости</strong></p>
      </td>
    </tr>
  </table>
</div>

### Личный кабинет жильца

<div align="center">
  <table>
    <tr>
      <td width="33%" align="center">
        <img src="docs/screenshots/my_apartment.png" width="150" alt="Моя квартира"/>
        <p><strong>Моя квартира</strong></p>
      </td>
      <td width="33%" align="center">
        <img src="docs/screenshots/payments.png" width="150" alt="Квартплата"/>
        <p><strong>Квартплата</strong></p>
      </td>
      <td width="33%" align="center">
        <img src="docs/screenshots/meters.png" width="150" alt="Счётчики"/>
        <p><strong>Счётчики</strong></p>
      </td>
    </tr>
    <tr>
      <td width="33%" align="center">
        <img src="docs/screenshots/invoice_payment.png" width="150" alt="Оплата"/>
        <p><strong>Оплата квитанций</strong></p>
      </td>
      <td width="33%" align="center">
        <img src="docs/screenshots/requests.png" width="150" alt="Заявки"/>
        <p><strong>Заявки</strong></p>
      </td>
      <td width="33%" align="center">
        <img src="docs/screenshots/appeals.png" width="150" alt="Обращения"/>
        <p><strong>Обращения</strong></p>
      </td>
    </tr>
  </table>
</div>

---

## 📋 Техническое задание (кратко)

### Функциональные требования

1. **Регистрация пользователя**: регистрация жильцов и сотрудников
2. **Подача заявок**: онлайн-формы для ремонта и обслуживания
3. **Оплата услуг**: интеграция с платежными системами
4. **Личный кабинет**: история заявок, оплат, редактирование профиля
5. **Панель администратора**: управление заявками, создание отчетов

### Требования к безопасности

- Шифрование данных при передаче
- Защита от SQL-инъекций
- Резервное копирование данных

---

## 🗺️ Перспективы развития

- [ ] Интеграция с системами поставщиков коммунальных ресурсов
- [ ] Внедрение мобильного приложения для жильцов
- [ ] Использование интеллектуальных счетчиков (IoT)
- [ ] Модуль аналитики и прогнозирования
- [ ] Система уведомлений (SMS, email, push)
- [ ] Система лояльности для жильцов

---

## 📂 Структура репозитория
housing-management-system/
├── README.md # Описание проекта
├── docs/ # Документация
│ ├── course_work.docx # Полный текст работы
│ ├── presentation.pptx # Презентация
│ └── screenshots/ # Скриншоты
├── database/ # База данных
│ ├── schema.sql # Схема БД
│ └── er_diagram.png # ER-диаграмма
├── wordpress/ # PHP-код для WordPress
└── diagrams/ # Все диаграммы


---

## 🔧 Установка и запуск

```bash
# Клонировать репозиторий
git clone https://github.com/alexey0bashkin/housing-management-system.git

# Импорт базы данных
mysql -u root -p < database/schema.sql

# Настройка WordPress
# 1. Установите WordPress
# 2. Скопируйте PHP-файлы из папки wordpress/ в тему
# 3. Настройте подключение к БД в wp-config.php
