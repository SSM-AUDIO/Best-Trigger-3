# Best Trigger 3: changelog

Русская версия ниже: [Русский](#русский)

## English

### 0.3.19
- **E-mail with a key.** The licence window has an e-mail field for the key, too (needed for a key bought on plati.ru). The **Lost your key?** page finds the key by it.

### 0.3.18
- **Messages from SSM-Audio.** The plugin may show a short message in a window (news, an important update). Each message is shown once.

### 0.3.17
- **The trial asks for your e-mail.** Type it in the licence window to start the 14-day trial.

### 0.3.16
- **Match in the trial:** you can search and listen to the answers; putting an answer into the mixer needs a licence key.
- **LUNA** is recognised as a DAW.

### 0.3.15
- **Lost your key?** A link in the licence window; on an activated computer **Show my key** shows the key.
- More programs are recognised: Fender Studio Pro, MorningDAW, LMMS, Zrythm, Qtractor, Mixcraft, Renoise. A program that is still not recognised shows a warning that stays.
- Renamed plates are kept by presets, Undo and A/B.

### 0.3.14
- **Match is part of the main window:** click **Match**, drop a reference hit on the scope, press **Start**. Each answer has **▶**, **Apply**, **Top / Body** and **i**; the **Phase** and **Spectrum** views show the answer you put into the mixer.
- **Better and faster Match:** it finds other layers and microphones of the same instrument, has a new **Top** option and is 3–4 times faster.
- **Repair of sample paths:** a project or preset finds a moved or converted sample again (a setting, on by default).

### 0.3.13
- **Match to a reference (experimental):** pick one hit and the plugin finds samples in your library whose sum sounds like it. Works with a licence key. Details in the manual.
- **Mono per sample:** **Alt + click** (**Opt** on a Mac) on the **Pan** knob.
- **Update notice:** the plugin tells you when this version is too old to work and where to download the new one.

### 0.3.12
- **Activation data:** when the plug-in runs in a program it does not recognise, it now reports the file name of that program (no folder, no user name) instead of just "Unknown". Nothing else changes.

### 0.3.11
- **Envelope on / off:** a right click on the **ENV** button of a channel switches its envelope off and on again; the numbers stay.
- **Channels selected with Ctrl + click change together:** with two or more channels selected, what you change with the mouse on one of them (fader, Pan, Tune, M / S / Ø / OUT, the EQ window, the envelope) is done on all of them.
- **EQ window:** the numbers of a dot (Frequency, Gain, Q) can be dragged up and down with the mouse (**Shift** = finer); the **shelves** have a **Slope** now: 6, 12, 18 or 24 dB per octave.
- **Hold:** a window opened again now shows the real state of the **Hold** button (the scope could stay frozen with the button looking released).

### 0.3.10
- **Cut filters go to the end of the range:** Low Cut and High Cut of the channel EQ (and of the detector) now cover 20 Hz to 20 kHz; before, High Cut could not go below 1 kHz and Low Cut above 2 kHz.
- **Copy / Paste channel settings:** two new items in the right-click menu of a plate copy all the numbers of a channel (fader, pan, EQ and the rest, not the sample) onto another channel. One step of Undo.
- Swapping or copying a channel by dragging is now one step of Undo too.

### 0.3.9
- **Undo works as expected:** every control is a step of its own (even when you change two controls quickly one after the other), **A** and **B** each keep their own history, clicks that change nothing and the scope smoothing are no longer steps, and **Copy** can be undone. **Undo / Redo** now keep the last 20 steps.
- **Video lessons:** a new item in the gear menu opens our YouTube channel. The link is also in the manual and on the download page.

### 0.3.8
- **Fast rolls:** with a low Threshold, a hit that follows another one closely sometimes got too low a velocity. Fixed: every hit of a roll gets its full velocity.
- **Phase view:** the picture and the **Sum gain** now include the EQ of every channel (Low Cut, shelves, bells), so they match what you hear. The pan is counted too.
- **Auto tools:** a right click on the blinking button stops the running tool.

### 0.3.7
- **Move a whole channel:** drag the name of a channel (**Smp 3** at the top of its strip) onto another channel. The two channels swap places with the sample and everything set for it (level, mute, solo, phase, pan, tune, envelope, filters, EQ, role, Offset). With **Ctrl / Cmd** the channel is copied instead. The **OUT** switch stays where it is. Dragging the name plate still swaps only the samples.
- **Window size:** drag the grip in the bottom right corner to change the size of the window (50–300%). The size is remembered; a double click on the grip sets 100%.
- **Licence** button moved to the right panel, under **Clear samples**.
- **Copy** (A/B) no longer opens a menu: it copies the setting that is on onto the other one.

### 0.3.6
- **EQ window:** live spectrum behind the curve (the **Spectrum** button switches it off); gain up to ±30 dB; Low Cut and High Cut slopes of 36 and 48 dB per octave.
- **Library browser:** **Show in Explorer** (Show in Finder on a Mac) in the right-click menu.
- **Sensitivity** starts at 100 in a new plugin.

### 0.3.5
- The **Auto** button is now **Auto menu**. In it, the choice of what the phase is measured on (**Phase detection wide range / narrow range**) moved into the **Phase** section.
- The menu item for starting playback automatically is removed.

### 0.3.4
- **Velocity follows the peak of the hit:** a hit at the **Input** level (−6 dB by default) is velocity 127. The **Soft** control is gone. Older projects may sound a little different: check **Input**.
- **Sensitivity** is a second threshold; the louder of the two decides.
- **Fast rolls and ghost notes** are played.
- **Auto Threshold** and **Full Auto** set **Input** to −6 dB.
- Converted **.tci** instruments play at the volume written in the file: run the **Migration** again to refresh them.
- The right panel has the buttons **Full Auto**, **Auto Threshold**, **Auto Phase** and **Auto** (a menu with the other tools).
- The value boxes above the scope are dragged **up and down**; the wheel changes them a little.
- The plugin's latency is 39 ms.

### 0.3.3
- **Velocity layers and volume** respond like in the well-known trigger.
- **Soft** line on the Timeline; **Input** up to +12 dB.
- **Precise sample start** (settings menu).
- Converted **.tci** instruments are played at the sample rate written in the file.
- The samples sit 3 dB lower; the plugin's output equals the original track and the samples side by side.
- The cross in the library search clears only the search.
- The **0 ms** mode is removed.
- **Buy** opens the payment page.

### 0.3.2
- **EQ:** Low Cut and High Cut get a **Slope** (6, 12, 18 or 24 dB per octave; 12 is the usual one, projects sound the same). The EQ curve no longer draws a line along the bottom edge.
- With **0 ms** on, the **Orig Gate** knob is greyed out (it cannot work without the delay).
- **Buying:** the new purchase page on the site: pay by card or ЮMoney wallet and get the licence key at once.

### 0.3.1
- **EQ on every channel, the Original too** (the FLT button is now EQ): Low Cut, Low Shelf, three Bells, High Shelf and High Cut in a window over the scope. Right-click a dot: that filter off and on. Right-click the EQ button: the whole EQ off and on. Older projects sound the same.
- **Samples:** drag a plate onto another one to swap them (Ctrl/Cmd: copy); Copy, Paste and Rename in the plate menu; select several samples (Ctrl/Cmd + click or a frame) and move their Offsets together.
- **Right-click on M, S or Ø:** only that channel gets it, the others lose it.
- **0 ms** switch on the Original: the original passes with no delay and the plugin reports no latency (off by default).
- **Timeline:** every hit is a line as tall as the hit was loud, with red dots at the ends; an **Input / Output** button shows what comes in or what comes out.
- **Browser:** a search box with a cross; **WAV to .bt3…** converts WAV files (a file, a folder or the whole library) and then asks whether to delete the WAVs.
- **Sum panel:** a **Threshold** knob; Spectrum **Reset** moved to the top; Full Auto keeps the Spectrum view open if it was open.
- **Sound:** a sample recorded at another sample rate than your project (for example a 44.1 kHz file in a 48 kHz project) is now converted with a high-quality filter. Before, the top end above about 6 kHz was slightly dulled; **Tune** keeps more of the top end.

### 0.3.0
- **14-day trial.** Press **Start 14-day trial** in the plugin window: all functions are open for 14 days, no key needed. It is one trial per computer.
- **The free version is gone.** Best Trigger 3 is one product now: the trial, then a licence key (see [how to buy](https://ssm-audio.github.io/Best-Trigger-3/download.html)).
- When the trial has ended the window asks for a licence key; your projects are not changed.
- The manual is reorganised: installation first, then trial and licence, a step-by-step quick start, and a separate description of the scope views.

### 0.2.14
- A **pop-up window** for typing a value (right-click a knob): the numbers are no longer hidden inside the interface.
- **Mac and trackpad:** where **Ctrl** was needed, use **Cmd** on a Mac; the Spectrum picture is dragged with the mouse or two fingers; **Cmd** + scroll stretches the curve.
- The **Audition** button of the browser is now above **Remember place**.
- The manual describes separate outputs in other DAWs and the controls on a Mac.

### 0.2.13
- **Samples:** the project remembers which file each sample was; if a file is not the one the project was saved with, the plugin says so.
- **Spectrum:** new **Reset** button; the settings you choose are remembered.
- **Auto trim** is off by default.
- A **video** button in the quick start window opens our YouTube channel.

### 0.2.12
- **Spectrum** — a third view of the scope (frequency response of the output): speeds from *Very slow* to *Total*, Energy / RMS, Slope typed in by hand, 41 / 61 / Hi-res bands, vertical stretch with the arrows, drag with the middle mouse button; the settings are remembered. Each view has its own button.
- **Activity lights:** level meter beside the fader, name plate fill, layer and take; the Original has a meter too. Each can be switched off in the settings menu.
- **Auto threshold** is more accurate; Auto also sets Sensitivity.
- **Remember last samples / settings** are off by default; the remembered samples no longer appear in other instances.
- Header: the logo opens the web site, the name opens *About*, the version opens the changelog.

### 0.2.11
- **Separate outputs** (full version): Original and Smp 1 … Smp 6 on their own stereo outputs; the **OUT** button on a channel sends it there. In REAPER: right-click the plugin → *Build multichannel routing*.
- **For best sound** balances only the close microphones.
- The interface size is remembered; new sizes **75%** and **110%**.
- **Hold** and **Phase** moved onto the scope; **Reset phase** and **Clear samples** are at the bottom of the right panel.
- **Online libraries** update when a new version is published. The Artem Music library is fixed: stereo and all takes (version 1.1).

### 0.2.10
- **For best sound** (Auto → Level): sets the levels of the samples for a modern kick sound.
- **Reset phase** and **Clear samples** buttons; **Clear all samples** in the browser.
- Auto phase works better with the LEAD / FOL / ALIGN roles.
- The right panel is more compact.

### 0.2.9
- Auto phase works with the LEAD / FOL / ALIGN roles.
- Auto threshold copes with fast passages.
- Auto Release does not cut a strong ring of a short hit.
- Auto trim is on by default.
- Sound files can be dragged from the browser into the DAW; **Copy sample name** in the sample menu.
- **Pitch All** and **db All** knobs in the Sum panel.

### 0.2.8
- Phase alignment follows the attack: no more flam on kicks.
- Sample roles **LEAD / FOL / ALIGN**.
- After Full Auto the scope switches to Phase.
- **Auto trim** (gear menu).

### 0.2.7
- Release: Auto by default.
- New knobs **Input**, **Samples**, **Pitch**; Ctrl + drag moves all faders or all Tune knobs.
- Better .tci migration: stereo, correct pitch, all layers.
- Browser remembers its place and refreshes itself.

### 0.2.6
- New flat fader handles, narrower buttons.

### 0.2.5
- Meters turn red when over 0 dB.
- The sum follows the shown traces.

### 0.2.4
- Shorter texts and manuals.

### 0.2.3
- Sum is on by default.
- Company name: SSM-Audio.

### 0.2.2
- Browser: a double-click loads a sound into the next free slot.
- Timeline is the starting view.
- Online libraries show the cover and the author's text.

### 0.2.1
- Online libraries show the cover and the author's text.
- The "new version is available" item in the settings menu is green.

### 0.2.0
- **Presets**: save and load all settings and samples.
- **Online libraries** in the browser: free sample libraries, installed in one click (full version).

### 0.1.0
- First release.

## Русский

### 0.3.19
- **E-mail при вводе ключа.** В окне лицензии есть поле e-mail и для ключа (нужен для ключа, купленного на plati.ru). Страница **«Потерял ключ?»** находит ключ по нему.

### 0.3.18
- **Сообщения от SSM-Audio.** Плагин может показать в окне короткое сообщение (новости, важное обновление). Каждое сообщение показывается один раз.

### 0.3.17
- **Триал просит e-mail.** Введите его в окне лицензии, чтобы начать 14-дневный триал.

### 0.3.16
- **Подбор в триале:** можно искать и слушать ответы; положить ответ в микшер можно только с лицензионным ключом.
- **LUNA** распознаётся как DAW.

### 0.3.15
- **Потеряли ключ?** Ссылка в окне лицензии; на компьютере, где ключ активирован, кнопка **Show my key** показывает ключ.
- Больше программ распознаётся: Fender Studio Pro, MorningDAW, LMMS, Zrythm, Qtractor, Mixcraft, Renoise. Если программа всё ещё не распознана, предупреждение не пропадает.
- Переименованные плашки сохраняются в пресетах, Undo и A/B.

### 0.3.14
- **Match стал частью основного окна:** нажмите **Match**, бросьте референс на осциллограф, нажмите **Start**. У каждого ответа есть **▶**, **Apply**, **Top / Body** и **i**; виды **Phase** и **Spectrum** показывают ответ, который вы положили в микшер.
- **Match стал точнее и быстрее:** находит другие слои и микрофоны того же инструмента, есть новая опция **Top**, быстрее в 3–4 раза.
- **Починка путей к семплам:** проект или пресет снова находит перемещённый или сконвертированный семпл (настройка, по умолчанию включена).

### 0.3.13
- **Match, подбор по референсу (экспериментально):** выберите один удар, и плагин найдёт в вашей библиотеке семплы, чья сумма звучит как он. Работает с лицензионным ключом. Подробности в руководстве.
- **Mono для семпла:** **Alt + щелчок** (**Opt** на Mac) по ручке **Pan**.
- **Уведомление об обновлении:** плагин сообщает, когда эта версия слишком старая для работы и где скачать новую.

### 0.3.12
- **Данные активации:** если плагин запущен в программе, которую он не узнаёт, он теперь сообщает имя файла этой программы (без папки и имени пользователя), а не просто «Unknown». Больше ничего не меняется.

### 0.3.11
- **Огибающая включается и выключается:** правый щелчок по кнопке **ENV** канала выключает и снова включает его огибающую; числа остаются.
- **Каналы, выделенные Ctrl + щелчком, меняются вместе:** если выделено два канала и больше, всё, что вы меняете мышью на одном из них (фейдер, Pan, Tune, M / S / Ø / OUT, окно EQ, огибающая), делается на всех.
- **Окно EQ:** числа точки (Frequency, Gain, Q) можно перетаскивать мышью вверх и вниз (**Shift** — точнее); у **полок** теперь есть **Slope**: 6, 12, 18 или 24 дБ на октаву.
- **Hold:** окно, открытое снова, теперь показывает настоящее состояние кнопки **Hold** (экран мог оставаться замороженным, а кнопка выглядела отпущенной).

### 0.3.10
- **Срезы доходят до конца диапазона:** Low Cut и High Cut в EQ канала (и в детекторе) теперь покрывают от 20 Гц до 20 кГц; раньше High Cut нельзя было опустить ниже 1 кГц, а Low Cut поднять выше 2 кГц.
- **Copy / Paste channel settings:** два новых пункта в меню правой кнопки по плашке копируют все числа канала (фейдер, pan, EQ и остальное, без сэмпла) на другой канал. Один шаг Undo.
- Перенос и копирование канала перетаскиванием теперь тоже один шаг Undo.

### 0.3.9
- **Undo работает как ожидается:** каждый регулятор — отдельный шаг (даже если вы быстро меняете два регулятора подряд), у **A** и **B** своя история, клики без изменений и сглаживание осциллографа больше не считаются шагами, а **Copy** можно отменить. **Undo / Redo** хранят последние 20 шагов.
- **Видеоуроки:** новый пункт в меню-шестерёнке открывает наш канал на YouTube. Ссылка есть и в мануале, и на странице скачивания.

### 0.3.8
- **Быстрые роллы:** при низком Threshold удар, идущий сразу за другим, иногда получал заниженную velocity. Исправлено: каждый удар ролла получает полную velocity.
- **Вид Phase:** картинка и индикатор **Sum gain** теперь учитывают EQ каждого канала (Low Cut, полки, колокола), так что совпадают с тем, что вы слышите. Учтён и пан.
- **Auto-инструменты:** правый щелчок по мигающей кнопке останавливает работающий инструмент.

### 0.3.7
- **Перенос целого канала:** перетащите название канала (**Smp 3** вверху полосы) на другой канал. Два канала меняются местами вместе с сэмплом и всем, что для него настроено (уровень, mute, solo, фаза, пан, Tune, огибающая, фильтры, EQ, роль, Offset). С **Ctrl / Cmd** канал копируется. Переключатель **OUT** остаётся на месте. Перетаскивание плашки с именем по-прежнему меняет только сэмплы.
- **Размер окна:** тяните уголок в правом нижнем углу, чтобы менять размер окна (50–300%). Размер запоминается; двойной щелчок по уголку — 100%.
- Кнопка **Licence** переехала в правую панель, под **Clear samples**.
- **Copy** (A/B) больше не открывает меню: сразу копирует включённую настройку на другую.

### 0.3.6
- **Окно EQ:** живой спектр за кривой (кнопка **Spectrum** его выключает); усиление до ±30 дБ; крутизна Low Cut и High Cut 36 и 48 дБ на октаву.
- **Браузер библиотеки:** **Show in Explorer** (Show in Finder на Mac) в меню правого щелчка.
- **Sensitivity** в новом плагине начинается со 100.

### 0.3.5
- Кнопка **Auto** теперь **Auto menu**. В ней выбор, по чему измеряется фаза (**Phase detection wide range / narrow range**), перенесён в раздел **Phase**.
- Пункт меню автозапуска воспроизведения убран.

### 0.3.4
- **Велосити следует за пиком удара:** удар на уровне **Input** (по умолчанию −6 дБ) — велосити 127. Регулятор **Soft** убран. Старые проекты могут звучать немного иначе: проверьте **Input**.
- **Sensitivity** — второй порог; решает больший из двух.
- **Быстрые роллы и призрачные ноты** играются.
- **Auto Threshold** и **Full Auto** ставят **Input** на −6 дБ.
- Конвертированные инструменты **.tci** играют с громкостью, записанной в файле: запустите **Migration** ещё раз, чтобы обновить их.
- В правой панели кнопки **Full Auto**, **Auto Threshold**, **Auto Phase** и **Auto** (меню с остальными инструментами).
- Плашки над осциллографом тянутся **вверх и вниз**; колесо меняет их понемногу.
- Задержка плагина 39 мс.

### 0.3.3
- **Слои велосити и громкость** отзываются как у известного триггера.
- Линия **Soft** на Timeline; **Input** до +12 дБ.
- **Точный старт сэмпла** (меню настроек).
- Конвертированные инструменты **.tci** играют с частотой дискретизации, записанной в файле.
- Сэмплы на 3 дБ тише; выход плагина равен оригинальной дорожке и сэмплам рядом.
- Крестик в поиске библиотеки очищает только поиск.
- Режим **0 ms** убран.
- **Buy** открывает страницу оплаты.

### 0.3.2
- **EQ:** у Low Cut и High Cut появился **Slope** (6, 12, 18 или 24 дБ на октаву; 12 — обычный, проекты звучат так же). Кривая EQ больше не рисует линию вдоль нижнего края.
- При включённом **0 ms** ручка **Orig Gate** становится серой (без задержки она работать не может).
- **Покупка:** на сайте новая страница покупки: оплата картой или кошельком ЮMoney, ключ выдаётся сразу.

### 0.3.1
- **EQ на каждом канале, в том числе на Original** (кнопка FLT стала EQ): Low Cut, Low Shelf, три колокола, High Shelf и High Cut в окне поверх осциллографа. Правый щелчок по точке: этот фильтр выключается и включается. Правый щелчок по кнопке EQ: выключается и включается весь EQ. Старые проекты звучат так же.
- **Сэмплы:** перетащите плашку на другую, чтобы поменять их местами (Ctrl/Cmd: копия); в меню плашки Copy, Paste и Rename; выделите несколько сэмплов (Ctrl/Cmd + щелчок или рамка) и двигайте их Offset вместе.
- **Правый щелчок по M, S или Ø:** включается только у этого канала, у остальных выключается.
- Переключатель **0 ms** у Original: оригинал идёт без задержки, плагин сообщает хосту нулевую задержку (по умолчанию выключен).
- **Timeline:** каждый удар — линия, высота которой показывает силу удара, с красными точками на концах; кнопка **Input / Output** показывает то, что приходит на вход, или то, что идёт на выход.
- **Браузер:** окошко поиска с крестиком; **WAV to .bt3…** превращает WAV в .bt3 (файл, папку или всю библиотеку) и потом спрашивает, удалять ли WAV.
- **Панель Sum:** ручка **Threshold**; **Reset** спектра переехал наверх; Full Auto не закрывает вид Spectrum, если он был открыт.
- **Звук:** сэмпл с другой частотой дискретизации, чем у проекта (например, файл 44,1 кГц в проекте 48 кГц), теперь пересчитывается качественным фильтром. Раньше верх выше примерно 6 кГц слегка тускнел; **Tune** сохраняет больше верха.

### 0.3.0
- **Пробный период 14 дней.** Нажмите в окне плагина **Start 14-day trial**: 14 дней открыты все функции, ключ не нужен. Пробный период один на компьютер.
- **Бесплатной версии больше нет.** Best Trigger 3 теперь один продукт: пробный период, затем лицензионный ключ (см. [как купить](https://ssm-audio.github.io/Best-Trigger-3/download.html)).
- Когда пробный период закончился, окно просит лицензионный ключ; ваши проекты не меняются.
- Руководство переработано: сначала установка, затем пробный период и лицензия, быстрый старт по шагам и отдельное описание видов осциллографа.

### 0.2.14
- **Всплывающее окно** для ввода числа (правый щелчок по ручке): цифры больше не прячутся внутри интерфейса.
- **Mac и трекпад:** где нужен **Ctrl**, на Mac используйте **Cmd**; картинку Spectrum можно тянуть мышью или двумя пальцами; **Cmd** + прокрутка растягивает кривую.
- Кнопка **Audition** в браузере теперь над **Remember place**.
- В руководстве описаны отдельные выходы в других DAW и управление на Mac.

### 0.2.13
- **Сэмплы:** проект запоминает, какой файл был у каждого сэмпла; если файл не тот, с которым проект сохранён, плагин сообщает об этом.
- **Spectrum:** новая кнопка **Reset**; выбранные настройки запоминаются.
- **Auto trim** по умолчанию выключен.
- Кнопка **видео** в окне быстрого старта открывает наш канал на YouTube.

### 0.2.12
- **Spectrum** — третий вид осциллографа (АЧХ выхода): скорости от *Very slow* до *Total*, Energy / RMS, Slope вводится числом, 41 / 61 / Hi-res полос, растяжение по вертикали стрелками, перетаскивание средней кнопкой мыши; настройки запоминаются. У каждого вида своя кнопка.
- **Индикация:** индикатор уровня у фейдера, заливка плашки, слой и дубль; у Original тоже есть индикатор. Каждый пункт отключается в меню настроек.
- **Auto threshold** стал точнее; Auto ещё и выставляет Sensitivity.
- **Remember last samples / settings** по умолчанию выключены; запомненные сэмплы больше не попадают в другие экземпляры.
- Шапка: логотип открывает сайт, название — *About*, версия — список изменений.

### 0.2.11
- **Отдельные выходы** (полная версия): Original и Smp 1 … Smp 6 на своих стерео-выходах; кнопка **OUT** на канале отправляет его туда. В REAPER: правый щелчок по плагину → *Build multichannel routing*.
- **For best sound** выравнивает только близкие микрофоны.
- Размер интерфейса запоминается; новые размеры **75%** и **110%**.
- **Hold** и **Phase** переехали на осциллограф; **Reset phase** и **Clear samples** внизу правой панели.
- **Онлайн-библиотеки** обновляются, когда выходит новая версия. Библиотека Artem Music исправлена: стерео и все дубли (версия 1.1).

### 0.2.10
- **For best sound** (Auto → Level): подбирает уровни сэмплов для современного звука кика.
- Кнопки **Reset phase** и **Clear samples**; **Clear all samples** в браузере.
- Auto phase лучше работает с ролями LEAD / FOL / ALIGN.
- Правая панель стала компактнее.

### 0.2.9
- Auto phase работает с ролями LEAD / FOL / ALIGN.
- Auto threshold справляется с быстрыми пассажами.
- Auto Release не обрывает сильный хвост короткого удара.
- Auto trim включён по умолчанию.
- Звуковые файлы можно перетащить из браузера в DAW; **Copy sample name** в меню сэмпла.
- Ручки **Pitch All** и **db All** на панели Sum.

### 0.2.8
- Фаза привязана к атаке: форшлага у бочки больше нет.
- Роли сэмплов **LEAD / FOL / ALIGN**.
- После Full Auto осциллограф переключается в Phase.
- **Auto trim** (меню шестерёнки).

### 0.2.7
- Release: по умолчанию Auto.
- Новые ручки **Input**, **Samples**, **Pitch**; Ctrl + перетаскивание двигает все фейдеры или все Tune.
- Лучше миграция .tci: стерео, верная высота, все слои.
- Браузер помнит место и обновляется сам.

### 0.2.6
- Новые плоские ручки фейдеров, кнопки уже.

### 0.2.5
- Индикаторы краснеют при выходе за 0 дБ.
- Сумма строится по показанным графикам.

### 0.2.4
- Тексты и руководства стали короче.

### 0.2.3
- Sum включён по умолчанию.
- Название компании: SSM-Audio.

### 0.2.2
- Браузер: двойной щелчок загружает звук в первый свободный слот.
- Видом при запуске стал Timeline.
- Онлайн-библиотеки показывают обложку и текст автора.

### 0.2.1
- Онлайн-библиотеки показывают обложку и текст автора.
- Пункт «доступна новая версия» в меню настроек стал зелёным.

### 0.2.0
- **Пресеты**: сохранение и загрузка всех настроек и сэмплов.
- **Онлайн-библиотеки** в браузере: бесплатные библиотеки сэмплов, установка в один щелчок (полная версия).

### 0.1.0
- Первый выпуск.
