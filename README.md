# Multimodal Music Datasets? Challenges and Future Goals in Music Processing

[![License: ](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs13735--024--00344--6-brightgreen)](https://doi.org/10.1007/s13735-024-00344-6)

[Anna-Maria Christodoulou](https://www.uio.no/ritmo/english/people/phd-fellows/annammc/index.html)<sup>1</sup>, 
[Olivier Lartillot](https://www.uio.no/ritmo/english/people/tenured/oliviel/index.html)<sup>1</sup>,
[Alexander Refsum Jensenius](https://www.uio.no/ritmo/english/people/management/alexanje/index.html)<sup>1</sup>,

<sup>1</sup> RITMO, UiO 


This repository contains information and supplementary materials for the paper titled "Defining Multimodal Music Datasets and Addressing Challenges in Their Construction and Evaluation."

![alt text](Fig1.png)

## Abstract
The term "multimodal music dataset" is frequently utilized to depict music-related data representing music as a multimedia art form and a multimodal experience. However, the interpretation of "multimodality" can vary across related disciplines such as musicology, music psychology, and music technology. This paper proposes a comprehensive definition of multimodality that is applicable across different music disciplines. It addresses various challenges associated with constructing, evaluating, and utilizing multimodal music datasets. Additionally, the paper categorizes these datasets based on tasks and explores theoretical methodologies aimed at improving their future construction. It also sheds light on diverse data preprocessing methods and their contributions to transparent music analysis. Furthermore, evaluation metrics, methods, and benchmarks tailored for multimodal music processing tasks are scrutinized, empowering researchers to make informed decisions and facilitating cross-study comparisons.

## Multimodal music dataset definition

We propose to define multimodality as the deliberate integration of varied information sources tailored to specific tasks.

## TABLE 1: 

Multimodal music datasets, with corresponding modalities, number of data (file count), task and macro-task, according to our proposed categorization.
The list is being continuously updated. To contribute, please contact: a.m.christodoulou@imv.uio.no

| Dataset Name | Modality | Number of Data | Specific Task | Macro Task |
|---|---|---|---|---|
| FMA | Audio, Video, Text, Music Scores, MIDI | 106574 | Emotion/Affect Recognition | Classification |
| CAL500 | Audio, Text | 500 | Genre Classification | Classification |
| EmoMV-A | Audio, Video | 4914 | Emotion/Affect Recognition | Classification |
| EmoMV-B | Audio, Video | 616 | Emotion/Affect Recognition | Classification |
| EmoMV-C | Audio, Video | 456 | Emotion/Affect Recognition | Classification |
| IMAC | Audio, Video | 3812 | Music Gesture Classification | Classification |
| TROMPA-MER | Audio, Text (Lyrics, Participant Information) | 1161 | Emotion/Affect Recognition | Classification |
| MERP | Audio, Labels, Text (Lyrics, Participant Information) | 54 | Emotion/Affect Recognition | Classification |
| NAVER Music | Audio, Images | 7484 | Emotion/Affect Recognition | Classification |
| PMEmo | Audio, Images, Physiological Data | 794 | Emotion/Affect Recognition | Classification |
| Hu et al | Audio, Text (Descriptive Labels, Lyrics, Participant Information) | 8784 | Genre Classification | Classification |
| Laurier et al | Audio,Text (Descriptive Labels, Lyrics, Participant Information) | 1000 | Emotion/Affect Recognition | Classification |
| Trochidis et al | Audio, Text (Descriptive Labels, Lyrics, Participant Information) | 100 | Genre Classification | Classification |
| Turnbull et al | Audio, Text (Descriptive Labels, Lyrics, Participant Information) | 500 | Genre Classification | Classification |
| LMD_Aligned | Audio, Scores, Model-based Features, Images (Album Covers), Text (Playlist Information, Lyrics) | 5164 | Music Gesture Classification | Classification |
| MSD-I | Audio, Images (Album Covers), Text (Genre Annotations) | 30000 | Singing Voice Analysis | Classification |
| MuMu | Images, Audio, Text (Album Reviews) | 147000 | Emotion/Affect Recognition | Classification |
| Mayer et al | Audio, Text (Lyrics) | 3610 | Genre Classification | Classification |
| Orio et al | Audio, Text | 2671 | Genre Classification | Classification |
| Schnidler et al | Audio, Video | 2212 | Genre Classification | Classification |
| Turkish Makam Music | Audio, Note-level Information | 257 | Genre Classification | Classification |
| CompMusic Art Indian Music | Audio, Annotations | 117 | Emotion/Affect Recognition | Classification |
| Saraga Music Research | Audio, Annotations | 563 | Genre Classification | Classification |
| Sarasua | Audio, Video, Motion Capture, Physiological Data (EMG, ECG), Text, MIDI | 211 | Emotion/Affect Recognition | Classification |
| Chang et al | Audio, Video, Motion Capture, Physiological Data (EMG, ECG), Text, MIDI |  | Auto-Tagging | Classification |
| Vocal92 | Audio, Text, Annotations | 4453 | Singing Voice Analysis | Classification |
| MTG Jamendo | Audio, Annotations | 55701 | Genre Classification | Classification |
| CocoChorales | Audio, MIDI, Note Annotations | 240000 | Music Segmentation | Time-Dependent Representation |
| MUSIC21 | Audio, Video | 365 | Music Generation | Music Generation |
| TRIOS | Audio, MIDI |  | Music Transcription | Time-Dependent Representation |
| Benetos et al | Audio, MIDI | 7 | Source Separation | Time-Dependent Representation |
| Cheng et al | Audio | 13 | Source Separation | Time-Dependent Representation |
| Hargreaves et al | Audio | 20 | Music Segmentation | Time-Dependent Representation |
| Gregorio et al | Audio, MIDI | 217 | Music Transcription | Time-Dependent Representation |
| Camera PrIMuS | Audio, Images | 87678 | Music Transcription | Time-Dependent Representation |
| MAPS | Audio, MIDI |  | Music Transcription | Time-Dependent Representation |
| MIREX multif0 | Audio, Annotations |  | Music Transcription | Time-Dependent Representation |
| Norwegian Hardanger Fiddle | Audio, Annotations | 60 | Music Transcription | Time-Dependent Representation |
| Gu et al | Audio, Video, IMU Data | 20 | Music Exploration and Discovery | Music Similarity |
| Poliner et al | Audio, MIDI | 130 | Music Exploration and Discovery | Music Similarity |
| Perez-Carillo et al | Audio, 3D Motion Data, Musical Score Information | 10 | Music Exploration and Discovery | Music Similarity |
| MSD | Audio, Text, Annotations | 1000000 | Music Exploration and Discovery | Music Similarity |
| MSD-500 | Audio, Text, Annotations |  | Music Exploration and Discovery | Music Similarity |
| Music4AllOnion | Audio, Text | 109269 | Music Exploration and Discovery | Music Similarity |
| Poltronieri et al | Audio, Annotations | 18 | Music Generation | Music Generation |
| Watanabe et al | Lyrics, Audio Excerpts, Artist IDs | 433936 | Music Generation | Music Generation |
| AtinPiano | Audio, Video |  | Piano Tutoring | Time-Dependent Representation |
| MUSIC | Audio, Video | 685 | Song Retrieval | Music Similarity |
| MusiCaps | Audio, Text | 5500 | Multi-Task | Multi-Task |
| URMP | Audio, Video, Scores (MIDI, PDF), Annotations | 187 | Multi-Task | Multi-Task |
| Groux et al | EEG, Audio, Video |  | Multi-Task | Multi-Task |
| DALI | Audio, Lyrics | 5358 | Multi-Task | Multi-Task |
| ENST-Drums | Audio, Video, Text, Music Scores, MIDI, Annotations | 187 | Multi-Task | Multi-Task |
| MedleyDB | Audio, Genre Labels, Note Annotations | 122 | Multi-Task | Multi-Task |
| RWC | Audio, Video, Text, Music Scores, MIDI, Annotations | 3544 | Multi-Task | Multi-Task |
| SDD | Audio, Captions | 1100 | Multi-Task | Multi-Task |
| Essid et al | Audio | Multi-Task | Multi-Task |


# Dataset Availability

![Distribution of available datasets across different music tasks. The width of each bar represents the number of datasets associated with each task, providing insights into the availability of resources for various areas in music research and analysis.](Fig3.png)


## Citation

If you find this useful for your research, please consider citing our work:

```bibtex
@article{christodoulou_multimodal_2024,
	title = {Multimodal music datasets? {Challenges} and future goals in music processing},
	volume = {13},
	issn = {2192-662X},
	shorttitle = {Multimodal music datasets?},
	url = {https://doi.org/10.1007/s13735-024-00344-6},
	doi = {10.1007/s13735-024-00344-6},
	number = {3},
	urldate = {2024-08-29},
	journal = {International Journal of Multimedia Information Retrieval},
	author = {Christodoulou, Anna-Maria and Lartillot, Olivier and Jensenius, Alexander Refsum},
	month = aug,
	year = {2024},
	pages = {37},
}
```

For any inquiries or suggestions, please contact [a.m.christodoulou@imv.uio.no].
