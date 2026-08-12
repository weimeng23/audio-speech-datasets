# Audio/Speech Datasets

A list of various Audio/Speech datasets about Speech Recognition, Speech Synthesis, Noise, Audio Tagging/Sound Event Detection, Speaker Diarization, Speaker Recognition, Speaker and Speech Traits, (Inverse) Text normalization, Speech Translation, Multilingual, etc. (continuously update)

- [Audio/Speech Datasets](#audiospeech-datasets)
  - [Task](#task)
    - [Speech Recognition](#speech-recognition)
    - [Speech Synthesis](#speech-synthesis)
    - [Noise](#noise)
    - [Audio Tagging/Sound Event Detection](#audio-taggingsound-event-detection)
    - [Speaker Diarization](#speaker-diarization)
    - [Speaker Recognition](#speaker-recognition)
    - [Speaker and Speech Traits](#speaker-and-speech-traits)
    - [(Inverse) Text normalization](#inverse-text-normalization)
    - [Speech Translation](#speech-translation)
  - [Reference](#reference)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

> [!NOTE]
> **License / Terms:** Official licenses are listed before additional usage terms. `Not stated` does not imply unrestricted use.
>
> **Access:** `Direct` = direct download; `Registration` = account or contact information required; `Gated` = terms must be accepted; `Application` = access must be requested; `Unavailable` = no working official download was found. Labels may be combined when more than one requirement applies.
>
> Metadata reviewed: 2026-08-12.

## Task

### Speech Recognition

#### Chinese

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [THCHS-30](https://www.openslr.org/18/) | 30 | Apache-2.0 | Direct |
| [AISHELL-1](https://www.openslr.org/33/) | 178 | Apache-2.0 | Direct |
| [AISHELL-2](https://www.aishelltech.com/aishell_2) | 1,000 | Academic use only | Application |
| [Free ST Chinese Mandarin (ST-CMDS)](https://www.openslr.org/38/) | 110 | CC BY-NC-ND 4.0 | Direct |
| [Primewords Chinese Corpus Set 1](https://www.openslr.org/47/) | 99 | CC BY-NC-ND 4.0 | Direct |
| [aidatatang_200zh](https://openslr.elda.org/62/) | 200 | CC BY-NC-ND 4.0 | Unavailable |
| [aidatatang_1505zh](https://github.com/xiayongtao/aidatatang_1505zh) | 1,505 | Academic use only | Application |
| [MAGICDATA Mandarin Read](https://www.openslr.org/68/) | 755 | CC BY-NC-ND 4.0 | Direct |
| [MAGICDATA Mandarin Conversational (RAMC)](https://www.openslr.org/123/) | 180 | CC BY-NC-ND 4.0 | Direct |
| [AliMeeting (M2MeT)](https://www.openslr.org/119/) | 118.75 | CC BY-SA 4.0 | Direct |
| [WenetSpeech](https://wenet-e2e.github.io/WenetSpeech/) | 22,400+ | CC BY 4.0 · non-commercial terms | Application |
| [TAL-ASR (Adult Chinese Teaching Audio)](https://ai.100tal.com/openData/voice) | 100 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TALCS / TAL-CSASR](https://ai.100tal.com/openData/voice) | 587 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [DiDiSpeech](https://athena-team.github.io/DiDiSpeech/) | 800 | Not stated | Unavailable |

- The official `aidatatang_200zh` download is currently unavailable; the entry and linked metadata/license record are retained.
- AliMeeting is also listed under [Speaker Diarization](#speaker-diarization). Its train/dev/test split is 104.75/4/10 hours.
- WenetSpeech contains more than 22,400 hours in total, including more than 10,000 hours of high-quality labeled data. Its official page states CC BY 4.0 and separately limits the release to non-commercial use.
- DiDiSpeech's former official download is no longer available; third-party mirrors are not treated as authoritative license sources.

#### English

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [LibriSpeech](https://www.openslr.org/12/) | 1,000 | CC BY 4.0 | Direct |
| [GigaSpeech](https://huggingface.co/datasets/speechcolab/gigaspeech) | 33,000+ | Apache-2.0 · non-commercial research/education terms | Application |
| [Libri-Light](https://github.com/facebookresearch/libri-light) | 60,000+ | Not stated | Direct |
| [LibriHeavy](https://github.com/k2-fsa/libriheavy) | 50,000 | Apache-2.0 repository · audio terms not stated | Direct |
| [SPGISpeech](https://huggingface.co/datasets/kensho/spgispeech) | 5,000 | Custom terms · research use only | Gated |
| [The People's Speech](https://huggingface.co/datasets/MLCommons/peoples_speech) | 30,000+ | CC BY 4.0 / CC BY-SA | Direct |

- GigaSpeech contains more than 33,000 hours in total, of which about 10,000 hours are transcribed; its audio remains subject to source-owner rights and the dataset's additional terms.
- Libri-Light's repository license applies to the accompanying code; no explicit dataset license was found on the official dataset page.
- LibriHeavy's Apache-2.0 license covers its repository; its audio is inherited from Libri-Light, whose official page does not state a dataset license.
- The People's Speech license varies by source subset; check the per-file metadata before reuse.

#### Multilingual

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [Multilingual LibriSpeech (MLS)](https://www.openslr.org/94/) | 50,000+ | CC BY 4.0 | Direct |

### Speech Synthesis

#### Chinese

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [AISHELL-3](https://www.openslr.org/93/) | 85 | Apache-2.0 | Direct |

#### English

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [LibriTTS](https://www.openslr.org/60/) | 585 | CC BY 4.0 | Direct |

### Noise

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [MUSAN](https://www.openslr.org/17/) | — | CC BY 4.0 | Direct |
| [Aachen Impulse Response Database (AIR)](https://www.openslr.org/20/) | — | Not stated | Direct |
| [Simulated Room Impulse Response Database](https://www.openslr.org/26/) | — | Apache-2.0 | Direct |
| [Room Impulse Response and Noise Database](https://www.openslr.org/28/) | — | Apache-2.0 | Direct |

### Audio Tagging/Sound Event Detection

### Speaker Diarization

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [AliMeeting (M2MeT)](https://www.openslr.org/119/) | 118.75 | CC BY-SA 4.0 | Direct |

### Speaker Recognition

### Speaker and Speech Traits

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [TAL-ASR (Adult Chinese Teaching Audio)](https://ai.100tal.com/openData/voice) | 100 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TAL Adult Chinese Speech Emotion](https://ai.100tal.com/openData/voice) | 12.5 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TALCS / TAL-CSASR](https://ai.100tal.com/openData/voice) | 587 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TAL Child Chinese Read Speech](https://ai.100tal.com/openData/voice) | 5.4 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TAL Child English Read Speech](https://ai.100tal.com/openData/voice) | 4.5 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TAL Adult Chinese Read Speech](https://ai.100tal.com/openData/voice) | 1,750 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TAL Adult English Read Speech](https://ai.100tal.com/openData/voice) | 180 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |
| [TAL Adult English Teaching Audio](https://ai.100tal.com/openData/voice) | 160 | [Custom terms · internal research only](https://ai.100tal.com/dataset-auth) | Registration · Gated |

- The child/adult corpus names provide coarse, corpus-level age-group labels; exact ages are not stated on the official page.
- The 12.5-hour speech-emotion corpus explicitly includes gender metadata. Per-utterance gender labels are not stated for the other corpora and should be verified after access.
- TAL's terms prohibit commercial use of the datasets and models trained from them, as well as redistribution or creation of derivative datasets.

### (Inverse) Text normalization

### Speech Translation

| Dataset | Hours | License / Terms | Access |
| :--- | ---: | :--- | :--- |
| [GigaST](https://st-benchmark.github.io/resources/GigaST) | 10,000 | CC BY-NC 4.0 | Direct |
| [GigaS2S](https://github.com/SpeechTranslation/GigaS2S) | — | CC BY 4.0 | Direct |

- GigaST provides English-to-German and English-to-Chinese translations; the source audio follows GigaSpeech's separate access terms.
- GigaS2S provides English-to-Chinese synthetic target speech.

## Reference

- [double22a/speech_dataset: The dataset of Speech Recognition (github.com)](https://github.com/double22a/speech_dataset#the-dataset-of-speech-recognition)

- [talhanai/speech-nlp-datasets: Contains links to publicly available datasets for modeling health outcomes using speech and language. (github.com)](https://github.com/talhanai/speech-nlp-datasets)

- [coqui-ai/open-speech-corpora: 💎 A list of accessible speech corpora for ASR, TTS, and other Speech Technologies (github.com)](https://github.com/coqui-ai/open-speech-corpora)
