# Sprint Planning

## Мета

Sprint Planning визначає, які елементи Product Backlog команда планує виконати протягом Sprint, який Business Value має бути отриманий та як робота буде організована.

---

## Sprint 1

**Sprint Goal:**  
Забезпечити базовий наскрізний процес обробки замовлення пелет — від перевірки наявності продукції до її резервування та підготовки до відвантаження.

**Тривалість:** 2 тижні

**Учасники:**

- Product Owner
- Business Analyst
- Development Team
- QA
- представники Sales, Warehouse, Logistics та Finance за потреби

---

## Sprint Goal

У межах Sprint команда має реалізувати та перевірити основний сценарій:

**Перевірка наявності → Створення замовлення → Підтвердження оплати → Резервування → Підготовка до відвантаження**

---

# Sprint Backlog

| ID | Product Backlog Item | Priority | Estimate | Status |
|---|---|---|---|---|
| PB-01 | Перегляд актуального залишку продукції | High |  | Planned |
| PB-02 | Перегляд прогнозної дати готовності | High |  | Planned |
| PB-03 | Перевірка доступної кількості продукції | High |  | Planned |
| PB-04 | Створення замовлення клієнта | High |  | Planned |
| PB-05 | Резервування продукції після підтвердження оплати | High |  | Planned |
| PB-10 | Передача інформації про резервування складу | High |  | Planned |
| PB-18 | Підтвердження отримання оплати | High |  | Planned |
| PB-20 | Контроль можливості відвантаження після підтвердження оплати | High |  | Planned |

---

# Sprint Scope

## In Scope

- перевірка доступності продукції;
- відображення залишків;
- відображення прогнозу виробництва;
- створення замовлення;
- підтвердження оплати;
- резервування продукції;
- передача інформації на склад;
- контроль готовності замовлення до відвантаження.

## Out of Scope

- повна автоматизація доставки;
- вибір перевізника;
- розрахунок вартості доставки;
- підтвердження доставки;
- KPI та управлінська звітність;
- зміни виробничого процесу.

---

# Preparation Before Sprint

Перед початком Sprint перевіряється відповідність елементів **Definition of Ready**:

- [ ] Business Goal визначена.
- [ ] Scope визначений.
- [ ] User Story сформульована.
- [ ] Functional Requirements описані.
- [ ] Acceptance Criteria визначені.
- [ ] Business Rules визначені.
- [ ] Залежності визначені.
- [ ] Critical Open Questions закриті.
- [ ] Елементи можуть бути оцінені командою.

---

# Sprint Planning Activities

### 1. Review Product Backlog

Команда переглядає пріоритетні елементи Product Backlog.

### 2. Clarification

Business Analyst пояснює:

- Business Context;
- Business Requirements;
- User Stories;
- Business Rules;
- Acceptance Criteria;
- очікуваний Business Value.

### 3. Dependency Review

Визначаються залежності між:

- задачами;
- командами;
- системами;
- даними;
- зовнішніми учасниками процесу.

### 4. Estimation

Development Team оцінює обсяг роботи та визначає, які елементи можуть бути виконані протягом Sprint.

### 5. Sprint Commitment

Команда формує Sprint Backlog відповідно до доступної capacity та Sprint Goal.

---

# Expected Sprint Outcome

До завершення Sprint має бути доступний перевірений наскрізний сценарій:

1. Sales Manager отримує запит клієнта.
2. Перевіряє доступну кількість продукції.
3. Перевіряє прогнозну дату готовності.
4. Створює замовлення.
5. Finance підтверджує оплату.
6. Замовлення переходить до резервування.
7. Продукція резервується.
8. Warehouse отримує інформацію про необхідність підготовки продукції.
9. Замовлення готове до наступного етапу відвантаження.

---

# Definition of Done

Sprint Item може бути визнаний **Done**, якщо:

- реалізація завершена;
- Acceptance Criteria виконані;
- необхідне тестування пройдено;
- критичні дефекти відсутні;
- необхідна документація оновлена;
- результат відповідає погодженим вимогам.

---

# Sprint Review

Після завершення Sprint команда демонструє реалізовану функціональність Stakeholders та Product Owner.

Отриманий Feedback використовується для:

- уточнення Product Backlog;
- створення нових User Stories;
- зміни пріоритетів;
- формування наступного Sprint.

---

# Sprint Retrospective

Команда аналізує:

- що працювало добре;
- які проблеми виникли;
- що можна покращити;
- які Action Items необхідно виконати в наступному Sprint.

---

## Пов'язані артефакти

- Epic Backlog
- Product Backlog
- Definition of Ready
- Definition of Done
- User Stories
- Functional Requirements
- Acceptance Criteria
- Business Rules
- Requirements Traceability Matrix
- UAT Plan
