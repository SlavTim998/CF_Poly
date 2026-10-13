# CF Poly

Онлайн-инструмент для задач Codeforces и генерации тестов на GitHub Pages.

## Возможности
- Загрузка публичных метаданных задач Codeforces (название, теги, рейтинг); если Codeforces блокирует CORS, ручной ввод
- Генератор чисел, массивов, строк и шаблонов
- Редактирование и экспорт тестов ZIP, экспорт задачи JSON

## Публикация
В GitHub откройте Settings → Pages → Build and deployment → Source: GitHub Actions. Workflow `.github/workflows/pages.yml` выполнит публикацию на https://slavtim998.github.io/CF_Poly/ .

## Важно
GitHub Pages не выполняет backend. Полный текст условия Codeforces официальный API не отдаёт. Прямая загрузка в Polygon не реализована, она потребует защищённого сервера. API-ключи нельзя вводить в статический сайт.

## Авторство
SlavTim998 by Timoshenko Vyacheslav. Исходный QW_Poly: © 2026 Fortoshka (MIT); уведомление сохранено в LICENSE.
