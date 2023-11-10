# Audio/Speech Datasets

A list of various Audio/Speech datasets about Speech Recognition, Speech Synthesis, Noise, Audio Tagging/Sound Event Detection, Speaker Diarization, Speaker Recognition, (Inverse) Text normalization, Speech Translation, Multilingual, etc. (continuously update)

- [Audio/Speech Datasets](#audiospeech-datasets)
  - [Overview](#overview)
  - [Task](#task)
    - [Speech Recognition](#speech-recognition)
    - [Speech Synthesis](#speech-synthesis)
    - [Noise](#noise)
    - [Audio Tagging/Sound Event Detection](#audio-taggingsound-event-detection)
    - [Speaker Diarization](#speaker-diarization)
    - [Speaker Recognition](#speaker-recognition)
    - [(Inverse) Text normalization](#inverse-text-normalization)
    - [Speech Translation](#speech-translation)
  - [Reference](#reference)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Overview

- Task
  - ASR
  - TTS
  - Noise
  - Audio/Sound
  - SD
  - SR
  - TN/ITN
  - ST
- Language
  - chinese
  - english
  - ohter

## Task

### Speech Recognition

#### chinese

| Name                                     | Duration(hours)                     | Links                                                        | Comments                                                     |
| :--------------------------------------- | ----------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| THCHS-30                                 | 30                                  | [[SLR18]](https://www.openslr.org/18/)                       | train 30 speakers, 10893 utterances<br />test 10 speakers, 2496 utterances |
| Aishell                                  | 179                                 | [[SLR33]](https://www.openslr.org/33/)                       | 400 speakers                                                 |
| Aishell2                                 | 1000                                | [[Website]](https://www.aishelltech.com/aishell_2)           | **if available**, 1991 speakers                              |
| Free ST Chinese Mandarin (ST-CMDS)       | 110                                 | [[SLR38]](https://www.openslr.org/38/)                       | 855 speakers, 102600 utterances                              |
| Primewords Chinese Corpus Set 1          | 99                                  | [[SLR47]](https://www.openslr.org/47/)                       | 296 native Chinese speakers                                  |
| aidatatang_200zh                         | 200                                 | [[SLR62]](https://www.openslr.org/62/)                       | 600 speakers                                                 |
| aidatatang_1505zh                        | 1505                                | [[Github]](https://github.com/xiayongtao/aidatatang_1505zh)  | **if available**                                             |
| MAGICDATA Mandarin Read                  | 755                                 | [[SLR68]](https://www.openslr.org/68/)                       | 1080 speakers                                                |
| MAGICDATA Mandarin Conversational (RAMC) | 180                                 | [[SLR123]](https://www.openslr.org/123/)                     | 663 speakers                                                 |
| AliMeeting (M2MeT)                       | 118.75 (train/dev/test 104.75/4/10) | [[SLR119]](https://www.openslr.org/119/)                     | ASR, SD                                                      |
| WenetSpeech                              | 10000+                              | [[SLR121]](https://www.openslr.org/121/)<br />[[Github]](https://github.com/wenet-e2e/WenetSpeech)<br />[[Website]](https://wenet-e2e.github.io/WenetSpeech/) |                                                              |
| TAL-ASR                                  | 100                                 | [[Website]](https://ai.100tal.com/openData/voice)            | 80+ speakers                                                 |
| TAL-CSASR                                | 587                                 | [[Website]](https://ai.100tal.com/openData/voice)            | code-switching, 200+ speakers                                |
| didispeech                               |                                     |                                                              | **if available**                                             |

#### english

| Name                           | Duration(hours)                                     | Links                                                        | Comments                                   |
| :----------------------------- | --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------ |
| LibriSpeech                    | 1000                                                | [[SLR12]](https://www.openslr.org/12/)<br />[[LM]](https://www.openslr.org/11/) |                                            |
| GigaSpeech                     | 33,000+ for unsupervised<br />10,000 for supervised | [[Github]](https://github.com/SpeechColab/GigaSpeech)        |                                            |
| Multilingual LibriSpeech (MLS) |                                                     | [[SLR94]](https://www.openslr.org/94/)                       | Multilingual                               |
| libri-light                    | 60,000 unlabelled speech                            | [[Github]](https://github.com/facebookresearch/libri-light)  | pretraining, unsupervised, semi-supervised |
| libriheavy                     | 50,000                                              | [[Github]](https://github.com/k2-fsa/libriheavy)             | casing, punctuation, context               |
| Spgispeech                     |                                                     |                                                              |                                            |
| People's Speech                |                                                     |                                                              |                                            |

### Speech Synthesis

#### chinese

| Name      | Duration(hours) | Links                                              | Comments                                              |
| :-------- | --------------- | -------------------------------------------------- | ----------------------------------------------------- |
| AISHELL-3 | 85              | [[Website]](https://www.aishelltech.com/aishell_3) | 44.1k, 218 native Chinese spearkers, 88035 utterances |
| LibriTTS  |                 |                                                    |                                                       |
|           |                 |                                                    |                                                       |
|           |                 |                                                    |                                                       |

### Noise

| Name                                     | Duration(hours) | Links                                  | Comments |
| :--------------------------------------- | --------------- | -------------------------------------- | -------- |
| MUSAN                                    |                 | [[SLR17]](https://www.openslr.org/17/) |          |
| Aachen Impulse Response database (AIR)   |                 | [[SLR20]](https://www.openslr.org/20/) |          |
| Simulated Room Impulse Response Database |                 | [[SLR26]](https://www.openslr.org/26/) |          |
| Room Impulse Response and Noise Database |                 | [[SLR28]](https://www.openslr.org/28/) |          |

### Audio Tagging/Sound Event Detection

### Speaker Diarization

| Name               | Duration(hours)                  | Links                                    | Comments |
| :----------------- | -------------------------------- | ---------------------------------------- | -------- |
| AliMeeting (M2MeT) | 118.75 (train/dev/test 104.75/4/10) | [[SLR119]](https://www.openslr.org/119/) | ASR, SD  |

### Speaker Recognition

### (Inverse) Text normalization

### Speech Translation

GigaST

GigaS2S

## Reference

- [double22a/speech_dataset: The dataset of Speech Recognition (github.com)](https://github.com/double22a/speech_dataset#the-dataset-of-speech-recognition)

- [talhanai/speech-nlp-datasets: Contains links to publicly available datasets for modeling health outcomes using speech and language. (github.com)](https://github.com/talhanai/speech-nlp-datasets)
