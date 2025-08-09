# History

## 2025 07 20 Глаголы

1. Хочу сделать 3 категории глаголов
    1. обязательно знать
    1. желательно знать
    1. нафиг не нужны
1. В итоге конвертировал таблицу [001-irregular-verbs.pdf](resources/verb/001-irregular-verbs.pdf) в [002-irregular-verbs.csv](resources/verb/002-irregular-verbs.csv)
1. Дальше решил спросить у Gemeni 100 самых употребимых глаголов. Получил [003-100-irregular-verbs-sorted-by-importance.csv](resources/verb/in-progress/003-100-irregular-verbs-sorted-by-importance.csv)
1. Теперь спросил Gemeni скомибинировать [002-irregular-verbs.csv](resources/verb/002-irregular-verbs.csv) и [003-100-irregular-verbs-sorted-by-importance.csv](resources/verb/in-progress/003-100-irregular-verbs-sorted-by-importance.csv), чтобы получить 100 отсортированных глаголов с 3 формами, переводом и примерами предложений
1. Получил 2 файла
    - [004-100-irregular-verbs-sorted-with-translation.csv](./resources/verb/in-progress/004-100-irregular-verbs-sorted-with-translation.csv) - отсортированные на основе файа 003 
    - [005-100-leftover-verb-non-sorted.csv](./resources/verb/in-progress/005-100-leftover-verb-non-sorted.csv) - оставшиеся не отстортированные
1. Дальше думаю оттуда отсечь 30-35 глаголов для первой группы
1. Пока сортировал в файле [006-100-irregular-verbs-sorted-+soreted-by-me-with-translation.csv](./resources/verb/in-progress/006-100-irregular-verbs-sorted-+soreted-by-me-with-translation.csv), понял, что для первой группы глаголов 86 получится и надо их тоже разбивать - это отражено в файле, 86 первых глаголов до empty line. Так что тепрерь делаю так
    - Группа tag "verb_p1" - 28 первых глаголов, идут в файл - [002-irregular-verbs-top-001-028](./import/002-irregular-verbs-top-001-028.csv)
    - Группа tag "verb_p2" - 28 глаголов второго пака, идут в файл - [003-irregular-verbs-top-029-057](./import/003-irregular-verbs-top-029-057.csv)
    - Группа tag "verb_p3" - 30 глаголов третьего пака, идут в файл - [004-irregular-verbs-top-058-088.csv](./import/004-irregular-verbs-top-058-088.csv)
    - Группа tag "verb_p4" - 24 глаголов четвертого пака, идут в файл - [005-irregular-verbs-top-089-113.csv](./import/005-irregular-verbs-top-089-113.csv)
    - Группа tag "verb_p5" - оставшиеся глаголы из файла [005-100-leftover-verb-non-sorted.csv](./resources/verb/in-progress/005-100-leftover-verb-non-sorted.csv) идут в [006-irregular-verbs-top-114-128.csv](./import/006-irregular-verbs-top-114-128) - это глаголы которые совсем можно не учить


## 2025 07 20 Import and Sentences

### Sentences

- [Sentence adder for any language with batch add option](https://ankiweb.net/shared/info/1682655437)
- https://tatoeba.org/en/downloads - предложения

### Задавать вопросы по обеим сторонам

- https://youtu.be/DnbKwHEQ1mA?si=t8Uv7Q0IJAcwZ-z3 [[source](https://www.reddit.com/r/Anki/comments/1cdfdli/comment/l1cff3w/)]

### Import

- [Text Files \[ankiweb.net\]](https://docs.ankiweb.net/importing/text-files.html) - официальная документация