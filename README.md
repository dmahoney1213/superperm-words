# superperm-words

My shortest superpermutations, from my own searches. Where I have several words at my best length that are distinct from every published word, all of them are here.

Status as of 2026-11-17.

| n | my best | status | files |
|---|---|---|---|
| 9 | 408,717 | ties the current record ([Almanac W-0103](https://superpermutations.com/w/W-0103)) | `n9/408717-a.detour` to `n9/408717-g.detour` (7 words) |
| 12 | 522,736,437 | current record ([Almanac W-0102](https://superpermutations.com/w/W-0102)) | `n12/522736437.detour` |
| 13 | 6,747,801,734 | previous record | `n13/6747801734.detour` |
| 14 | 93,904,804,289 | previous record | `n14/93904804289.detour` |
| 15 | 1,401,325,411,389 | tentative record | `n15/1401325411389.uplan.xz` |
| 16 | 22,320,795,905,601 | tentative record | `n16/22320795905601.uplan.xz` |

Up to n = 14 every word is in the [Superpermutation Almanac](https://superpermutations.com/)'s Detour format. The words for n = 15 and 16 are too big for that (1.4 TB and 22 TB), so each file is the plan the word is built from. Jakub Halfar's [tools](https://github.com/jhalfar/superpermutations) turn a plan back into its word.

`records.json` lists, for each word, its SHA-256 (for a plan, the SHA-256 of the word it rebuilds to), the checker that passed it, how it was found, and where it was posted.
