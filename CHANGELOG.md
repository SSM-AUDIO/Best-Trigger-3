# Best Trigger 3: changelog

Русская версия ниже: [Русский](#русский)

## English

### 0.3.7
- **Move a whole channel:** drag the name of a channel (**Smp 3** at the top of its strip) onto another channel. The two channels swap places with the sample and everything set for it (level, mute, solo, phase, pan, tune, envelope, filters, EQ, role, Offset). With **Ctrl / Cmd** the channel is copied instead. The **OUT** switch stays where it is. Dragging the name plate still swaps only the samples.
- **Window size:** drag the grip in the bottom right corner to change the size of the window (50–300%). The size is remembered; a double click on the grip sets 100%.
- **Licence** button moved to the right panel, under **Clear samples**.
- **Copy** (A/B) no longer opens a menu: it copies the setting that is on onto the other one.

### 0.3.6
- **EQ window: live spectrum.** Behind the curve you see the spectrum of the channel: the filled area is the sound after the EQ (so you see what your changes do), the thin line is the sound before it. The **Spectrum** button switches it off. It does not load the plugin's audio.
- **EQ gain up to ±30 dB** for bells and shelves. The picture zooms out by itself (3, 6, 12, 30 dB) when you drag a dot towards its edge.
- **Low Cut and High Cut slopes: 36 and 48 dB per octave** are added (6, 12, 18, 24, 36, 48). The mouse wheel over a cut dot changes its slope.
- **Library browser:** the right-click menu of a sample or folder has **Show in Explorer** (Show in Finder on a Mac) at the bottom.
- **Sensitivity** starts at 100 in a new plugin, so only the **Threshold** decides at first. Saved projects keep their value.

### 0.3.5
- The **Auto** button is now **Auto menu**. In it, the choice of what the phase is measured on (**Phase detection wide range / narrow range**) moved into the **Phase** section.
- The menu item for starting playback automatically is removed.

### 0.3.4
- **Velocity is read the way the well-known trigger reads it:** it is proportional to the peak of the hit, and a hit at the **Input** level (−6 dB by default) is velocity 127. The **Soft** control is gone. Quiet hits of the first layer start from silence and grow louder, as in the well-known trigger. Older projects may sound a little different: check **Input**.
- **Sensitivity** is now a second threshold (the higher the number, the lower it is); the louder of the two thresholds decides. At 100 only the **Threshold** decides.
- **Fast rolls and ghost notes:** a hit that follows another one closely and clearly rises above its tail is now played, so rolls and ghost notes are not skipped.
- **Auto Threshold** and **Full Auto** set **Input** to −6 dB and put the Threshold closer to the soft hits.
- Converted **.tci** instruments play at the volume written in the file. **Run the Migration again** to refresh instruments that were converted before.
- The right panel has the buttons **Full Auto**, **Auto Threshold**, **Auto Phase** and **Auto** (a menu with the other tools).
- The value boxes above the scope (Retrigger, Sensitivity, Smp Offset) are dragged **up and down**; the wheel changes them a little.
- The plugin's latency is 39 ms. The update check no longer depends on the GitHub limit.

### 0.3.3
- **Velocity layers and volume now respond like in the well-known trigger.** A harder hit changes the velocity layer and, inside a layer, is a little louder. New plugins start with the scale set for this (**Soft** −19 dB, **Input** −6.9 dB); the Threshold is only where a hit is noticed. Projects saved earlier sound the same as before.
- **Soft** line on the Timeline and **Input** up to +12 dB: set where the velocity scale begins and ends.
- **Precise sample start** (settings menu, on for new plugins): the sample starts at the real beginning of the hit, whatever the Threshold.
- Converted **.tci** instruments are played at the sample rate written in the file, as the well-known trigger plays them.
- The samples sit 3 dB lower, as in the well-known trigger, and the original that passes through the plugin keeps its level: the plugin's output now equals the original track and the plugin's samples played side by side. The **Output** knob stays at 0 dB.
- The cross in the library search clears only the search.
- The **Soft** line is pink (green is the Input line).
- The **0 ms** mode is removed: the original is always delayed by the plugin latency (36 ms) so that samples can start before it.
- **Buy** opens the payment page, the update notice opens the download page.

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

### 0.3.7
- **Перенос целого канала:** перетащите название канала (**Smp 3** вверху полосы) на другой канал. Два канала меняются местами вместе с сэмплом и всем, что для него настроено (уровень, mute, solo, фаза, пан, Tune, огибающая, фильтры, EQ, роль, Offset). С **Ctrl / Cmd** канал копируется. Переключатель **OUT** остаётся на месте. Перетаскивание плашки с именем по-прежнему меняет только сэмплы.
- **Размер окна:** тяните уголок в правом нижнем углу, чтобы менять размер окна (50–300%). Размер запоминается; двойной щелчок по уголку — 100%.
- Кнопка **Licence** переехала в правую панель, под **Clear samples**.
- **Copy** (A/B) больше не открывает меню: сразу копирует включённую настройку на другую.

### 0.3.6
- **Окно EQ: живой спектр.** За кривой виден спектр канала: закрашенная область — звук после EQ (видно, что делают ваши изменения), тонкая линия — звук до него. Кнопка **Spectrum** выключает его. На звуковую часть плагина он не влияет.
- **Усиление EQ до ±30 дБ** у колоколов и полок. Масштаб картинки сам увеличивается (3, 6, 12, 30 дБ), когда вы тянете точку к краю.
- **Крутизна Low Cut и High Cut: добавлены 36 и 48 дБ на октаву** (6, 12, 18, 24, 36, 48). Колесо мыши над точкой среза меняет крутизну.
- **Браузер библиотек:** в меню по правому клику на семпле или папке внизу есть **Show in Explorer** (на Mac — Show in Finder).
- **Sensitivity** у нового плагина стоит на 100, поэтому сначала решает только **Threshold**. Сохранённые проекты сохраняют своё значение.

### 0.3.5
- Кнопка **Auto** теперь **Auto menu**. В ней выбор, по чему измеряется фаза (**Phase detection wide range / narrow range**), перенесён в раздел **Phase**.
- Пункт меню автозапуска воспроизведения убран.

### 0.3.4
- **Velocity считается так же, как в известном триггере:** она пропорциональна пику удара, а удар на уровне **Input** (по умолчанию −6 дБ) даёт velocity 127. Параметр **Soft** убран. Тихие удары первого слоя начинаются с тишины и становятся громче, как в известном триггере. Старые проекты могут звучать немного иначе: проверьте **Input**.
- **Sensitivity** теперь второй порог (чем больше число, тем он ниже); решает более высокий из двух порогов. На 100 решает только **Threshold**.
- **Быстрые роллы и призрачные ноты:** удар, который идёт сразу за предыдущим и заметно выше его хвоста, теперь играется, поэтому роллы и призрачные ноты не пропускаются.
- **Auto Threshold** и **Full Auto** ставят **Input** −6 дБ и кладут Threshold ближе к тихим ударам.
- Конвертированные инструменты **.tci** играют с громкостью, записанной в файле. **Повторите Migration**, чтобы обновить инструменты, сконвертированные раньше.
- В правой панели кнопки **Full Auto**, **Auto Threshold**, **Auto Phase** и **Auto** (меню с остальными инструментами).
- Окошки над осциллографом (Retrigger, Sensitivity, Smp Offset) тянутся **вверх и вниз**; колесо меняет значение понемногу.
- Задержка плагина 39 мс. Проверка обновлений больше не зависит от лимита GitHub.

### 0.3.3
- **Слои по велосити и громкость теперь отзываются как в известном триггере.** Более сильный удар меняет слой и внутри слоя звучит немного громче. Новый плагин стартует со шкалой, настроенной для этого (**Soft** −19 дБ, **Input** −6,9 дБ); Threshold — только место, где удар замечается. Проекты, сохранённые раньше, звучат как прежде.
- Линия **Soft** на Timeline и **Input** до +12 дБ: задают, где шкала велосити начинается и заканчивается.
- **Precise sample start** (меню настроек, у нового плагина включено): сэмпл стартует с настоящего начала удара, при любом Threshold.
- Конвертированные инструменты **.tci** играются с частотой дискретизации, записанной в файле, как их играет известный триггер.
- Сэмплы звучат на 3 дБ тише, как в известном триггере, а оригинал, проходящий через плагин, сохраняет свой уровень: выход плагина теперь равен оригинальной дорожке и сэмплам плагина, пущенным рядом. Ручка **Output** остаётся на 0 дБ.
- Крестик в поиске по библиотеке очищает только строку поиска.
- Линия **Soft** розовая (зелёная — линия Input).
- Режим **0 ms** убран: оригинал всегда задержан на задержку плагина (36 мс), чтобы сэмплы могли начинаться раньше него.
- Кнопка **Buy** открывает страницу оплаты, уведомление об обновлении — страницу скачивания.

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
