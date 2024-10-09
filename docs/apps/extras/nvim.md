# NEOVIM


> :information_source: **Інформація:** Це текстовий редактор на основі Vim, створений для розширюваності та зручності використання, щоб стимулювати нові :package: програми та внески.

:open_file_folder: **Розділ** :hammer_and_wrench: *Інструменти Розробника*

---

## Про neovim

| Опис                          | Інформація                            |
|-------------------------------|---------------------------------------|
| **версія :package: програми** | :zero: . :one: :zero: . :two:         |
| :computer: **розробник**      | Neovim team                           |
| **сайт**                      | [:link: посилання](https://neovim.io) |

## :inbox_tray: Встановлення

- :inbox_tray: встановлення з :octocat: за [:link: посилання](https://github.com/neovim/neovim/blob/master/INSTALL.md)

### :desktop_computer: Windows

- :inbox_tray: встановлення за допомогою терміналу:
  - **Winget** *Release*: `winget install Neovn`
  - **Chocolatey:**
    - *Latest Rlease*: `choco install neovim`
    - *Development (pre-release)*: `choco install neovim --pre`
  - **Scoop** *Release*: `scoop install neovim`
- :inbox_tray: встановлення з :cloud: Хмарного сховища

### :penguin: Linux

- :inbox_tray: встановлення за допомогою **Flathub**(Unverified):
  - вводимо команду у терміналі: `flatpak install flathub io.neovim.nvim`
- :inbox_tray: встановлення за допомогою **Snap Store**:
  - **версія :package: програми** latest/stable команда для терміналу: `sudo snap install nvim --classic`
  - **версія :package: програми** latest/edge команда для терміналу: `sudo snap install nvim --edge --classic`

#### fedora WORKSTATION

- :inbox_tray: встановлення з **Центру :package: програмного забезпечення**
- :inbox_tray: встановлення за допомогою командного рядка: `sudo dnf install nvim`

## Сполучення клавіш

| опис | команда |
|-----:|:-------:|
| перезавантажити файл init.vim без виходу | `:source $MYVIMRC` |

### Переміщення курсору

| опис | команда |
|-----:|:-------:|
| переміщення вліво | <kbd>h</kbd> |
| переміщення вниз | <kbd>j</kbd> |
| переміщення вгору | <kbd>k</kbd> |
| переміщення вправо | <kbd>l</kbd> |
| перемістити курсор на два слова вперед | <kbd>2</kbd><kbd>w</kbd> |
| перемістити курсор у кінець третього слова вперед | <kbd>3</kbd><kbd>e</kbd> |
| перехід на початок рядка | <kbd>0</kbd> |

### Вихід з Neovim

| опис | команда |
|-----:|:-------:|
| закрити вікно | `:q` |
| вийти без збереження змін | <kbd>Esc</kbd> `:q!` <kbd>Enter</kbd> |
| вийти зі збереженням змін | <kbd>Esc</kbd> `:wq` <kbd>Enter</kbd> |

### Редагування тексту: видалення

| опис | команда |
|-----:|:-------:|
| видалення символу під курсором | <kbd>x</kbd> |
| видалити слово | <kbd>d</kbd><kbd>w</kbd> |
| видалити два слова з ВЕЛИКОЇ ЛІТЕРИ | <kbd>d</kbd><kbd>2</kbd><kbd>w</kbd> |
| до кінця поточного слова | <kbd>d</kbd><kbd>e</kbd> |
| до кінця рядка | <kbd>d</kbd> <kbd>Shift</kbd> <kbd>4</kbd> |
| видалення цілого рядка | <kbd>d</kbd><kbd>d</kbd> |

### Редагування тексту: вставлення

| опис | команда |
|-----:|:-------:|
| вставлення тексту | <kbd>i</kbd> |

### Редагування тексту: додавання

| опис | команда |
|-----:|:-------:|
| додавання тексту | <kbd>a</kbd>, <kbd>Shift</kbd> <kbd>a</kbd> |

### Команда "відкрити"

| опис | команда |
|-----:|:-------:|
| відкрити лінію під курсором і перевести вас у режим вставлення | <kbd>o</kbd> |

### Команда "скасувати"

| опис | команда |
|-----:|:-------:|
| скасування останніх команд | <kbd>u</kbd> |
| виправлення цілої лінії | <kbd>Shift</kbd> <kbd>U</kbd> |
| скасувати | <kbd>Ctrl</kbd> <kbd>r</kbd> |

### Команда "вставити"

| опис | команда |
|-----:|:-------:|
| вставте раніше видалений текст після курсору | <kbd>p</kbd> |

### Команда "замінити"

| опис | команда |
|-----:|:-------:|
| замінити символ біля курсору на x | <kbd>r</kbd><kbd>x</kbd> |
| щоб замінити більше ніж один символ | <kbd>Shift</kbd> <kbd>r</kbd> |

### Оператор зміни

| опис | команда |
|-----:|:-------:|
| видаляє слово та розміщує в режимі вставки | <kbd>c</kbd><kbd>e</kbd> |
| видаляє слово та розміщує в режимі вставки | <kbd>c</kbd><kbd>w</kbd> |
| видалити до кінця рядка в режимі вставки | <kbd>c</kbd> <kbd>Shift</kbd> <kbd>4</kbd> |

### Редагування файлу

| опис | команда |
|-----:|:-------:|
| nvim команда для запуску редактора, 'FILENAME' ім’я файлу, який ви бажаєте редагувати | `$ nvim FILENAME` |

### Місце курсору та стан файлу

| опис | команда |
|-----:|:-------:|
| показати розташування у файлі та статус | <kbd>Ctrl</kbd> <kbd>g</kbd> |
| перейти до кінця файлу | <kbd>Shift</kbd> <kbd>g</kbd> |
| перейти до початку файлу | <kbd>g</kbd><kbd>g</kbd> |

### Команда пошуку

| опис | команда |
|-----:|:-------:|
| фраза для пошуку фрази | <kbd>/</kbd> |
| Для пошуку фрази в зворотному напрямку | <kbd>?</kbd> |
| знову шукати ту саму фразу | <kbd>n</kbd> |
| Для пошуку тієї самої фрази у зворотному напрямку | <kbd>Shift</kbd> <kbd>n</kbd> |
| Повернутися туди, звідки прийшов | <kbd>Ctrl</kbd> <kbd>o</kbd> |
| Повторіть, щоб повернутися далі | <kbd>Ctrl</kbd> <kbd>i</kbd> |

### Пошук в дужках

| опис | команда |
|-----:|:-------:|
| щоб знайти відповідність ),] або } | <kbd>Shift</kbd> <kbd>5</kbd> |

### Команда заміни

| опис | команда |
|-----:|:-------:|
| змінив перший збіг у лінії | `:s/thee/the/` |
| замінити глобально в лінії | `:s/thee/the/g` |
| Щоб змінити кожне входження рядка символів між двома рядками | `:#,#s/old/new/g` |
| щоб змінити кожне входження у всьому файлі | `:%s/old/new/g` |
| щоб знайти кожне входження у всьому файлі з підказкою, замінювати чи ні | `:%s/old/new/gc` |

### Як виконати зовнішню команду

| опис | команда |
|-----:|:-------:|
| а потім зовнішня команда для виконання цієї команди | `:!command` |

### Більше про запис файлів

| опис | команда |
|-----:|:-------:|
| записує поточний файл | `:w FILENAME` |
| показує список каталогу | `:!ls` |
| видалити файл | `:!rm FILENAME` |

### Вибір тексту для напису

| опис | команда |
|-----:|:-------:|
| Візуальний режим | <kbd>v</kbd> |
|  | `:'<,'>` |

### Отримання та об'єднання файлів

| опис | команда |
|-----:|:-------:|
| Щоб отримати вміст файлу | `:r FILENAME` |
|  | `:r !ls` |
| читає вивід команди dir і розміщує його під позицією курсору | `:r !dir` |

### Копіюйте і вставте текст

| опис | команда |
|-----:|:-------:|
| копія | <kbd>y</kbd>   |
| копіювати одне слово | <kbd>y</kbd><kbd>w</kbd> |

### Отримання допомоги

| опис | команда |
|-----:|:-------:|
| допомога | <kbd>F1</kbd> |
| допомога | `:help` |

## КОЛЬОРОВІ ТЕМИ VIM

### Стандартні Кольорові Теми

- blue
- darkblue
- default
- delek
- desert
- elflord
- evening
- industry
- koehler
- morning
- murphy
- pablo
- peachpuff
- ron
- shine
- slate
- torte
- zellner

### Інші Кольорові Теми

