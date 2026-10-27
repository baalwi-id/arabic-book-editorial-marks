# arabic-book-editorial-marks

> SVG artwork for 26 Arabic editorial/structural marks used in classical kitab (book) typesetting, in three styles—Thuluth, Nasta'liq and Naskh—freely available for use in any digital or print project.

[![npm](https://img.shields.io/npm/v/arabic-book-editorial-marks)](https://www.npmjs.com/package/arabic-book-editorial-marks)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![License: OFL 1.1 (naskh)](https://img.shields.io/badge/License-OFL%201.1%20(naskh)-lightgrey.svg)](https://openfontlicense.org)
[![GitHub](https://img.shields.io/badge/GitHub-baalwi--id-teal)](https://github.com/baalwi-id)

---

## Background

Classical Arabic books (kitab) make use of a small, recurring set of formulaic words and phrases as structural markers—chapter and section headings, a foreword, a table of contents, prayer openers, a closing colophon, and so on. In carefully typeset kitab, these markers are often rendered as single decorative units rather than plain running text.

This collection provides high-resolution, ready-to-use SVG artwork for these marks, for use in book design, digital typesetting, or any other project.

The Thuluth and Nasta'liq artwork was generated using Kaleam and Kelk, and is released under CC BY 4.0, freely available for any project—digital, print, educational, commercial, or otherwise.

The Naskh style, added in v1.4.0, follows the Madinah Mushaf hand of Shaykh ʿUthmān Ṭāhā. It was composed from the open-licensed [DigitalKhatt New Madina](https://github.com/DigitalKhatt/madinafont) font by Amine Anane, which is modelled on that hand; every letterform and diacritic comes from DigitalKhatt New Madina, and no outline from KFGQPC or any other closed font was used. Because the Naskh marks are a modified version of an OFL font, they are released under the SIL Open Font License 1.1 rather than CC BY 4.0 (see [License](#license)).

---

## Styles

Each mark is available in three calligraphic styles:

- **Thuluth** (`svg/thuluth/`)—the more commonly used, more ornamental style.
- **Nasta'liq** (`svg/nastaliq/`)—a flowing, more slanted alternative style.
- **Naskh** (`svg/naskh/`)—the Naskh of the Madinah Mushaf (Shaykh ʿUthmān Ṭāhā), fully vocalised, with extended letter joins (kashida) where the phrase allows. Composed from DigitalKhatt New Madina; licensed under OFL 1.1.

Thuluth and Nasta'liq are sized to match the same physical scale used in [arabic-honorific-ligatures](https://github.com/baalwi-id/arabic-honorific-ligatures) (same source font, same unit conversion)—so artwork from both projects can be combined smoothly, with no rescaling needed. Naskh comes from a different source font, so it is scaled to match instead: its dots (nuqṭa) have the same size as those of the Thuluth marks, which keeps the three styles visually comparable when placed side by side.

---

## Contents

| Path | Description |
|------|-------------|
| `svg/thuluth/` | Individual SVG files, Thuluth style, one per mark |
| `svg/nastaliq/` | Individual SVG files, Nasta'liq style, one per mark |
| `svg/naskh/` | Individual SVG files, Naskh (Madinah Mushaf) style, one per mark |
| `png/thuluth/` | Individual PNG files, Thuluth style, one per mark (black on transparent) |
| `png/nastaliq/` | Individual PNG files, Nasta'liq style, one per mark (black on transparent) |
| `png/naskh/` | Individual PNG files, Naskh style, one per mark (black on transparent) |
| `specimen/specimen-sheet.png` | Full specimen sheet, Thuluth, Nasta'liq & Naskh (all 26 marks) |
| `specimen/specimen-sheet.pdf` | Specimen sheet in PDF format |

---

## Glyph list

Files are named after a plain transliteration of the phrase, e.g. `bab.svg`, `khatimah.svg`. The same name is used in every style folder (`svg/thuluth/bab.svg`, `svg/nastaliq/bab.svg`, `svg/naskh/bab.svg`), and PNG files in `png/` use the same names as their SVG counterparts.

| File | Arabic | Transliteration | Meaning |
|------|--------|-----------------|---------|
| basmalah | بسم الله الرحمن الرحيم | bismillāhir raḥmānir raḥīm | "In the name of Allah, the Most Gracious, the Most Merciful" |
| muqaddimah | مقدمة | muqaddimah | introduction |
| tamhid | تمهيد | tamhīd | prologue |
| bayna-yaday-kitab | بين يدي الكتاب | bayna yaday al-kitāb | foreword (lit. "before the book") |
| khutbatul-kitab | خطبة الكتاب | khuṭbat al-kitāb | the book's opening sermon/preface |
| fihris | فهرس | fihris | table of contents / index |
| muhtawiyat | المحتويات | al-muḥtawayāt | table of contents (alternate) |
| juz | جزء | juz' | part / volume (indefinite) |
| aljuz | الجزء | al-juz' | the part / volume (definite) |
| bab | باب | bāb | chapter (indefinite) |
| albab | الباب | al-bāb | the chapter (definite) |
| fasl | فصل | faṣl | section (indefinite) |
| alfasl | الفصل | al-faṣl | the section (definite) |
| farun | فرع | far' | subsection / branch |
| allahumma | اللهم | Allāhumma | "O Allah" |
| rabbana | ربنا | Rabbanā | "Our Lord" |
| faidah | فائدة | fā'idah | a benefit / editorial note |
| tanbih | تنبيه | tanbīh | notice / caution |
| tanwih | تنويه | tanwīh | highlight / remark |
| amma-badu | أما بعد | ammā ba'du | classical transitional phrase ("to proceed") |
| tahanina | تهانينا | tahānīnā | congratulations |
| khatimah | خاتمة | khātimah | conclusion |
| intaha | انتهى | intahā | "the end" |
| tammat | تمت | tammat | "finished" |
| tamma-bi-hamdillah | تم بحمد الله | tamm bi ḥamdillāh | "completed, with praise to Allah" |
| waqafa-lillahi-taala | وقف لله تعالى | waqf lillāhi ta'ālā | "endowed for the sake of Allah, exalted is He" |

---

## Contributing

Found an issue or want to request another mark? [Open an issue](https://github.com/baalwi-id/arabic-book-editorial-marks/issues).

Interested in developing this artwork into a full font, or have ideas for collaboration? We'd love to hear from you. Feel free to reach out via the issues page or at info@baalwi.net.

---

## License

- **Thuluth and Nasta'liq** (`svg/thuluth/`, `svg/nastaliq/`, `png/thuluth/`, `png/nastaliq/`): CC BY 4.0—Waqf 2026 by Ba Alawi Masters Heritage Trust. See `LICENSE`.
- **Naskh** (`svg/naskh/`, `png/naskh/`): SIL Open Font License 1.1. See `OFL.txt`. These marks are composed from **DigitalKhatt New Madina** by Amine Anane (© 2020–2025 Amine Anane, © 2024–2025 Tarteel Inc.), modelled on the Madinah Mushaf calligraphy of Shaykh ʿUthmān Ṭāhā. As OFL requires, any font built from them must also be released under OFL 1.1 and may not be sold by itself. Documents, books and web pages that merely use the marks are not affected by this.

**About Us:** Ba Alawi Masters Heritage Trust is dedicated to the preservation and advancement of the cultural and textual heritage of the Ba'alwi Masters—collecting, authenticating, and digitising manuscripts and making them freely available through digital platforms and emerging technologies. Learn more at [baalwi.net](https://baalwi.net).

---

*—[@baalwi-id](https://github.com/baalwi-id) · info@baalwi.net · [baalwi.net](https://baalwi.net)*
