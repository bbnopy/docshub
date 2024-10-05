# GNU EMACS


> :information_source: **Інформація:** Це вид текстового редактора, який має розширюваний набір можливостей, популярний у середовищі програмістів і технічно просунутих користувачів комп'ютера.

:open_file_folder: **Розділ** :hammer_and_wrench: *Інструменти Розробника*

---

## Про GNU Emacs

| Опис | Інформація |
| ---- | ---------- |
| **версія :package: програми** | :two: :nine: . :four: |
| :computer: **розробник** | The GNU Project |
| **сайт** | [:link: посилання](https://www.gnu.org/software/emacs/) |

## :inbox_tray: Встановлення

### :desktop_windows: Windows

- :inbox_tray: встановлення з сайту **nearby GNU mirror** за [:link: посилання](https://www.artfiles.org/gnu.org/emacs/windows/)
- :inbox_tray: встановлення з сайту **main GNU FTP server** за [:link: посилання](https://ftp.gnu.org/gnu/emacs/windows/)
- :inbox_tray: встановлення з :cloud: Хмарного сховища

### :penguin: Linux

- :inbox_tray: встановлення з сайту за [:link: посилання](https://www.gnu.org/software/emacs/download.html#gnu-linux)
- :inbox_tray: встановлення за допомогою **Flathub**(Unverified):
  - вводимо команду у терміналі: `flatpak install flathub org.gnu.emacs`
- :inbox_tray: встановлення за допомогою **Snap Store**:
  - **версія :package: програми** latest/stable команда для терміналу: `sudo snap install emacs --classic`
  - **версія :package: програми** latest/candidate команда для терміналу: `sudo snap install emacs --candidate --classic`
  - **версія :package: програми** latest/beta команда для терміналу: `sudo snap install emacs --beta --classic`
  - **версія :package: програми** latest/edge команда для терміналу: `sudo snap install emacs --edge --classic`
  - **версія :package: програми** pgtk/edge команда для терміналу: `sudo snap install emacs --channel=pgtk/edge --classic`
  - **версія :package: програми** :two: :eight: .x/stable команда для терміналу: `sudo snap install emacs --channel=28.x/stable --classic`

#### fedora WORKSTATION

- :inbox_tray: встановлення з **Центру :package: програмного забезпечення**
- :inbox_tray: встановлення за допомогою командного рядка: `sudo dnf install emacs`

## :keyboard: Сполучення клавіш

| Опис | Команда |
|-----:|:-------:|
| перервати команду | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>G</kbd> |
| многоцільова команда виходу | <kbd>Esc</kbd> <kbd>Esc</kbd> <kbd>Esc</kbd> |
| новий фрейм | <kbd>Meta</kbd>-<kbd>X</kbd> make-frame |
| переключатися на наступний буфер | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-arrow_right |
| переключитися на попередній буфер | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-arrow_left |
| відкрити файл в нижньому вікні разом з курсором | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> foo |
| записати файл | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>S</kbd> |
| зберегти деякі буфери | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>S</kbd> |
| перемістити на початок тексту | <kbd>Meta</kbd>-<kbd>Shift</kbd>-<kbd><</kbd> |
| на початок файлу | <kbd>Ctrl</kbd>-<kbd>Home</kbd> |
| переміщення у кінець тексту | <kbd>Meta</kbd>-<kbd>Shift</kbd>-arrow_right |
| переміщення у кінець файлу | <kbd>Ctrl</kbd>-<kbd>End</kbd> |
| перейти на специфічну лінію | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>G</kbd> |
| вузький буфер до поточного регіону | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>N</kbd> |
| відновити буфер/розширити | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>W</kbd> |
| видалити попереднє слово | <kbd>Meta</kbd>-<kbd>Backspace</kbd> |
| відміна останню введену команду | <kbd>Ctrl</kbd>-<kbd>/</kbd> |
| перетворити регіон на макрос коментування або розкоментувати | <kbd>Meta</kbd>-<kbd>X</kbd> comment-down? <kbd>Meta</kbd>-<kbd>;</kbd> |
| пошук останнього шуканого елемента | <kbd>Ctrl</kbd>-<kbd>S</kbd> <kbd>Ctrl</kbd>-<kbd>S</kbd> |
| пошук | <kbd>Meta</kbd>-<kbd>X</kbd> iserch-forward |
| шукайте слово під курсором | <kbd>Ctrl</kbd>-<kbd>S</kbd> <kbd>Ctrl</kbd>-<kbd>W</kbd> |
| наступний пункт в історії пошуку | <kbd>Ctrl</kbd>-<kbd>S</kbd> <kbd>Meta</kbd>-<kbd>N</kbd> |
| попередній елемент в історії пошуку | <kbd>Ctrl</kbd>-<kbd>S</kbd> <kbd>Meta</kbd>-<kbd>P</kbd> |
| регулярний вираз додатковий пошук | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>S</kbd> |
| лічильник повторень | <kbd>Meta</kbd>-<kbd>1</kbd> <kbd>Meta</kbd>-<kbd>0</kbd> |
| відновлення із резервної копії | <kbd>Meta</kbd>-<kbd>X</kbd> recover-file |
| виводить різницю, яка показує зміни, зроблені у поточному файлі | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> |
| RSS-feed | <kbd>Meta</kbd>-<kbd>X</kbd> gnus |
| запустити оболонку у буфері з іменем **shell**/**start** інтерфейс оболонки | <kbd>Meta</kbd>-<kbd>X</kbd> shell |
| викликає **make** і виводить вивід у новий буфер | <kbd>Meta</kbd>-<kbd>X</kbd> compile |
| відображає man-сторінки | <kbd>Meta</kbd>-<kbd>X</kbd> man |
| простий калькулятор | <kbd>Meta</kbd>-<kbd>X</kbd> calculator |
| календар | <kbd>Meta</kbd>-<kbd>X</kbd> calendar |
| показує майбутні чверті місяця | <kbd>Meta</kbd>-<kbd>X</kbd> phases-of-moon |
| сортувати рядки за певним стовпцем, як **string** | <kbd>Meta</kbd>-<kbd>X</kbd> sort-fields |
| сортувати рядки за певним стовпцем, як число | <kbd>Meta</kbd>-<kbd>X</kbd> sort-numeric-fields |
| результат - поточна позиція курсору/eval-last-sexp | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>E</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> eval-last-sexp |
| компіляція, запуск та тестування програм | <kbd>Meta</kbd>-<kbd>X</kbd> gdb |
| відмінності | <kbd>Meta</kbd>-<kbd>X</kbd> ediff |
| файловий менеджер | <kbd>Meta</kbd>-<kbd>X</kbd> dired |
| редагування у **dired-mode** | <kbd>Meta</kbd>-<kbd>X</kbd> wired-change-to-wired-mode |
| знайти комбінацію клавіш для команди | <kbd>Meta</kbd>-<kbd>X</kbd> description-function |
| переглянути зовнішні пакунки | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>E</kbd> |
| переглянути новини Emacs | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>N</kbd> |
| описати дистрибутив | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| переглянути Emacs todo | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>T</kbd> |
| описати без гарантії | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>W</kbd> |
| опишіть метод введення | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>\\</kbd> |
| відобразити локальну довідку | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>.</kbd> |
| щодо документації | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>D</kbd> |
| перглянути повідомлення ехо-зони | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>E</kbd> |
| описати проект GNU | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>G</kbd> |
| вийти з довідки | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Q</kbd> |
| інформація з керівництва Emacs | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>R</kbd> |
| зупиняє дію введеної команди/Вийдіть і встановіть курсор у вихідне положення/вихід з клавіатури | <kbd>Ctrl</kbd>-<kbd>G</kbd> |
| редагувати в дротовому режимі | <kbd>Meta</kbd>-<kbd>X</kbd> wdired-change-to-wdired-mode |
| щоб обчислити весь код у поточному файлі | <kbd>Meta</kbd>-<kbd>X</kbd> eval-buffer |
| зворотний sexp/перехід до попереднього члена | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_left |
| переадресація/перехід до наступного члена | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_right |
| списком зворотного копіювання/перемістити до головного | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_up |
| зменшити список/перейти до першої дочірньої | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_down |
| list-directory | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>D</kbd> |
| setselective-display | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>$</kbd> |
| kmacro-end-macro | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>)</kbd> |
| calCtrl+Dispatch | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>*</kbd> |
| dired | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>D</kbd> |
| kmacro-add-counter | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>A</kbd> |
| kmacro-set-counter | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>C</kbd> |
| kmacro-delete-ring-head | <kbd>Ctrl<kbd>-<kbd>X<kbd> <kbd>Ctrl<kbd>-<kbd>K<kbd> <kbd>Ctrl<kbd>-<kbd>D<kbd> |
| kmacro-edit-macro-repeat | <kbd>Ctrl<kbd>-<kbd>X<kbd> <kbd>Ctrl<kbd>-<kbd>K<kbd> <kbd>Ctrl<kbd>-<kbd>E<kbd> |
| kmacro-set-format | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> |
| exit-recursive-edit | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>C</kbd> |
| w32-drag-n-drop-other-frame | <kbd>Ctrl</kbd>-drag-n-drop |
| mouse-drag-secondary | <kbd>Meta</kbd>-down-mouse-1 |
| mouse-appearance-menu | S-down-mouse-1 |
| kmacro-end-call-mouse | S-mouse-3 |
| mwheel-scroll | <kbd>Ctrl</kbd>-wheel-down, <kbd>Ctrl</kbd>-wheel-up, S-wheel-down, S-wheel-up |
| clipboard-kill-ring-save | <kbd>F16</kbd>, copy |
| clipboard-kill-region | <kbd>F20</kbd>, cut |
| mouse-drag-region | down-mouse-1 |
| move-end-of-line | end |
| execute-extended-command | menu, execute |
| menu-bar-open, text terminal | <kbd>Meta</kbd-<kbd>X</kbd> menu-bar-open, <kbd>F10</kbd> |
| clipboard-yank | <kbd>F18</kbd>, paste |
| search-forward | find |
| move-beginning-of-line | home |
| ignore-event | iconify-frame, make-frame-visible |
| overwrite-mode | insert, insertchar |
| ignore | language-change, lwindow, mouse-movement, rwindow |
| backward-char | left |
| handle-select-window | select-window |
| handle-switch-frame | switch-frame |
| describe-copying | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>C</kbd> |
| view-emacs-debugging | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>D</kbd> |
| view-external-packages | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>E</kbd> |
| view-emacs-FAQ | <kbd>Ctrl<kbd>-<kbd>H<kbd> <kbd>Ctrl<kbd>-<kbd>F<kbd> |
| help-for-help | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>H</kbd>, <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>?</kbd>, <kbd>Ctrl</kbd>-<kbd>H</kbd> help |
| view-order-manuals | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>RET</kbd> |
| describe-distribution | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| view-emacs-problems | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| view-emacs-todo | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>T</kbd> |
| describe-no-warranty | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>W</kbd> |
| describe-input-method | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>\\</kbd> |
| display-local-help | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>.</kbd> |
| describe-coding-system | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>C</kbd> |
| apropos-documentation | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>D</kbd> |
| view-echo-area-messages | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>E</kbd> |
| describe-gnu-project | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>G</kbd> |
| view-hello-file | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>H</kbd> |
| help-quit | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Q</kbd> |
| info-emacs-manual | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>R</kbd> |
| help-with-tutorial | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>T</kbd> |
| kmacro-keymap | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> |
| find-file-read-only | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>R</kbd> |
| save-buffer | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>S</kbd> |
| find-alternate-file | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>V</kbd> |
| write-file | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>W</kbd> |
| exchange-point-and-mark | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>X</kbd> |
| suspend-frame | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>Z</kbd> |
| split-window-horizontally | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>3</kbd> |
| 2 <kbd>Ctrl</kbd>-command | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>6</kbd> |
| comment-set-column | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>;</kbd> |
| next-error | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>`</kbd>, <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>N</kbd> |
| insert-file | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>I</kbd> |
| compose-mail | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>M</kbd> |
| kbd-macro-query | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Q</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Q</kbd> |
| save-some-buffers | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>S</kbd> |
| undo | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>U</kbd> |
| repeat | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Z</kbd> |
| pop-global-mark | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>@</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>Spc</kbd> |
| text-scale-adjust | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>+</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>-</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>0</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>=</kbd> |
| end-of-defun | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>End</kbd>, <kbd>Esc</kbd> <kbd>Ctrl</kbd>-<kbd>End</kbd> |
| forward-sexp/Move to next sibling. (move to the (end of) next sexp unit) | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_right, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>F</kbd>, <kbd>Esc</kbd> <kbd>Ctrl</kbd>-arrow_right, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_right |
| forward-list | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>N</kbd> |
| backward-list | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>P</kbd> |
| isearch-backward-regexp | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>R</kbd> |
| scroll-other-window | <kbd>Meta</kbd>-next, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>V</kbd>, <kbd>Esc</kbd> next |
| asynCtrl-Shell-command | <kbd>Meta</kbd>-<kbd>&</kbd> |
| abbrev-prefix-mark | <kbd>Meta</kbd>-<kbd>'</kbd> |
| insert-parentheses | <kbd>Meta</kbd>-<kbd>(</kbd> |
| move-past-close-and-reindent | <kbd>Meta</kbd>-<kbd>)</kbd> |
| pop-tag-mark | <kbd>Meta</kbd>-<kbd>*</kbd> |
| tags-loop-continue | <kbd>Meta</kbd>-<kbd>,</kbd> |
| find-tag | <kbd>Meta</kbd>-<kbd>.</kbd> |
| dabbrev-expand | <kbd>Meta</kbd>-<kbd>/</kbd> |
| eval-expression | <kbd>Meta</kbd>-<kbd>:</kbd>, <kbd>Meta</kbd>-<kbd>Esc</kbd> <kbd>:</kbd> |
| indent-new-comment-line | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>J</kbd>, <kbd>Meta</kbd>-<kbd>J</kbd> |
| facemenu-keymap | <kbd>Meta</kbd>-<kbd>O</kbd> |
| move-to-window-line-top-bottom | <kbd>Meta</kbd>-<kbd>R</kbd> |
| not-modified | <kbd>Meta</kbd>-<kbd>~</kbd> |
| scroll-other-window-down | <kbd>Meta</kbd>-prior, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>S</kbd> <kbd>V</kbd>, <kbd>Esc</kbd> prior |
| find-tag-regexp | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>.</kbd> |
| dabbrev-completion | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>/</kbd> |
| backward-kill-sexp | <kbd>Esc</kbd> <kbd>Ctrl</kbd>-<kbd>Backspace</kbd>, <kbd>Esc</kbd> <kbd>Ctrl</kbd>-<kbd>Del</kbd> |
| down-list/Move to first child. (move into the (beginning of) first inner paren pair) | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>D</kbd>, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-down, <kbd>Esc</kbd> <kbd>Ctrl</kbd>-down, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_down |
| beginning-of-defun | <kbd>Ctrl</kbd>-<kbd>Meta</kbd><kbd>Home</kbd>, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>A</kbd> |
| backward-sexp/Move to previous sibling. (move to the (beginning of) previous sexp unit) | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>B</kbd>, <kbd>Esc</kbd> <kbd>Ctrl</kbd>-left, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_left |
| backward-up-list/Move to parent. (move to the (beginning of) outer paren pair) | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-up, <kbd>Esc</kbd> <kbd>Ctrl</kbd>-up, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-arrow_up |
| beginning-of-buffer-other-window | <kbd>Meta</kbd>-begin, <kbd>Meta</kbd>-<kbd>Home</kbd>, <kbd>Esc</kbd> begin, <kbd>Esc</kbd> <kbd>Home</kbd> |
| end-of-buffer-other-window | <kbd>Meta</kbd>-<kbd>End</kbd>, <kbd>Esc</kbd> <kbd>End</kbd> |
| isearch-forward-word | <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>W</kbd> |
| previous-error | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>P</kbd> |
| keyboard-escape-quit | <kbd>Meta</kbd>-<kbd>Esc</kbd> `Es` |
| mouse-drag-vertical-line | vertical-line down-mouse-1 |
| scroll-bar-toolkit-scroll | vertical-scroll-bar mouse-1 |
| mouse-drag-header-line | header-line down-mouse-1 |
| mouse-split-window-horizontally | mode-line <kbd>Ctrl</kbd>-mouse-2 |
| mouse-drag-mode-line | mode-line down-mouse-1 |
| facemenu-background-menu | <kbd>Ctrl</kbd>-down-mouse-2 `BG` |
| list-faces-display | <kbd>Ctrl</kbd>-down-mouse-2 `DF` |
| describe-text-properties | <kbd>Ctrl</kbd>-down-mouse-2 `DP` |
| facemenu-face-menu | <kbd>Ctrl</kbd>-down-mouse-2 `FC` |
| facemenu-foreground-menu | <kbd>Ctrl</kbd>-down-mouse-2 `FG` |
| facemenu-indentation-menu | <kbd>Ctrl</kbd>-down-mouse-2 `IN` |
| facemenu-justification-menu | <kbd>Ctrl</kbd>-down-mouse-2 `JU` |
| facemenu-remove-all | <kbd>Ctrl</kbd>-down-mouse-2 `RA` |
| facemenu-remove-face-props | <kbd>Ctrl</kbd>-down-mouse-2 `RM` |
| facemenu-special-menu | <kbd>Ctrl</kbd>-down-mouse-2 `SP` |
| 2<kbd>Ctrl</kbd>-two-columns | <kbd>F2</kbd> <kbd>2</kbd> |
| 2<kbd>Ctrl</kbd>-associate-buffer | <kbd>F2</kbd> <kbd>B</kbd> |
| 2<kbd>Ctrl</kbd>-split | <kbd>F2</kbd> <kbd>S</kbd> |
| 2<kbd>Ctrl</kbd>-two-columns | <kbd>F2</kbd> <kbd>F2</kbd> |
| info-other-window | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>4</kbd> <kbd>I</kbd> |
| kmacro-insert-counter | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Tab</kbd> |
| kmacro-end-or-call-macro-repeat | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> |
| kmacro-call-ring-2nd-repeat | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| kmacro-edit-macro | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ret</kbd> |
| kmacro-cycle-ring-next | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>N</kbd> |
| kmacro-cycle-ring-previous | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| kmacro-swap-ring | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>T</kbd> |
| kmacro-view-macro-repeat | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>V</kbd> |
| kmacro-step-edit-macro | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Spc</kbd> |
| kmacro-bind-to-key | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>B</kbd> |
| edit-kbd-macro | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>E</kbd> |
| kmacro-edit-lossage | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>L</kbd> |
| kmacro-name-last-macro | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>N</kbd> |
| apply-macro-to-region-lines | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>R</kbd> |
| set-input-method | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>Ctrl</kbd>-<kbd>\\</kbd> |
| set-file-name-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>F</kbd> |
| set-next-selection-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>X</kbd> |
| universal-coding-systeAlt-argument | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>C</kbd> |
| set-keyboard-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>K</kbd> |
| set-language-environment | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>L</kbd> |
| set-buffer-process-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>P</kbd> |
| revert-buffer-with-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>R</kbd> |
| set-terminal-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>T</kbd> |
| set-selection-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>X</kbd> |
| add-change-log-entry-other-window | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>A</kbd> |
| clone-indirect-buffer-other-window | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>C</kbd> |
| display-buffer-other-frame | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| delete-other-frames | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>Ctrl</kbd>-<kbd>1</kbd> |
| other-frame | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| 2<kbd>Ctrl</kbd>-two-columns | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>6</kbd> <kbd>2</kbd> |
| 2<kbd>Ctrl</kbd>-associate-buffer | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>6</kbd> <kbd>B</kbd> |
| 2<kbd>Ctrl</kbd>-split | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>6</kbd> <kbd>S</kbd> |
| 2<kbd>Ctrl</kbd>-two-columns | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>6</kbd> <kbd>F2</kbd> |
| ucs-insert | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>8</kbd> <kbd>Ret</kbd> |
| add-mode-abbrev | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>Ctrl</kbd>-<kbd>A</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>+</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>L</kbd> |
| inverse-add-global-abbrev | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>-</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>I</kbd> <kbd>G</kbd> |
| expand-abbrev | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>'</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>'</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>E</kbd> |
| add-global-abbrev | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>G</kbd> |
| expand-jump-to-next-slot | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>N</kbd> |
| expand-jump-to-previous-slot | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>P</kbd> |
| narrow-to-defun | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>D</kbd> |
| narrow-to-region | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>N</kbd> |
| narrow-to-page | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>P</kbd> |
| widen | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>W</kbd> |
| bookmark-bmenu-list | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>L</kbd> |
| copy-rectangle-to-register | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>R</kbd> |
| v<kbd>Ctrl</kbd>-update | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>+</kbd> |
| v<kbd>Ctrl</kbd>-root-diff | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>D</kbd> |
| v<kbd>Ctrl</kbd>-update-change-log | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>A</kbd> |
| v<kbd>Ctrl</kbd>-Switch-backend | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>B</kbd> |
| v<kbd>Ctrl</kbd>-rollback | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>C</kbd> |
| v<kbd>Ctrl</kbd>-insert-headers | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>H</kbd> |
| v<kbd>Ctrl</kbd>-register | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>I</kbd> |
| v<kbd>Ctrl</kbd>-merge | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>M</kbd> |
| v<kbd>Ctrl</kbd>-retrieve-tag | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>R</kbd> |
| v<kbd>Ctrl</kbd>-create-tag | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>S</kbd> |
| v<kbd>Ctrl</kbd>-revert | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>U</kbd> |
| v<kbd>Ctrl</kbd>-next-action | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>V</kbd> |
| hi-lock-find-patterns | <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>H</kbd> <kbd>F</kbd> |
| highlight-lines-matching-regexp | <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>H</kbd> <kbd>L</kbd> |
| unhighlight-regexp | <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>H</kbd> <kbd>U</kbd> |
| hi-lock-write-interactive-patterns | <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>H</kbd> <kbd>W</kbd> |
| center-paragraph/center-line | <kbd>Meta</kbd>-<kbd>O</kbd> <kbd>Meta</kbd>-<kbd>S</kbd> |
| font-lock-fontify-block | <kbd>Meta</kbd>-<kbd>O</kbd> <kbd>Meta</kbd>-<kbd>O</kbd> |
| facemenu-set-foreground | <kbd>Ctrl</kbd>-down-mouse-2 `FG` `O` |
| facemenu-set-background | <kbd>Ctrl</kbd>-down-mouse-2 `BG` `O` |
| facemenu-set-read-only | <kbd>Ctrl</kbd>-down-mouse-2 `SP` `R` |
| facemenu-remove-special | <kbd>Ctrl</kbd>-down-mouse-2 `SP` `S` |
| facemenu-set-intangible | <kbd>Ctrl</kbd>-down-mouse-2 `SP` `T` |
| facemenu-set-invisible | <kbd>Ctrl</kbd>-down-mouse-2 `SP` `V` |
| decrease-left-margin | <kbd>Ctrl</kbd>-down-mouse-2 `IN` decrease-left-margin |
| decrease-right-margin | <kbd>Ctrl</kbd>-down-mouse-2 `IN` decrease-right-margin |
| increase-left-margin | <kbd>Ctrl</kbd>-down-mouse-2 `IN` increase-left-margin |
| increase-right-margin | <kbd>Ctrl</kbd>-down-mouse-2 `IN` increase-right-margin |
| inverse-add-mode-abbrev | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>A</kbd> <kbd>I</kbd> <kbd>L</kbd> |
| event-apply-shift-modifier | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>@</kbd> <kbd>S</kbd> |
| event-apply-Alt-modifier | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>@</kbd> <kbd>A</kbd> |
| event-apply-control-modifier | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>@</kbd> <kbd>C</kbd> |
| event-apply-hyper-modifier | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>@</kbd> <kbd>H</kbd> |
| event-apply-meta-modifier | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>@</kbd> <kbd>M</kbd> |
| previous-buffer | <kbd>Ctrl</kbd>-<kbd>X</kbd> arrow_left, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-arrow_left |
| next-buffer | <kbd>Ctrl</kbd>-<kbd>X</kbd> arrow_right, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-arrow_right |
| set-buffer-file-coding-system | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ret</kbd> <kbd>F</kbd> |
| kill-whole-line | <kbd>Ctrl</kbd>-<kbd>Space</kbd>-<kbd>Backspace</kbd> |
| mouse-buffer-menu | <kbd>Ctrl</kbd>-down-mouse-1 |
| facemenu-menu | <kbd>Ctrl</kbd>-down-mouse-2 |
| kill-buffer to close it | <kbd>Meta</kbd>-<kbd>X</kbd> |
| split top/bottom | <kbd>Meta</kbd>-<kbd>X</kbd> split-window-below |
| start irc | <kbd>Meta</kbd>-<kbd>X</kbd> irc |
| Open the file or directory | <kbd>Enter</kbd> dired-find-file |
| Done. Display last buffer (call kill-buffer if you actually want to close it) | <kbd>Q</kbd> quit-window |
| Copy file | <kbd>C</kbd> dired-do-copy |
| Rename/move file | <kbd>R</kbd> dired-do-rename |
| Delete file or directory | <kbd>D</kbd> dired-do-delete |
| create new dir | <kbd>+</kbd> dired-create-directory |
| compress/decompress the file by gzip | <kbd>Z</kbd> dired-do-compress |
| mark a file | <kbd>M</kbd> dired-mark |
| unmark | <kbd>U</kbd> dired-unmark |
| unmark all marked | <kbd>U</kbd> dired-unmark-all-marks |
| refresh dir listing | <kbd>G</kbd> revert-buffer |
| go to parent dir | <kbd>^</kbd> dired-up-directory |
| Move cursor to next subdirectory | dired-next-dirline |
| Move cursor to previous subdirectory | <kbd><</kbd> dired-prev-dirline |

## Безліч Вікон

### Поділ вікон

| Опис | Команда |
|-----:|:-------:|
| Розбити вікно по горизонталі/розділити вибране вікно на два, одна під іншим `split-windows-horizontally` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>2</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> split-window-bellow |
| Розбити вікно по вертикалі/розділити вибране вікно на два, одне поряд з іншим `split-window-vertically` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>3</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> split-window-right |
| У рядку режиму або смузі прокрутки, розділяє це вікно | <kbd>Ctrl</kbd>+mouse-2 |

### Використання інших вікон

| Опис | Команда |
|-----:|:-------:|
| Переміщення між вікнами, переміщення в інше вікно | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>O</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> other-window |
| Прокрутка другого вікна донизу | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>V</kbd>, <kbd>Esc</kbd> <kbd>Ctrl-V</kbd> |
| Знайти наступне місце, де текст вибраного вікна не збігається з текстом в наступному вікні | <kbd>Meta</kbd>-<kbd>X</kbd> compare-windows |
| на рядку режиму якогось вікна вибирає це вікно, але не переміщує в нову точку `mouse-select-window` | mouse-1 |

### Зображення іншому вікні

| Опис | Команда |
|-----:|:-------:|
| вибрати буфер в іншому вікні, при цьому запускається `switch-to-buffer-other-window` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>B</kbd> foo <kbd>Ret</kbd> |
| показувати буфер в іншому вікні, але не вибирати знову цей буфер, це запускається `display-buffer` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> foo <kbd>Ret</kbd> |
| звернуться до файлу і вибрати його буфер в іншому вікні, при цьому запускається `find-file-other-window` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>F</kbd> foo <kbd>Ret</kbd> |
| вибрати буфер **Dired** для каталогу в іншому вікні, при цьому запускається `dired-other-window` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>D</kbd> foo <kbd>Ret</kbd> |
| почати складання поштового повідомлення в іншому вікні, при цьому запускається `mail-other-window`, аналог цієї команди, що працює в тому ж вікні - <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>M</kbd> | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>M</kbd> |
| знайти тег в поточній таблиці тегів в іншому вікні, при цьому запускається `find-tag-other-window`, багатовіконний варіант | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> |
| звернуться до файлу в режимі тільки для читання і вибрати його буфер в іншому вікні, ця опція розпочне команду `find-file-read-only-other-window` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>R</kbd> foo <kbd>Ret</kbd> |

### Видалення переупорядковувати вікнах

| Опис | Команда |
|-----:|:-------:|
| видалити вибране вікно `delete-window`, останній знак в цій послідовності ключів - nul | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>O</kbd> |
| залишити лише вікно з курсором/одно вікно, закрити всі інші вікна | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>1</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> delete-other-windows |
| видалите вибране вікно і знищити буфер, який був в нову показаний `kill-buffer-and-window` в цій послідовності ключів - nul | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>0</kbd> |
| зробити вибране вікно вище `enlarge-window` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>^</kbd> |
| розширити вибране вікно `enlarge-window-horizontally` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>}</kbd> |
| звузити вибране вікно `shrink-window-horizontally` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>{</kbd> |
| зменшити це вікно, якщо буфер в ньому не вимагає стільки рядків `shrink-window-if-larger-than-buffer` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>-</kbd> |
| вирішити висоту всіх вікон `balance-windows` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>+</kbd> |
| переміщення рядка режиму за допомогою **mouse-1** змінює висоту вікон | drag-mouse-1 |
| **mouse-2** на рядку режиму вікна видаляє всі інші вікна в цьому фреймі `mouse-delete-other-windows` | mouse-2 |
| **mouse-3** на рядку режиму якогось вікна видаляє це вікно `mouse-delete-window` | mouse-3 |

## Фрейми Windows

### Команди миші для редагування

| Опис | Команда |
|-----:|:-------:|
| переміщення точку туди, де ви клацнули `mouse-set-point`, зазвичай це ліва кнопка | mouse-1 |
| встановлює область навколо тексту за яким ви провели і копіює цей текст в список знищен `mouse-set-region`, за допомогою цієї команди ви можете вказати обидва кінці області. Якщо при проведенні мишею ви перемістіть її за верхню чи нижню межу вікна, це вікно безперервно безперервно прокручується, поки ви не повернете в нього миша, таким чином ви можете виділяти області, що не вміщаються на екрані, число прокручуваних за один крок рядків залежить від того, наскільки далеко за край вікна пішла миша, мінімальний розмір кроку визначає заміна `mouse-scroll-min-lines` | drag-mouse-1 |
| відновлює останній знищений текст в тому місці, де ви клацнули `mouse-yank-at-clickd`, зазвичай це середня кнопка | mouse-2 |
| ця команда `mouse-save-then-kill` має кілька призначень в залежності від того, де ви клацнули і від стану області. Найголовніший випадок - це коли ви натискаєте **mouse-1** в одному місці, а потім **mouse-3** в іншому, це виділяє текст між двома цими позиціями в якості області, це також копіює нову область в список знищень, щоб ви могли скопіювати його в інше місце. Якщо ви клацните в тексті **mouse1** перейдіть вікно за допомогою смужки прокрутки і потім клацніть **mouse-3**, Emacs запам'ятає де була точка перед прокруткою (де ви помістили її за допомогою **mouse-1**), і використовує цю позицію як інший кінець області, це зроблено, щоб ви могли виділяти області, які не поміщаються повністю на екрані. У більш загальному вигляді, якщо у вас немає підсвічується області, **mouse-3** виділяє в якості області текст між точкою і місцем клацання, вона робить це, встановлюючи мітку там, де була точка і переміщаючи точку до тієї позиції де ви клацнули. Якщо у вас є підсвічена область або якщо область була встановлена безпосередньо перед цим за допомогою проведення кнопкою 1, **mouse-3** підлаштовує найближчий кінець області, переміщуючи його до місця клацання, також текст підлаштований області заміщає в списку знищень текст старої області. Якщо ви з самого початку задали область, використовуючи подвійне або потрійне клацання **mouse-1**, щоб визначити область як що складається з цілих або рядків то підстроювання області за допомогою **mouse-3** також проходить цілими словами або рядками. Якщо ви застосуєте **mouse-3** два раз поспіль на одному місці, ви знищите вже виділену область | mouse-3 |
| цей ключ встановлює область навколо слова на якому ви клацнули, якщо ви клацнули на знаку з синтаксичною категорією **symbol** (наприклад, на почерк в режимі C), він встановлює область навколо символу, якому належить цей знак. Якщо ви клацнули на знаку з синтаксичною категорією відкриває або закриває круглої дужки, область встановлюється навколо групи (s-вирази), яка завершується або починається на цьому знаку, якщо ви клацнули на знаку з синтаксичною категорією роздільник рядків (такому як лапки або подвійні лапки в C), область буде встановлена навколо цієї строкової константи (з використанням евристики, щоб з'ясувати, чи є цей знак початком або завершенням) | double-mouse-1 |
| цей ключ виділяє область, що складається з слів за якими ви провели | double-drag-mouse-1 |
| цей ключ встановлює область навколо рядка на який ви клацнули | triple-mouse-1 |
| цей ключ виділяє область, що складається з рядку по яких ви провели | triple-drag-mouse-1 |

### Вторинне виділення

| Опис | Команда |
|-----:|:-------:|
| встановлює вторинне виділення з одним кінцем в тому місці де ви натиснули кнопку і іншим - в тому місці, де ви її відпустили `mouse-set-secondary`, коли ви проводите мишею, з'являється і змінюється підсвічування. Якщо при проведенні мишею ви зрушите її за верхню чи нижню межу вікна, це вікно безперервно прокручується поки ви не повернете в ного миша, таким чином ви можете виділити область, що не вміщаються на екрані | <kbd>Meta</kbd> drag-mouse-1 |
| встановлює одну з граничних точок вторинного виділення `mouse-start-secondary` | <kbd>Meta</kbd> mouse-1 |
| створює вторинне виділення, використовуючи місце, вказане за допомогою <kbd>Meta</kbd>-mouse-1, як його другий кінець `mouse-secondary-save-then-kill`, друге клацання на цьому ж місці змушує тільки що зроблене вторинне виділення | <kbd>Meta</kbd> mouse-3 |
| вставляє в місці клацання вторинне виділення `mouse-yank-secondary`, це поміщає точку в кінець виділеного тексту |<kbd>Meta</kbd> mouse-1 |

### Клацання миші для меню

| Опис | Команда |
|-----:|:-------:|
| це меню для вибору буфера | <kbd>Ctrl</kbd> mouse-1 |
| це меню для завдання накреслень і інших властивостей тексту для редагування тексту фіксованої | <kbd>Ctrl</kbd> mouse-2 |
| це меню визначається режимом, для більшості режимів дане меню має ті ж пункти, що містяця у всіх визначених режимом меню з смужки меню, деякі режими можуть визначити для цієї кнопки інше меню | <kbd>Ctrl</kbd> mouse-3 |
| це меню для завдання основного шрифту фрейму | <kbd>S</kbd>-mouse-1 |

### Команди миші для рядку режиму

| Опис | Команда |
|-----:|:-------:|
| **mouse-1** на рядку режиму вибирає вікно зверху, проводячи мишею з натиснутою на рядку режиму **mouse-1**, ви можете переміщати цей рядок режиму, змінюючи таким чином висоту вікон зверху і знизу | mouse-1 |
| **mouse-2** на рядку режиму розкриває вікно на весь фрейм | mouse-2 |
| **mouse-3** на рядку режиму видаляє вікно зверху | mouse-3 |
| на рядку режиму розбиває вікно зверху по вертикалі в тому місці, де ви клацнули | <kbd>Ctrl</kbd> mouse-2 |

### Створення фреймів

| Опис | Команда |
|-----:|:-------:|
| створює новий фрейм `make-frame-command` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>2</kbd> |
| вибирає буфер в іншому фреймі, це запускає `switch-to-bufer-other-frame` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>B</kbd> foo <kbd>Ret</kbd> |
| звертається до файлу і вибирає його буфер в іншому фреймі, це запускає `find-file-other-frame` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>F</kbd> foo <kbd>Ret</kbd> |
| вибирає буфер **Dired** для каталогу каталог в іншому фреймі, це запускає `dired-other-frame` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>D</kbd> foo <kbd>Ret</kbd> |
| дозволяє почати складання поштового повідомлення в іншому фреймі `mail-other-frame`, це варіант <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>M</kbd>, що працює в іншому фреймі | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>M</kbd> |
| звертається до тегу з поточної таблиці тегів в іншому фреймі, це запускає `find-tag-other-frame` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> |
| звертається до файлу в режимі тільки для читання і вибирає його буфер в іншому фреймі, це запускає `find-file-read-only-other-frame` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>R</kbd> foo <kbd>Ret</kbd> |

### Безліч дисплеїв

| Опис | Команда |
|-----:|:-------:|
| створює новий фрейм на дисплей | <kbd>Meta</kbd>-<kbd>X</kbd> make-frame-on-display <kbd>Ret</kbd> display <kbd>Ret</kbd> |
| задає колір для тексту в обраному фреймі | <kbd>Meta</kbd>-<kbd>X</kbd> set-foreground-color <kbd>Ret</kbd> color <kbd>Ret</kbd> |
| задає колір для фону в обраному фреймі, також змінює колір тексту в зображені **modeline**, щоб воно залишалося інверсією зображення за замовчуванням | <kbd>Meta</kbd>-<kbd>X</kbd> set-background-color <kbd>Ret</kbd> color <kbd>Ret</kbd> |
| задає колір курсора в обраному фреймі | <kbd>Meta</kbd>-<kbd>X<8kbd> set-cursor-color <kbd>Ret</kbd> color <kbd>Ret</kbd> |
| задає колір покажчика миші, коли він знаходиться над обраним фреймом | <kbd>Meta</kbd>-<kbd>X</kbd> set-mouse-color <kbd>Ret</kbd> color <kbd>Ret</kbd> |
| задає колір рамки обраного фрейма | <kbd>Meta</kbd>-<kbd>X</kbd> set-border-color <kbd>Ret</kbd> color <kbd>Ret</kbd> |
| виводить певні імена квітів і показує, як ці кольори виглядають, це декілька повільна команда | <kbd>Meta</kbd>-<kbd>X</kbd> list-colors-display |
| перемикає автоматичне підняття обраного фрейма, автоматичне підняття означає, що всякий раз, коли ви пересуваєте мишу в цей фрейм, він піднімається. Зверніть увагу, це засіб автоматичного підняття реалізовано самим Emacs, деякі програми управління вікнами також реалізуют авто-підняття, якщо ви включите авто-підняття для фреймів Emacs в вашій програмі управління X-вікнами, це буде працювати, але не під контролем Emacs і отже `auto-raise-mode` не зіграє ролі | <kbd>Meta</kbd>-<kbd>X</kbd> auto-raise-mode |
| перемикає автоматичне опускання обраного фрейма, автоматичне опускання означає, що всякий раз, коли ви пересуваєте мишу за межі цього фрейму, він переноситься вниз стека X-вікон, команда `auto-lower-mode` не впливає на автозапуск, реалізоване програмою управління X-вікнами, щоб контролювати це, ви повинні використовувати відповідні кошти своєї програми управління вікнами | <kbd>Meta</kbd>-<kbd>X</kbd> auto-lower-mode |
| визначає шрифт як основний шрифт в обраному фреймі, основний шрифт використовується для всього відображуваного в цьому фреймі тексту, крім випадків, коли для якогось тексту за допомогою накреслення визначено інший, щоб дізнатися про способи перерахування доступних у вашій системі шрифтів. Ви також можете встановити основний шрифт фрейма через спливаючи меню, щоб викликати це меню, натисніть <kbd>S</kbd>-mouse-1 | <kbd>Meta</kbd>-<kbd>X</kbd> set-frame-font <kbd>Ret</kbd> font <kbd>Ret</kbd> |
| мінімізує обраний фрейм `iconify-or-deiconify-frame`, звичайне значення <kbd>Ctrl</kbd>-<kbd>Z</kbd> припинення Emacs, марно під віконною системою, тому в даному випадку у цього ключа інша прив'язка. Якщо ви введете цю команду в піктограмі фрейма Emacs, вона де-мінімізує цей фрейм | <kbd>Ctrl</kbd>-<kbd>Z</kbd> |
| видаляє обраний фрейм `delete-frame` це не допускається, якщо є тільки один фрейм | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>0</kbd> |
| вибирає інший фрейм, піднімає його і переносить в нього миша, щоб він залишався обраним, якзо ви повторюєте цю команду вона цілком проходить по всім фреймам на вашому терміналі | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>O</kbd> |

### Установка параметрів фрейму

| Опис | Команда |
|-----:|:-------:|
| виводить певні імена квітів і показує, як ці кольори виглядають, це декілька повільна команда | <kbd>Meta</kbd>-<kbd>X</kbd> list-color-display |

### Інші можливості X-windows

| Опис | Команда |
|-----:|:-------:|
| вибирає інший фрейм, піднімає його і переносить в нього миша, щоб він залишався обраним, якщо ви повторюєте ці команду, вона циклічно проходить по всім фреймам на вашому терміналі | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>0</kbd> |

## Команда для Виправлення Помилок

### Знищення ваших помилок

| Опис | Команда |
|-----:|:-------:|
| видалити останній знак `delete-backward-char` | <kbd>Del</kbd> |
| знищити останнє слово `backward-kill-word` | <kbd>Meta</kbd>-<kbd>Del</kbd> |
| знищити все до початку пропозиції `backward-kill-sentence` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Del</kbd> |

### Перестановка тексту

| Опис | Команда |
|-----:|:-------:|
| переставити два знаки `rapsone-chars` | <kbd>Ctrl</kbd>-<kbd>T</kbd> |
| переставити два слова `transpose-words` | <kbd>Meta</kbd>-<kbd>T</kbd> |
| переставити два збалансовані вираження `transpose-sexps` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>T</kbd> |
| переставити два рядки `transpose-lines` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>T</kbd> |

### Зміна регістру

| Опис | Команда |
|-----:|:-------:|
| перевести останнє слово у нижній регістр | <kbd>Meta</kbd>-<kbd>Meta</kbd>-<kbd>L</kbd> |
| перевести останнє слово у великий регістр | <kbd>Meta</kbd>-<kbd>Meta</kbd>-<kbd>U</kbd> |
| перевести останнє слово у нижній регістр з першою великою літерою | <kbd>Meta</kbd>-<kbd>Meta</kbd>-<kbd>C</kbd> |

### Пошук виправлення орфографічних помилок

| Опис | Команда |
|-----:|:-------:|
| включити режим **Flyspell**, який виправляє усі неправильно написані слова | <kbd>Meta</kbd>-<kbd>X</kbd> flyspell-mode |
| перевірити і виправити написані слова у точці `ispell-word` | <kbd>Meta</kbd>-<kbd>$</kbd> |
| завершує слово перед точкою, ґрунтуючись на орфографічному словнику `ispell-complete-word` | <kbd>Meta</kbd>-<kbd>Tab</kbd> |
| перевіряє і виправляє написання усіх слів у буфері | <kbd>Meta</kbd>-<kbd>X</kbd> ispell-buffer |
| перевіряє і виправляє написання усіх слів у області | <kbd>Meta</kbd>-<kbd>X</kbd> ispell-region |
| перевіряє і виправляє написання усіх слів в чернетці поштового повідомлення за винятком цитованого матеріалу | <kbd>Meta</kbd>-<kbd>X</kbd> ispell-message |
| перезапустити процес **ispell** використовуючи словник у якості словника | <kbd>Meta</kbd>-<kbd>X</kbd> ispell-change-dictionary <kbd>Ret</kbd> dictionary <kbd>Ret</kbd> |
| знищує підпроцес **ispell** | <kbd>Meta</kbd>-<kbd>X</kbd> ispell-kill-ispell |
| пропустити це слово - продовжувати вважати це слово неправильним, але не змінювати його тут | <kbd>Spc</kbd> |
| замінити слово (тільки в цьому місці) на нове | <kbd>r</kbd> foo <kbd>Ret</kbd> |
| замінити слово на нове і виконати `query-replace`, щоб ви могли замінити його у всіх інших місцях буфера, якщо хочете | <kbd>R</kbd> foo <kbd>Ret</kbd> |
| замінити це слово (тільки в цьому місці) на одне з показаних схожих слів, кожному схоже слово перераховується з цифрою, щоб вибрати його, наберіть цю цифру | number |
| прийняти неправильне слово - вважати його правильним, але тільки в цьому сенсі редагування | <kbd>a</kbd> |
| прийняти неправильне слово - вважати його правильним, але тільки в цьому сенсі редагування і для цього буфера | <kbd>A</kbd> |
| вставити це слово в ваш особистий файл словника, щоб **spell** відверте вважав його правильних навіть в майбутніх сеансах | <kbd>i</kbd> |
| вставити це слово в нижньому регістрі в ваш особистий файл словника | <kbd>u</kbd> |
| як і але ви також можете вказати відомості про завершення для словника | <kbd>m</kbd> |
| пошукати в словнику слова, зіставляти зі словом, ці слова новим списком відмінні одне від одного, ви можете вибрати для заміни одне з них, набравши цифру, ви можете використовувати в слові знак * для опису шаблону | <kbd>I</kbd> foo <kbd>Ret</kbd> |
| вийти з інтерактивною перевіркою правопису, ви можете перезаписати її пізніше за допомогою <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Meta</kbd>-<kbd>$</kbd> | <kbd>Ctrl</kbd>-<kbd>G</kbd> |
| те ж що і <kbd>Ctrl</kbd>-<kbd>G</kbd> | <kbd>X</kbd> |
| вийти з інтерактивно перевірку правопису і перемістити точку назад, де вона була, коли ви запустили перевірку | <kbd>x</kbd> |
| вийти з інтерактивною перевірку правопису і знищити процес **ispell** | <kbd>q</kbd> |
| перемалювати екран | <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| цей ключ має своє звичайне значення (призупинити Emacs або мінімізувати цей фрейм) | <kbd>Ctrl</kbd>-<kbd>Z</kbd> |

## Команди для Природних Мов

### Слова

| Опис | Команда |
|-----:|:-------:|
| перейти вперед через слово `forward-word` | <kbd>Meta</kbd>-<kbd>F</kbd> |
| перейти назад через слово `backward-word` | <kbd>Meta</kbd>-<kbd>B</kbd> |
| позначити кінець наступного слова `mark-word` | <kbd>Meta</kbd>-<kbd>@</kbd> |

### Речення

| Опис | Команда |
|-----:|:-------:|
| назад на початок речення | <kbd>Meta</kbd>-<kbd>A</kbd> |
| вперед у кінець речення | <kbd>Meta</kbd>-<kbd>E</kbd> |
| знищити вперед до кінця пропозицій `kill-sentence` | <kbd>Meta</kbd>-<kbd>K</kbd> |

### Абзаци

| Опис | Команда |
|-----:|:-------:|
| перейти назад до початку попереднього абзацу `backward-paragraph` | <kbd>Meta</kbd>-<kbd>{</kbd> |
| перемістіться вперед до кінця наступного абзацу `forward-paragraph` | <kbd>Meta</kbd>-<kbd>}</kbd> |
| поставити крапку і мітку навколо цього або наступного абзацу `mark-paragraph` | <kbd>Meta</kbd>-<kbd>H</kbd> |

### Сторінки

| Опис | Команда |
|-----:|:-------:|
| змістити точку на попередню сторінку `backward-page` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>[</kbd> |
| змістити точку на наступну сторінку `forward-page` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>]</kbd> |
| поставити крапку і мітку по краях цієї (або інші) сторінку `mark-page` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| порахувати рядки в цій сторінці `count-lines-page` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>L</kbd> |

### Режим AutoFill

| Опис | Команда |
|-----:|:-------:|
| включення і виключення режиму **Auto Fill** | <kbd>Meta</kbd>-<kbd>X</kbd> auto-fill-mode |
| у режимі **Auto Fill** перериває рядок, якщо це потрібно | <kbd>Spc</kbd>, <kbd>Ret</kbd> |

### Явні команди заповнення

| Опис | Команда |
|-----:|:-------:|
| заповнити поточний абзац `fill-paragraph` | <kbd>Meta</kbd>-<kbd>Q</kbd> |
| встановити стовпець заповнення `set-fill-column` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>F</kbd> |
| заповнити кожен абзац в області `fill-region` | <kbd>Meta</kbd>-<kbd>X</kbd> fill-region |
| заповнити область, розглядаючи її як один абзац | <kbd>Meta</kbd>-<kbd>X</kbd> fill-region-as-paragraph |
| відцентрувати рядок | <kbd>Meta</kbd>-<kbd>S</kbd> |

### Префікс заповнення

| Опис | Команда |
|-----:|:-------:|
| встановити префікс заповнення `set-fill-prefix` | <kbd>Ctrl</kbd>-<kbd>X</kbd> |
| заповнити область, розглядаючи кожну зміну відступу як початок нового абзацу | <kbd>Meta</kbd>-<kbd>X</kbd> fill-individual-paragraph |
| заповнити область вважаючи початком нового абзацу тільки рядки-роздільники абзаців | <kbd>Meta</kbd>-<kbd>X</kbd> fill-nonuniform-paragraph |

## Команди Перетворення Регістру

| Опис | Команда |
|-----:|:-------:|
| перевести наступне слово в нижній регістр `downcase-word` | <kbd>Meta</kbd>-<kbd>L</kbd> |
| перевести наступне слово в верхній регістр `upcase-word` | <kbd>Meta</kbd>-<kbd>U</kbd> |
| зробити першу букву наступного слова у верхньому регістрі, а інші - малими `capitalize-word` | <kbd>Meta</kbd>-<kbd>C</kbd> |
| перевести область в нижній регістр `downcase-region` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| перевести область у верхній регістр `upcase-region` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>U</kbd> |

### Команди переміщення по структурі

| Опис | Команда |
|-----:|:-------:|
| пересунути точку до наступної видимої рядку заголовка `outline-next-visible-heading` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>N</kbd> |
| пересунути точку до попередньої видимої рядку заголовка `outline-previous-visible-heading` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| пересунути точку до наступної видимої рядку заголовка того ж рівня, що і рядок на якій знаходиться точка `outline-forward-same-level` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> |
| пересунути точку до попередньої видимої рядку заголовка цього ж рівня `outline-backward-same-level` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>B</kbd> |
| пересунути точку назад до видимої рядку заголовка нижнього рівня `outline-up-heading` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>U</kbd> |

### Команди управління видимості структури

| Опис | Команда |
|-----:|:-------:|
| зробити всі рядки тіла в буфері невидимим `hide-body` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>T</kbd> |
| зробити всі рядки в буфері видимими `show-all` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>A</kbd> |
| зробити все під цим заголовком невидимим, але не сам цей заголовок `hide-subtree` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>D</kbd> |
| зробити все під цим заголовком видимим, включаючи тіло, підзаголовки і їх тіла `show-subtree` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>S</kbd> |
| зробити тіло цього рядка заголовка і все його підзаголовки невидимими `hide-leaves` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| зробити всі підзаголовки цього заголовка видимими на всіх рівнях `show-branches` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> |
| зробити безпосередні підзаголовки (на один рівень вниз) цього заголовка видимим `show-children` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>I</kbd> |
| зробити тіло цього заголовка невидимим `hide-entry` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>C</kbd> |
| зробити тіло цього заголовка видимим `show-entry` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>E</kbd> |
| приховати все, крім **n** верхнів рівнів рядків заголовків `hode-sublevels` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>Q</kbd> |
| приховати все, крім заголовка або тіла, в якому знаходиться точка і заголовків, які ведуть звідси до верховного рівня структури `hide-other` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |

### Команди редагування режиму TEX

| Опис | Команда |
|-----:|:-------:|
| вставити згідно контексту або ', або ", ''' `text-insert-quote` | <kbd>"</kbd> |
| вставити розрив абзацу (два переклади рядка) і перевірити попередній абзац на незюалансовані фігурні дужки або знаки долара `text-terminate-paragraph` | <kbd>Ctrl-J</kbd> |
| перевірити кожен абзац в буфері на незбалансовані фігурні дужки або знаки долара | <kbd>Meta-X</kbd> text-validate-region |
| вставити **{** і розташувати точку між ними `text-insert-brances` | <kbd>Ctrl-C</kbd> <kbd>{</kbd> |
| перейти вперед за наступну непарну закриває фігурну дужку `up-list` | <kbd>Ctrl-C</kbd> <kbd>}</kbd> |

### Команди редагування режиму LaTEX

| Опис | Команда |
|-----:|:-------:|
| вставляє **\\begin** і **\\end** для блоку LaTEX і поміщає точку на рядку між ними `text-latex-block` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| закриває самий внутрішній ще не закритий блок LaTEX `text-close-latex-block` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>E</kbd> |

### Команди друку для TEX

| Опис | Команда |
|-----:|:-------:|
| викликати TEX для поточної області разом з заголовком буфера `tex-region` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>R</kbd> |
| викликати TEX для чого поточного буфера `tex-buffer` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>B</kbd> |
| викликати BibTEX для поточного файлу `tex-bibtex-file` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Tab</kbd> |
| викликати TEX для поточного файлу `tex-file` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> |
| перемістити центр вікна, що показує висновок підлеглого TEX, щоб можна було побачити останній рядок `tex-recenter-output-buffer` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| знищити підпроцес TEX `tex-kill-job` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> |
| друкувати висновок з останньої команди <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>R</kbd>, <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>B</kbd> або <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> `text-print` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| запустити попередній перегляд виведення останньої команди <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>R</kbd>, <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>B</kbd> або <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> `tex-view` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>V</kbd> |
| показати чергу принтера `tex-show-print-queue` | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>Q</kbd> |

### Режим Nrof

| Опис | Команда |
|-----:|:-------:|
| перейти на початок наступного рядка, яка не є командою **nroff** `forward-text-line`, аргумент служит лічильником повторів | <kbd>Meta</kbd>-<kbd>N</kbd> |
| схожа на <kbd>Meta</kbd>-<kbd>N</kbd>, але зрушує вгору `backward-text-line` | <kbd>Meta</kbd>-<kbd>P</kbd> |
| надрукувати в луна-області число текстових рядків (рядків, які не є командами **nroff**) в поточній області `count-text-lines` | <kbd>Meta</kbd>-<kbd>?</kbd> |

### Накреслення форматованому тексті

| Опис | Команда |
|-----:|:-------:|
| каже, що область або наступний вставлений знак повинні з'являтися в накресленні **default** `facemenu-set-default` | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>D</kbd> |
| каже, що область або наступний знак повинні з'явитися в накресленні **bold** `facemenu-set-bold` | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>B</kbd> |
| каже, що область або наступні вставлений знак повинні з'явитися в накресленні **italic** `facemenu-set-italic` | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>I</kbd> |
| каже, що область або наступний вставлений знак повинні з'явитися в накресленні **bold-italic** `facemenu-set-bold-italic` | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>L</kbd> |
| каже, що область або наступний вставлений знак повинні з'явитися в накресленні **underline** `facemenu-set-underline` | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>U</kbd> |
| каже, що область або наступний вставлений знак повинні з'явитися в заданому зображенні `facemenu-set-face` | <kbd>Meta</kbd>-<kbd>G</kbd> <kbd>O</kbd> |

### Вирівнювання форматованому тексті

| Опис | Команда |
|-----:|:-------:|
| центрує область `set-justification-center` | <kbd>Meta</kbd>-<kbd>J</kbd> <kbd>C</kbd>, <kbd>Meta</kbd>-<kbd>S</kbd> |
| робить область невирівняною `set-justification-none` | <kbd>Meta</kbd>-<kbd>J</kbd> <kbd>U</kbd> |
| вирівнює область зліва `set-justification-left` | <kbd>Meta</kbd>-<kbd>J</kbd> <kbd>L</kbd> |
| вирівнює область праворуч `set-justification-right` | <kbd>Meta</kbd>-<kbd>J</kbd> <kbd>R</kbd> |
| вирівнює область повністю `set-justification-full` | <kbd>Meta</kbd>-<kbd>J</kbd> <kbd>F</kbd> |

## Мінібуфер

### Команди завершення

| Опис | Команда |
|-----:|:-------:|
| завершити представлений в мінібуфері текст наскільки це можливо `minibufer-complete` | <kbd>Tab</kbd> |
| завершити текст в мінібуфері, але не додавати більше одного слова `minibuffer-complete-word` | <kbd>Spc</kbd> |
| представити текст в мінібуфер як аргумент, можливо для початку доповнюючи його, як описано нижче `minibuffer-complete-and-exit` | <kbd>Ret</kbd> |
| надрукувати список усіх можливих завершень тексту в мінібуфері `minibuffer-list-completions` | <kbd>?</kbd> |
| вибирає вікно, показує буфер з перечнєм завершенням `switch-to-completions` | <kbd>Meta</kbd>-<kbd>V</kbd> |
| буфери з перечнем завершен оберіть завершення, на якому або після якого знаходяться `choose-completion` | <kbd>Ret</kbd> |
| пересуває точку до наступного завершення | right |
| рухає точку ближче до початку буфера до попереднього завершення `previous-completion` | left |

### Історія мінібуфера

| Опис | Команда |
|-----:|:-------:|
| переміщується до попереднього рядка аргумента, збереженої в історії мінібуфера `previous-history-element` | <kbd>Meta</kbd>-<kbd>P</kbd> |
| переміщується до наступного рядка аргумента в історії мінібуфера `next-history-element` | <kbd>Meta</kbd>-<kbd>N</kbd> |
| переміщується до більш раннього атрибуту в історії мінібуферу в якому є спів-падіння з **regexp** `previous-matching-history element` | <kbd>Meta</kbd>-<kbd>R</kbd> regexp <kbd>Ret</kbd> |
| переміщується до більш пізнього аргументу в історії мінібуфера в якому є спів-падіння з **regexp** `next-matching-history-element` | <kbd>Meta</kbd>-<kbd>S</kbd> regexp <kbd>Ret</kbd> |

### Повтор команд мінібуфера

| Опис | Команда |
|-----:|:-------:|
| повторне виконання останньої команди мінібуфера `repeat-complex-command` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Esc</kbd> <kbd>Esc</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Meta</kbd>-<kbd>:</kbd> |
| вивести повну історію усіх команд, які можуть повторити <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Esc</kbd> <kbd>Esc</kbd>, починаючи з більш нових | <kbd>Meta</kbd>-<kbd>X</kbd> list-command-history |

## Основні Команди Редагування

### Вставка тексту

| Опис | Команда |
|-----:|:-------:|
| за яким може іти будь-який не графічний знак (навіть <kbd>Ctrl</kbd>-<kbd>G</kbd>), вставляйте цей знак | <kbd>Ctrl</kbd>-<kbd>Q</kbd> |

### Зміна положення точки

| Опис | Команда |
|-----:|:-------:|
| на початок рядка `beginning-of-line` | <kbd>Ctrl</kbd>-<kbd>A</kbd> |
| у кінець рядка `end-of-line` | <kbd>Ctrl</kbd>-<kbd>E</kbd> |
| на символ вперед `forward-char` | <kbd>Ctrl</kbd>-<kbd>F</kbd> |
| на символ назад `blackward-char` | <kbd>Ctrl</kbd>-<kbd>B</kbd> |
| на наступний рядок `next-line` | <kbd>Ctrl</kbd>-<kbd>N</kbd> |
| на попередній рядок `previous-line` | <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| здвинути точку до лівого краю на рядок до середини вікна `move-to-window-line` | <kbd>Meta</kbd>-<kbd>R</kbd> |
| на початок документу `beginning-of-buffer` | <kbd>Meta</kbd>-<kbd><</kbd> |
| у кінець документа `end-of-buffer` | <kbd>Meta</kbd> arrow_right |
| зчитує число **n** і зрушує точку до позиції **n** в буфері | <kbd>Meta</kbd>-<kbd>X</kbd> goto-char |
| зчитує число **n** і зрушує точку до рядка з номером **n** | <kbd>Meta</kbd>-<kbd>X</kbd> goto-line |
| використовує поточний стовпець в якому знаходиться точка в якості полу-постійного цільового стовпчика для <kbd>Ctrl</kbd>-<kbd>N</kbd> і <kbd>Ctrl</kbd>-<kbd>P</kbd> `set-goal-column` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>N</kbd> |
| скасувати цільовий стовпець | <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>N</kbd> |

### Стирання тексту

| Опис | Команда |
|-----:|:-------:|
| видалити символ слідуючий за (над) рядким `delete-char` | <kbd>Ctrl-<kbd>D</kbd> |
| вбити все від курсора до кінця рядку `kill-line` | <kbd>Ctrl-<kbd>K</kbd> |

### Відміна зроблених змін

| Опис | Команда |
|-----:|:-------:|
| відміна змін | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>U</kbd> |
| відміна | <kbd>Ctrl</kbd>-<kbd>_</kbd> |
| відмінити одну групу змін в області | <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>U</kbd> |

### Файли

| Опис | Команда |
|-----:|:-------:|
| відкрити знайти файл `find-file` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> |

### Порожні рядки

| Опис | Команда |
|-----:|:-------:|
| вставити після курсору одну або декілька порожніх рядків `open-file` | <kbd>Ctrl</kbd>-<kbd>O</kbd> <kbd>Ctrl</kbd>-<kbd>Q</kbd> <kbd>Ctrl</kbd>-<kbd>J</kbd> |
| знищити усі послідовні рядки, окрім однієї `delete-blank-lines` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>O</kbd> |

### Інформація позиції курсора

| Опис | Команда |
|-----:|:-------:|
| надрукувати номер сторінки, на якій знаходиться точка і номер строки в межах цієї сторінки | <kbd>Meta</kbd>-<kbd>X</kbd> what-page |
| надрукувати номер строки в якій знаходиться точка в буфері | <kbd>Meta</kbd>-<kbd>X</kbd> what-line |
| переключити режим автоматичного відображення номера поточного рядку | <kbd>Meta</kbd>-<kbd>X</kbd> line-number-mode |
| надрукувати кількість рядків в поточної області `count-lines-region` | <kbd>Meta</kbd>-<kbd>=</kbd> |
| надрукувати код замку після точки знакове положення точки і стовпець точки `what-cursor-position` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>=</kbd> |

### Числові аргументи

| Опис | Команда |
|-----:|:-------:|
| передвинути на 5 рядків до низу | <kbd>Meta</kbd>-<kbd>5</kbd> <kbd>Ctrl</kbd>-<kbd>N</kbd> |
| за яким іде слідом цифри аргумента, помножує на чотири аргумент наступної команди `universal-argument` | <kbd>Ctrl</kbd>-<kbd>U</kbd> |
| переміщення на 4 в залежності від команди `$0` | <kbd>Ctrl</kbd>-<kbd>U</kbd> `$0` |
| переміщення на 16 | <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Ctrl</kbd>-<kbd>U</kbd> |
| переміщення 64 | <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Ctrl</kbd>-<kbd>U</kbd> |

### Повторення команди

| Опис | Команда |
|-----:|:-------:|
| повторити | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Z</kbd> |

## Пошук і Заміна

### Нарощуваний пошук

| Опис | Команда |
|-----:|:-------:|
| пошук вперед `isearch-forward` | <kbd>Ctrl</kbd>-<kbd>S</kbd> |
| пошук назад `iserch-backward` | <kbd>Ctrl</kbd>-<kbd>R</kbd> |

### Ненарощуваємий пошук

| Опис | Команда |
|-----:|:-------:|
| пошук заданого рядку | <kbd>Ctrl</kbd>-<kbd>S</kbd> <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| пошук рядку в обраному напрямку | <kbd>Ctrl</kbd>-<kbd>R</kbd> <kbd>Ret</kbd> foo <kbd>Ret</kbd> |

### Пошук слів

| Опис | Команда |
|-----:|:-------:|
| шукає слова, ігнорує пунктуацію між ними | <kbd>Ctrl</kbd>-<kbd>S</kbd> <kbd>Ret</kbd> <kbd>Ctrl</kbd>-<kbd>W</kbd> foo <kbd>Ret</kbd> |
| шукає слова в зворотньому направленні, ігнорує пунктуацію між ними | <kbd>Ctrl</kbd>-<kbd>R</kbd> <kbd>Ret</kbd> <kbd>Ctrl</kbd>-<kbd>W</kbd> foo <kbd>Ret</kbd> |

### Синтаксис регулярних виразів

| Опис | Команда |
|-----:|:-------:|
| точка є спеціальним знаком, які відповідає будь-якому одиничному знаку за бийнятком перекладу рядка, використовуючи конкатенацію (зчеплення), ви можете скласти регулярний вираз, подібне **a.b**, яке відповідає будь-якому трьох-знаковому рядку, що починається з **a** і закінчується на **b** | `.` |
| сама по собі не є конструкцією, це постфіксний оператор, який означає, що попереднє редагувальний вираз має бути повторено стільки разів, скільки це можливо таким чином , **'o*''** відповідає будь-якому числу букв **o** (включаючи nul). Завжди відноситься до найменшого можливого попереднього виразу. Таким чином **'fo*'** містить повторювану **o**, а не **fo**, вона збігається з **f**, **fo**, **foo** і так далі. Конструкція **'*'** обробляється шляхом зіставлення з найбільшою кількістю повторень, яке відразу може бути знайдено, потім триває порівняння із залишком шаблону, якщо воно пройшло невдало, то відбувається перебір з поверненням, деякі з збігів з конструкцією з модифікатором. Конструкція **'*'** обробляється шляхом зіставлення з найбільшою кількістю повторень, яке відразу може бути знайдено, потім триває порівняння із залишком шаблону, якщо воно пройшло невдало, то відбувається перебір з поверненням, деякі з збігів з конструкцією з модифікатором. **'*'** скидаються, щоб дати можливість пошуку відповідності для залишку структури, наприклад порівнюючи **'ca*ar'** з рядком **caaar**, **'a*'** спочатку ставиться у відповідність з усіма трьома **a**, але залишок шаблону - це **ar**, а в цьому випадку для підбору залишається тільки **r**, тому ця спроба невдала. Наступний варіант - це поставити у відповідність з **'a*'** тільки дві літери **a**, при такому виборі залишок регулярного виразу успішного відповідає рядку | `*` |
| це такий же постфіксний оператор, як і **'*'**, за винятком того, що вимагає, щоб попереднє йому вираз зіставлялося принаймні один раз, так наприклад **ca+r** буде відповідати рядкам **car** і **caaar**, але не рядку **cr**, тоді як **ca*r** відповідає всім трьом рядкам | `+` |
| постфіксний оператор, як і **'*'**, але він може відповідати передньому вислову або один раз, або жодного, наприклад, **ca?r** буде що відповідало значенню **car** або **cr** і нічому більше | `?` |
| це набір знаків, який починається **[** і завершується **]**, у найпростішому випадку співпадає набір формують знаки між цими дужками, таким чином, **[ad]** відповідає або однією **a**, або одному **d**, а **'[ad]*'** відповідає будь-якому рядку, складеної просто з **a** і **d** (включаючи порожній рядок), з усього цього виправляє що  **c[ad]*r** відповідає **cr**, **car**, **cdr**, **caddaar** і так далі. Ви також можете включити в безліч знаків інтервалу, написавши два знака, розділені **-**, таким чином, **[a-z]** відповідає будь-якої малої букви ASCII, інтервали можуть бути вільно переміщені з окремими знаками, як в **[a-z$%]**, що відповідає будь-якої малої букви ASCII, або **$**, або **%**, або точці. Зауважимо, що спеціальні знаки регулярних виразів всередині такого безліч більше не є спеціальними, усередині знакового безлічі існують зовсім інший набір спеціальних знаків **]**, **-** і **^**. Щоб включити в знаковий набір **]**, ви повинні поставити його першим, наприклад, **[]a]** відповідає **]** або **a**, щоб включити **-**, напишіть **-** першим або останнім знаком в наборі або помістіть його після вказівки інтервалу, таким чином **[]-]** відповідає **]** і **-**. Щоб включити в набір знак **^**, пишіть його де завгодно, але не першим.Якщо ви задаєте інтервалу при пошуку без урахування регістру, ви повинні або написати обидва кінці інтервалу великими літерами, або обидва малими, або обидва вони не повинні бути буквами, поведінка інтервалу з кінцями, заданими в різних регістрах, визначено погано і може бути змінено в майбутніх версіях Emacs | `[...]` |
| **[^** починає додатковий набір знаків який відповідає будь-якому знаку, виключаючи описані в ньому, таким чином, **[^a-z0-9A-Z]** відповідає всім знакам, виключаючи букви і цифри. `^` не є спеціальним в наборі знаків, якщо він не стоїть першим знак, наступний за **^**, трактується так, як якщо б він був першим (іншими словами **-** і **]** тут не є спеціальним). Додатковий набір знаків може відповідати знаку нового рядка, якщо він не згадується як один з незбіжних знаків, це суперечить способу обробки регулярних виразів в таких програмах, як **grep** | `[^...]` |
| це специфічний знак, який відповідає порожньому рядку, але тільки на початку рядка зіставляється тексту в іншому випадку, порівняння не вдається. Таким чином **^foo** відповідає **foo**, яка зустрінута на початку рядка | `^` |
| подібний **^**, але порівняння відбувається тільки в кінці рядка, таким чином, **xx*$** відповідає рядку з одного або більше **x** в кінці рядка | `$` |
| має дві функції: скасовує особливий сенс спеціальних знаків (включаючи **\**) і вводить додаткові спеціальні конструкції. Так як **\** скасовує сенс спеціальних знаків, то **\$** - це регулярний вираз, яке відповідає тільки **$**, а **\[** - регулярний вираз, яке відповідає тільки **[** і так далі | `\\` |
| описує альтернативу, два регулярних вирази **a** і **b**, **c**, **\[** між ними формують вираз, яке відповідає будь-якому з них окремо, або **a**, або **b**, це працює так: спочатку пробується **a** і якщо відповідності не знайдено пробується **b**. Таким чином **foo\bar** відповідає або **food**, або **bar** але не іншому рядку. **\|** застосовується до найбільших охоплює виразами, тільки що охоплюють дужки **\(...\)** можуть обмежити групуються силу **\|**, існує можливість повного зворотнього відновлення для обробки багаторазових використань **\|** | `\[` |
| групувальна конструкція, яка служить для трьох цілей: 1. щоб відокремити набір альтернатив **\|** від інших операцій, таким чином **\(foo\|mar\)x** відповідає або **foox**, або **marx**. 2. щоб обмежити складаний вираз для вій постфіксні операторів **'*'**, **+** і **?**, таким чином **'ba\(na\)*' відповідає **bananana** і так далі з будь-яким (нульовим або великим) числовим рядків **na**. 3. щоб відзначити відповідну підстроку для майбутнього посилання | `\(...\)` |
| відповідає тексту, що співпала з n-ною появою конструкції **\(..\)**. Після кінця конструкції **\(...\)** зіставлення запам'ятовує початок і кінець тексту, що співпала з цією конструкцією, потім, пізніше в регулярному виразі ви можете використовувати **\**, за яким слідує цифра n, щоб сказати зіставити з тим же текстом, який збігся з n-ною появою конструкції **\(...\)**. Рядках, що відповідають першим дев'яти конструкціями **\(...\)**, які з'являються в регулярному виразі, присвоюються номера від 1 до 9 в тому рядку в якому в регулярному виразі з'явилися відкриваються дужки, конструкції від **\1** до **\9** можуть використовуватися для посилання на текст конструкції **\(...\)** з цим номером. Наприклад **\(.*\)\1** відповідає будь-якому рядку, що не містить знаків перекладу рядка, яка складається з двох однакових половин **\(.*\)** відповідає першій половині, яка може бути будь-який, але **\1**, що іде слідом, половина відповідати точно такому ж тексту. Якщо для будь-якої конструкції **\(...\)** знайдено більше однієї відповідності (що може легко статися, якщо за нею іде **'*'**), то запам'ятовується тільки останній збій | `\n` |
| відповідає порожньому рядку, але тільки на початку буфера або рядку, де відбувається пошук | `\\` |
| відповідає порожньому рядку, але тільки в кінці буфера або рядки, де відбувається пошук | `\` |
| відповідає порожньому рядку, але тільки в точці | `\=` |
| відповідає порожньому рядку, якщо ця конструкція знаходиться на початку або кінці слова, таким чином **\bfoo\b** відповідає будь-який появі **foo** як окремого слова, **bballs?\b** відповідає **ball** або **balls** як окремим словам. **\b** знаходить відповідність на початку або наприкінці буфера незалежно від того, який текст іде далі | `\b` |
| відповідає порожньому рядку, якщо тільки вона знаходиться не на початку або кінці слова | `\B` |
| відповідає порожньому рядку, якщо вона знаходиться на початку слова **\<** знаходить відповідність на початку буфера, але тільки якщо потім іде знак, який є частиною слова | `\<` |
| відповідає порожньому рядку, якщо вона знаходиться в кінці слова **\>** знаходить відповідність у кінці буфера, але тільки якщо буфер завершується знаком, що є частиною слова | `\>` |
| відповідає будь-якому знаку, що є частиною слова, які саме це знаку, визначає синтаксична таблиця | `\w` |
| відповідає будь-якому знаку, яка не є частиною слова | `\W` |
| відповідає будь-якому знаку, чий синтаксис визначається кодом **c**, тут **c** - це знак, який являє собою синтаксичний код, наприклад, це **w** для частини слова **-** для пробільних знаків **(** для відкриваючої дужки і так далі ви можете позначити пробільний знак (який може бути перекладом рядка) або як **-**, або одним пропуском | `\sc` |
| відповідає будь-якому знаку чий синтаксис не визначається кодом **c** | `\Sc` |

### Безумовна заміна

| Опис | Команда |
|-----:|:-------:|
| замінити кожне входження рядка на новий рядок | <kbd>Meta</kbd>-<kbd>X</kbd> replace-string <kbd>Ret</kbd> foo <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| замінює кожен збіг з **regexp** на новий рядок | <kbd>Meta</kbd>-<kbd>X</kbd> replace-regexp <kbd>Ret</kbd> regexp <kbd>Ret</kbd> foo <kbd>Ret</kbd> |

### Заміна регулярних виразів

| Опис | Команда |
|-----:|:-------:|
| замінить (наприклад) **cadr** на **cadr-safe** і **cddr** на **cddr-safe** | <kbd>Meta</kbd>-<kbd>X</kbd> replace-regexp <kbd>Ret</kbd> c[ad]+r <kbd>Ret</kbd> \&-safe <kbd>Ret</kbd> |
| робить зворотнє перетворення | <kbd>Meta</kbd>-<kbd>X</kbd> replace-regexp <kbd>Ret</kbd> \(c[ad]+r\)-safe <kbd>Ret</kbd> \1 <kbd>Ret</kbd> |

### Заміна з підтвердженням

| Опис | Команда |
|-----:|:-------:|
| замінює деякі збіги з regexp на новий рядок | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>%</kbd> regexp <kbd>Ret</kbd> foo <kbd>Ret</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> query-replace-regexp <kbd>Ret</kbd> regexp <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| щоб замінити це входження на новий рядок | <kbd>Spc</kbd> |
| щоб знайти наступний примірник не замінюючи це | <kbd>Del</kbd> |
| (кома) щоб замінити це входження і показати результат потім у вас запитують введення ще одного знака, щоб дізнатися, що робити далі, так як заміна вже проведена, то <kbd>Del</kbd> і <kbd>Spc</kbd> в цій ситуації еквівалентні, обидві переходять до наступного входження ви можете набрати в цьому місці <kbd>Ctrl</kbd>-<kbd>R</kbd> (дивіться нижче), щоб змінити замінений текст, ви можете також набрати <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>U</kbd>, щоб скасувати зроблену заміну, ця команда виходить з `query-replace`, так що якщо ви хочете робити подальші заміни, ви повинні використовувати <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Esc</kbd> <kbd>Esc</kbd> <kbd>Ret</kbd>, щоб запустити заміну заново | `,` |
| щоб вийти без здійснення подальших замін | <kbd>Ret</kbd> |
| (точка) щоб замінити цей екземпляр і потім вийти без продовження пошуку сліду цих входжень | `.` |
| щоб замінити всі екземпляри, що залишилися без повторних запитів | `!` |
| щоб повернутися до положення попереднього входження (або до того, що ним було), якщо ви змінили його помилково, це робиться за допомогою виштовхування зі списку позначок, можна використовувати тільки один `^` поспіль, так як під час роботи `query-replace` зберігається тільки одна попередня позиція заміни | `^` |
| щоб увійти в новий рівень рекурсивного редагування в тому випадку, коли екземпляр потребує скоріше в редагуванні, ніж просто в заміні його нового рядка, коли ви зробите це, вийдіть з цього рівня рекурсивного редагування, набравши <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>C</kbd>, щоб перейти до наступного входження | <kbd>Ctrl</kbd>-<kbd>R</kbd> |
| щоб видати це входження і потім увійти в новий рівень рекурсивного редагування, як в <kbd>Ctrl</kbd>-<kbd>R</kbd>, використовуйте рекурсивне редагування для вставки тексту і заміни віддаленого входження рядка, коли ви закінчите вийдіть з того рівня рекурсивного редагування за допомогою <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>C</kbd>, щоб перейти до наступного входження | <kbd>Ctrl</kbd>-<kbd>W</kbd> |
| щоб відновити зображення екрану, потім ви повинні набрати ще один знак, щоб вказати, що робити з цим входження | <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| щоб переглянути повідомлення, резюмуючи ці варіанти, потім ви повинні набрати ще один знак, щоб робити з цим входженням | <kbd>Ctrl</kbd>-<kbd>H</kbd> |

### Інші команди пошуку в циклі

| Опис | Команда |
|-----:|:-------:|
| виводити перелік, який показує кожен рядок буфера, яка містить збіг з **regexp**, числовий аргумент задає число рядків контексту, які повинні бути надруковані перед і після кожної порівнюєш рядки значень за замовченням - не друкувати контекст, щоб обмежити пошук частиною буфера, звузьте до цієї частини. Буфер **occur**, в який записується висновок, служить в якості меню для пошуку входжень в їх оригінальному контексті, клацніть **mouse-2** на входження, перерахованому в **occur**, або помістіть там пошук і перемістити точку до оригіналу обраного входження | <kbd>Meta</kbd>-<kbd>X</kbd> occur <kbd>Ret</kbd> regexp <kbd>Ret</kbd>, <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>O</kbd> |
| синонім для <kbd>Meta</kbd>-<kbd>X</kbd> occur | <kbd>Meta</kbd>-<kbd>X</kbd> list-matching-lines |
| друкує число збігів з **regepx** після точки | <kbd>Meta</kbd>-<kbd>X</kbd> count-matches <kbd>Ret</kbd> regexp <kbd>Ret</kbd> |
| видаляє кожен рядок, наступну після точки і містить збіг з **regexp** | <kbd>Meta</kbd>-<kbd>X</kbd> flush-lines <kbd>Ret</kbd> regexp <kbd>Ret</kbd> |
| видаляє кожен рядок, наступну після точки і не містить збіг з **regexp** | <kbd>Meta</kbd>-<kbd>X</kbd> keep-lines <kbd>Ret</kbd> regexp <kbd>Ret</kbd> |

## Позначка і Область

### Встановлення позначка

| Опис | Команда |
|-----:|:-------:|
| підсвічує текст між курсором і точкою `set-make-command` | <kbd>Ctrl</kbd>-<kbd>Spc</kbd>, <kbd>Ctrl</kbd>-<kbd>@</kbd> |
| змінити місцями мітку і точку `exchange-point-mark` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>X</kbd> |

### Робота з областю

| Опис | Команда |
|-----:|:-------:|
| видаляє помічений текст `kill-region` | <kbd>Ctrl</kbd>-<kbd>W</kbd> |
| записати його в регістр за допомогою | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>S</kbd> |
| преобразувати регістр | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>L</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>U</kbd> |
| зробити відступ | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Tab</kbd>, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>\\</kbd> |
| роздрукувати за допомогою | <kbd>Meta</kbd>-<kbd>X</kbd> print-region |
| вирахувати його як Lysp-код за допомогою | <kbd>Meta</kbd>-<kbd>X</kbd> eval-region |

### Команди для позначки текстуальних об'єктів

| Опис | Команда |
|-----:|:-------:|
| встановити мітку після кінця наступного Lisp виразу `mark-sexp`, команда не рухає точку | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>@</kbd> |
| встановити область навколо поточного визначення функції Lispa `mark-defun` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>H</kbd> |
| встановити область навколо усього поточного буфера `mark-whole-buffer` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>H</kbd> |

## Регістри

| Опис | Команда |
|-----:|:-------:|
| видати опис того, що містить регістр **r** | <kbd>Meta</kbd>-<kbd>X</kbd> view-register <kbd>Ret</kbd> <kbd>r</kbd> |

### Запис позицій в регистрі

| Опис | Команда |
|-----:|:-------:|
| записати положення точки в регістр **r** `point-to-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>Spc</kbd> r |
| перейти в позицію записану в регістр **r** `jump-to-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>J</kbd> r |

### Запис тексту в регістрі

| Опис | Команда |
|-----:|:-------:|
| копіювати область в регістр **r** `copy-to-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>S</kbd> r |
| вставити текст із регістру **r** `insert-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>I</kbd> r |

### Запис прямокутника в регістрі

| Опис | Команда |
|-----:|:-------:|
| копіює область-прямокутник в регістр **r** `copy-region-to-rectangle` з числовим аргументом ще і видаляє його | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>R</kbd> r |
| вставляє прямокутник, який записаний в регістрі **r**, якщо той містить прямокутник `insert-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>I</kbd> <kbd>R</kbd> r |

### Запис конфігурації вікон в реєстрації

| Опис | Команда |
|-----:|:-------:|
| записати стан вікон обраного фрейма в регістр **r** `window-configuration-to-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>W</kbd> r |
| записати стан всіх фреймів, включаючи всі їхні вікна, в регістр **r** `frame-configuration-to-register` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R<kbd> <kbd>F</kbd> r |

### Зберігання чисел в регістрах

| Опис | Команда |
|-----:|:-------:|
| записати число в регістер **per** `number-to-register` | <kbd>Ctrl</kbd>-<kbd>U</kbd> foo <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>N</kbd> per |
| збільшити число в регістрі **per** на задане число `increment-register` | <kbd>Ctrl</kbd>-<kbd>U</kbd> foo <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>+</kbd> per |
| вставити число із регістра **per** в буфер | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>G</kbd> per |

### Закладки

| Опис | Команда |
|-----:|:-------:|
| закласти закладку в поточному файлі в позиції точки | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>M</kbd> <kbd>Ret</kbd> |
| закласти в точці закладку з ім'ям закладка `bookmark-set` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>M</kbd> foo <kbd>Ret</kbd> |
| перейти до закладки з ім'ям закладки `bookmark-jump` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>B</kbd> foo <kbd>Ret</kbd> |
| перерахувати усі закладки `list-bookmarks` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>L</kbd> |
| зберегти всі поточні значення закладок в файлі закладок, використовуваному за замовчуванням | <kbd>Meta</kbd>-<kbd>X</kbd> bookmark-save |
| завантажити файл з ім'ям, що містить список значень закладок. Ви можете використовувати цю команду, як і команду `bookmark-write`, для роботи з іншими файлами закладок крім вашого файлу закладок за замовчуванням | <kbd>Meta</kbd>-<kbd>X</kbd> bookmark-load <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| завантажити файл з ім'ям файлу, що містить список закладок. Ви можете використовувати цю команду, як і команду `bookmark-write`, для роботи з іншими файлами закладок крім вашого файлу закладок за замовчуванням | <kbd>Mate</kbd>-<kbd>X</kbd> bookmark-load <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| зберегти всі поточні значення закладок в файлі | <kbd>Meta</kbd>-<kbd>X</kbd> bookmark-write <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| видалити закладку | <kbd>Meta</kbd>-<kbd>X</kbd> bookmark-delete <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| вставити в буфер ім'я файлу на який вказує закладка | <kbd>Meta</kbd>-<kbd>X</kbd> bookmark-insert-location </kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| вставити в буфер вміст файлу на який вказує закладка | <kbd>Meta</kbd>-<kbd>X</kbd> bookmark-insert <kbd>Ret</kbd> foo <kbd>Ret</kbd> |

## Управління Зображенням

### Прокрутка

| Опис | Команда |
|-----:|:-------:|
| очистити екран і відновити зображення, зрушуючи по вертикалі вбрання вікно до центральної точки в межах вікна `recentr` | <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| **next** - прокрутити вперед (на одне вікно або на певне число рядків) `scroll-up` | <kbd>Ctrl</kbd>-<kbd>V</kbd> |
| **prior** - прокрутити назад `scroll-down` | <kbd>Meta</kbd>-<kbd>V</kbd> |
| прокрутити таким чином, що точка виявляється на рядку аргумента `recentr` | foo <kbd>Ctrl</kbd>-<kbd>L</kbd> |
| прокрутити еврестичний, щоб вивести на екран корисну інформацію `reposition-window` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>L</kbd> |

### Горизонтальна прокрутка

| Опис | Команда |
|-----:|:-------:|
| прокручує текст поточного вікна вліво `scroll-left` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd><</kbd> |
| прокручує вправо `scroll-right` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>></kbd> |

## Відступи

| Опис | Команда |
|-----:|:-------:|
| зробити відступ поточного рядка відповідний режим | <kbd>Tab</kbd> |
| виконати <kbd>Ret</kbd> за яким слід <kbd>Tab</kbd> `newline-and-indent` | <kbd>Ctrl</kbd>-<kbd>J</kbd> |
| злити два рядки `delete-indentation` це скасовує дію <kbd>Ctrl</kbd>-<kbd>J</kbd> | <kbd>Meta</kbd>-<kbd>^</kbd> |
| розбити рядок в точці, текст на рядку після крапки стає новим рядком з відступом до того, з якого він починається зараз зараз `split-line` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>O</kbd> |
| пересунути (вперед або назад) до першого не порожнього знаку на поточному рядку `back-to-indentation` | <kbd>Meta</kbd>-<kbd>M</kbd> |
| зробити відступ кількох рядків до одного і того ж стовпчика `indent-region` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>\**<kbd> |
| жорстко зрушити блок рядків вліво або вправо `indent-rigidly` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Tab</kbd> |
| зробити відступ від точки до наступного зумовленої колонки позиції табуляції `tab-to-tab-stop` | <kbd>Meta</kbd>-<kbd>I</kbd> |
| зробити відступ від точки до місця під точкою відступу в попередньому рядку | <kbd>Meta</kbd>-<kbd>X</kbd> indent-relative |

## Вхід і Вихід з Emacs

### Вихід з Emacs

| Опис | Команда |
|-----:|:-------:|
| призупинити Emacs `suspend-emacs` або мінімізувати поточний фрейм `iconify-or-deiconify-frame`, тимчасовий вихід із Emacs `fg` або `%emacs` для повернення | <kbd>Ctrl</kbd>-<kbd>Z</kbd> |
| знищити Emacs `save-buffers-kill-emacs` завершити роботу | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>C</kbd> |

## Використання Безлічі Буферів

### Створення і вибір буферів

| Опис | Команда |
|-----:|:-------:|
| переключення в буфер **foo** `switch-to-buffer` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>B</kbd> foo <kbd>Ret</kbd> |
| вбирає буфер в другому фреймі `switch-to-buffer-other-frame` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>5</kbd> <kbd>B</kbd> buffer <kbd>Ret</kbd> |
| список буферів `list-buffers` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>B</kbd> |

### Різноманітні операції над буфером

| Опис | Команда |
|-----:|:-------:|
| переключити доступ на запис в буфер `vs-toggle-read-only` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>Q</kbd> |
| змінити імя поточного буфера | <kbd>Meta</kbd>-<kbd>X</kbd> rename-buffer <kbd>Ret</kbd> foo <kbd>Ret</kbd> |
| перейменувати буфер доданням числа у кінець імені | <kbd>Meta</kbd>-<kbd>X</kbd> rename-uniquely |
| подивиться буфер | <kbd>Meta</kbd>-<kbd>X</kbd> view-buffer <kbd>Ret</kbd> buffer <kbd>Ret</kbd> |
| знищити буфер `kill-buffer` | <kbd>Ctrl</kbd>-<kbd>X</kbd> buffer <kbd>Ret</kbd> |
| пропонує знищити кожен буфер один за одним | <kbd>Meta</kbd>-<kbd>X</kbd> kill-some-buffers |

### Дії над декількома буферами

| Опис | Команда |
|-----:|:-------:|
| почати редагувати буфер, що містить список усіх буферів Emacs | <kbd>Meta</kbd>-<kbd>X</kbd> buffer-menu |
| запросити видалення (знищення) буфера і потім зрушити вниз, запит показується як **D** на рядку перед імям буфера, витребувані, видаленні, коли ви друкуєте команду **x** | <kbd>D</kbd> |
| як **d** але зрушує вгору а не вниз | <kbd>Ctrl</kbd>-<kbd>D</kbd> |
| запросити збереження буфера, запит показується як **S** на рядку, необхідні збереження відбуваються, коли використовується команда **x**, ви можете запросити і запис, і видалення для одного і того ж буфера | <kbd>S</kbd> |
| виконати раніше заплутані видалення і збереження | <kbd>X</kbd> |
| знищити будь-який запит, зроблений для поточного рядка і зрушити курсор донизу | <kbd>U</kbd> |
| зрушити курсор до попереднього рядка і знищити будь-який запит, зроблений для цього рядка | <kbd>Del</kbd> |
| позначити буфер як незмінний, команда **~** робить це негайно після того, як ви її ввели | <kbd>~</kbd> |
| перемикає прапор доступності на запис для буфера, команда `%` діє відразу після введення | <kbd>%</kbd> |
| звернутися до буферу як до таблиці тегів | <kbd>T</kbd> |
| вийти з меню буферів - відразу відобразити останній буфер, що був раніше видимим на його місці | <kbd>Q</kbd> |
| негайно вибрати буфер на цьому рядку на місці буфера **Buffer List** | <kbd>Ret</kbd> <kbd>F</kbd> |
| негайно вибрати буфер на цьому рядку в іншому вікні, як якщо б це було зроблено за допомогою <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>4</kbd> <kbd>B</kbd>, залишаючи **Buffer List** видимим | <kbd>O</kbd> |
| негайно відобразити буфер на цьому рядку в іншому вікні, але не вибрати це вікно | <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| негайно вибрати буфер на цьому рядку в повноекранному вікні | <kbd>1</kbd> |
| негайно створити два вікна, одне з буфером на цьому рядку, а друге з попереднім обраним буфером (крім буфера **Bufer List**) | <kbd>2</kbd> |
| сховати буфер, перерахований в поточному рядку | <kbd>B</kbd> |
| помітити цей буфер для показу в іншому вікні, якщо ви вийдіть з допомогою команди **q**, такий запит показується як **>** на початку рядка (один і той же буфер не може мати і запит на показ і запит на видалення) | <kbd>M</kbd> |
| негайно вибрати буфер на цьому рядку, а також показати в інших вікнах будь-які буфери, перш помічені за допомогою команди **m**, якщо таких буферів немає, то ця команда еквівалентна 1 | <kbd>V</kbd> |

### Непрямі буфери

| Опис | Команда |
|-----:|:-------:|
| створює непрямий буфер з імям, чи й базовий буфер - це базовий буфер | <kbd>Meta</kbd>-<kbd>X</kbd> make-inderect-buffer buffer <kbd>Ret</kbd> foo <kbd>Ret</kbd> |

## Запуск Команд за Ім'ям

| Опис | Команда |
|-----:|:-------:|
| будь-яка команда може бути викликана за ім'ям <kbd>Meta</kbd>-<kbd>X</kbd> forward-char <kbd>Ret</kbd> або <kbd>Meta</kbd>-<kbd>X</kbd> form <kbd>Tab</kbd> <kbd>C</kbd> <kbd>Ret</kbd> це команда <kbd>Ctrl</kbd>-<kbd>F</kbd> | <kbd>Meta</kbd>-<kbd>X</kbd> |

## Знищення і Переміщення Тексту

### Видалення

| Опис | Команда |
|-----:|:-------:|
| видалити усі пробіли і табуляції навколо точки `delete-horizontal-space` | <kbd>Meta</kbd>-<kbd>\\</kbd> |
| видалити пробіли з табуляції навколо точки, залишаючи один пробіл `just-one-space` | <kbd>Meta</kbd>-<kbd>Spc</kbd> |

### Інші команди знищення

| Опис | Команда |
|-----:|:-------:|
| знищити s-витаз `kill-sexp` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>K</kbd> |
| знищити аж до наступної появи знака `zap-to-char` | <kbd>Meta</kbd>-<kbd>Z</kbd> foo |

### Відновлення

| Опис | Команда |
|-----:|:-------:|
| повертає останній видалений текст `yank` | <kbd>Ctrl</kbd>-<kbd>Y</kbd> |
| для заміни відновленого тексту тим який був знищений раніше `yank-pop` | <kbd>Meta</kbd>-<kbd>Y</kbd> |
| зберегти область як останній знищений текст без фактичного знищення `kill-ring-save` | <kbd>Meta</kbd>-<kbd>W</kbd> |
| додати наступне знищення до останнього куску знищення тексту `append-next-kill` | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>W</kbd> |

### Накопичення тексту

| Опис | Команда |
|-----:|:-------:|
| додати область в заданий буфер після точки | <kbd>Meta</kbd>-<kbd>X</kbd> append-to-buffer |
| додати область в заданий буфер перед точкою | <kbd>Meta</kbd>-<kbd>X</kbd> prepend-to-buffer |
| копіювати область в заданий буфер, видаляючи старий вміст буфера | <kbd>Meta</kbd>-<kbd>X</kbd> copy-to-buffer |
| вставити вміст заданого буфера в поточній буфер в точці | <kbd>Meta</kbd>-<kbd>X</kbd> inset-buffer |
| вставити область в кінець заданого файлу | <kbd>Meta</kbd>-<kbd>X</kbd> append-to-file |

### Прямокутник

| Опис | Команда |
|-----:|:-------:|
| знищити текст області прямокутника, зберігаючи його вміст в якості останнього знищеного прямокутника `kill-rectangle` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>K</kbd> |
| видалити текст області прямокутника `delete-rectangle` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>D</kbd> |
| відновити останній знищений прямокутник, поміщаючи його верхній лівий кут в точці `yank-rectangle` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>Y</kbd> |
| вставити порожнє місце заповнюючи простір області прямокутника `open-rectangle` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>O</kbd> |
| очистити область прямокутника замінюючи її вміст пробілами | <kbd>Meta</kbd>-<kbd>X</kbd> clear-rectangle |
| видалити пробільні знаки в кожному рядку заданого прямокутника, починаючи з його самого лівого стовпця | <kbd>Meta</kbd>-<kbd>X</kbd> delete-whitespace-rectangle |
| вставити рядок в кожній області прямокутника `string-rectangle` | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>R</kbd> <kbd>T</kbd> foo <kbd>Ret</kbd> |

## Ido-modes

| Опис | Команда |
|-----:|:-------:|
| включити/виключити ido-mode | <kbd>Meta</kbd>-<kbd>X</kbd> ido-mode |
| переключити буфер | <kbd>Meta</kbd>-<kbd>X</kbd> ido-switch-buffer |
| відкрити файл | <kbd>Meta</kbd>-<kbd>X</kbd> ido-find-file |
| зробити наступний вибір | arrows |
| зупинити пропозицію, непогано при створені нового файлу | <kbd>Ctrl</kbd>-<kbd>F</kbd> |
| повернути до буфер секції | <kbd>Ctrl</kbd>-<kbd>B</kbd> |
| переключити до відкриття directory-mode | <kbd>Ctrl</kbd>-<kbd>D</kbd> |
| відміна | <kbd>Ctrl</kbd>-<kbd>G</kbd> |

## Довідка

| Опис | Команда |
|-----:|:-------:|
| допомога | <kbd>Ctrl</kbd>-<kbd>H</kbd>, <kbd>F1</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> help <kbd>Ret</kbd> |
| друкує список усіх можливих параметрів допомоги з коротким описом кожного з них | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>H</kbd> |
| показати список команд, чиї імена відповідають регулярному вислову **regexp** `apropos-command` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>A</kbd> regexp <kbd>Ret</kbd> |
| показати таблицю усіх прив'язок ключів, діючих на даний момент в наступному порядку: прив'язку поточних другорядних режимів, прив'язку основного режиму і глобальні прив'язки `describe-bindings` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>B</kbd> |
| надрукувати ім'я команди, яку запускає запускає на виконання заданий ключ `describe-key-briefly`, тут 'С' означає **character** (**знак**), для отримання більш докладної інформації про ключі, використовується <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>K</kbd> | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>C</kbd> foo |
| показати документацію на лісповськиє функції з ім'ям функція `describe-function`, так як команди є лісповські функції, ви можете використовувати ім'я команди | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>F</kbd> foo <kbd>Ret</kbd> |
| вивести файл "hello", який показує приклади різних наборів знаків | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>H</kbd> |
| запустити інфо, програми для перегляду файлу документації **info**, повне керівництво по Emacs існує як діалоговий файл в **info** | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>I</kbd> |
| показати ім'я і опис команди, яку запускає ключ `describe-key` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>K</kbd> foo |
| показує опис останніх 100 набраних вами знаків `view-lossage` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>L</kbd> |
| показати опис поточного основного режиму `describe-mode` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>M</kbd> |
| показує опис змін в Emacs, першим саме останнє `view-emacs-news` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>N</kbd> |
| знайти пакет по ключовим словам `finder-by-keyword` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>P</kbd> |
| показати поточний зміст синтаксичної таблиці і пояснити, що воно означає `describe-syntax` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>S</kbd> |
| зайти в інтерактивний самовчитель по Emacs `help-with-titorial` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>T</kbd> |
| показати опис лисповської змінної `describe-variable` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>V</kbd> foo <kbd>Ret</kbd> |
| надрукувати, які ключі запускають на виконання команду з ім'ям команда (where-is) | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>W</kbd> foo <kbd>Ret</kbd> |
| дивиться деталі про наборах знаків, системах кодування і методах введення, використовуваних у мовному середовищі `describe-language-environment` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>L</kbd> foo <kbd>Ret</kbd> |
| показати умови копіювання GNU Emacs | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>C</kbd> |
| показати інформацію о отриманні нових версій GNU Emacs | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>D</kbd> |
| ввійти в **info** с перейти до ноде, описує функцію Emacs з ім'ям функції `info-goto-emacs-command-node` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> foo <kbd>Ret</kbd> |
| ввійти в **info** с перейти до ноде, описує задану послідовність ключів `info-goto-emacs-key-command-node` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> foo |
| показати інформацію о проекті GNU | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>P</kbd> |
| показати документацію **info** на мовний символ у відповідності з мовою програмування, на якому ви пишите `info-lookup-symbol` | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Tab</kbd> foo <kbd>Ret</kbd> |
| про Emacs | <kbd>Ctrl</kbd>-<kbd>H</kbd> <kbd>Ctrl</kbd>-<kbd>A</kbd> |

### Команди режиму Help

| Опис | Команда |
|-----:|:-------:|
| прокручує у період | <kbd>Spc</kbd> |
| прокручує назад | <kbd>Del</kbd> |
| переходити по перехресному посиланні в точці | <kbd>Ret</kbd> |
| переміщує вперед до наступного перехресного посилання | <kbd>Tab</kbd> |
| переміщує назад до попереднього перехресного посилання | <kbd>S</kbd>-<kbd>Tab</kbd> |

## Пошук Бібліотеках Ліспа за Ключовими Словами

| Опис | Ключове слово |
|-----:|:-------:|
| управління скороченнями, швидкі клавіші, макроси | **abbrev** |
| підтримка обробника бібліографті bib | **bib** |
| підтримка мов C і C++ | **c** |
| підтримка календаря та операції з часом | **calendar** |
| комунікації, мережі, віддалений доступ до файлу | **comm** |
| підтримка редагування файлів з даними | **data** |
| підтримка документації Emacs | **docs** |
| емуляція інших редакторів | **emulations** |
| розширення мови Emacs Lisp | **extensions** |
| підтримка різних накреслень (шрифтів і кольорів) | **faces** |
| підтримка фреймів і віконних систем | **frames** |
| ігри, жарти і розваги | **games** |
| підтримка інтерфейсів з екзотичної апаратури | **hardware** |
| підтримка інтерактивних довідкових систем | **help** |
| підтримка для посилань у тексті | **hypermedia** |
| підтримка різних мов і алфавітів | **i18n** |
| внутрішній код Emacs, збірка, значення за замовчуванням | **internal** |
| спеціалізовані режими для редагування коду | **languages** |
| підтримка використання Лиспа (включаючи Emacs Lisp) | **lisp** |
| бібліотеку, локальні для вашої системи | **local** |
| кошти підтримки для групи розробників Emacs | **maint** |
| режими для роботи з електронною поштою | **mail** |
| пошукові програми | **matching** |
| підтримка читання і відправки мережевих новин | **news** |
| підтримка для редагування не текстових файлів | **non-text** |
| підтримка об'єктно-орієнтованого програмування | **oop** |
| перегляд ієрархічної структури тексту | **outlines** |
| процеси, оболонка, компіляції і управління завданнями | **processes** |
| підтримка різних типів терміналів | **terminals** |
| підтримка для програми комп'ютерного набору TEX | **tex** |
| утиліти для програмування | **tools** |
| інтерфейсу або емулятору можливостей Unix | **unix** |
| підтримка VMS | **vms** |
| обробка тексту | **wp** |

## Маркування

| Опис | Команда |
|-----:|:-------:|
| встановлення мітки | <kbd>Alt</kbd>-<kbd>X</kbd> set-mark-command, <kbd>Ctrl</kbd>-<kbd>Space</kbd>, <kbd>Ctrl</kbd>-<kbd>@</kbd> |
| прокрутити кільце з міткою | <kbd>Ctrl</kbd>-<kbd>U</kbd> <kbd>Ctrl</kbd>-<kbd>Space</kbd> |
| точка та позначка заміни | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>X</kbd> |
| зробити так, щоб регіон містив поточний абзац | <kbd>Meta</kbd>-<kbd>H</kbd> |
| вузький буфер до поточного регіону | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>N</kbd> |
| відновити буфер/розширити | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>N</kbd> <kbd>W</kbd> |
| зробити регіон коментарем або без коментаря | <kbd>Meta</kbd>-<kbd>X</kbd> comment-dwin, <kbd>Meta</kbd>-<kbd>;</kbd> |

## Макрос

| Опис | Команда |
|-----:|:-------:|
| почати запис макросу | <kbd>F3</kbd> |
| зупинити запис макросу/відтворити макрос один раз | <kbd>F4</kbd> |
| відтворити макрос `$0` разів | <kbd>Alt</kbd>-`$0` <kbd>F4</kbd> |
| відтворювати макрос знову і знову, доки він не завершиться невдачею | <kbd>Meta</kbd>-<kbd>0</kbd> <kbd>F4</kbd>  |

## Версії

| Опис | Команда |
|-----:|:-------:|
| виводить різницю, яка показує зміни, зроблені у поточному файлі | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>=</kbd> |
| запитує номер версії і показує цю версію поточного файлу в іншому вікні | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>~</kbd> |
| виводить анотовану версію файлу, показуючи для кожного рядка | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>G</kbd> |
| виводить журнал попередніх змін у файлі | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>V</kbd> <kbd>L</kbd> |

## Major-mode

| Опис | Команда |
|-----:|:-------:|
| режим для редагування java-файлів | <kbd>Meta</kbd>-<kbd>X</kbd> java-mode |
| режим для редагування python-файлів | <kbd>Meta</kbd>-<kbd>X</kbd> python-mode |
| режим для редагування текстових файлів | <kbd>Meta</kbd>-<kbd>X</kbd> text-mode |
| режим без будь-яких спеціалізацій | <kbd>Meta</kbd>+<kbd>X</kbd> fundamental-mode |

## Minor-mode

| Опис | Команда |
|-----:|:-------:|
| якщо буфер відображається у двох вікнах поруч, режим follow змушує їх прокручуватися разом | <kbd>Meta</kbd>-<kbd>X</kbd> follow-mode |
| показувати завершення під час введення | <kbd>Meta</kbd>-<kbd>X</kbd> icomplete-mode |
| показувати всі імена буферів при перемиканні буферів за допомогою <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>B</kbd> | <kbd>Alt</kbd>-<kbd>X</kbd> iswitchb-mode |

## Mode

| Опис | Команда |
|-----:|:-------:|
| емуляція поведінки редагування vi у Emacs | <kbd>Meta</kbd>-<kbd>X</kbd> viper-mode |
| Стандартні клавіші режиму cua для копіювання, вирізання та вставки | <kbd>Meta</kbd>-<kbd>X</kbd> cua-mode |
| вирізати, копіювати, вставляти, скасовувати в режимі cua | <kbd>Ctrl</kbd>-<kbd>X</kbd>, <kbd>Ctrl</kbd>-<kbd>C</kbd>, <kbd>Ctrl</kbd>-<kbd>V</kbd>, <kbd>Ctrl</kbd>-<kbd>Z</kbd> |

## Ігри

| Опис | Команда |
|-----:|:-------:|
| тетріс | <kbd>Meta</kbd>-<kbd>X</kbd> tetris |
| гра "вежі ханоя" | <kbd>Meta</kbd>-<kbd>X</kbd> hanoi |
| психотерапевт emacs | <kbd>Meta</kbd>-<kbd>X</kbd> doctor |

## View-mode Minor Mode Bindings

| Опис | Команда |
|-----:|:-------:|
| View-scroll-line-forward | <kbd>Ctrl</kbd>-<kbd>J</kbd> |
| View-scroll-page-forward | <kbd>Spc</kbd> |
| View-goto-percent | <kbd>%</kbd> |
| register-to-point | <kbd>'</kbd> |
| negative-argument | <kbd>Ctrl</kbd>-<kbd>-</kbd>, <kbd>Meta</kbd>-<kbd>-</kbd>, <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>-</kbd> |
| View-search-regexp-forward | <kbd>/</kbd> |
| digit-argument | <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>0</kbd> .. <kbd>Ctrl</kbd>-<kbd>Meta</kbd>-<kbd>9</kbd>, <kbd>Meta</kbd>-<kbd>0</kbd> .. <kbd>Meta</kbd>-<kbd>9</kbd> |
| View-back-to-mark | <kbd>@</kbd> |
| View-kill-and-leave | <kbd>C</kbd> |
| View-exit-and-edit | <kbd>E</kbd> |
| View-revert-buffer-scroll-page-forward | <kbd>F</kbd> |
| View-quit-all | <kbd>Q</kbd> |
| View-search-regexp-backward | <kbd>\\</kbd> |
| View-leave | <kbd>C</kbd> |
| View-scroll-half-page-forward | <kbd>D</kbd> |
| View-exit | <kbd>E</kbd> |
| View-goto-line | <kbd>G</kbd> |
| View-search-last-regexp-forward | <kbd>N</kbd> |
| View-scroll-to-buffer-end | <kbd>O</kbd> |
| View-search-last-regexp-backward | <kbd>P</kbd> |
| View-quit | <kbd>Q</kbd> |
| View-scroll-half-page-backward | <kbd>U</kbd> |
| View-scroll-page-backward-set-page-size | <kbd>W</kbd> |
| View-scroll-line-backward | <kbd>Y</kbd> |
| View-scroll-page-forward-set-page-size | <kbd>Z</kbd> |

## Major Mode Bindings

| Опис | Команда |
|-----:|:-------:|
| префікс команди, що залежить від режиму/Існує також winner-redo | <kbd>Ctrl</kbd>-<kbd>C</kbd> |
| forward-button | <kbd>Tab</kbd> |
| backward-button | <kbd>Meta</kbd>-<kbd>Tab</kbd>, <kbd>Backtab</kbd> |
| help-go-back | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>B</kbd> |
| help-follow-symbol | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>C</kbd> |
| help-go-forward | <kbd>Ctrl</kbd>-<kbd>C</kbd> <kbd>Ctrl</kbd>-<kbd>F</kbd> |

## Global Bindings

| Опис | Команда |
|-----:|:-------:|
| open-line | <kbd>Ctrl</kbd>-<kbd>O</kbd> |
| quoted-insert | <kbd>Ctrl</kbd>-<kbd>Q</kbd> |
| transpose-chars | <kbd>Ctrl</kbd>-<kbd>T</kbd> |
| Control-X-prefix | <kbd>Ctrl</kbd>-<kbd>X</kbd> |
| toggle-input-method | <kbd>Ctrl</kbd>-<kbd>\\</kbd> |
| abort-recursive-edit | <kbd>Ctrl</kbd>-<kbd>]</kbd> |

## Shell

| Опис | Команда |
|-----:|:-------:|
| run the previous shell command | <kbd>Ctrl</kbd>-arrow_up |
| this will create a new term for each command call | <kbd>Meta</kbd>-<kbd>X</kbd> term |
| run just 1 shell command | <kbd>Meta</kbd>-<kbd>X</kbd> shell-command, <kbd>Meta</kbd>-<kbd>!</kbd> |
| tm<kbd>Meta</kbd>-menubar | <kbd>Meta</kbd>-` |
| Back (last node) | <kbd>L</kbd> |
| Forward | <kbd>R</kbd> |
| parent node (up) | <kbd>U</kbd> |
| previous node | <kbd>P</kbd> |
| next node | <kbd>N</kbd> |
| search | <kbd>S</kbd> |
| quit info | <kbd>Q</kbd> |
| view help | <kbd>H</kbd> |
| find a function's documentation in the emacs lisp manual | <kbd>Meta</kbd>-<kbd>X</kbd> elisp-index-search |
| spell check whole buffer | <kbd>Meta</kbd>-<kbd>X</kbd> flyspell-buffer |
| move cursor to next error (only when flyspell-mode is on.) | <kbd>Meta</kbd>-<kbd>X</kbd> flyspell-goto-next-error, <kbd>Ctrl</kbd>-<kbd>,</kbd> |
| correct the word under cursor | <kbd>Meta</kbd>-<kbd>X</kbd> flyspell-auto-correct-word, <kbd>Ctrl</kbd>-<kbd>.</kbd> |
| image-next-file to view next image | N |
| image-previous-file to view previous image | P |

## Viewing a gif animation:

| Опис | Команда |
|-----:|:-------:|
| image-next-frame for next frame | <kbd>F</kbd> |
| image-previous-frame for previous frame | <kbd>B</kbd> |
| image-goto-frame to go to a specific frame | <kbd>F</kbd> |
| image-increase-speed | `a` `+` |
| image-decrease-speed | `a` `-` |
| image-reset-speed | `a` `0` |
| image-reverse-speed | `a` `r` |
| eval function definition block the cursor is in. (the elisp code must be well-indended, otherwise emacs may have problem finding function.) | eval-defun |
| start emacs interactive emacs lisp shell | <kbd>Meta</kbd>-<kbd>X</kbd> ielm |
| search variable names | <kbd>Meta</kbd>-<kbd>X</kbd> apropos-variable |
| search variable values | <kbd>Meta</kbd>-<kbd>X</kbd> apropos-value |
| search all symbols space (commands, functions, variables, faces) | <kbd>Meta</kbd>-<kbd>X</kbd> apropos |
| find a function's documentation in the emacs manual | <kbd>Meta</kbd>-<kbd>X</kbd> emacs-index-search |
| turn on syntax highlight | <kbd>Meta</kbd>-<kbd>X</kbd> emacs-lisp-mode |
| split left/right/split-window-right | <kbd>Ctrl</kbd>-<kbd>X</kbd>-<kbd>3</kbd> |
| can go back to previous split pane config | <kbd>Meta</kbd>-<kbd>X</kbd> winner-undo |
| customize a particular mode directly | <kbd>Meta</kbd>-<kbd>X</kbd> customize-group |
| show a list of available themes | <kbd>Meta</kbd>-<kbd>X</kbd> load-theme |
| mark all backup files for deletion | dired-flag-backup-files, `~` |
| (execute) delete files flagged for deletion | dired-do-flagged-delete, `x` |
| change all cursor movement/edit commands to stop in-between the “camelCase” words | <kbd>Meta</kbd>-<kbd>X</kbd> subword-mode |
| similar. It treats text like “x_y” as one word. Useful for “snake_case” | <kbd>Meta</kbd>-<kbd>X</kbd> superword-mode |

## Eww Web Browser

| Опис | Команда |
|-----:|:-------:|
| start the web browser | <kbd>Meta</kbd>-<kbd>X</kbd> eww |

### Eww Keybinding

| Опис | Команда |
|-----:|:-------:|
| eww-previous-url | `P` |
| eww-forward-url | `R` |
| eww-browse-with-external-browser | `&` |
| eww-reload | `G` |
| eww-copy-page-url | `W` |
| eww-view-source | `V` |
| eww-open-file | <kbd>Meta</kbd>-<kbd>X</kbd> |
| eww-browse-with-external-browser, & - When in eww | <kbd>Meta</kbd>-<kbd>X</kbd> |
| open the file path under cursor, also works for URL | <kbd>Meta</kbd>-<kbd>X</kbd> find-file-at-point |
| insert a literal tab | <kbd>Ctrl</kbd>-<kbd>Q</kbd> <kbd>Ctrl</kbd>-<kbd>Tab</kbd> |
| insert a newline | <kbd>Ctrl</kbd>-<kbd>Q</kbd> <kbd>Return</kbd> |
| Emacs has a interactive regex mode | <kbd>Meta</kbd>-<kbd>X</kbd> regexp-builder |
| list all matching text of all files in the current directory | <kbd>Meta</kbd>-<kbd>X</kbd> grep |
| A - will prompt you for a search string, then open the first file of the match, with your cursor placed at the matching location | <kbd>Meta</kbd>-<kbd>X</kbd> dired-do-search |

## Files by Regex

| Опис | Команда |
|-----:|:-------:|
| list all opened files | <kbd>Meta</kbd>-<kbd>X</kbd> ibuffer |
| start recording | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>(</kbd>, <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>Ctrl</kbd>-<kbd>K</kbd> <kbd>Ctrl</kbd>-<kbd>S</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> kmacro-start-macro |
| stop recording | <kbd>Meta</kbd>-<kbd>X</kbd> kmacro-end-macro |
| and start over | <kbd>Meta</kbd>-<kbd>X</kbd> keyboard-quit |

## Run Keyboard Macro

| Опис | Команда |
|-----:|:-------:|
| kmacro-end-and-call-macro | <kbd>Ctrl</kbd>-<kbd>X</kbd> <kbd>E</kbd>, <kbd>Meta</kbd>-<kbd>X</kbd> kmacro-end-and-call-macro |
| give it a name | <kbd>Meta</kbd>-<kbd>X</kbd> name-last-kbd-macro |
| This will insert the lisp code for a named kmacro at the cursor position | <kbd>Meta</kbd>-<kbd>X</kbd> insert-kbd-macro |

### in the bookmark file

| Опис | Команда |
|-----:|:-------:|
| mark the current item for remove | <kbd>D</kbd> |
| remove all D marked ones | <kbd>X</kbd> |
| rename current item's title | <kbd>R</kbd> |
| save the change | <kbd>S</kbd> |
| toggle search case-sensitivity | <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>C</kbd> |
| before isearch | <kbd>Meta</kbd>-<kbd>X</kbd> toggle-case-fold-search |
| Search the “symbol” under cursor, with boundary check | <kbd>Meta</kbd>-<kbd>X</kbd> isearch-forward-symbol-at-point, <kbd>Meta</kbd>-<kbd>S</kbd> <kbd>.</kbd> |
| show line numbers in all buffers | <kbd>Meta</kbd>-<kbd>X</kbd> global-display-line-numbers-mode |
| show line numbers in current buffer | <kbd>Meta</kbd>-<kbd>X</kbd> display-line-numbers-mode |
| toggle line number in current | <kbd>Meta</kbd>-<kbd>X</kbd> linuAlt-mode |
| toggle line number in all buffers | <kbd>Meta</kbd>-<kbd>X</kbd> global-linuAlt-mode |
| show line number and cursor column position in mode line (aka status bar), like this: (166,3). The first is line number, the second is position from the beginning of line | <kbd>Meta</kbd>-<kbd>X</kbd> column-number-mode |
| display a ruler at top of current window | <kbd>Meta</kbd>-<kbd>X</kbd> ruler-mode |
| show the current cursor position | <kbd>Meta</kbd>-<kbd>X</kbd> describe-char |
| turn it on | <kbd>Meta</kbd>-<kbd>X</kbd> recentf-mode |
| list recently opened file | <kbd>Meta</kbd>-<kbd>X</kbd> recentf-open-files |
| insert a literal tab | <kbd>Ctrl</kbd>-<kbd>Q</kbd> <kbd>Tab</kbd>, <kbd>Ctrl</kbd>-<kbd>Q</kbd> <kbd>Ctrl</kbd>-<kbd>I</kbd> |
| search the same word searched last time | <kbd>Ctrl</kbd>-<kbd>S</kbd>-<kbd>Ctrl</kbd>-<kbd>S</kbd> |
| search the word under the cursor. You can type  multiple times to expand the word selection | <kbd>Ctrl</kbd>-<kbd>S</kbd>-<kbd>Ctrl</kbd>-<kbd>W</kbd> |
| reverse order in region by lines | <kbd>Meta</kbd>-<kbd>X</kbd> reverse-region |
| does it to the whole buffer | <kbd>Meta</kbd>-<kbd>X</kbd> delete-trailing-whitespace |

in dired press L (dired-do-load) on the file name

| Опис | Команда |
|-----:|:-------:|
| open the file as hex | <kbd>Meta</kbd>-<kbd>X</kbd> hexl-find-file |
| toggle on/off globally for current emacs session | <kbd>Meta</kbd>-<kbd>X</kbd> global-whitespace-mode |
