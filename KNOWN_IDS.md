# KNOWN_IDS — Shia History Website
Last updated: this session

## Scholar IDs (SCHOLARS array + SCHOLAR_BIOS popup)
All 36 scholars in the Academic Map:

| ID | Name | Domains |
|----|------|---------|
| kulayni | Sheikh al-Kulayni | hadith |
| saduq | Sheikh al-Saduq | hadith, kalam |
| mufid | Sheikh al-Mufid | kalam, fiqh, tarikh |
| murtadha | Sayyid al-Murtadha | kalam, fiqh |
| tusi-sheikh | Sheikh al-Tusi | fiqh, hadith, kalam |
| tusi-nasir | Nasir al-Din al-Tusi | kalam, falsafa, akhlaq |
| hilli | Allama al-Hilli | kalam, fiqh |
| shahid1 | Shahid al-Awwal | fiqh |
| shahid2 | Shahid al-Thani | fiqh |
| mulla-sadra | Mulla Sadra | falsafa, irfan, kalam |
| majlisi | Allama Majlisi | hadith, tarikh |
| ansari | Sheikh al-Ansari | fiqh |
| tabatabai | Allama Tabataba'i | falsafa, tafsir, irfan |
| sadr | Shahid al-Sadr | fiqh, kalam |
| khoei | Grand Ayatullah al-Khoei | fiqh, hadith |
| khomeini | Imam Khomeini | fiqh, irfan, kalam |
| sistani | Grand Ayatullah Sistani | fiqh |
| nusrat-amin | Nusrat Amin (Bānū Amīn) | tafsir, irfan |
| bint-al-huda | Bint al-Hudā (Āmina al-Ṣadr) | akhlaq, tarikh |
| bihbahani | Wahid Bihbahani | fiqh |
| khorasani | Akhund Khorasani | fiqh |
| karaki | Muhaqqiq al-Karaki | fiqh, kalam |
| mir-damad | Mir Damad | falsafa, kalam |
| sabzawari | Mulla Hadi Sabzawari | falsafa, irfan |
| fayd-kashani | Fayd Kashani | hadith, irfan, kalam |
| tabarsi | Sheikh al-Tabarsi | tafsir, hadith |
| jawadi-amoli | Jawadi Amoli | falsafa, irfan, tafsir |
| qummi-abbas | Sheikh Abbas al-Qummi | tarikh, hadith |
| ibn-fahd | Ibn Fahd al-Hilli | akhlaq, fiqh |
| misbah | Ayatullah Misbah Yazdi | kalam, akhlaq |
| muhaqqiq-hilli | Muhaqqiq al-Hilli | fiqh |
| borujerdi | Grand Ayatullah Borujerdi | fiqh, hadith |
| fadlallah | Sayyid Muhammad Husayn Fadlallah | tafsir, fiqh |
| mutahhari | Shahid Murtadha Mutahhari | falsafa, kalam, akhlaq |
| mirza-shirazi | Mīrzā-ye Shīrāzī | fiqh |
| naini | Mīrzā Muḥammad Ḥusayn Nāʾīnī | fiqh, kalam |

## Doctrine Section IDs (doc-*)
New order (as of this session):
| ID | Section |
|----|---------|
| doc-architecture | I · Theological Architecture |
| doc-imamate | II · The Imamate |
| doc-isma | III · ʿIṣma |
| doc-ghayba | IV · The Living Absence |
| doc-authority | V · Authority in Occultation |
| doc-karbala | VI · Karbala as Paradigm |
| doc-embodied | VII · The Embodied Tradition |
| doc-just-order | VIII · The Just Order |
| doc-irfan | IX · ʿIrfān |
| doc-akhlaq | X · Akhlāq |
| doc-contested | XI · Contested Doctrines |
| doc-eschatology | XII · Eschatology |

## Encounters Section IDs (enc-*)
| ID | Section |
|----|---------|
| enc-sunni | I · Sunni Islam |
| enc-ismaili | II · Ismailis & Zaydis |
| enc-sufism | III · Sufism |
| enc-greek | IV · Greek Philosophy |
| enc-christianity | V · Christianity |
| enc-judaism | VI · Judaism |
| enc-persian | VII · Persian & Zoroastrian |
| enc-india | VIII · The Indian World |
| enc-orientalism | IX · Orientalism |
| enc-left | X · Marxism & the Left |
| enc-humanism | XI · Humanism & Modernity |

## Imam Hash IDs (timeline)
shia-timeline.html#imam-1 through #imam-12, #imam-prophet, #imam-fatima
Opens the imam modal for the corresponding figure.

## Scholar Popup
Call showScholarPopup('scholar-id') from any page.
scholar-popup.js must be in same directory as HTML files.

## Cross-link class
class="cross-link" — gold-dim color with gold hover, used for all inter-page links.

## Files
- shia-timeline.html (Page I)
- shia-academia.html (Page II) 
- shia-encounters.html (Page III)
- shia-doctrine.html (Page IV)
- about.html
- scholar-popup.js (shared, must deploy with HTML files)
