# ИУ7 Лекции 1-го курса

Конспекты лекций 1-го курса 2023 года ИУ7 "Программная инженерия"

## В АРХИВЕ

Репозиторий архивирован и более не поддерживается. Актуальная версия тут: [https://github.com/zhikh23/iu7-apollo](https://github.com/zhikh23/iu7-apollo).

## Как посмотреть?

1. Открываете директорию с интересующим Вас предметом. Например, если Вам нужна лекция по математическому анализу, открываете `mathematical_analysis`.
2. Далее зависит от предмета:
  - Для всех предметов, **кроме программирования**:
Находите файл `<название предмета>.pdf`.
В этом файле ***все*** лекции по выбранному предмету.
`PDF` для удобства можно скачать на устройство.
  - **Только для программирования**:
Находите файл `programming.md`. 
Здесь, в `github`, он откроется для просмотра автоматически, ничего более делать не нужно. 

##### Если интересует исходный код...

...то обратите внимание на `*.tex`-файлы:
1. `<название предмета>.tex` - основной файл лекции, "точка входа".
2. `common/preamble.tex` - преамбула документа. Здесь находятся некоторые "настройки" документа.
3. `lec??.tex` - непосредственно сам исходный файл лекции.
4. `sec??.tex` - аналогично `lec??.tex`, только деление идет не по лекциям, а по секциям (темам).

## Немного о самом репозитории

Автор максимально возможно конспектирует каждую лекцию и выкладывает их в открытый доступ, чтобы Вы, дорогие читатели, могли воспользоваться этими конспектами по назначению, например, чтобы ознакомиться с упущенным материалом, или просто, чтобы проверить свои записи.

#### Но не ошибается только тот, кто ничего не делает!

Автор по несколько раз перечитывает конспекты, прежде чем они окажутся здесь. 
Однако автор - тоже человек, который может упустить что-то из виду. 
Пожалуйста, если Вы заметили опечатку или ошибку, сообщите об этом (контакты можно найти ниже). 
Именно благодаря Вам, неравнодушные читатели, этот репозиторий становится надёжным источником :)

#### Как это работает?

Под капотом: 
- [LaTeX](https://ru.wikipedia.org/wiki/LaTeX) (читается как "лэйтех", а не "латекс"!) - см. [TeX](https://ru.wikipedia.org/wiki/TeX) - язык разметки.
  - [texlive](https://tug.org/texlive/) - программа для компиляции `.tex`.
- [Neovim](https://neovim.io/) - текстовый редактор.
  - [vimtex](https://github.com/lervag/vimtex) - расширение для `neovim`, позволяющее "подружить" редактор с `tex`-ом.
  - [ultisnips](https://github.com/SirVer/ultisnips) - расширение для `neovim`, позволяющее использовать _сниппеты_ (когда-нибудь автор их выложит в открытый доступ...). Сниппет - это своего рода умное "автодополнение". Именно благодаря ним, маленьким помощникам, автору и удается конспектировать в режиме реального времени!
- [Zathura](https://pwmt.org/projects/zathura/) - минималистическая программа в стиле vim-a для просмотра `.pdf`.

Для лекций по программированию:
- [Markdown](https://www.markdownguide.org/) - простой язык разметки, удобен для комбинации текста и кода.
- [VS Code](https://code.visualstudio.com/) - современный текстовый редактор с огромным количеством расширений. Также используется для поиска ошибок в `.tex` файлах и их исправлений.

#### Хочу так же!

~~Что-ж, Вы выбрали путь боли...~~ На самом деле не всё так страшно. Расскажу, как можно к этому прийти на примере опыта автора:
1. Да, эти самые зловещие три буквы: `vim`. Очень мощный текстовый редактор, к которому нужно привыкнуть. Первое время на нём будет тяжело... но после жизнь уже не будет прежней! Чтобы "набить руку", можно набирать в виме код для лабороторных по программированию. А также именно в виме есть поддержка сниппетов в том виде, в котором их использует автор.
2. Вёрстка? Автор начинал с простейшего языка разметки, [Markdown](https://www.markdownguide.org/). Кстати всё, что Вы сейчас читаете, тоже было написано при помощи Markdown-a! В нём есть поддержка [KaTeX](https://katex.org/docs/supported.html) для набора математических формул.
3. К слову, о математических формулах. https://katex.org/docs/supported.html - эту ссылку автор использует как шпаргалку для записей математических формул.
4. Перед тем, как сразу идти ~~в бой~~ на лекцию с ноутбуком, автор конспектировал всё на бумаге, а после, дома, в спокойной обстановке, переводил в электронный вид (сначала markdown, а потом и latex). И лишь спустя десяток часов практики приступил к реальным задачам.

Сложно? Однозначно да. А стоит ли игра свеч? Решать Вам...

## Контакты

Вот они, сверху вниз:
1. Telegram `@zhikhkirill`
2. VK `@zhikh.localhost`
3. Discord `@zhikh`

--- 

## Источник вдохновения

Многое из того, что использовал автор, взято [отсюда](https://github.com/gillescastel).

