# Muslim Panel

A home-screen face for [omalauncher](https://github.com/SimonSchubert/omalauncher): the day's prayer times under the clock, and beside them the Fortification of the Muslim (Hisnul Muslim), a verse of the Qur'an and a hadith for each day.

![Muslim Panel in the Parchment look](screenshots/parchment.png)

## What's on it

**Left: the clock and the prayers**
- The Hijri day in an arch, the time, the Gregorian and Hijri dates, weather, battery and the next alarm
- The coming prayer with a countdown, highlighted in the list of the day's prayers
- Tap the circle beside a prayer to mark it prayed today
- Imsak, midnight and the last third of the night
- A dock of pinned apps (tap **+** to choose them, long-press an icon to pin or unpin it)

**Right: three tabs**
- **Fortification (الحصن):** all 132 chapters of *Hisnul Muslim* by Sa'id al-Qahtani, searchable and sorted into 11 categories. A card suggests the morning and evening, sleep or after-prayer remembrances by the hour. Each dua shows the Arabic, transliteration and English translation, with a tap counter for its repeat count that starts over each day. Long-press a chapter to save it. Chapters you've opened are kept for offline use.
- **Qur'an:** a verse a day in Arabic with Saheeh International's translation, and a link to read the surah.
- **Hadith:** a hadith a day from an-Nawawi's Forty, Hadith Qudsi, Bukhari or Muslim.

Notifications sit under the tabs.

## Looks

Choose one under Appearance in settings (tap the arch or the gear):

- **Parchment:** paper, ink and maroon, set in Reem Kufi, Amiri, Newsreader and Instrument Sans
- **Night:** the same at night
- **Theme & wallpaper:** your Omarchy theme's colours over your wallpaper, on frosted glass that follows the home screen's tile opacity and blur

## Settings

Location (automatic or a city), the calculation method (Umm al-Qura, Dubai, Gulf, MWL, Egypt, ISNA, Karachi, Diyanet), the Asr method, a Hijri date correction, a 24-hour clock and transliteration on or off.

## Install

Copy `muslim-panel.owl` into `~/.config/omalauncher/widgets/`. It appears as a face left of your first home page within seconds; move it in settings › pages. It runs no Linux commands, so it works without Linux installed.

## Sources

- Prayer times and Hijri dates: [Aladhan](https://aladhan.com)
- Hisnul Muslim: [hisnmuslim.com](https://www.hisnmuslim.com)
- Qur'an: [alquran.cloud](https://alquran.cloud)
- Hadith: [fawazahmed0/hadith-api](https://github.com/fawazahmed0/hadith-api)
- Weather and location: [wttr.in](https://wttr.in), [Open-Meteo geocoding](https://open-meteo.com)
- Fonts: [Google Fonts](https://fonts.google.com) (OFL)

## License

MIT
