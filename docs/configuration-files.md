# Файлы конфигурации

Они обязательно должны быть изолированы от системы контроля версий `.gitignore`-ом,
чтобы каждый разработчик не коммитил случайно свои настройки.

# Шаблоны конфигов

## Что?

Шаблон конфига — это просто болванка настоящего файла конфигурации.\
Это нужно для того, чтобы потом было удобнее создать файл конфига, не залезая в код.

К примеру, в `/packages/server/` есть `appSettings.template.json`.\
Это значит, что в этой же директории **обязательно** должен присутствовать `appSettings.json` с аналогичной шаблону структурой.

## Нейминг

`myconfig.template.json` — это шаблон для `myconfig.json`.
