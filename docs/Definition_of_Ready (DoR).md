# Definition of Ready (DoR)

## Мета

Definition of Ready визначає мінімальний набір критеріїв, за яких вимога або User Story вважається достатньо опрацьованою для передачі команді розробки та включення до Sprint.

DoR допомагає уникнути ситуацій, коли команда починає роботу з неповною, неоднозначною або непогодженою вимогою.

---

## Критерії готовності

### 1. Business Context

- Визначена Business Goal.
- Описана бізнес-потреба або проблема.
- Зрозуміло, для кого та навіщо потрібна зміна.
- Визначений очікуваний Business Value.

### 2. Scope

- Визначено, що входить у Scope.
- Визначено, що не входить у Scope.
- Виявлені основні залежності від інших процесів або систем.

### 3. Requirements

- Functional Requirements сформульовані.
- Non-functional Requirements визначені, якщо вони застосовуються.
- Business Rules описані.
- User Story сформульована зрозумілою мовою.
- Use Case створений, якщо сценарій потребує детального опису.
- Edge Cases розглянуті.
- Вимога не містить суперечностей або неоднозначних формулювань.

### 4. Acceptance Criteria

- Acceptance Criteria визначені.
- Критерії є однозначними та перевірюваними.
- За критеріями можна визначити, чи виконана вимога.

### 5. Stakeholders

- Визначені ключові Stakeholders.
- Необхідні Stakeholder Interviews проведені.
- Вимога погоджена відповідальними представниками бізнесу.
- Відомі потенційні конфлікти або різні очікування Stakeholders.

### 6. Process & Impact

- Визначено, який Business Process змінюється.
- За необхідності оновлено AS IS / TO BE.
- Виявлено вплив зміни на пов'язані процеси, ролі та системи.
- Визначені залежності та потенційні ризики.

### 7. Open Questions

- Критичні Open Questions закриті.
- Невирішені питання не блокують початок розробки.
- Припущення, які впливають на реалізацію, зафіксовані.

### 8. Technical Context

- Визначені системи та компоненти, яких стосується зміна.
- Відомі необхідні інтеграції або залежності.
- Технічні питання, які потребують рішення команди розробки, ідентифіковані.

Business Analyst не визначає технічну реалізацію, якщо це належить до відповідальності Development Team або Solution Architect.

### 9. Traceability

- Вимога має унікальний Identifier.
- Встановлений зв'язок із відповідним Epic.
- Визначений зв'язок із User Story / Use Case.
- Acceptance Criteria пов'язані з відповідною вимогою.
- За необхідності вимога включена до Requirements Traceability Matrix.

---

## Ready Checklist

Перед початком Sprint перевіряється:

- [ ] Business Goal визначена
- [ ] Business Problem зрозуміла
- [ ] Scope визначений
- [ ] Stakeholders визначені
- [ ] Необхідні інтерв'ю проведені
- [ ] Functional Requirements описані
- [ ] Non-functional Requirements визначені
- [ ] Business Rules описані
- [ ] User Story сформульована
- [ ] Use Case описаний, якщо необхідно
- [ ] Acceptance Criteria визначені
- [ ] Edge Cases розглянуті
- [ ] Залежності визначені
- [ ] Вплив зміни проаналізований
- [ ] Критичні Open Questions закриті
- [ ] Ризики та припущення зафіксовані
- [ ] Вимога має Identifier та Traceability
- [ ] Команда має достатньо інформації для оцінки та реалізації

---

## Definition of Ready Decision

### READY

Елемент може бути включений до Sprint, якщо всі критичні критерії виконані, а команда має достатньо інформації для оцінки та реалізації.

### NOT READY

Елемент не готовий до Sprint, якщо:

- відсутня ключова бізнес-вимога;
- незрозумілий очікуваний результат;
- відсутні Acceptance Criteria;
- є критичні невирішені питання;
- є суттєві залежності, які не визначені;
- вимога потребує додаткового аналізу.

У такому випадку елемент повертається на Refinement.

---

## Відповідальність

**Business Analyst**

- забезпечує повноту та зрозумілість вимог;
- координує уточнення з Stakeholders;
- підтримує актуальність документації.

**Product Owner / Business Stakeholder**

- підтверджує бізнес-потребу;
- визначає пріоритет;
- погоджує очікуваний результат.

**Development Team**

- уточнює технічні питання;
- визначає технічні залежності;
- бере участь в оцінці та підтвердженні готовності вимоги.

---

## Пов'язані артефакти

- Epic Backlog
- Product Backlog
- Stakeholder Analysis
- Stakeholder Interviews
- Business Problem Statement
- Scope Definition
- Functional Requirements
- Non-functional Requirements
- User Stories
- Use Cases
- Acceptance Criteria
- Business Rules
- Requirements Traceability Matrix
- Impact Analysis
- Open Questions
- Risk Analysis & Assumptions
- Backlog Refinement
