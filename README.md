# Тренинг «Unit Testing & TDD»
24 часа

# Цели тренинга
После тренинга участники смогут:
1. Объяснить себе и менеджменту, где им нужны тесты, а где нет
1. Разрабатывать поддерживаемые тесты и их наборы
1. Разрабатывать тесты как «спецификации на примерах» в роли документации
1. Подменять сложные компоненты системы на время тестирования
1. Анализировать тестовое покрытие для принятия решений по покрытию и дизайну
1. Обеспечивать поддерживаемый дизайн системы при помощи TDD
1. Обеспечивать контролируемый cycle time задач
1. Обеспечивать контролируемое качество системы

# Программа
## Введение
1. Обзор тренинга
1. Знакомство и сбор проблем
1. Разбивка по парам

# Тестирование как способ обеспечения качества продукта
1. Что такое качество?
1. Какие способы обеспечения качества существуют?
1. Каковы их ограничения?

# Скоупы автотестов
1. Системные
1. Интеграционные
1. Модульные
1. Их ценность и затраты?
1. Как по коду определить скоуп?

# Автоматизированное тестирование
1. Каковы цели и задачи?
2. В чем отличие от отладки?
3. Определение модуля и возможные виды модулей
4. Понятие контракта по Б. Мейеру
5. Понятие трасс выполнения (flows)
6. Граничные условия
7. Тест = спецификация

# Структура автоматизированного теста
1. Именование тест-кейса и теста
1. Подход AAA
1. Подход GWT
1. Роль фикстуры

# Фреймворки автоматизированного тестирования
1. Разработка тест-кейса
1. Разработка теста
1. Простые сравнения
1. Сложные сравнения
1. Таймауты
1. Исключения
1. Параметризованные тесты

# Интеграционные и модульные тесты
1. В чем их специфика?
1. Виды тест-дублеров
1. Фреймворк тест-дублеров
1. Fixture Builders

# Тестопригодный дизайн
1. Как оценить тестопригодность?
1. Метрика Coupling
1. Метрика Cohesion
1. Каков тестопригодный дизайн?
1. Принципы проектирования SOLID
1. Шаблоны Factory и DI
1. Шаблоны Strategy/State

# Тестовое покрытие
1. Понятие покрытия
1. Виды расчета покрытия
1. Инструменты расчета покрытия

# Шаблоны группировки тестов в наборы
1. Зачем нужны test suites?
1. Шаблоны группировок
1. Способы группировок от фреймворка

# Поддержка качества тестов и снижение дублирования
1. Как обеспечить качество самих тестов?
1. Сначала поломанный тест
1. Анализ покрытия: паттерны
1. Ревью кода тестов
1. Mutation coverage

#	Анти-паттерны разработки модульных тестов
1. Каковы "вредные советы"?
1. Отношение к тестам не как к обычному коду
1. Большие расфокусированные тесты
1. Неговорящие имена
1. Дублирование фикстуры

#	Покрытие тестами legacy code
1. Какие выделяем проблемы с тестопригодностью?
1. Каковы способы упрощения покрытия legacy code?


# Введение в TDD
1. Что такое TDD?
1. Зачем нужен TDD?
1. Минимизация отладки
1. TDD как практика проектирования
1. Снижение затрат на инкрементальную разработку
1. Быстрая обратная связь
1. Повышение поддерживаемости дизайна
1. Удобство API "из коробки"
1. Тесты как документация
1. Предсказуемость поставки
1. Чистый работающий код
1. Управление страхом

# Мантра TDD
1. Red – Green – Refactor
1. Демо
1. Скорость отработки тестового набора как предусловие практики TDD

# Инкрементальный дизайн
1. Инкрементальная реализация трасс через покрытие граничных условий
1. Дублирование тестов в классах эквивалентности

# Базовые шаблоны TDD
1. Test First
1. Isolated Tests
1. Assertion First
1. Test Data
1. Child Test
1. Test List
1. Mock Object
1. Crash Test Dummy

#	Шаблоны красной полосы
1. One-step Test
1. Starter Test
1. Another Test
1. Regression Test

# Шаблоны зеленой полосы
1. Obvious Implementation
1. Triangulation
1. One to Many

# Внедрение в процесс разработки
1. Каковы затраты на TDD?
1. Постановка экономической задачи
1. Общение с менеджментом
1. Secure sandbox
1. Последовательное расширение scope

# Типовые ошибки использования TDD
1. Code First
1. Too Many Obvious Implementation
1. Too Many Triangulations
1. Coverage Affinity
1. Implementation Testing but not Contract Testing

# Финальная ретроспектива
