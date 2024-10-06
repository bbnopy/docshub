# FIREFOX BROWSER


> :information_source: **Інформація:** Вільний безкоштовний браузер з відкритим кодом, використовує ядро Quantum.

:open_file_folder: **Розділ** :globe_with_meridians: *Інтернет*

---

## Про Firefox Браузер

| Опис | Інформація |
| ---- | ---------- |
| **версія :package: програми** | :one: :three: :one: . :zero: |
| :computer: **розробник** | Mozilla Foundation, Mozilla Messaging |
| **сайт** | [:link: посилання](https://www.mozilla.org/uk/firefox/new/) |

## :inbox_tray: Встановлення

#### :desktop_computer: Windows

- :inbox_tray: встановлення з **Microsoft Store** за [:link: посиланням](https://apps.microsoft.com/store/detail/mozilla-firefox/9NZVDKPMR9RD)
- :inbox_tray: встановлення з сайту за [:link: посиланням](https://www.mozilla.org/uk/firefox/download/thanks/)
- :inbox_tray: встановлення з :cloud: Хмарного сховища

### :penguin: Linux

> :information_source: **Інформація:** щодо :inbox_tray: встановлення за [:link: посиланням](https://www.mozilla.org/uk/firefox/download/thanks/)

- :inbox_tray: встановлення за допомогою **Flathub**:
  - вводимо команду у терміналі: `flatpak install flathub org.mozilla.firefox`
- :inbox_tray: встановлення за допомогою **Snap Store**:
  - **версія :package: програми** latest/stable команда для терміналу: `sudo snap install firefox`
  - **версія :package: програми** latest/candidate команда для терміналу: `sudo snap install firefox --candidate`
  - **версія :package: програми** latest/beta команда для терміналу: `sudo snap install firefox --beta`
  - **версія :package: програми** latest/edge команда для терміналу: `sudo snap install firefox --edge`
  - **версія :package: програми** esr/stable команда для терміналу: `sudo snap install firefox --channel=esr/stable`

#### fedora WORKSTATION

- :inbox_tray: встановлення з **Центру :package: програмного забезпечення**

## :gear: Налаштування

Переходимо в :gear: налаштування в адресній строці вводимо `about:config`

- Обираємо "Погодитись на ризик і продовжити".
- Тепер ми починаємо відключати все, що може стежити за нами. Спочатку вводимо значення **extensions.pocket.enabled**, та натискаємо переключити, в значення *false*.
- **media.peerconnection.enabled** - *false*.
- Вимикаємо доступ до геолокації, вводимо значення **geo.enabled** - *false*.
- **geo.provider.ms-windows-location** - *false*.
- Забороняємо збір різних даних зі статистики браузера. Вводимо значення **beacon.enabled** та натискаємо на значок “перемкнути”.
- Забороняємо метрики продуктивності. Вводимо **dom.enable_performance**, **dom.enable_performance_navigation_timing** та **dom.enable_performance_observer** і відключаємо.
- **network.predictor.enabled** - *false*.
- Відключаємо доступ до інформації про встановлені доповнення. Вводимо **extensions.getAddons.cache.enabled** і відключаємо.
- Вимикаємо доступ до датчиків комп’ютера Вводимо **device.sensors.enabled** та **device.sensors.motion.enabled** і відключаємо.
- Вводимо **dom.webaudio.enabled** і відключаємо.
- Вводимо **privacy.resistFingerprinting** і відключаємо.
- Вводимо **dom.netinfo.enabled** і відключаємо.
- Вводимо **dom.gamepad.enabled** і відключаємо.
- Вводимо **media.getusermedia.noise_enabled** і відключаємо, як показано на скріншоті.
- Вводимо **media.navigator.enabled**, **media.navigator.permission.disabled** та **media.navigator.video.enabled** і відключаємо.
- Вводимо **media.webspeech.synth.enabled** та **media.webspeech.test.enable** і відключаємо.
- Вводимо **dom.battery.enabled** і відключаємо.
- Вводимо **dom.vibrator.enabled** і відключаємо.
- Вводимо **dom.vr.require-gesture** і відключаємо.
- Вводимо **dom.vr.poseprediction.enable** і відключаємо.
- Вводимо **dom.vr.openvr.enab** і відключаємо.
- Вводимо **dom.vr.oculus.enabled** та **dom.vr.oculus.invisible.enabled** і відключаємо.
- Вводимо **toolkit.telemetry.archive.enabled**, **toolkit.telemetry.bhrPing.enabled** та **toolkit.telemetry.firstShutdownPing.enabled** і відключаємо.
- Вводимо **toolkit.telemetry.shutdownPingSender.enabledFirstSession** та **toolkit.telemetry.unified** і відключаємо.
- Вводимо **datareporting.healthreport.uploadEnabled** та **datareporting.policy.dataSubmissionEnabled** і відключаємо.
- Вводимо **dom.push.connection.enabled** та **dom.push.enabled** і відключаємо.
- Вводимо **network.dns.disableIPv6** та **network.dns.disablePrefetch** і відключаємо.
- Вводимо **network.trr.mode** і вводимо - 2.
- Вводимо **network.captive-portal-service.maxInterval** і вводимо - 0.
- Вводимо **browser.eme.ui.enabled** і відключаємо.
- Вводимо **media.eme.enabled** і відключаємо.

Переходимо до **Personalize new tab**, там обираємо **Manage more settings**, переходимо до розділу **Privacy & Security** у розділі **Browser Privacy** обираємо *Custom*, мають бути обрані усі налаштування:

- **Cookies** - *Cross-site tracking cookies, and isolate other cross-site cookies*
- **Tracking content** - *обрати*
- **Cryptominers** - *обрати*
- **Known fingerprinters** - *обрати*
- **Suspected fingerprinters** - *Only in private windows*

Переходимо до розділу **Permissions** - відключаємо галочки та забороняємо усі дозволи

У розділі **Firefox Data Collection and Use**

- **Allow Firefox to send technical and interaction data to Mozilla** - забираємо галочку
- **Allow Firefox to install and run studies** - забираємо галочку

У розділі **Security** **Deceptive Content and Dangerous Software Protection** перевіряємо, щоб усі галочки стояли:

- **Block dangerous and deceptive content** - увімкнено
- **Block dangerous downloads** - увімкнено
- **Warn you about unwanted and uncommon software** - увімкнено

Розділ **Certificates** галочки мають стояти навпроти **Query OCSP responder servers to confirm the current validity of certificates** та **Allow Firefox to automatically trust third-party root certificates you install**

Розділ **HTTPS-Only Mode** має бути обрано **Don’t enable HTTPS-Only Mode**

Розділ **Enable DNS over HTTPS using** обираємо **Max Protection**

### Увімкнути або Вимкнути Апаратне Прискорення

> :information_source: **Інформація:** Запускаємо Firefox. Нам потрібно отримати доступ до розширених параметрів конфігурації, які можна відкрити, ввівши `about:config` в адресному рядку. Може попередження, що ви збираєтеся отримати доступ до деяких розширених :gear: налаштувань
> конфігурації - просто натисніть "Прийняти ризик і продовжити".
> У рядку пошуку параметрів введіть `layers.acceleration.force-enabled`. Коли опція з'явиться, буде написано **"false"**, якщо вона вимкнена, і **"true"**, якщо увімкнена. Щоб увімкнути або вимкнути цей параметр, клацніть крайню праву іконку.
> Після увімкнення або вимкнення, перезапустіть браузер **Firefox**.

### Функція WebRender

> :information_source: **Інформація:** Увімкнути WebRender у **Firefox** можна вручну :inbox_tray: встановити значення параметра `gfx.webrender.enabled` або `gfx.webrender.all` в **true** на сторінці `about:config` і перезапустити браузер. Щоб вимкнути вручну :inbox_tray: встановити значення параметра `gfx.webrender.enabled` або `gfx.webrender.all` в **false** на сторінці `about:config` і перезапустити браузер.
> Запустіть Firefox з **MOZ_WEBRENDER=1** як змінною оточення 1. Для відключення запустіть Firefox з **MOZ_WEBRENDER=0** в якості змінної оточення 1.
