# Licensing of the Quran layer

Not legal advice. This file summarises the terms as recorded in the project charter (§6);
the wording published by each source is authoritative and must be re-read before any release.

| Material | Source | Terms as recorded | Consequence here |
|---|---|---|---|
| Quran text (Uthmani, Ḥafṣ) | [Tanzil](https://tanzil.net/download) | CC BY 3.0, verbatim copies only, with attribution and a link to tanzil.net | The text file is stored unmodified, including its header. It is never edited, re-vowelled or normalised in place; tools work on copies in memory. |
| Morphological annotation v0.4 | [Quranic Arabic Corpus](https://corpus.quran.com/faq.jsp) | research / non-commercial use, with attribution | Anything derived from it (occurrence counts, word-to-lexeme links) stays in this repository and is **not** available for commercial use. Open point O-3: ask the maintainers about other uses. |
| Scripts in `tools/` | OpenArabee | MIT (`LICENSE`) | |

Until the legal consultation foreseen in the charter has taken place, treat **all data in
this repository as non-commercial**.

Open questions (charter §11): O-3 (terms of the Quranic Arabic Corpus for non-research use),
O-4 (whether the root list derived from frequency counts may live in the core).