- 0x7A69_dark
- 1989
- 256-grayvim
- 256-jungle
- 256_noir
- abbott
- abstract
- alduin
- amber
- ambient
- amcolors
- amdark
- amlight
- ampresent
- ancient
- anderson
- angr
- antares
- apprentice
- arcadia
- atlantis
- archman, argonaut
- atlantic-dark
- atlas
- atom
- austere
- ayu
- azuki
- alchemie
- base16-atelierdune
- badwolf
- base
- bclean
- beauty256
- benlight
- Benokai
- bernhard
- birds-of-paradise
- blackboard
- black_is_the_color
- blacklight
- blame
- blandon
- blaquemagick
- blayu
- bleh
- blue-mood
- bluewery-light
- bluewery
- boa
- borland
- breezy
- breve
- brighton
- briofita
- broduo
- bubblegum-256-dark
- bubblegum-256-light
- burnttoast256
- bushfire8
- bushfire
- BusyBee
- bw
- base16-duotone-dark
- cryslominsa
- C64
- cabin
- cake16
- cake
- calmar256-light
- candid
- CandyPaper
- carbonized-dark
- carbonized-light
- cascadia
- ceudah
- cjameleon
- Chasing_Logic
- ChocolateLiquor
- cleanroom
- cmptrclr
- cobalt2
- cobalt
- colibri
- colorful256
- colorsbox-faff
- colorsbox-greenish
- colorsbox-material
- colorsbox-stblue
- colorsbox-stbright
- colorsbox-steighties
- colorsbox-stnight
- contrastneed
- cosme
- cosmic_latte
- crayon
- codeburn
- desert-night
- dante
- darcula
- darkglass
- dark_purple
- darkslategray
- darkspectrum
- darktheme
- desertEx
- despacio
- Dev_Delight
- diokai
- disciple
- distilled
- donbass
- dragon-energy
- duna
- duoduo
- duo-mini
- dvo
- earendel
- ecostation
- edge
- editplus
- ego
- eink
- elrodeo
- erez
- eva01-LCL
- eva01
- evening
- fairy-garden
- fairyfloss
- falcon
- fantasy
- feral
- film_noir
- FiraCode
- flatcolor
- flatlandia
- flattened_dark
- flattened_light
- flattown
- flattr
- flatui
- focusedpanic
- focuspoint
- ice-age
- lost-shrine
- mustang
- vanilla-cake
- zenburn

## OPTIONS

>&#128161; Vim має ряд внутрішніх змінних і перемикачів, які можна налаштувати для
для досягнення спеціальних ефектів.

Ці варіанти бувають трьох видів:
- **boolean** - може бути тільки *увімкненим* або *вимкненим* булевим перемикачем
- **number** - має числове значення
- **string** - має рядкове значення

<u>'aleph'</u>  <u>'al'</u>                   ASCII code of the letter Aleph (Hebrew)

<u>'allowrevins'</u>  <u>'ari'</u>            allow <kbd>Ctrl</kbd>-<kbd>_</kbd> in Insert and Command-line mode

<u>'ambiwidth'</u>  <u>'ambw'</u>             what to do with Unicode chars of ambiguous width

<u>'autochdir'</u>  <u>'acd'</u>              change directory to the file in the current window

<u>'arabic'</u>  <u>'arab'</u>                for Arabic as a default second language

<u>'arabicshape'</u>  <u>'arshape'</u>        do shaping for Arabic characters

<u>'autoindent'</u>  <u>'ai'</u>              take indent for new line from previous line

<u>'autoread'</u>  <u>'ar'</u>                autom. read file when changed outside of Vim

<u>'autowrite'</u>  <u>'aw'</u>               automatically write file if changed

<u>'autowriteall'</u>  <u>'awa'</u>           as 'autowrite', but works with more commands

<u>'background'</u>  <u>'bg'</u>              "dark" or "light", used for highlight colors

<u>'backspace'</u>  <u>'bs'</u>               how backspace works at start of line

<u>'backup'</u>  <u>'bk'</u>                  keep backup file after overwriting a file

<u>'backupcopy'</u>  <u>'bkc'</u>             make backup as a copy, don't rename the file

<u>'backupdir'</u>  <u>'bdir'</u>             list of directories for the backup file

<u>'backupext'</u>  <u>'bex'</u>              extension used for the backup file

<u>'backupskip'</u>  <u>'bsk'</u>             no backup for files that match these patterns

<u>'balloondelay'</u>  <u>'bdlay'</u>         delay in mS before a balloon may pop up

<u>'ballooneval'</u>  <u>'beval'</u>          switch on balloon evaluation in the GUI

<u>'balloonevalterm'</u>  <u>'bevalterm'</u>  switch on balloon evaluation in the terminal

<u>'balloonexpr'</u>  <u>'bexpr'</u>          expression to show in balloon

<u>'belloff'</u>  <u>'bo'</u>                 do not ring the bell for these reasons

<u>'binary'</u>  <u>'bin'</u>                 read&bsol;write&bsol;edit file in binary mode

<u>'bomb'</u>                                 prepend a Byte Order Mark to the file

<u>'breakat'</u>  <u>'brk'</u>                characters that may cause a line break

<u>'breakindent'</u>  <u>'bri'</u>            wrapped line repeats indent

<u>'breakindentopt'</u>  <u>'briopt'</u>      settings for 'breakindent'

<u>'browsedir'</u>  <u>'bsdir'</u>            which directory to start browsing in

<u>'bufhidden'</u>  <u>'bh'</u>               what to do when buffer is no longer in window

<u>'buflisted'</u>  <u>'bl'</u>               whether the buffer shows up in the buffer list

<u>'buftype'</u>  <u>'bt'</u>                 special type of buffer

<u>'casemap'</u>  <u>'cmp'</u>                specifies how case of letters is changed

<u>'cdhome'</u>  <u>'cdh'</u>                 change directory to the home directory by "&colon;cd"

<u>'cdpath'</u>  <u>'cd'</u>                  list of directories searched with "&colon;cd"

<u>'cedit'</u>                                key used to open the command-line window

<u>'charconvert'</u>  <u>'ccv'</u>            expression for character encoding conversion

<u>'cindent'</u>  <u>'cin'</u>                do C program indenting

<u>'cinkeys'</u>  <u>'cink'</u>               keys that trigger indent when 'cindent' is set

<u>'cinoptions'</u>  <u>'cino'</u>            how to do indenting when 'cindent' is set

<u>'cinwords'</u>  <u>'cinw'</u>              words where 'si' and 'cin' add an indent

<u>'clipboard'</u>  <u>'cb'</u>               use the clipboard as the unnamed register

<u>'cmdheight'</u>  <u>'ch'</u>               number of lines to use for the command-line

<u>'cmdwinheight'</u>  <u>'cwh'</u>           height of the command-line window

<u>'colorcolumn'</u>  <u>'cc'</u>             columns to highlight

<u>'columns'</u>  <u>'co'</u>                 number of columns in the display

<u>'comments'</u>  <u>'com'</u>               patterns that can start a comment line

<u>'commentstring'</u>  <u>'cms'</u>          template for comments; used for fold marker

<u>'complete'</u>  <u>'cpt'</u>               specify how Insert mode completion works

<u>'completefunc'</u>  <u>'cfu'</u>           function to be used for Insert mode completion

<u>'completeopt'</u>  <u>'cot'</u>            options for Insert mode completion

<u>'concealcursor'</u>  <u>'cocu'</u>         whether concealable text is hidden in cursor line

<u>'conceallevel'</u>  <u>'cole'</u>          whether concealable text is shown or hidden

<u>'confirm'</u>  <u>'cf'</u>                 ask what to do about unsaved/read-only files

<u>'copyindent'</u>  <u>'ci'</u>              make 'autoindent' use existing indent structure

<u>'cpoptions'</u>  <u>'cpo'</u>              flags for Vi-compatible behavior

<u>'cscopepathcomp'</u>  <u>'cspc'</u>        how many components of the path to show

<u>'cscopeprg'</u>  <u>'csprg'</u>            command to execute cscope

<u>'cscopequickfix'</u>  <u>'csqf'</u>        use quickfix window for cscope results

<u>'cscoperelative'</u>  <u>'csre'</u>        Use cscope.out path basename as prefix

<u>'cscopetag'</u>  <u>'cst'</u>              use cscope for tag commands

<u>'cscopetagorder'</u>  <u>'csto'</u>        determines ":cstag" search order

<u>'cursorbind'</u>  <u>'crb'</u>             move cursor in window as it moves in other windows

<u>'cursorcolumn'</u>  <u>'cuc'</u>           highlight the screen column of the cursor

<u>'cursorline'</u>  <u>'cul'</u>             highlight the screen line of the cursor

<u>'cursorlineopt'</u>  <u>'culopt'</u>       settings for 'cursorline'

<u>'debug'</u>                                set to "msg" to see all error messages

<u>'define'</u>  <u>'def'</u>                 pattern to be used to find a macro definition

<u>'delcombine'</u>  <u>'deco'</u>            delete combining characters on their own

<u>'dictionary'</u>  <u>'dict'</u>            list of file names used for keyword completion

<u>'diff'</u>                                 use diff mode for the current window

<u>'diffexpr'</u>  <u>'dex'</u>               expression used to obtain a diff file

<u>'diffopt'</u>  <u>'dip'</u>                options for using diff mode

