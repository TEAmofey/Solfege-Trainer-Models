# Solfege Trainer — downloadable files

Public model and music school resources used by Solfege Trainer. The application source code is maintained separately.

- [Analysis model](https://github.com/TEAmofey/Solfege-Trainer-Models/releases/tag/models-v1): the five HTDemucs files, SHA-256 catalog and MIT license. The app downloads these once when source separation is needed.
- [Music literature materials](https://github.com/TEAmofey/Solfege-Trainer-Models/releases/tag/school-v1): 194 recordings, an index with titles and performer credits, and a ZIP containing books, chapter PDFs, notes, 125 app images and the homework catalog. A separate original-score-images.zip preserves the original score images.

Recordings download individually when played and remain available offline. The app checks downloaded files against pinned SHA-256 hashes. Keep release filenames unchanged and publish updates under a new version tag.

## Contents

`audio-index.csv` maps recording IDs to titles, performance credits and MP3 files. `music-literature-materials.zip` contains readable source materials with their original names. `SchoolAudioDownloads.json` describes the audio downloads. `ModelDownloads.json` describes the separation model.

The HTDemucs model is based on Demucs by Meta Platforms, Inc. and affiliates and is distributed with its MIT license. Recording and book attribution is retained in the materials and index.
