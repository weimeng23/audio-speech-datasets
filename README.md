# Audio/Speech Datasets

A list of various Audio/Speech datasets about Speech Recognition, Speech Synthesis, Noise, Audio Tagging/Sound Event Detection, Speaker Diarization, Speaker Recognition, (Inverse) Text normalization, Speech Translation, Multilingual, etc. (continuously update)

- [Audio/Speech Datasets](#audiospeech-datasets)
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

## Task

### Speech Recognition

#### Chinese

| Name                                     | Duration(hours)                     | Links                                                        | Comments                                                     |
| :--------------------------------------- | ----------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| THCHS-30                                 | 30                                  | [[SLR18]](https://www.openslr.org/18/)                       | train 30 speakers, 10893 utterances<br />test 10 speakers, 2496 utterances |
| AISHELL-1                                | 178                                 | [[SLR33]](https://www.openslr.org/33/)                       | 400 speakers                                                 |
| AISHELL-2                                | 1000                                | [[Website]](https://www.aishelltech.com/aishell_2)           | 1991 speakers                                                |
| Free ST Chinese Mandarin (ST-CMDS)       | 110                                 | [[SLR38]](https://www.openslr.org/38/)                       | 855 speakers, 102600 utterances                              |
| Primewords Chinese Corpus Set 1          | 99                                  | [[SLR47]](https://www.openslr.org/47/)                       | 296 native Chinese speakers                                  |
| aidatatang_200zh                         | 200                                 | [[SLR62]](https://www.openslr.org/62/)                       | 600 speakers                                                 |
| aidatatang_1505zh                        | 1505                                | [[GitHub]](https://github.com/xiayongtao/aidatatang_1505zh)  |                                                              |
| MAGICDATA Mandarin Read                  | 755                                 | [[SLR68]](https://www.openslr.org/68/)                       | 1080 speakers                                                |
| MAGICDATA Mandarin Conversational (RAMC) | 180                                 | [[SLR123]](https://www.openslr.org/123/)                     | 663 speakers                                                 |
| AliMeeting (M2MeT)                       | 118.75 (train/dev/test 104.75/4/10) | [[SLR119]](https://www.openslr.org/119/)                     | ASR, SD                                                      |
| WenetSpeech                              | 10000+                              | [[SLR121]](https://www.openslr.org/121/)<br />[[GitHub]](https://github.com/wenet-e2e/WenetSpeech)<br />[[Website]](https://wenet-e2e.github.io/WenetSpeech/) |                                                              |
| TAL-ASR                                  | 100                                 | [[Website]](https://ai.100tal.com/openData/voice)            | 80+ speakers                                                 |
| TAL-CSASR                                | 587                                 | [[Website]](https://ai.100tal.com/openData/voice)            | code-switching, 200+ speakers                                |
| DiDiSpeech                               | 800                                 | [[Paper]](https://arxiv.org/abs/2010.09275)<br />[[Project]](https://athena-team.github.io/DiDiSpeech/) | 6000 speakers, 48 kHz; ASR, TTS, and voice conversion        |

#### English

| Name                           | Duration(hours)                                     | Links                                                        | Comments                                   |
| :----------------------------- | --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------ |
| LibriSpeech                    | 1000                                                | [[SLR12]](https://www.openslr.org/12/)<br />[[LM]](https://www.openslr.org/11/) |                                            |
| GigaSpeech                     | 33,000+ total<br />10,000 transcribed                | [[GitHub]](https://github.com/SpeechColab/GigaSpeech)        | supervised, semi-supervised, and unsupervised learning       |
| Libri-Light                    | 60,000+ unlabelled                                  | [[GitHub]](https://github.com/facebookresearch/libri-light)  | pretraining, unsupervised, semi-supervised                   |
| LibriHeavy                     | 50,000                                              | [[GitHub]](https://github.com/k2-fsa/libriheavy)             | casing, punctuation, context                                 |
| SPGISpeech                     | 5000                                                | [[Dataset]](https://huggingface.co/datasets/kensho/spgispeech)<br />[[Paper]](https://arxiv.org/abs/2104.02014) | financial earnings calls, fully formatted transcriptions     |
| The People's Speech           | 30,000+                                             | [[Website]](https://mlcommons.org/datasets/peoples-speech/)  | transcribed conversational English                           |

#### Multilingual

| Name                           | Duration(hours) | Links                                  | Comments                                                        |
| :----------------------------- | --------------- | -------------------------------------- | --------------------------------------------------------------- |
| Multilingual LibriSpeech (MLS) | 50,000+         | [[SLR94]](https://www.openslr.org/94/) | English, German, Dutch, Spanish, French, Italian, Portuguese, Polish |

### Speech Synthesis

#### Chinese

| Name      | Duration(hours) | Links                                  | Comments                                        |
| :-------- | --------------- | -------------------------------------- | ----------------------------------------------- |
| AISHELL-3 | 85              | [[SLR93]](https://www.openslr.org/93/) | 218 native Mandarin speakers, 88,035 utterances |

#### English

| Name     | Duration(hours) | Links                                  | Comments                         |
| :------- | --------------- | -------------------------------------- | -------------------------------- |
| LibriTTS | 585             | [[SLR60]](https://www.openslr.org/60/) | read English speech, 24 kHz audio |

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

| Name    | Duration(hours) | Links                                                                  | Comments                                         |
| :------ | --------------- | ---------------------------------------------------------------------- | ------------------------------------------------ |
| GigaST  | 10,000          | [[Website]](https://st-benchmark.github.io/resources/GigaST)           | English-to-German and English-to-Chinese         |
| GigaS2S | Not stated      | [[GitHub]](https://github.com/SpeechTranslation/GigaS2S)               | English-to-Chinese; synthetic target speech      |

## Reference

- [double22a/speech_dataset: The dataset of Speech Recognition (github.com)](https://github.com/double22a/speech_dataset#the-dataset-of-speech-recognition)

- [talhanai/speech-nlp-datasets: Contains links to publicly available datasets for modeling health outcomes using speech and language. (github.com)](https://github.com/talhanai/speech-nlp-datasets)

- [coqui-ai/open-speech-corpora: 💎 A list of accessible speech corpora for ASR, TTS, and other Speech Technologies (github.com)](https://github.com/coqui-ai/open-speech-corpora)
