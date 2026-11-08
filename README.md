LEAF Quran Dataset

Public versioned Quran dataset repository for the LEAF Android application.

Dataset contents

Each release will contain:

- Arabic Uthmani Quran text
- Bengali translation
- English translation
- English transliteration
- Word-by-word Arabic and English transliteration
- Release manifest with SHA-256 checksum

Download

Latest release manifest:

https://github.com/jihad8893/LEAF-Quran-Dataset/releases/latest/download/release-manifest.json

Latest dataset archive:

https://github.com/jihad8893/LEAF-Quran-Dataset/releases/latest/download/leaf-quran-dataset.zip

Validation

- 114 Surahs
- 6,236 Ayahs
- 82,429 lexical word records (when word-level data is available)

The Android application verifies SHA-256 before installing the dataset into Room Database.

Data sources

- Al Quran Cloud API
- Quran Foundation Content Sync API

The Android application source code is maintained separately in a private repository.

Generated Bengali pronunciation is a reading aid, not a certified Tajweed transcription.
