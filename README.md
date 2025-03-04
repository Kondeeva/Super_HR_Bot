### # Super_HR_Bot

Сслылка на проект: https://t.me/Super_HR2025_bot



#### **Описание проекта**
Super_HR_Bot — это инновационный HR-ассистент, созданный для автоматизации и оптимизации процессов подбора персонала. Бот способен эффективно взаимодействовать с кандидатами и рекрутерами, предоставляя профессиональные консультации, анализируя резюме, готовя вопросы для интервью, планируя встречи и составляя итоговые отчеты для руководителей.

---

## **Функционал**

### 1. **Осмысленное ведение диалога с помощью нейросети**
   - Super_HR_Bot использует передовые технологии искусственного интеллекта для понимания контекста разговора и предоставления релевантных ответов.
   - Бот может вести естественные диалоги с пользователями, адаптируясь к их запросам и потребностям.
   - Поддерживает как структурированные, так и свободные форматы общения.

### 2. **Ответы на вопросы по базе знаний**
   - Бот имеет доступ к обширной базе знаний, созданной с помощью Qwen, которая содержит информацию о различных аспектах HR-процессов, таких как:
     - Оценка резюме.
     - Подготовка вопросов для интервью.
     - Анализ софт- и хард-скиллов.
     - Рекомендации по культурному соответствию.
   - Пользователи могут задавать вопросы по любой теме, связанной с подбором персонала, и получать точные и актуальные ответы.

### 3. **Оценка резюме на соответствие вакансии**
   - Super_HR_Bot анализирует резюме кандидата относительно требований конкретной вакансии.
   - Оценка включает:
     - Ключевые навыки (хард-скиллы).
     - Опыт работы и его релевантность.
     - Образование.
     - Софт-скиллы.
     - Дополнительные факторы (например, географическое расположение, уровень английского языка и т.д.).
   - По результатам анализа бот выдает оценку в баллах (например, из 10) и предоставляет детальный отчет о сильных и слабых сторонах кандидата.

### 4. **Запись на телефонное/онлайн интервью и добавление встречи в Google Календарь**
   - Super_HR_Bot интегрирован с Google Календарем, что позволяет автоматически планировать телефонные или онлайн интервью с кандидатами.
   - Процесс записи выглядит следующим образом:
     1. Кандидат выбирает удобное время для интервью (телефонного или онлайн).
     2. Бот проверяет доступность расписания и подтверждает встречу.
     3. Информация о встрече автоматически добавляется в Google Календарь как для рекрутера, так и для кандидата.
   - Это значительно упрощает процесс координации и минимизирует вероятность ошибок.

### 5. **Итоговое саммари для заказчика (руководителя)**
   - После проведения интервью бот составляет подробное итоговое саммари для руководителя, которое включает:
     - Краткое описание общего уровня соответствия кандидата требованиям.
     - Ответы на ключевые вопросы интервью.
     - Оценку мотивации и культуры общения.
     - Рекомендации по дальнейшим действиям (например, "Передать на следующий этап", "Отклонить" или "Рассмотреть для другой вакансии").
   - Саммари помогает руководителю быстро принять решение о кандидате.

---

## **Используемые сервисы**

### 1. **Qwen**
   - Qwen был использован для создания системного промпта и базы знаний бота.
   - Системный промпт определяет логику работы бота, обеспечивая четкую последовательность действий:
     - Приветствие пользователя.
     - Запрос резюме и вакансии.
     - Анализ соответствия резюме требованиям.
     - Подготовка вопросов для интервью.
     - Создание итогового саммари для руководителя.
   - База знаний содержит стандартные вопросы для всех кандидатов, примеры желаемых ответов и другие важные данные.

### 2. **Savvy (https://suvvy.ai/)**
   - Savvy — платформа для создания ИИ-ассистентов, которая была использована для реализации пользовательского интерфейса и функциональности Super_HR_Bot.
   - Благодаря Savvy, бот получил возможность легко интегрироваться с различными системами (например, Google Календарь) и масштабироваться при необходимости.
   - Платформа также обеспечивает высокую производительность и надежность работы бота.

---

## **Преимущества Super_HR_Bot**

1. **Экономия времени:** Автоматизация процессов анализа резюме, подготовки вопросов, планирования интервью и составления отчетов существенно снижает нагрузку на HR-специалистов.
2. **Повышение качества отбора:** Использование AI помогает более объективно оценивать кандидатов, основываясь на данных, а не на предвзятых мнениях.
3. **Улучшение опыта кандидатов:** Бот обеспечивает быстрое и профессиональное взаимодействие, что повышает уровень удовлетворенности кандидатов.
4. **Гибкость и масштабируемость:** Super_HR_Bot можно легко адаптировать под различные типы вакансий и требований.

---

## **Технические детали**

- **Язык программирования:** Python (для backend-логики).
- **Интеграции:**
  - Google Календарь (для планирования телефонных/онлайн интервью).
  - Qwen (для создания системного промпта и базы знаний).
  - Savvy (для реализации пользовательского интерфейса).
- **Deployment:** Облачные решения для обеспечения высокой доступности и производительности.

---

## **Целевая аудитория**

- HR-специалисты и рекрутеры, желающие оптимизировать процессы подбора персонала.
- Компании, стремящиеся повысить эффективность найма за счет использования современных технологий.
- Кандидаты, которые ценят быстрое и профессиональное взаимодействие с работодателями.

---

## **Будущее развития**

В планах дальнейшего развития Super_HR_Bot:
- Добавление функции автоматического анализа голосовых и видеозаписей интервью для оценки невербальных сигналов.
- Расширение базы знаний для покрытия большего количества специализированных вакансий.
- Интеграция с другими популярными HR-системами (например, ATS).


