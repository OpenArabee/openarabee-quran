# OpenArabee: Quran layer

Quranic attestations for the [OpenArabee core dataset](https://github.com/OpenArabee/openarabee-core):
for each verb, how often it occurs in the Quran and one to three example verses.

**Status: Phase 0 (setup). There is no data here yet.** It is filled in sub-phase 1c of the
[project charter](https://github.com/OpenArabee/openarabee-core/blob/main/docs/charter.md).

## Why a separate repository

The core dataset contains only material that permits commercial reuse (CC BY 4.0). The
sources needed for the Quran layer have their own, narrower terms, so everything derived
from them is kept here and never copied into the core (charter §8, D-003).
**Read [LICENSING.md](LICENSING.md) before reusing anything from this repository.**

## Planned layout

| Path | Content |
|---|---|
| `text/` | the Tanzil Quran text (Uthmani, Ḥafṣ), unmodified, with its checksum and download date |
| `attestations/<root id>.json` | per core lexeme id: occurrence count and example verses (sura:verse references) |
| `tools/` | scripts that compute counts and check references against the text |

Entries refer to core data by id (`r-ktb`, `v-ktb-1`); identifiers are defined in the core
repository (`docs/data-model.md`).

## Claims

Numbers are published only if computed here, with the script that produced them
(charter §9). "Recognising a word" is not "understanding the text".
