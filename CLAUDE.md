# OpenArabee Quran layer: working rules

Derived from the charter in `openarabee-core` (`docs/charter.md`), which wins if this file
disagrees with it. Read the charter and `docs/handoff.md` there before starting.

1. **Nothing from this repository goes into `openarabee-core`.** The core must stay
   commercially reusable; this layer is not (see `LICENSING.md`). References go one way:
   from here to core ids.
2. **The Tanzil text is never modified.** Store it verbatim with header, checksum and
   download date. Do not normalise, re-vowel or re-encode the file.
3. **Quranic Arabic Corpus data is used for research purposes only**, with attribution, and
   is not redistributed beyond what its terms allow. When unsure, ask the owner.
4. **Quote verses only from the stored Tanzil text**, by sura:verse reference, never from
   memory. An AI-recalled verse is not a source.
5. **Numbers are computed, with a committed script**, never estimated (charter §9).
6. No tafsīr, no religious rulings (charter §1, non-goals).
7. Ask the owner before anything public, irreversible, paid or licence-related. Work on a
   branch and open a pull request; the owner merges.

Languages: code and docs English; conversation with the owner German.
