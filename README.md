# superperm-words

My shortest superpermutations, from my own searches. Where I have several words at my best length that are distinct from every published word (up to relabelling and reversal), all of them are here. Every word passed an exact checker before it went in.

Status as of 2026-11-17.

| n | my best | status | files |
|---|---|---|---|
| 9 | 408,717 | ties the current record ([Almanac W-0103](https://superpermutations.com/w/W-0103)) | `n9/408717-a.txt.xz`, `n9/408717-b.txt.xz` |
| 12 | 522,736,437 | current record ([Almanac W-0102](https://superpermutations.com/w/W-0102)) | `n12/522736437.detour` |
| 13 | 6,747,801,734 | previous record | `n13/6747801734.plan.xz` |
| 14 | 93,904,804,289 | previous record | `n14/93904804289.uplan.xz` |
| 16 | 22,320,795,905,601 | tentative record | `n16/22320795905601.uplan.xz` |

For n = 9 the file is the word itself, and for n = 12 it is the word in the Almanac's [Detour](https://superpermutations.com/) format. From n = 13 up a word is too big to keep (n = 13 is 45 MB compressed), so the file is the plan it was built from. Jakub Halfar's [tools](https://github.com/jhalfar/superpermutations) turn a plan back into the word.

`records.json` lists, for each word, its SHA-256 (for a plan, the SHA-256 of the word it rebuilds to), the checker that passed it, how it was found, and where it was posted.
