# Change Log

This is the Changelog for the vim-language-1c-bsl project.

## [0.3]

* Добавлена документация по командам
* Добавлена опция отключения подсветки SDBL внутри BSL

## [0.2]

* Добавлена функция автоматической установки отступов.
* Определены расширения для файлов `1C (SDBL)` (*.query, *.sdbl).
* Исправлена ошибка подсветки запросов в файлах `1C (BSL)`.
Ключевые слова запроса подсвечивались во всем файле.
* Оптимизированы грамматики `1C (SDBL)`.
* Добавлена поддержка сворачивания участков кода заключенных в конструкцию вида '#Область'...'#КонецОбласти'.
Поддерживаются вложенные конструкции.
* Добавлено автодополнение для процедур и функций текущего файла, с выводом в подсказке параметров метода.
* Добавлено автодополнение для переменных текущего файла, объявленных с использование ключевого слова `Перем`.
Автодополнение не учитывает области видимости переменной.

## [0.1] - Первый релиз

* Добавлена подсветка для русского и английского синтаксиса языка `1C (BSL)`
* Добавлена подстветка синтаксиса языка запросов `SDBL`
* Добавлена поддержка шаблонов кода [vim-snipmate](https://github.com/garbas/vim-snipmate)
* Добавлена поддержка плагина [tagbar](https://github.com/majutsushi/tagbar)
* Добавлена возможность сворачивать блоки кода процедур и функций
