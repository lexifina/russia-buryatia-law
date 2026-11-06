# Republic of Buryatia: catalogue of laws in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Republic of Buryatia, Russia, which global-law reads at `russia/buryatia/acts/`.

**Facts only: no law text.**

A catalogue of the laws of Republic of Buryatia (Республика Бурятия), a federal subject of the Russian Federation, as a git history: one file per law, holding the facts the Official Internet Portal of Legal Information gives for it, added on the day the portal published it. `git log` lists the laws in the order they were published; checking out a date shows which laws had been published by then.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The federal law of Russia is in [lexifina/russia-law](https://github.com/lexifina/russia-law).

## What this repository holds

1,747 laws published from 2014-12-18 to 2026-10-13 (191 publication days): every document of a law type the portal lists for Republic of Buryatia (laws, charter or constitutional laws, the charter or constitution and the laws amending it). Decrees, resolutions and orders are not included.

Each file, `zakony-<year>/<number>.md` (the year of publication, the law's number in Latin letters), holds:

- the official title;
- the document type and number;
- the date signed and the publication date;
- the electronic publication number;
- the signing body the portal names;
- the link to the law's official publication page on the portal, where its text can be read.

No text of any law is copied.

## Source

The [Official Internet Portal of Legal Information](http://publication.pravo.gov.ru/documents/block/region03) (ÐžÑ„Ð¸Ñ†Ð¸Ð°Ð»ÑŒÐ½Ñ‹Ð¹ Ð¸Ð½Ñ‚ÐµÑ€Ð½ÐµÑ‚-Ð¿Ð¾Ñ€Ñ‚Ð°Ð» Ð¿Ñ€Ð°Ð²Ð¾Ð²Ð¾Ð¹ Ð¸Ð½Ñ„Ð¾Ñ€Ð¼Ð°Ñ†Ð¸Ð¸, publication.pravo.gov.ru), section Республика Бурятия: its metadata API (`/api/Documents`), read on 2026-10-30. The portal's open data may be reused freely, keeping a link to the source (http://publication.pravo.gov.ru/OpenData).

## Dates

Each law is added on the day the portal published it, at noon Asia/Irkutsk time, and credited to the portal. Publication on the portal is official publication, but a law may take effect on another day: read its own text.

## How it is checked

- Every version is read back from git on its day and on the day before, and must match the corpus.
- Every file's facts are compared, field by field, with the portal's API records, read by a second, independent reader.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future.

## Limits

This is not an official publication. The catalogue lists what the portal holds; its sections for the federal subjects start in the 2010s, so older laws are missing. It does not say whether a law is in force, has been amended or has lapsed.

---

# Республика Бурятия: ÐºÐ°Ñ‚Ð°Ð»Ð¾Ð³ Ð·Ð°ÐºÐ¾Ð½Ð¾Ð² Ð² git

**Ð¢Ð¾Ð»ÑŒÐºÐ¾ ÑÐ²ÐµÐ´ÐµÐ½Ð¸Ñ: Ð±ÐµÐ· Ñ‚ÐµÐºÑÑ‚Ð¾Ð² Ð·Ð°ÐºÐ¾Ð½Ð¾Ð².**

ÐšÐ°Ñ‚Ð°Ð»Ð¾Ð³ Ð·Ð°ÐºÐ¾Ð½Ð¾Ð² ÑÑƒÐ±ÑŠÐµÐºÑ‚Ð° Ð Ð¾ÑÑÐ¸Ð¹ÑÐºÐ¾Ð¹ Ð¤ÐµÐ´ÐµÑ€Ð°Ñ†Ð¸Ð¸ Ð¿Ð¾ Ð´Ð°Ð½Ð½Ñ‹Ð¼ ÐžÑ„Ð¸Ñ†Ð¸Ð°Ð»ÑŒÐ½Ð¾Ð³Ð¾ Ð¸Ð½Ñ‚ÐµÑ€Ð½ÐµÑ‚-Ð¿Ð¾Ñ€Ñ‚Ð°Ð»Ð° Ð¿Ñ€Ð°Ð²Ð¾Ð²Ð¾Ð¹ Ð¸Ð½Ñ„Ð¾Ñ€Ð¼Ð°Ñ†Ð¸Ð¸ (publication.pravo.gov.ru): Ð¾Ð´Ð¸Ð½ Ñ„Ð°Ð¹Ð» Ð½Ð° Ð·Ð°ÐºÐ¾Ð½ (Ð½Ð°Ð¸Ð¼ÐµÐ½Ð¾Ð²Ð°Ð½Ð¸Ðµ, Ð²Ð¸Ð´, Ð½Ð¾Ð¼ÐµÑ€, Ð´Ð°Ñ‚Ð° Ð¿Ð¾Ð´Ð¿Ð¸ÑÐ°Ð½Ð¸Ñ, Ð´Ð°Ñ‚Ð° Ð¾Ð¿ÑƒÐ±Ð»Ð¸ÐºÐ¾Ð²Ð°Ð½Ð¸Ñ, Ð½Ð¾Ð¼ÐµÑ€ ÑÐ»ÐµÐºÑ‚Ñ€Ð¾Ð½Ð½Ð¾Ð³Ð¾ Ð¾Ð¿ÑƒÐ±Ð»Ð¸ÐºÐ¾Ð²Ð°Ð½Ð¸Ñ, Ð¿Ñ€Ð¸Ð½ÑÐ²ÑˆÐ¸Ð¹ Ð¾Ñ€Ð³Ð°Ð½ Ð¸ ÑÑÑ‹Ð»ÐºÐ° Ð½Ð° ÑÑ‚Ñ€Ð°Ð½Ð¸Ñ†Ñƒ Ð¾Ð¿ÑƒÐ±Ð»Ð¸ÐºÐ¾Ð²Ð°Ð½Ð¸Ñ), Ð¾Ð´Ð¸Ð½ ÐºÐ¾Ð¼Ð¼Ð¸Ñ‚ Ð½Ð° Ð´ÐµÐ½ÑŒ Ð¾Ð¿ÑƒÐ±Ð»Ð¸ÐºÐ¾Ð²Ð°Ð½Ð¸Ñ. Ð­Ñ‚Ð¾ Ð½Ðµ Ð¾Ñ„Ð¸Ñ†Ð¸Ð°Ð»ÑŒÐ½Ð¾Ðµ Ð¾Ð¿ÑƒÐ±Ð»Ð¸ÐºÐ¾Ð²Ð°Ð½Ð¸Ðµ.
