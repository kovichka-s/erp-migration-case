# 28. Definition of Ready (DoR)

## Мета документа

Definition of Ready (DoR) визначає набір обов'язкових критеріїв, яким повинен відповідати елемент беклогу продукту (PBI / User Story), щоб бути прийнятим Scrum-командою у розробку під час Sprint Planning. DoR запобігає взяттю в робочий спринт сирих, неоднозначних чи незабезпечених вимог.

---

# Пов'язані артефакти

- [14. User Stories](14_User_Stories.md) — користувацькі історії
- [16. Acceptance Criteria](16_Acceptance_Criteria.md) — критерії прийняття
- [25. Open Questions](25_Open_Questions.md) — відкриті питання
- [27. Product Backlog](27_Product_Backlog.md) — беклог продукту
- [30. Refinement Notes](30_Refinement_Notes.md) — протоколи уточнення беклогу

---

# Чек-лист Definition of Ready (DoR)

Щоб PBI вважався **Ready** (готовим до взяття у Спринт), він повинен відповідати наступним 7 критеріям:

| № | Критерій Ready | Опис та перевірка | Відповідальний |
| --- | --- | --- | --- |
| **1** | **INVEST Compliance** | Історія є незалежною (Independent), обговорюваною (Negotiable), цінною (Valuable), оцінюваною (Estimable), маленькою (Small) та тестованою (Testable). | Business Analyst / PO |
| **2** | **Clear User Story Format** | Чітко сформульовано роль, бажану дію та бізнес-цінність: *«Як [роль], я хочу [дія], щоб [мета]»*. | Business Analyst |
| **3** | **Unambiguous Acceptance Criteria** | Критерії прийняття сформульовані та погоджені у форматі **Gherkin** (`Given-When-Then`) або у вигляді перевіряємого списку (AC). | Business Analyst / QA |
| **4** | **No Blockers / Closed Open Questions** | Усі відкриті питання (OQ) щодо цієї історії закриті (Status: Closed у `25_Open_Questions.md`). Відсутні зовнішні блоки. | Product Owner / BA |
| **5** | **Estimated in Story Points** | Команда розробки оцінила складність історії у Story Points (Planning Poker) під час Refinement. Оцінка ≤ 8 SP. | Scrum Team |
| **6** | **Dependencies Identified** | Визначено всі технічні та функціональні залежності (інші PBI, Odoo модулі, доступи). | Lead Developer / BA |
| **7** | **UX/UI & Data Specs Ready** | Якщо історія вимагає екранних форм чи звітів — макети або специфікація полів Odoo додані до картки PBI. | BA / UI Designer |

---

# Процедура перевірки DoR

1. **Перед Refinement:** Бізнес-аналітик перевіряє відповідність пунктів 1–4.
2. **Під час Refinement:** Команда розробки обговорює історію, визначає залежності (пункт 6) та оцінює у Story Points (пункт 5).
3. **На Sprint Planning:** Product Owner ставить статус **Ready** елементам, що пройшли всі 7 пунктів чек-листа. Елементи без статусу Ready у Спринт не беруться.