<u>'digraph'</u>  <u>'dg'</u>                 enable the entering of digraphs in Insert mode

<u>'directory'</u>  <u>'dir'</u>              list of directory names for the swap file

<u>'display'</u>  <u>'dy'</u>                 list of flags for how to display text

<u>'eadirection'</u>  <u>'ead'</u>            in which direction 'equalalways' works

<u>'encoding'</u>  <u>'enc'</u>               encoding used internally

<u>'endofline'</u>  <u>'eol'</u>              write &lt;EOL&gt; for last line in file

<u>'equalalways'</u>  <u>'ea'</u>             windows are automatically made the same size

<u>'equalprg'</u>  <u>'ep'</u>                external program to use for "=" command

<u>'errorbells'</u>  <u>'eb'</u>              ring the bell for error messages

<u>'errorfile'</u>  <u>'ef'</u>               name of the errorfile for the QuickFix mode

<u>'errorformat'</u>  <u>'efm'</u>            description of the lines in the error file

<u>'eventignore'</u>  <u>'ei'</u>             autocommand events that are ignored

<u>'expandtab'</u>  <u>'et'</u>               use spaces when &lt;Tab&gt; is inserted

<u>'exrc'</u>  <u>'ex'</u>                    read &period;nvimrc and &period;exrc in the current directory

<u>'fileencoding'</u>  <u>'fenc'</u>          file encoding for multibyte text

<u>'fileencodings'</u>  <u>'fencs'</u>        automatically detected character encodings

<u>'fileformat'</u>  <u>'ff'</u>              file format used for file I/O

<u>'fileformats'</u>  <u>'ffs'</u>            automatically detected values for 'fileformat'

<u>'fileignorecase'</u>  <u>'fic'</u>         gnore case when using file names

<u>'filetype'</u>  <u>'ft'</u>                type of file, used for autocommands

<u>'fillchars'</u>  <u>'fcs'</u>              characters to use for displaying special items

<u>'fixendofline'</u>  <u>'fixeol'</u>        make sure last line in file has &lt;EOL&gt;

<u>'foldclose'</u>  <u>'fcl'</u>              close a fold when the cursor leaves it

<u>'foldcolumn'</u>  <u>'fdc'</u>             width of the column used to indicate folds

<u>'foldenable'</u>  <u>'fen'</u>             set to display all folds open

<u>'foldexpr'</u>  <u>'fde'</u>               expression used when 'foldmethod' is "expr"

<u>'foldignore'</u>  <u>'fdi'</u>             ignore lines when 'foldmethod' is "indent"

<u>'foldlevel'</u>  <u>'fdl'</u>              close folds with a level higher than this

<u>'foldlevelstart'</u>  <u>'fdls'</u>        Sets 'foldlevel' when starting to edit a file

<u>'foldmarker'</u>  <u>'fmr'</u>             markers used when 'foldmethod' is "marker"

<u>'foldmethod'</u>  <u>'fdm'</u>             folding type

<u>'foldminlines'</u> <u>'fml'</u>            minimum number of lines for a fold to be closed

<u>'foldnestmax'</u>  <u>'fdn'</u>            maximum fold depth

<u>'foldopen'</u>  <u>'fdo'</u>               for which commands a fold will be opened

<u>'foldtext'</u>  <u>'fdt'</u>               expression used to display for a closed fold

<u>'formatexpr'</u>  <u>'fex'</u>             expression used with "gq" command

<u>'formatlistpat'</u>  <u>'flp'</u>          pattern used to recognize a list header

<u>'formatoptions'</u>  <u>'fo'</u>           how automatic formatting is to be done

<u>'formatprg'</u>  <u>'fp'</u>               name of external program used with "gq" command

<u>'fsync'</u>  <u>'fs'</u>                   whether to invoke fsync() after file write

<u>'gdefault'</u>  <u>'gd'</u>                the "&colon;substitute" flag 'g' is default on

<u>'grepformat'</u>  <u>'gfm'</u>             format of 'grepprg' output

<u>'grepprg'</u>  <u>'gp'</u>                 program to use for "&colon;grep"

<u>'guicursor'</u>  <u>'gcr'</u>              GUI&colon; settings for cursor shape and blinking

<u>'guifont'</u>  <u>'gfn'</u>                GUI&colon; Name(s) of font(s) to be used

<u>'guifontwide'</u>  <u>'gfw'</u>            list of font names for double-wide characters

<u>'guioptions'</u>  <u>'go'</u>              GUI&colon; Which components and options are used

<u>'guitablabel'</u>  <u>'gtl'</u>            GUI&colon; custom label for a tab page

<u>'guitabtooltip'</u>  <u>'gtt'</u>          GUI&colon; custom tooltip for a tab page

<u>'helpfile'</u>  <u>'hf'</u>                full path name of the main help file

<u>'helpheight'</u>  <u>'hh'</u>              minimum height of a new help window

<u>'helplang'</u>  <u>'hlg'</u>               preferred help languages

<u>'hidden'</u>  <u>'hid'</u>                 don't unload buffer when it is YXXYabandon&vert;ed

<u>'hlsearch'</u>  <u>'hls'</u>               highlight matches with last search pattern

<u>'history'</u>  <u>'hi'</u>                 number of command-lines that are remembered

<u>'hkmap'</u>  <u>'hk'</u>                   Hebrew keyboard mapping

<u>'hkmapp'</u>  <u>'hkp'</u>                 phonetic Hebrew keyboard mapping

<u>'icon'</u>                                 let Vim set the text of the window icon

<u>'iconstring'</u>                           string to use for the Vim icon text

<u>'ignorecase'</u>  <u>'ic'</u>              ignore case in search patterns

<u>'imcmdline'</u>  <u>'imc'</u>              use IM when starting to edit a command line

<u>'imdisable'</u>  <u>'imd'</u>              do not use the IM in any mode

<u>'iminsert'</u>  <u>'imi'</u>               use &colon;lmap or IM in Insert mode

<u>'imsearch'</u>  <u>'ims'</u>               use &colon;lmap or IM when typing a search pattern

<u>'include'</u>  <u>'inc'</u>                pattern to be used to find an include file

<u>'includeexpr'</u>  <u>'inex'</u>           expression used to process an include line

<u>'incsearch'</u>  <u>'is'</u>               highlight match while typing search pattern

<u>'indentexpr'</u>  <u>'inde'</u>            expression used to obtain the indent of a line

<u>'indentkeys'</u>  <u>'indk'</u>            keys that trigger indenting with 'indentexpr'

<u>'infercase'</u>  <u>'inf'</u>              adjust case of match for keyword completion

<u>'insertmode'</u>  <u>'im'</u>              start the edit of a file in Insert mode

<u>'isfname'</u>  <u>'isf'</u>                characters included in file names and pathnames

<u>'isident'</u>  <u>'isi'</u>                characters included in identifiers

<u>'iskeyword'</u>  <u>'isk'</u>              characters included in keywords

<u>'isprint'</u>  <u>'isp'</u>                printable characters

<u>'joinspaces'</u>  <u>'js'</u>              two spaces after a period with a join command

<u>'jumpoptions'</u>  <u>'jop'</u>            specifies how jumping is done

<u>'keymap'</u>  <u>'kmp'</u>                 name of a keyboard mapping

<u>'keymodel'</u>  <u>'km'</u>                enable starting/stopping selection with keys

<u>'keywordprg'</u>  <u>'kp'</u>              program to use for the "K" command

<u>'langmap'</u>  <u>'lmap'</u>               alphabetic characters for other language mode

<u>'langmenu'</u>  <u>'lm'</u>                language to be used for the menus

<u>'langremap'</u>  <u>'lrm'</u>              do apply 'langmap' to mapped characters

<u>'laststatus'</u>  <u>'ls'</u>              tells when last window has status lines

<u>'lazyredraw'</u>  <u>'lz'</u>              don't redraw while executing macros

<u>'linebreak'</u>  <u>'lbr'</u>              wrap long lines at a blank

<u>'lines'</u>                                number of lines in the display

<u>'linespace'</u>  <u>'lsp'</u>              number of pixel lines to use between characters

<u>'lisp'</u>                                 automatic indenting for Lisp

<u>'lispwords'</u>  <u>'lw'</u>               words that change how lisp indenting works

<u>'list'</u>                                 show &lt;Tab&gt; and &lt;EOL&gt;

<u>'listchars'</u>  <u>'lcs'</u>              characters for displaying in list mode

<u>'loadplugins'</u>  <u>'lpl'</u>            load plugin scripts when starting up

<u>'magic'</u>                                changes special characters in search patterns

<u>'makeef'</u>  <u>'mef'</u>                 name of the errorfile for "&colon;make"

<u>'makeencoding'</u>  <u>'menc'</u>          encoding of external make&bsol;grep commands

<u>'makeprg'</u>  <u>'mp'</u>                 program to use for the ":make" command

<u>'matchpairs'</u>  <u>'mps'</u>             pairs of characters that "&percnt;" can match

<u>'matchtime'</u>  <u>'mat'</u>              tenths of a second to show matching paren

