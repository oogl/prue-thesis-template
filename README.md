# prue-thesis-template
[![GitHub](https://img.shields.io/github/license/oogl/prue-thesis-template?label=license)](https://github.com/oogl/prue-thesis-template/blob/master/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/oogl/prue-thesis-template)](https://github.com/oogl/prue-thesis-template/commits/master)

Шаблон диплома РЭУ в LaTeX. Альтернатива шаблонам ВКР бакалавра от кафедры ПИиИБ.

## Оформление

* Формат листа: А4
* Поля
    * верхнее / нижнее – 25 мм
    * левое – 30 мм
    * правое – 10 мм
* Шрифт
    * Tempora-TLF (аналог Times New Roman)
    * интервал: 1.5
    * размер: 14 пт
* Номер страницы
    * сквозной
    * на середине верхнего поля
    * не указан, но учитывается для:
        * титульного листа
        * аннотаций
        * оглавления
* Заголовки главы и подглав
    * в середине строки без точки в конце
    * более крупный шрифт
    * двухкратный междуабзацный интервал сверху / снизу (18пт)
* Таблицы и рисунки
    * последовательно пронумерованы
    * шаблон надписи "Рисунок / Таблица X — Название"
    * поддержка комментария "(сделано студентом Y в программном продукте Z)"

## Структура проекта

```
prue-thesis-template
├── sections
│   └── ...
├── src
│   ├── code
│   │   └── ...
│   ├── img
│   │   └── ...
│   └── pdf
│       └── ...
├── LICENCE
├── prue-thesis.sty
├── README.md
├── thesis.pdf
├── thesis.tex
└── YOUR-DATA.tex
```