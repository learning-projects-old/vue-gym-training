# Путеводитель: vue-gym-training

Автономная инструкция: достаточно этой папки, исходников и перечисленных защищённых копий. История чатов и центральный каталог не требуются.

[Восстановление](RECOVERY.md) · [Карта файлов и зависимостей](PROJECT_MAP.json)

## Назначение

По [README.md](README.md): See Configuration Reference.

Обнаруженные языки: JavaScript, TypeScript, Vue SFC.

## Порядок чтения

1. Локальные AGENTS.md / CLAUDE.md и документы ниже.
2. Манифесты: версии среды, зависимости, команды.
3. Кандидаты точек входа; фактический запуск проверить по манифесту.
4. PROJECT_MAP.json: imports_local от источника к импортируемому файлу; входящие рёбра — потребители модуля.
5. RECOVERY.md: независимые данные, восстановление среды, запуск и критерии приёмки.

- [README.md](README.md)

## Манифесты

- [package.json](package.json)
- [docs/.vitepress/cache/deps/package.json](docs/.vitepress/cache/deps/package.json)

## Кандидаты точек входа

- [docs/theme/index.ts](docs/theme/index.ts)
- [src/main.js](src/main.js)

## Основные файлы по локальным импортам

| Файл | Входящих импортов |
|---|---:|
| [docs/.vitepress/cache/deps/chunk-G3PMV62Z.js](docs/.vitepress/cache/deps/chunk-G3PMV62Z.js) | 8 |
| [docs/.vitepress/cache/deps/chunk-JD3CXNQ6.js](docs/.vitepress/cache/deps/chunk-JD3CXNQ6.js) | 4 |
| [docs/.vitepress/cache/deps/chunk-SYPOPCWC.js](docs/.vitepress/cache/deps/chunk-SYPOPCWC.js) | 2 |
| [src/pages/admin/dynamic-docs/InfoComponent.vue](src/pages/admin/dynamic-docs/InfoComponent.vue) | 2 |
| [src/modules/shared/tables/sborka/tableStore.js](src/modules/shared/tables/sborka/tableStore.js) | 2 |
| [src/router.js](src/router.js) | 1 |
| [src/App.vue](src/App.vue) | 1 |
| [src/pages/form-1/api/clients.js](src/pages/form-1/api/clients.js) | 1 |
| [src/pages/form-2/api/nom_list.js](src/pages/form-2/api/nom_list.js) | 1 |
| [src/pages/form-2/api/nom_dir.js](src/pages/form-2/api/nom_dir.js) | 1 |
| [src/pages/form-3/api/nom_info.js](src/pages/form-3/api/nom_info.js) | 1 |
| [src/modules/_main/components/Breadcrumbs.vue](src/modules/_main/components/Breadcrumbs.vue) | 1 |

## Проверки


## Чтение карты без специальных плагинов

PROJECT_MAP.json — UTF-8 JSON: nodes и edges. Пути файлов относительные. contains обозначает наличие файла; imports_local — статически распознанный импорт; declares_dependency — объявление пакета в манифесте. evidence содержит источник и, где доступно, строку. Карта не исполняет код.

Статус исходного анализа: static-scan-complete; ограничений чтения: 0. Исходный снимок: 2026-10-30T14:47:11.360Z.

После изменения кода перечитайте затронутые файлы: карта является снимком. Отсутствие ребра не доказывает отсутствие зависимости.