<u>'maxcombine'</u>  <u>'mco'</u>             maximum nr of combining characters displayed

<u>'maxfuncdepth'</u>  <u>'mfd'</u>           maximum recursive depth for user functions

<u>'maxmapdepth'</u>  <u>'mmd'</u>            maximum recursive depth for mapping

<u>'maxmempattern'</u>  <u>'mmp'</u>          maximum memory (in Kbyte) used for pattern search

<u>'menuitems'</u>  <u>'mis'</u>              maximum number of items in a menu

<u>'mkspellmem'</u>  <u>'msm'</u>             memory used before &vert;&nbsp;&colon;mkspell&nbsp;&vert; compresses the tagrelative

<u>'modeline'</u>  <u>'ml'</u>                recognize modelines at start or end of file

<u>'modelineexpr'</u>  <u>'mle'</u>           allow setting expression options from a modeline

<u>'modelines'</u>  <u>'mls'</u>              number of lines checked for modelines

<u>'modifiable'</u>  <u>'ma'</u>              changes to the text are not possible

<u>'modified'</u>  <u>'mod'</u>               buffer has been modified

<u>'more'</u>                                 pause listings when the whole screen is filled

<u>'mouse'</u>                                enable the use of mouse clicks

<u>'mousefocus'</u>                           'mousef'  keyboard focus follows the mouse

<u>'mousehide'</u>  <u>'mh'</u>               hide mouse pointer while typing

<u>'mousemodel'</u>  <u>'mousem'</u>          changes meaning of mouse buttons

<u>'mouseshape'</u>                           'mouses'  shape of the mouse pointer in different modes

<u>'mousetime'</u>                            'mouset'  max time between mouse double-click

<u>'nrformats'</u>  <u>'nf'</u>               number formats recognized for &lt;C-a&gt; command

<u>'number'</u>  <u>'nu'</u>                  print the line number in front of each line

<u>'numberwidth'</u>  <u>'nuw'</u>            number of columns used for the line number

<u>'omnifunc'</u>  <u>'ofu'</u>               function for filetype-specific completion

<u>'opendevice'</u>  <u>'odev'</u>            allow reading&bsol;writing devices on MS-Windows

<u>'operatorfunc'</u>  <u>'opfunc'</u>        function to be called for &vert;&nbsp;g&commat;&nbsp;&vert; operator

<u>'packpath'</u>  <u>'pp'</u>                list of directories used for packages

<u>'paragraphs'</u>  <u>'para'</u>            nroff macros that separate paragraphs

<u>'paste'</u>                                allow pasting text

<u>'pastetoggle'</u>  <u>'pt'</u>             key code that causes 'paste' to toggle

<u>'patchexpr'</u>  <u>'pex'</u>              expression used to patch a file

<u>'patchmode'</u>  <u>'pm'</u>               keep the oldest version of a file

<u>'path'</u>  <u>'pa'</u>                    list of directories searched with "gf" et&period;al&period;

<u>'perldll'</u>                              name of the Perl dynamic library

<u>'preserveindent'</u>  <u>'pi'</u>          preserve the indent structure when reindenting

<u>'previewheight'</u>  <u>'pvh'</u>          height of the preview window

<u>'previewpopup'</u>  <u>'pvp'</u>           use popup window for preview

<u>'previewwindow'</u>  <u>'pvw'</u>          identifies the preview window

<u>'printdevice'</u>  <u>'pdev'</u>           name of the printer to be used for &colon;hardcopy

<u>'printencoding'</u>  <u>'penc'</u>         encoding to be used for printing

<u>'printexpr'</u>  <u>'pexpr'</u>            expression used to print PostScript for &colon;hardcopy

<u>'printfont'</u>  <u>'pfn'</u>              name of the font to be used for &colon;hardcopy

<u>'printheader'</u>  <u>'pheader'</u>        format of the header used for &colon;hardcopy

<u>'printmbcharset'</u>  <u>'pmbcs'</u>       CJK character set to be used for &colon;hardcopy

<u>'printmbfont'</u>  <u>'pmbfn'</u>          font names to be used for CJK output of &colon;hardcopy

<u>'printoptions'</u>  <u>'popt'</u>          controls the format of &colon;hardcopy output

<u>'pumheight'</u>  <u>'ph'</u>               maximum height of the popup menu

<u>'pumwidth'</u>  <u>'pw'</u>                minimum width of the popup menu

<u>'pythondll'</u>                            name of the Python 2 dynamic library

<u>'pythonthreedll'</u>                       name of the Python 3 dynamic library

<u>'pyxversion'</u>  <u>'pyx'</u>             Python version used for pyx* commands

<u>'quoteescape'</u>  <u>'qe'</u>             escape characters used in a string

<u>'readonly'</u>  <u>'ro'</u>                disallow writing the buffer

<u>'redrawtime'</u>  <u>'rdt'</u>             timeout for 'hlsearch' and &vert;&nbsp;&colon;match&nbsp;&vert; highlighting

<u>'regexpengine'</u>  <u>'re'</u>            default regexp engine to use

<u>'relativenumber'</u>  <u>'rnu'</u>         show relative line number in front of each line

<u>'remap'</u>                                allow mappings to work recursively

<u>'report'</u>                               threshold for reporting nr&period; of lines changed

<u>'revins'</u>  <u>'ri'</u>                  inserting characters will work backwards

<u>'rightleft'</u>  <u>'rl'</u>               window is right-to-left oriented

<u>'rightleftcmd'</u>  <u>'rlc'</u>           commands for which editing works right-to-left

<u>'rubydll'</u>                              name of the Ruby dynamic library

<u>'ruler'</u>  <u>'ru'</u>                   show cursor line and column in the status line

<u>'rulerformat'</u>  <u>'ruf'</u>            custom format for the ruler

<u>'runtimepath'</u>  <u>'rtp'</u>            list of directories used for runtime files

<u>'scroll'</u>  <u>'scr'</u>                 lines to scroll with &lt;C-u&gt; and &lt;C-d&gt;

<u>'scrollbind'</u>  <u>'scb'</u>             scroll in window as other windows scroll

<u>'scrolljump'</u>  <u>'sj'</u>              minimum number of lines to scroll

<u>'scrolloff'</u>  <u>'so'</u>               minimum nr&period; of lines above and below cursor

<u>'scrollopt'</u>  <u>'sbo'</u>              how 'scrollbind' should behave

<u>'sections'</u>  <u>'sect'</u>              nroff macros that separate sections

<u>'secure'</u>                               secure mode for reading &period;vimrc in current dir

<u>'selection'</u>  <u>'sel'</u>              what type of selection to use

<u>'selectmode'</u>  <u>'slm'</u>             when to use Select mode instead of Visual mode

<u>'sessionoptions'</u>  <u>'ssop'</u>        options for &vert;&nbsp;&colon;mksession&nbsp;&vert;

<u>'shada'</u>  <u>'sd'</u>                   use &period;shada file upon startup and exiting

<u>'shell'</u>  <u>'sh'</u>                   name of shell to use for external commands

<u>'shellcmdflag'</u>  <u>'shcf'</u>          flag to shell to execute one command

<u>'shellpipe'</u>  <u>'sp'</u>               string to put output of "&colon;make" in error file

<u>'shellquote'</u>  <u>'shq'</u>             quote character(s) for around shell command

<u>'shellredir'</u>  <u>'srr'</u>             string to put output of filter in a temp file

<u>'shellslash'</u>  <u>'ssl'</u>             use forward slash for shell file names

<u>'shelltemp'</u>  <u>'stmp'</u>             whether to use a temp file for shell commands

<u>'shellxescape'</u>  <u>'sxe'</u>           characters to escape when 'shellxquote' is &lpar;

<u>'shellxquote'</u>  <u>'sxq'</u>            like 'shellquote', but include redirection

<u>'shiftround'</u>  <u>'sr'</u>              round indent to multiple of shiftwidth

<u>'shiftwidth'</u>  <u>'sw'</u>              number of spaces to use for (auto)indent step

<u>'shortmess'</u>  <u>'shm'</u>              list of flags, reduce length of messages

<u>'showbreak'</u>  <u>'sbr'</u>              string to use at the start of wrapped lines

<u>'showcmd'</u>  <u>'sc'</u>                 show (partial) command in status line

<u>'showfulltag'</u>  <u>'sft'</u>            show full tag pattern when completing tag

<u>'showmatch'</u>  <u>'sm'</u>               briefly jump to matching bracket if insert one

<u>'showmode'</u>  <u>'smd'</u>               message on status line to show current mode

<u>'showtabline'</u>  <u>'stal'</u>           tells when the tab pages line is displayed

<u>'sidescroll'</u>  <u>'ss'</u>              minimum number of columns to scroll horizontal

<u>'sidescrolloff'</u>  <u>'siso'</u>         min&period; nr&period; of columns to left and right of cursor

<u>'signcolumn'</u>  <u>'scl'</u>             when and how to display the sign column

