# DOCKER


> :information_source: **Інформація:** Надає набір інструментів розробки, сервісів, надійного контенту та автоматизації, які можна використовувати як окремо, так і разом, щоб пришвидшити створення безпечних додатків.

:open_file_folder: **Розділ** :hammer_and_wrench: *Інструменти Розробника*

---

## Про docker

| Опис | Інформація |
| ---- | ---------- |
| **версія :package: програми** | :four: . :two: :four: . :zero: |
| :computer: **розробник** | Docker, Inc. |
| **сайт** | [:link: посилання](https://www.docker.com/) |

## :inbox_tray: Встановлення

- :inbox_tray: встановити з **SOURCEFORGE** за [:link: посиланням](https://sourceforge.net/projects/docker-compose.mirror/files/)

### :desktop_computer: Windows

- :inbox_tray: встановлення з сайту за [:link: посиланням](https://hub.docker.com/)
- :inbox_tray: встановлення з :cloud: Хмарного сховища

### :penguin: Linux

> :information_source: **Інформація:** Docker Desktop для :penguin: Linux запускає віртуальну машину (VM), тому створює і використовує власний контекст докера desktop-linux під час запуску.
>Це означає, що образи і контейнери, розгорнуті на :penguin: Linux Docker Engine (до встановлення), недоступні у Docker Desktop для :penguin: Linux.

#### Підтримувані платформи

| Платформа |    x86_64/amd64    |
|:---------:|:------------------:|
|  Ubuntu   | :white_check_mark: |
|  Debian   | :white_check_mark: |
|  Fedora   | :white_check_mark: |

- :inbox_tray: встановлення за допомогою **Snap Store**:
  - **версія :package: програми** latest/stable команда для терміналу: `sudo snap install docker`
  - **версія :package: програми** latest/candidate команда для терміналу: `sudo snap install docker --candidate`
  - **версія :package: програми** latest/beta команда для терміналу: `sudo snap install docker --beta`
  - **версія :package: програми** latest/edge команда для терміналу: `sudo snap install docker --edge`
  - **версія :package: програми** core :one: :eight: /stable команда для терміналу: `sudo snap install docker --channel=core18/stable`

#### fedora WORKSTATION

##### :inbox_tray: Встановлення за допомогою rpm-репозиторію

Перед першим встановленням Docker Engine на новий хост-машину, вам потрібно налаштувати репозиторій Docker. Після цього ви зможете встановлювати та оновлювати Docker з репозиторію.

###### :gear: Налаштування сховища

:inbox_tray: Встановіть пакунок `dnf-plugins-core` (який містить команди для керування вашими сховищами DNF) та :gear: налаштуйте сховище.

```bash
sudo dnf -y install dnf-plugins-core
sudo dnf config-manager --add-repo https://download.docker.com/linux/fedora/docker-ce.repo
```

:inbox_tray: Install Docker Engine

```bash
sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
