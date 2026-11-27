<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Republic of Buryatia only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:17 UTC, Republic of Buryatia: Official Internet Portal of Legal Information (region03): 12 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Republic of Buryatia: Official Internet Portal of Legal Information (region03)](http://publication.pravo.gov.ru/documents/block/region03) | `zakony-<year>/` | daily | 2026-11-27 05:17 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:16](checks/2026-11.md#ru-pravo-buryatia-20261127t051645z) | pravo-buryatia | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:20](checks/2026-11.md#ru-pravo-buryatia-20261126t052028z) | pravo-buryatia | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 05:18](checks/2026-11.md#ru-pravo-buryatia-20261125t051803z) | pravo-buryatia | 12 | 19 | 0 | 0 | 0 (0) | changes found | [3](https://github.com/lexifina/russia-buryatia-law/compare/37ad7c5b3dc4...b214ced716b5) |
| [2026-11-24 13:05](checks/2026-11.md#ru-pravo-buryatia-20261124t130522z) | pravo-buryatia | 11 | 19 | 0 | 0 | 19 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