<u>'smartcase'</u>  <u>'scs'</u>              no ignore case when pattern has uppercase

<u>'smartindent'</u>  <u>'si'</u>             smart autoindenting for C programs

<u>'smarttab'</u>  <u>'sta'</u>               use 'shiftwidth' when inserting &lt;Tab&gt;

<u>'softtabstop'</u>  <u>'sts'</u>            number of spaces that &lt;Tab&gt; uses while editing

<u>'spell'</u>                                enable spell checking

<u>'spellcapcheck'</u>  <u>'spc'</u>          pattern to locate end of a sentence

<u>'spellfile'</u>  <u>'spf'</u>              files where &vert;&nbsp;zg&nbsp;&vert; and &vert;&nbsp;zw&nbsp;&vert; store words

<u>'spelllang'</u>  <u>'spl'</u>              language(s) to do spell checking for

<u>'spelloptions'</u>  <u>'spo'</u>           options for spell checking

<u>'spellsuggest'</u>  <u>'sps'</u>           method(s) used to suggest spelling corrections

<u>'splitbelow'</u>  <u>'sb'</u>              new window from split is below the current one

<u>'splitright'</u>  <u>'spr'</u>             new window is put right of the current one

<u>'startofline'</u>  <u>'sol'</u>            commands move cursor to first non-blank in line

<u>'statusline'</u>  <u>'stl'</u>             custom format for the status line

<u>'suffixes'</u>  <u>'su'</u>                suffixes that are ignored with multiple match

<u>'suffixesadd'</u>  <u></u>                 suffixes added when searching for a file

<u>'swapfile'</u>  <u>'swf'</u>               whether to use a swapfile for a buffer

<u>'switchbuf'</u>  <u>'swb'</u>              sets behavior when switching to another buffer

<u>'synmaxcol'</u>  <u>'smc'</u>              maximum column to find syntax items

<u>'syntax'</u>  <u>'syn'</u>                 syntax to be loaded for current buffer

<u>'tabline'</u>  <u>'tal'</u>                custom format for the console tab pages line

<u>'tabpagemax'</u>  <u>'tpm'</u>             maximum number of tab pages for &vert;&nbsp;-p&nbsp;&vert; and "tab all"

<u>'tabstop'</u>  <u>'ts'</u>                 number of spaces that &lt;Tab&gt; in file uses

<u>'tagbsearch'</u>  <u>'tbs'</u>             use binary searching in tags files

<u>'tagcase'</u>  <u>'tc'</u>                 how to handle case when searching in tags files

<u>'taglength'</u>  <u>'tl'</u>               number of significant characters for a tag

<u>'tagrelative'</u>  <u>'tr'</u>             file names in tag file are relative

<u>'tags'</u>  <u>'tag'</u>                   list of file names used by the tag command

<u>'tagstack'</u>  <u>'tgst'</u>              push tags onto the tag stack

<u>'term'</u>                                 name of the terminal

<u>'termbidi'</u>  <u>'tbidi'</u>             terminal takes care of bi-directionality

<u>'terse'</u>                                shorten some messages

<u>'textwidth'</u>  <u>'tw'</u>               maximum width of text that is being inserted

<u>'thesaurus'</u>  <u>'tsr'</u>              list of thesaurus files for keyword completion

<u>'thesaurusfunc'</u>  <u>'tsrfu'</u>        function to be used for thesaurus completion

<u>'tildeop'</u>  <u>'top'</u>                tilde command "&tilde;" behaves like an operator

<u>'timeout'</u>  <u>'to'</u>                 time out on mappings and key codes

<u>'timeoutlen'</u>  <u>'tm'</u>              time out time in milliseconds

<u>'title'</u>                                let Vim set the title of the window

<u>'titlelen'</u>                             percentage of 'columns' used for window title

<u>'titleold'</u>                             old title, restored when exiting

<u>'titlestring'</u>                          string to use for the Vim window title

<u>'ttimeout'</u>                             time out on mappings

<u>'ttimeoutlen'</u>  <u>'ttm'</u>            time out time for key codes in milliseconds

<u>'ttytype'</u>  <u>'tty'</u>                alias for 'term'

<u>'undodir'</u>  <u>'udir'</u>               where to store undo files

<u>'undofile'</u>  <u>'udf'</u>               save undo information in a file

<u>'undolevels'</u>  <u>'ul'</u>              maximum number of changes that can be undone

<u>'undoreload'</u>  <u>'ur'</u>              max nr of lines to save for undo on a buffer reload

<u>'updatecount'</u>  <u>'uc'</u>             after this many characters flush swap file

<u>'updatetime'</u>  <u>'ut'</u>              after this many milliseconds flush swap file

<u>'varsofttabstop'</u>  <u>'vsts'</u>        a list of number of spaces when typing &lt;Tab&gt;

<u>'vartabstop'</u>  <u>'vts'</u>             a list of number of spaces for &lt;Tab&>s

<u>'verbose'</u>  <u>'vbs'</u>                give informative messages

<u>'verbosefile'</u>  <u>'vfile'</u>          file to write messages in

<u>'viewdir'</u>  <u>'vdir'</u>               directory where to store files with &colon;mkview

<u>'viewoptions'</u>  <u>'vop'</u>            specifies what to save for &colon;mkview

<u>'virtualedit'</u>  <u>'ve'</u>             when to use virtual editing

<u>'visualbell'</u>  <u>'vb'</u>              use visual bell instead of beeping

<u>'warn'</u>                                 warn for shell command when buffer was changed

<u>'whichwrap'</u>  <u>'ww'</u>               allow specified keys to cross line boundaries

<u>'wildchar'</u>  <u>'wc'</u>                command-line character for wildcard expansion

<u>'wildcharm'</u>  <u>'wcm'</u>              like 'wildchar' but also works when mapped

<u>'wildignore'</u>  <u>'wig'</u>             files matching these patterns are not completed

<u>'wildignorecase'</u>  <u>'wic'</u>         ignore case when completing file names

<u>'wildmenu'</u>  <u>'wmnu'</u>              use menu for command line completion

<u>'wildmode'</u>  <u>'wim'</u>               mode for 'wildchar' command-line expansion

<u>'wildoptions'</u>  <u>'wop'</u>            specifies how command line completion is done

<u>'winaltkeys'</u>  <u>'wak'</u>             when the windows system handles &lt;Alt&gt; keys

<u>'window'</u>  <u>'wi'</u>                  nr of lines to scroll for &lt;C-f&gt; and &lt;C-b&gt;

<u>'winheight'</u>  <u>'wh'</u>               minimum number of lines for the current window

<u>'winhighlight'</u>  <u>'winhl'</u>         window-local highlighting

<u>'winfixheight'</u>  <u>'wfh'</u>           keep window height when opening&bsol;closing windows

<u>'winfixwidth'</u>  <u>'wfw'</u>            keep window width when opening&bsol;closing windows

<u>'winminheight'</u>  <u>'wmh'</u>           minimum number of lines for any window

<u>'winminwidth'</u>  <u>'wmw'</u>            minimal number of columns for any window

<u>'winwidth'</u>  <u>'wiw'</u>               minimal number of columns for current window

<u>'wrap'</u>                                 long lines wrap and continue on the next line

<u>'wrapmargin'</u>  <u>'wm'</u>              chars from the right where wrapping starts

<u>'wrapscan'</u>  <u>'ws'</u>                searches wrap around the end of the file

<u>'write'</u>                                writing to a file is allowed

<u>'writeany'</u>  <u>'wa'</u>                write to file with no need for "!" override

<u>'writebackup'</u>  <u>'wb'</u>             make a backup before overwriting a file

<u>'writedelay'</u>  <u>'wd'</u>              delay this many msec for each char (for debug)

## LAZYVIM

### Installation

#### Linux/MacOS

- Встановити початкову конфігурацію

```bash
git clone https://github.com/LazyVim/starter ~/.config/nvim
```

- Запустити NeoVim

```bash
nvim
```

>[!TIP]
>
>Після встановлення запустити :checkhealth

### Keymaps

- за замовчуванням `<leader>` - <kbd>Space</kbd>
- локальний `<leader>` за замовчуванням - <kbd>\\</kbd>

>&#128161; Для запам'ятовування комбінацій клавіш. Просто натисніть будь-яку клавішу, наприклад <kbd>Space</kbd>, і ви побачите спливаюче вікно з усіма можливими комбінаціями клавіш, що починаються з <kbd>Space</kbd>.

<img src="image\lazyvim-keymaps.png" title="LazyVim Keymaps"/>

