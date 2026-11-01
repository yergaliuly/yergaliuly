# Статус нового оформления

Обновлено: 2026-11-01.

## Исходная цель

Владелец запросил профессиональное оформление вместо темы Саске, расширенный подтверждённый стек, проекты личного аккаунта и KDvibers, сертификаты Coursera. Позже добавлен сертификат участия в HackAlem AI.
Профиль должен производить впечатление конкретными работами и проверяемыми сведениями.

## Согласовано

- Выбран вариант «Техническое портфолио».
- Работаем в существующем профильном репозитории. Публичный текст на английском.
- Историю и прежние ресурсы сохраняем. Настройки аккаунта — отдельные действия.
- Владелец переключился на свой аккаунт Coursera Daniyar и разрешил изучить сертификаты для профиля.

## Выполнено

- Проверены текущие README и AGENTS, локальная ветка и история. Последняя опубликованная версия на момент начала исследования — `7a6f916`.
- Через GitHub connector найдены личные StudyMate, Habit-Tracker и профильный репозиторий; в KDvibers — FocusDuo, HackAtlas, forte-cash-audit. Все перечисленные репозитории публичные.
- Прочитаны корневые README, релевантные документы о ролях и основные манифесты зависимостей. Не скопированы обещания готовности продукта как подтверждённые результаты.
- В Coursera пройдены все страницы: сохранены 110 уникальных ссылок — 94 курса и 16 программ. Локальный исходный каталог находится вне публикуемого репозитория; он не содержит паролей, cookie или платежных данных.
- Одностраничный PDF HackAlem отрисован и визуально прочитан. Это сертификат участия, дата — 1 ноября 2026 года, имя — Daniyar Yergalyuly. Текстовый слой и встроенные ссылки отсутствуют.
- Подготовлен краткий дизайн: [2026-11-01-professional-profile-design.md](superpowers/specs/2026-11-01-professional-profile-design.md).

## Матрица доказательств

| Область | Что подтверждено | Что требует осторожности |
| --- | --- | --- |
| Java backend | HackAtlas прямо закрепляет backend/infra/CI за yergaliuly; Spring Boot, Security, JPA, PostgreSQL, Flyway, Maven и Testcontainers есть в pom.xml | Наличие библиотеки не определяет уровень владения |
| Applied AI | Forte Cash Audit закрепляет анализатор за Данияром; Python, Qwen3-VL, llama.cpp, PyAV и Pillow описаны в рабочем runtime | PyTorch/RF-DETR относятся к экспериментам; не называть основой сервиса |
| Web и mobile | React/Vite/JavaScript в StudyMate; Node/Express/Prisma в Habit-Tracker; Kotlin/Compose в FocusDuo и HackAtlas | Это стек команды; личный объём работы во всех этих частях не установлен |
| Delivery/testing | CI и infra входят в роль HackAtlas; Dockerfile/Compose, серверные тесты и инструменты контрактов присутствуют | Не заявлять облачную сертификацию или production-опыт по одному конфигурационному файлу |
| Обучение | Названия, организации, месяцы и ссылки всех сертификатов получены из интерфейса Coursera | Окончание курса не равно профессиональному экзамену или экспертному владению технологией |
| Хакатон | Предоставленный PDF подтверждает участие в HackAlem AI | Победа, призовое место и личный рекорд не подтверждены |

## Источники для продолжения

- [StudyMate](https://github.com/yergaliuly/StudyMate#readme), [распределение задач](https://github.com/yergaliuly/StudyMate/blob/main/docs/team-tasks.md), [backend pom](https://github.com/yergaliuly/StudyMate/blob/main/backend/pom.xml).
- [FocusDuo](https://github.com/KDvibers/FocusDuo#readme), [релиз 0.1.0](https://github.com/KDvibers/FocusDuo/releases/tag/v0.1.0), [backend pom](https://github.com/KDvibers/FocusDuo/blob/main/backend/pom.xml).
- [HackAtlas](https://github.com/KDvibers/HackAtlas#readme), [backend pom](https://github.com/KDvibers/HackAtlas/blob/main/backend/pom.xml).
- [Forte Cash Audit и роли](https://github.com/KDvibers/forte-cash-audit#team), [анализатор](https://github.com/KDvibers/forte-cash-audit/blob/main/analyzer/README.md), [рабочие зависимости](https://github.com/KDvibers/forte-cash-audit/blob/main/analyzer/requirements.txt).
- [Habit-Tracker](https://github.com/yergaliuly/Habit-Tracker#readme).
- [Coursera My Learning](https://www.coursera.org/my-learning): вкладка Certificates; исходный каталог сохранён отдельно локально.

## Что ещё не выполнено

Новый README и оформление ещё не реализованы. Дизайн документа ожидает согласования. Изменения новой версии не отправлены на GitHub.
Релиз FocusDuo пока подтверждён README, но коллекция GitHub Releases отдельно не сверена.
Публичные страницы всех 110 сертификатов отдельно не открывались: ссылки получены из аккаунта владельца.

## Этапы и следующий шаг

1. Исследование проектов и сертификатов — выполнено.
2. Направление — выбрано; краткий дизайн — на согласовании.
3. Соразмерный план, оформление и каталог сертификатов — после согласования дизайна.
4. Проверка локального результата и подготовка конкретного пакета публикации.
5. Подтверждение публикации, отправка и проверка реального профиля.

Работать одним агентом. Не перечитывать все источники без изменений или конкретного вопроса. Не переносить приватные исходные материалы в публичный коммит автоматически.