#### Загальні

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Перехід до лівого вікна | n, t | <kbd>Ctrl</kbd>-<kbd>h</kbd> |
| Перехід до нижнього вікна | n, t | <kbd>Ctrl</kbd>-<kbd>j</kbd> |
| Перехід до верхнього вікна | n, t | <kbd>Ctrl</kbd>-<kbd>k</kbd> |
| Перехід до правого вікна | n, t | <kbd>Ctrl</kbd>-<kbd>l</kbd> |
| Збільшити висоту вікна | n | <kbd>Ctrl</kbd>-arrow_up |
| Зменшити висоту вікна | n | <kbd>Ctrl</kbd>-arrow_down |
| Зменшити ширину вікна | n | <kbd>Ctrl</kbd>-arrow_left |
| Збільшити ширину вікна | n | <kbd>Ctrl</kbd>-arrow_right |
| Переміщення вниз | n, i, v | <kbd>Alt</kbd>-<kbd>j</kbd> |
| Перемістити вгору | n, i, v | <kbd>Alt</kbd>-<kbd>k</kbd> |
| Попередній буфер | n | <kbd>Shift</kbd>-<kbd>h</kbd>, <kbd>[</kbd><kbd>b</kbd> |
| Наступний буфер | n | <kbd>Shift</kbd>-<kbd>l</kbd>, <kbd>]</kbd><kbd>b</kbd> |
| Перехід до іншого буфера | n | `<leader>`<kbd>b</kbd><kbd>b</kbd>, `<leader>`<kbd>`</kbd> |
| Вихід та очищення hlsearch | i, n | <kbd>Esc</kbd> |
| Перемалювати / очистити hlsearch / оновити diff | n | `<leader>`<kbd>u</kbd><kbd>r</kbd> |
| Наступний результат пошуку | n, x, o | <kbd>n</kbd> |
| Попередній результат пошуку | n, x, o | <kbd>N</kbd> |
| Зберегти файл | i, x, n, s | <kbd>Ctrl</kbd>-<kbd>s</kbd> |
| Ключове словоprg | n | `<leader>`<kbd>K</kbd> |
| Лінивий | n | `<leader>`<kbd>l</kbd> |
| Новий файл | n | `<leader>`<kbd>f</kbd><kbd>n</kbd> |
| Список розташування | n | `<leader>`<kbd>x</kbd><kbd>l</kbd> |
| Список швидких виправлень | n | `<leader>`<kbd>x</kbd><kbd>q</kbd> |
| Попереднє виправлення | n | <kbd></kbd>[<kbd>q</kbd> |
| Наступне швидке виправлення | n | <kbd>]</kbd><kbd>q</kbd> |
| Формат | n, v | `<leader>`<kbd>c</kbd><kbd>f</kbd> |
| Діагностика лінії | n | `<leader>`<kbd>c</kbd><kbd>d</kbd> |
| Наступна діагностика | n | <kbd>]</kbd><kbd>d</kbd> |
| Попередня діагностика | n | <kbd>[</kbd><kbd>d</kbd> |
| Наступна помилка | n | <kbd>]</kbd><kbd>e</kbd> |
| Попередня помилка | n | <kbd>[</kbd><kbd>e</kbd> |
| Наступне попередження | n | <kbd>]</kbd><kbd>w</kbd> |
| Попереднє попередження | n | <kbd>[</kbd><kbd>w</kbd> |
| Переключити автоформат (глобальний) | n | `<leader>`<kbd>u</kbd><kbd>f</kbd> |
| Увімкнути автоматичний формат (буферний) | n | `<leader>`<kbd>u</kbd><kbd>F</kbd> |
| Переключити правопис | n | `<leader>`<kbd>u</kbd><kbd>s</kbd> |
| Увімкнути перенесення слів | n | `<leader>`<kbd>u</kbd><kbd>w</kbd> |
| Увімкнути відносні номери рядків | n | `<leader>`<kbd>u</kbd><kbd>L</kbd> |
| Перемикання номерів рядків | n | `<leader>`<kbd>u</kbd><kbd>l</kbd> |
| Переключити діагностику | n | `<leader>`<kbd>u</kbd><kbd>d</kbd> |
| Увімкнути приховування | n | `<leader>`<kbd>u</kbd><kbd>c</kbd> |
| Увімкнути підказки вкладки | n | `<leader>`<kbd>u</kbd><kbd>h</kbd> |
| Увімкнути підсвічування дерев | n | `<leader>`<kbd>u</kbd><kbd>T</kbd> |
| Lazygit (кореневий каталог) | n | `<leader>`<kbd>g</kbd><kbd>g</kbd> |
| Lazygit (cwd) | n | `<leader>`<kbd>g</kbd><kbd>G</kbd> |
| Вийти з усіх | n | `<leader>`<kbd>q</kbd><kbd>q</kbd> |
| Перевірити позицію | n | `<leader>`<kbd>u</kbd><kbd>i</kbd> |
| LazyVim Журнал змін | n | `<leader>`<kbd>L</kbd> |
| Термінал (кореневий каталог) | n | `<leader>`<kbd>f</kbd><kbd>t</kbd> |
| Термінал (cwd) | n | `<leader>`<kbd>f</kbd><kbd>T</kbd> |
| Термінал (кореневий каталог) | n | <kbd>Ctrl</kbd>-<kbd>/</kbd> |
| which_key_ignore | n, t | <kbd>Ctrl</kbd>-<kbd>_</kbd> |
| Увійти у звичайний режим | t | <kbd>Esc</kbd><kbd>Esc</kbd> |
| Приховати термінал | t | <kbd>Ctrl</kbd>-<kbd>/</kbd> |
| Інше вікно | n `<leader>`<kbd>w</kbd><kbd>w</kbd> |
| Видалити вікно | n | `<leader>`<kbd>w</kbd><kbd>d</kbd> |
| Розділити вікно нижче | n | `<leader>`<kbd>w</kbd><kbd>-</kbd> |
| Розділити вікно праворуч | n | `<leader>`<kbd>w</kbd><kbd>\|</kbd> |
| Розділити вікно нижче | n | `<leader>`<kbd>-</kbd> |
| Розділити вікно праворуч | n | `<leader>`<kbd>\|</kbd> |
| Останній табулятор | n | `<leader>`<kbd>Tab</kbd><kbd>l</kbd> |
| Перша вкладка | n | `<leader>`<kbd>Tab</kbd><kbd>f</kbd> |
| Нова вкладка | n | `<leader>`<kbd>Tab</kbd><kbd>Tab</kbd> |
| Наступний табулятор | n | `<leader>`<kbd>Tab</kbd><kbd>]</kbd> |
| Закрити табуляцію | n | `<leader>`<kbd>Tab</kbd><kbd>d</kbd> |
| Previous Tab | n | `<leader>`<kbd>Tab</kbd><kbd>[</kbd> |

#### LSP

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Lsp Info | n | `<leader>`<kbd>c</kbd><kbd>l</kbd> |
| Перейти до визначення | n | <kbd>g</kbd><kbd>d</kbd> |
| Посилання | n | <kbd>g</kbd><kbd>r</kbd> |
| Декларація goto | n | <kbd>g</kbd><kbd>D</kbd> |
| Реалізація Goto | n | <kbd>g</kbd><kbd>I</kbd> |
| Goto T[y]pe Визначення | n | <kbd>g</kbd><kbd>y</kbd> |
| Наведення | n | <kbd>K</kbd> |
| Допомога за підписом | n | <kbd>g</kbd><kbd>K</kbd> |
| Підказка до підпису | i | <kbd>Ctrl</kbd>-<kbd>k</kbd> |
| Код дії | n, v | `<leader>`<kbd>c</kbd><kbd>a</kbd> |
| Дія джерела | n | `<leader>`<kbd>c</kbd><kbd>A</kbd> |
| Перейменувати | n | `<leader>`<kbd>c</kbd><kbd>r</kbd> |

#### bufferline.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Видалити буфери ліворуч | n | `<leader>`<kbd>b</kbd><kbd>l</kbd> |
| Видалити інші буфери | n | `<leader>`<kbd>b</kbd><kbd>o</kbd> |
| Перемикання виводу | n | `<leader>`<kbd>b</kbd><kbd>p</kbd> |
| Видалення не закріплених буферів | n | `<leader>`<kbd>b</kbd><kbd>P</kbd> |
| Видалення буферів праворуч | n | `<leader>`<kbd>b</kbd><kbd>r</kbd> |
| Попередній буфер | n | <kbd>[</kbd><kbd>b</kbd> |
| Наступний буфер | n | <kbd>]</kbd><kbd>b</kbd> |
| Попередній буфер | n | <kbd>Shift</kbd>-<kbd>h</kbd> |
| Наступний буфер | n | <kbd>Shift</kbd>-<kbd>l</kbd> |

#### conform.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Формат Формат інжектованих мов | n, v | `<leader>`<kbd>c</kbd><kbd>F</kbd> |

#### flash.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Перемикання пошуку спалаху | c | <kbd>Ctrl</kbd>-<kbd>s</kbd> |
| Віддалений спалах | o | <kbd>r</kbd> |
| Пошук за деревами | o, x | <kbd>R</kbd> |
| Спалах | n, o, x | <kbd>s</kbd> |
| Пошук спалахів | n, o, x | <kbd>S</kbd> |

#### mason.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Mason | n | `<leader>`<kbd>c</kbd><kbd>m</kbd> |

#### mini.bufremove

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Видалити буфер | n | `<leader>`<kbd>b</kbd><kbd>d</kbd> |
| Видалити буфер (примусово) n<leader>bD 

#### mini.pairs

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Перемикання автоматичних пар | n | `<leader>`<kbd>u</kbd><kbd>p</kbd> |

#### mini.surround

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Додати оточення | n, v | <kbd>g</kbd><kbd>s</kbd><kbd>a</kbd> |
| Видалити оточення | n | <kbd>g</kbd><kbd>s</kbd><kbd>d</kbd> |
| Знайти праве оточення | n | <kbd>g</kbd><kbd>s</kbd><kbd>f</kbd> |
| Знайти ліве оточення | n | <kbd>g</kbd><kbd>s</kbd><kbd>F</kbd> |
| Виділити оточення | n | <kbd>g</kbd><kbd>s</kbd><kbd>h</kbd> |
| Оновити MiniSurround.config.n_lines | n | <kbd>g</kbd><kbd>s</kbd>n</kbd> |
| Замінити оточення | n | <kbd>g</kbd><kbd>s</kbd><kbd>r</kbd> |

#### neo-tree.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Буферний провідник | n | `<leader>`<kbd>b</kbd><kbd>e</kbd> |
| Провідник NeoTree (кореневий каталог) | n | `<leader>`<kbd>e</kbd> |
| Провідник NeoTree (cwd) | n | `<leader>`<kbd>E</kbd> |
| Explorer NeoTree (кореневий каталог) | n | `<leader>`<kbd>f</kbd><kbd>e</kbd> |
| Explorer NeoTree (cwd) | n | `<leader>`<kbd>f</kbd><kbd>E</kbd> |
| Провідник Git'а | n | `<leader>`<kbd>g</kbd><kbd>e</kbd> |

#### noice.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Прокрутка назад | n, i, s | <kbd>Ctrl</kbd>-<kbd>b</kbd> |
| Прокрутка вперед | n, i, s | <kbd>Ctrl</kbd>-<kbd>f</kbd> |
| Сповістити всіх | n | `<leader>`<kbd>s</kbd><kbd>n</kbd><kbd>a</kbd> |
| Пропустити всі | n | `<leader>`<kbd>s</kbd><kbd>n</kbd><kbd>d</kbd> |
| Історія повідомлень | n | `<leader>`<kbd>s</kbd><kbd>n</kbd><kbd>h</kbd> |
| Сповістити про останнє повідомлення | n | `<leader>`<kbd>s</kbd><kbd>n</kbd><kbd>l</kbd> |
| Перенаправити командний рядок | c | <kbd>Shift</kbd>-<kbd>Enter</kbd> |

#### nvim-notify

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Відхилити всі сповіщення | n | `<leader>`<kbd>u</kbd><kbd>n</kbd> |

#### nvim-spectre

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Замінити у файлах (Spectre) | n | `<leader>`<kbd>s</kbd><kbd>r</kbd> |

#### nvim-treesitter

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Виділення за декрементом | x | <kbd>Backspace</kbd> |
| Виділення за збільшенням | n | <kbd>Ctrl</kbd>-<kbd>Space</kbd> |

#### nvim-treesitter-context

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Перемикання контексту обрізувача дерев | n | `<leader>`<kbd>u</kbd><kbd>t</kbd> |

#### persistence.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Не зберігати поточний сеанс | n | `<leader>`<kbd>q</kbd><kbd>d</kbd> |
| Відновити останній сеанс | n | `<leader>`<kbd>q</kbd><kbd>l</kbd> |
| Відновити сеанс | n | `<leader>`<kbd>q</kbd><kbd>s</kbd> |

#### telescope.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Знайти файли (кореневий каталог) | n | `<leader>`<kbd>Space</kbd> |
| Switch Buffer | n | `<leader>`<kbd>,</kbd> |
| Grep (root dir) | n | `<leader>`<kbd>/</kbd> |
| Історія команд | n | `<leader>`<kbd>:</kbd> |
| Буфери | n | `<leader>`<kbd>f</kbd><kbd>b</kbd> |
| Знайти конфігураційний файл | n | `<leader>`<kbd>f</kbd><kbd>c</kbd> |
| Знайти файли (кореневий каталог) | n | `<leader>`<kbd>f</kbd><kbd>f</kbd> |
| Знайти файли (cwd) | n | `<leader>`<kbd>f</kbd><kbd>F</kbd> |
| Останні | n | `<leader>`<kbd>f</kbd><kbd>r</kbd> |
| Останні (cwd) | n | `<leader>`<kbd>f</kbd><kbd>R</kbd> |
| комміти | n | `<leader>`<kbd>g</kbd><kbd>c</kbd> |
| статус | n | `<leader>`<kbd>g</kbd><kbd>s</kbd> |
| Регістри | n | `<leader>`<kbd>s</kbd><kbd>"</kbd> |
| Автоматичні команди | n | `<leader>`<kbd>s</kbd><kbd>a</kbd> |
| Буфер | n | `<leader>`<kbd>s</kbd><kbd>b</kbd> |
| Історія команд | n | `<leader>`<kbd>s</kbd><kbd>c</kbd> |
| Команди | n | `<leader>`<kbd>s</kbd><kbd>C</kbd> |
| Діагностика документів | n | `<leader>`<kbd>s</kbd><kbd>d</kbd> |
| Діагностика робочого простору | n | `<leader>`<kbd>s</kbd><kbd>D</kbd> |
| Grep (кореневий каталог) | n | `<leader>`<kbd>s</kbd><kbd>g</kbd> |
| Grep (cwd) | n | `<leader>`<kbd>s</kbd><kbd>G</kbd> |
| Сторінки довідки | n | `<leader>`<kbd>s</kbd><kbd>h</kbd> |
| Групи виділення пошуку | n | `<leader>`<kbd>s</kbd><kbd>H</kbd> |
| Карти ключів | n | `<leader>`<kbd>s</kbd><kbd>k</kbd> |
| Перехід до позначки | n | `<leader>`<kbd>s</kbd><kbd>m</kbd> |
| Сторінки користувача | n | `<leader>`<kbd>s</kbd><kbd>M</kbd> |
| Параметри | n | `<leader>`<kbd>s</kbd><kbd>o</kbd> |
| Продовжити | n | `<leader>`<kbd>s</kbd><kbd>R</kbd> |
| Перейти до символу | n | `<leader>`<kbd>s</kbd><kbd>s</kbd> |
| Перехід до символу (робоча область) | n | `<leader>`<kbd>s</kbd><kbd>S</kbd> |
| Слово (кореневий каталог) | n | `<leader>`<kbd>s</kbd><kbd>w</kbd> |
| Слово (cwd) | n | `<leader>`<kbd>s</kbd><kbd>W</kbd> |
| Виділення (кореневий каталог) | v | `<leader>`<kbd>s</kbd><kbd>w</kbd> |
| Selection (cwd) | v | `<leader>`<kbd>s</kbd><kbd>W</kbd> |
| Колірна схема з попереднім переглядом | n | `<leader>`<kbd>u</kbd><kbd>C</kbd> |

#### todo-comments.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Todo | n | `<leader>`<kbd>s</kbd><kbd>t</kbd> |
| Todo/Fix/Fixme | n | `<leader>`<kbd>s</kbd><kbd>T</kbd> |
| Todo (Trouble) | n | `<leader>`<kbd>x</kbd><kbd>t</kbd> |
| Todo/Fix/Fixme (Проблема) | n | `<leader>`<kbd>x</kbd><kbd>T</kbd> |
| Попередній коментар до справи | n | <kbd>[</kbd><kbd>t</kbd> |
| Наступний коментар до справи | n | <kbd>]</kbd><kbd>t</kbd> |

#### trouble.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Список локацій (Trouble) | n | `<leader>`<kbd>x</kbd><kbd>L</kbd> |
| Список швидкого виправлення (проблема) | n | `<leader>`<kbd>x</kbd><kbd>Q</kbd> |
| Діагностика документа (проблема) | n | `<leader>`<kbd>x</kbd><kbd>x</kbd> |
| Діагностика робочої області (проблема) | n | `<leader>`<kbd>x</kbd><kbd>X</kbd> |
| Попередня проблема/швидке виправлення | n | <kbd>[</kbd><kbd>q</kbd> |
| Наступна проблема/пункт швидкого виправлення | n | <kbd>]</kbd><kbd>q</kbd> |

#### vim-illuminate

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Попереднє посилання | n | <kbd>[</kbd><kbd>[</kbd> |
| Наступне посилання | n | <kbd>]</kbd><kbd>]</kbd>	|

#### yanky.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Відкрити історію янки | n | `<leader>`<kbd>p</kbd> |
| Поставити з відступом зліва | n | <kbd><</kbd><kbd>p</kbd> |
| Поставити перед і залишити відступ зліва | n | <kbd><</kbd><kbd>p</kbd> |
| Поставити після застосування фільтра | n | <kbd>=</kbd><kbd>p</kbd> |
| Поставити перед застосуванням фільтра | n | <kbd>=</kbd><kbd>p</kbd> |
| Поставити з відступом вправо | n | <kbd><</kbd><kbd>p</kbd> |
| Поставити перед і відступити вправо | n | <kbd>></kbd><kbd>P</kbd> |
| Поставити з відступом перед курсором (лінійно) | n | <kbd>[</kbd><kbd>p</kbd> |
| Поставити відступ перед курсором (лінійний) | n | <kbd>[</kbd><kbd>P</kbd> |
| Циклічно переходити вперед по історії якихось подій | n | <kbd>[</kbd><kbd>y</kbd> |
| Ставити відступ після курсору (лінійний) | n | <kbd>]</kbd><kbd>p</kbd> |
| Ставити відступ після курсору (лінійний) | n | <kbd>]</kbd><kbd>P</kbd> |
| Цикл назад по історії висмикування | n | <kbd>]</kbd><kbd>y</kbd> |
| Помістити виділений текст після виділення | n, x | <kbd>g</kbd><kbd>p</kbd> |
| Поставити виділений текст перед виділенням | n, x | <kbd>g</kbd><kbd>P</kbd> |
| Помістити виділений текст після курсору | n, x | <kbd>p</kbd> |
| Помістити виділений текст перед курсором | n, x | <kbd>P</kbd> |
| Витягнути текст | n, x | <kbd>y</kbd> |

#### nvim-dap

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Запустити з аргументами | n | `<leader>`<kbd>d</kbd><kbd>a</kbd> |
| Перемикати точку зупинки | n | `<leader>`<kbd>d</kbd><kbd>b</kbd> |
| Умова точки зупинки | n | `<leader>`<kbd>d</kbd><kbd>B</kbd> |
| Продовжити | n | `<leader>`<kbd>d</kbd><kbd>c</kbd> |
| Перейти до курсору | n | `<leader>`<kbd>d</kbd><kbd>C</kbd> |
| Перехід до рядка (без виконання) | n | `<leader>`<kbd>d</kbd><kbd>g</kbd> |
| Крок всередину | n | `<leader>`<kbd>d</kbd><kbd>i</kbd> |
| Вниз | n | `<leader>`<kbd>d</kbd><kbd>j</kbd> |
| Вгору | n | `<leader>`<kbd>d</kbd><kbd>k</kbd> |
| Виконати останнім | n | `<leader>`<kbd>d</kbd><kbd>l</kbd> |
| Крок назовні | n | `<leader>`<kbd>d</kbd><kbd>o</kbd> |
| Переступити | n | `<leader>`<kbd>d</kbd><kbd>O</kbd> |
| Пауза | n | `<leader>`<kbd>d</kbd><kbd>p</kbd> |
| Toggle REPL | n | `<leader>`<kbd>d</kbd><kbd>r</kbd> |
| Сеанс | n | `<leader>`<kbd>d</kbd><kbd>s</kbd> |
| Завершити | n | `<leader>`<kbd>d</kbd><kbd>t</kbd> |
| Віджети | n | `<leader>`<kbd>d</kbd><kbd>w</kbd> |

#### nvim-dap-ui

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Eval | n, v | `<leader>`<kbd>d</kbd><kbd>e</kbd> |
| Dap UI | n | `<leader>`<kbd>d</kbd><kbd>u</kbd> |

#### aerial.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Антена (символи) | n | `<leader>`<kbd>c</kbd><kbd>s</kbd> |

#### telescope.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Перехід до символу (Антена) | n | `<leader>`<kbd>s</kbd><kbd>s</kbd> |

#### flit.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| f | n, o, x | <kbd>f</kbd> |
| F | n, o, x | <kbd>F</kbd> |
| t | n, o, x | <kbd>t</kbd> |
| T | n, o, x | <kbd>T</kbd> |

#### leap.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Перехід з вікон | n, o, x | <kbd>g</kbd><kbd>s</kbd> |
| Перехід вперед до | n, o, x | <kbd>s</kbd> |
| Перехід назад до | n, o, x | <kbd>S</kbd> |

#### mini.files

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Відкрити міні-файли (каталог поточного файлу) | n | `<leader>`<kbd>f</kbd><kbd>m</kbd> |
| Відкрити міні-файли (cwd) | n | `<leader>`<kbd>f</kbd><kbd>M</kbd> |

#### symbols-outline.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Контур символів | n | `<leader>`<kbd>c</kbd><kbd>s</kbd> |

#### markdown-preview.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Попередній перегляд націнки | n | `<leader>`<kbd>c</kbd><kbd>p</kbd> |

#### nvim-dap-python

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Debug Class | n | `<leader>`<kbd>d</kbd><kbd>P</kbd><kbd>c</kbd> |
| Метод налагодження | n | `<leader>`<kbd>d</kbd><kbd>P</kbd><kbd>t</kbd> |

#### venv-selector.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Вибрати VirtualEnv | n | `<leader>`<kbd>c</kbd><kbd>v</kbd> |

#### neotest

| опис | режим | клавіши |
|-----:|:-----:|---------|
| для показу виводу | n | `<leader>`<kbd>t</kbd><kbd>o</kbd> |
| Перемкнути панель виводу | n | `<leader>`<kbd>t</kbd><kbd>O</kbd> |
| Запустити найближчий | n | `<leader>`<kbd>t</kbd><kbd>r</kbd> |
| Перемкнути підсумок | n | `<leader>`<kbd>t</kbd><kbd>s</kbd> |
| Зупинити | n | `<leader>`<kbd>t</kbd><kbd>S</kbd> |
| Виконати файл | n | `<leader>`<kbd>t</kbd><kbd>t</kbd> |
| Виконати усі тестові файли | n | `<leader>`<kbd>t</kbd><kbd>T</kbd> |

#### nvim-dap

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Налагоджувати найближчий | n | `<leader>`<kbd>t</kbd><kbd>d</kbd> |

#### edgy.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Edgy Перемикання | n | `<leader>`<kbd>u</kbd><kbd>e</kbd> |
| Edgy Вибрати вікно | n | `<leader>`<kbd>u</kbd><kbd>E</kbd> |

#### project.nvim

| опис | режим | клавіши |
|-----:|:-----:|---------|
| Проекти | n | `<leader>`<kbd>f</kbd><kbd>p</kbd> |

### Конфігурація

#### Структура файлів

```
~/.config/nvim
├── lua
│   ├── config
│   │   ├── autocmds.lua
│   │   ├── keymaps.lua
│   │   ├── lazy.lua
│   │   └── options.lua
│   └── plugins
│       ├── spec1.lua
│       ├── **
│       └── spec2.lua
└── init.toml
```

>&#128161; Файли `autocmds.lua`, `keymaps.lua`, `lazy.lua` та `options.lua` у `lua/config` буде автоматично завантажено. LazyVim постачається з набором конфігураційних файлів за замовчуванням, які будуть завантажені перед вашими власними. Але `autocmds.lua`, `keymaps.lua`, `lazy.lua`, `options.lua` можна переписати під себе.

##### Плагіни

>&#128161; Ви можете структурувати теку `lua/plugins` за допомогою файлів для кожного плагіна або окремого файлу, що містить усі специфікації плагіна для певної функціональності.

- Приклад додання плагіну `lua/plugins/wakatime.lua`

```lua
return {
	{ "wakatime/vim-wakatime" },
}
```

- Приклад вимкнення плагіна

```lua
return {
  { "wakatime/vim-wakatime", enabled = false },
}
```
###### Налаштування специфікацій плагіна

Правила злиття за замовчуванням:

>&#128161; будь-яка інша властивість замінить значення за замовчуванням

- cmd: список команд буде розширено вашими власними командами
- event: список подій буде доповнено вашими власними подіями
- ft: список типів файлів буде доповнено вашими власними типами файлів
- keys: список комбінацій клавіш буде доповнено вашими власними комбінаціями клавіш
- opts: ваші кастомні opts буде об'єднано зі стандартними opts
- dependencies: список залежностей буде доповнено вашими власними залежностями

##### Мапа клавіш

>&#128161; LazyVim надає кілька способів налаштування комбінацій клавіш. Якщо ви хочете замінити існуючу розкладку, переконайтеся, що спочатку вимкнули її у потрібному місці.

###### Глобальні комбінації клавіш

>&#128161; Глобальні комбінації клавіш - це комбінації клавіш, які завжди активні. Ви можете налаштувати їх у файлі `lua/config/keymaps.lua`. Стандартні карти клавіш LazyVim можна видалити за допомогою `vim.keymap.del`.

###### Мапа клавіш плагінів

>&#128161; Докладнішу інформацію про налаштування карт клавіш плагінів наведено у розділі Додавання та вимкнення карт клавіш плагінів

###### LSP-зображення клавіш

>&#128161; Це типові схеми клавіш, які буде додано, коли до поточного буфера буде приєднано сервер LSP. Іноді може знадобитися додати карти клавіш для певного LSP-сервера. Для цього у Lazyutils передбачено опцію `keys` LSP.

