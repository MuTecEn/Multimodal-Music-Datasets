# Multimodal Music Datasets? Challenges and Future Goals in Music Processing

[![License: ](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs13735--024--00344--6-brightgreen)](https://doi.org/10.1007/s13735-024-00344-6)

[Anna-Maria Christodoulou](https://www.uio.no/ritmo/english/people/phd-fellows/annammc/index.html)<sup>1</sup>, 
[Olivier Lartillot](https://www.uio.no/ritmo/english/people/tenured/oliviel/index.html)<sup>1</sup>,
[Alexander Refsum Jensenius](https://www.uio.no/ritmo/english/people/management/alexanje/index.html)<sup>1</sup>,

<sup>1</sup> RITMO, UiO 


This repository contains information and supplementary materials for the paper titled "Multimodal Music Datasets? Challenges and Future Goals in Music Processing"

![alt text](Fig1.png)

## Abstract
The term "multimodal music dataset" is frequently utilized to depict music-related data representing music as a multimedia art form and a multimodal experience. However, the interpretation of "multimodality" can vary across related disciplines such as musicology, music psychology, and music technology. This paper proposes a comprehensive definition of multimodality that is applicable across different music disciplines. It addresses various challenges associated with constructing, evaluating, and utilizing multimodal music datasets. Additionally, the paper categorizes these datasets based on tasks and explores theoretical methodologies aimed at improving their future construction. It also sheds light on diverse data preprocessing methods and their contributions to transparent music analysis. Furthermore, evaluation metrics, methods, and benchmarks tailored for multimodal music processing tasks are scrutinized, empowering researchers to make informed decisions and facilitating cross-study comparisons.

## Multimodal music dataset definition

We propose to define multimodality as the deliberate integration of varied information sources tailored to specific tasks.

## Existing Datasets 

Multimodal music datasets, with corresponding modalities, number of data (file count), task and macro-task, according to our proposed categorization.
The list is being continuously updated. To contribute, please contact: a.m.christodoulou@imv.uio.no

| Dataset Name | Modality | Number of Data | Specific Task | Macro Task |
|---|---|---|---|---|
| Acoustic Event Dataset [38] | Audio, Text | 5223 | Acoustic Event Classification | Classification |
| AIST Dance Video Database [39] | Audio, Video | 13940 | Dance classification |  |  |
| AMG1608 [40] | Audio, Text | 1608 | Emotion/Affect Recognition |  |  | 
| Ballroom [43] | Audio, Text | 698 | Dance Classification |  |  |
| DEAM [46] | Audio, Text, Features | 1802 | Emotion/Affect Recognition |  |  | 
| Emotion in Music Database [47] | Audio, Text | 1000 | Emotion/Affect Recognition |  |  |
| Emotify [48] | Audio, Text | 100 | Emotion/Affect Recognition |  |  |
| FMA [1] | Audio, Video, Text, Music Scores, MIDI, Annotations | 106574 | Emotion/Affect Recognition |  |  |
| CAL500 | Audio, Text | 500 | Genre Classification |  |  |
| CBFdataset [44] | Audio, Text | 10 performers | Music Playing Analysis |  |  | 
| EmoMV-A [2] | Audio, Video | 4914 | Emotion/Affect Recognition |  |  |
| EmoMV-B [2] | Audio, Video | 616 | Emotion/Affect Recognition |  |  |
| EmoMV-C [2] | Audio, Video | 456 | Emotion/Affect Recognition |  |  |
| Greek Music Dataset [50] | Audio, MIDI, Text | 1400 | Genre Classification |  |  | 
| Music Audio Benchmark [53] | Audio, Text (Genre Annotations) | Genre Classification |  |  |
| IMAC | Audio, Video | 3812 | Music Gesture Classification |  |  |
| TROMPA-MER [3] | Audio, Text (Lyrics, Participant Information) | 1161 | Emotion/Affect Recognition |  |  |
| MERP [4] | Audio, Labels, Text (Lyrics, Participant Information) | 54 | Emotion/Affect Recognition |  |  |
| NAVER Music | Audio, Images | 7484 | Emotion/Affect Recognition |  |  |
| OpenBMAT [57] | Audio, Annotations | 1647 | Music Detection |  |  |
| OpenMIC-2018 [58] | Audio, Annotations | 20000 | Instrument Recognition |  |  |
| PMEmo [5] | Audio, Images, Physiological Data | 794 | Emotion/Affect Recognition |  |  |
| Hu et al [6] | Audio, Text (Descriptive Labels, Lyrics, Participant Information) | 8784 | Genre Classification |  |  |
| IRMAS [55] | Audio, Text (Instrument annotation) | 2874 | Instrument Recognition |  |  |
| Laurier et al [7] | Audio,Text (Descriptive Labels, Lyrics, Participant Information) | 1000 | Emotion/Affect Recognition |  |  |
| Trochidis et al [8] | Audio, Text (Descriptive Labels, Lyrics, Participant Information) | 100 | Genre Classification |  |  |
| Turnbull et al [9] | Audio, Text (Descriptive Labels, Lyrics, Participant Information) | 500 | Genre Classification |  |  |
| LMD_Aligned [10] | Audio, Scores, Model-based Features, Images (Album Covers), Text (Playlist Information, Lyrics) | 5164 | Music Gesture Classification |  |  |
| MSD-I [11] | Audio, Images (Album Covers), Text (Genre Annotations) | 30000 | Singing Voice Analysis |  |  |
| MuMu | Images, Audio, Text (Album Reviews) | 147000 | Emotion/Affect Recognition |  |  |
| Mayer et al [12] | Audio, Text (Lyrics) | 3610 | Genre Classification |  |  |
| Orio et al [13] | Audio, Text | 2671 | Genre Classification |  |  |
| Schnidler et al [14] | Audio, Video | 2212 | Genre Classification |  |  |
| Turkish Makam Music | Audio, Note-level Information | 257 | Genre Classification |  |  |
| CompMusic Art Indian Music | Audio, Annotations | 117 | Emotion/Affect Recognition |  |  |
| Saraga Music Research | Audio, Annotations | 563 | Genre Classification |  |  |
| Sarasua [15] | Audio, Video, Motion Capture, Physiological Data (EMG, ECG), Text, MIDI | 211 | Emotion/Affect Recognition |  |  |
| Chang et al [16] | Audio, Video, Motion Capture, Physiological Data (EMG, ECG), Text, MIDI |  | Auto-Tagging |  |  |
| MusiClef 2012 [60] | Audio, Text, Annotations | 1355  | Auto-Tagging |  |  |
| Vocal92 [17] | Audio, Text, Annotations | 4453 | Singing Voice Analysis |  |  |
| MTG Jamendo [18] | Audio, Annotations | 55701 | Genre Classification |  |  |
| ASAP [41] | Audio, MIDI, MusicXML | 1068 MIDI files, 520 audio files, 222 scores  | Music Transcription  | Time-Dependent Representation  |
| CocoChorales | Audio, MIDI, Note Annotations | 240000 | Music Segmentation |  |  |
| GuitarSet [52] | Audio, Text (Pitch Annotations) | 360 | Music Transcription (Guitar) |  |  |
| TRIOS | Audio, MIDI |  | Music Transcription |  |  |
| Benetos et al [19] | Audio, MIDI | 7 | Source Separation |  |  |
| Cheng et al [20] | Audio | 13 | Source Separation |  |  |
| Hargreaves et al [21] | Audio | 20 | Music Segmentation |  |  |
| Gregorio et al [22] | Audio, MIDI | 217 | Music Transcription |  |  |
| Camera PrIMuS [23] | Audio, Images | 87678 | Music Transcription |  |  |
| ADC2004 [37] | Audio, Text | 20 | Music Transcription (Polyphonic Melody) | | |
| Groove Midi Dataset [51] | MIDI, Text, Audio | 1150 | Music Transcription (Drum) |  |  |
| MAPS [24] | Audio, MIDI |  | Music Transcription |  |  |
| MIREX multif0 | Audio, Annotations |  | Music Transcription |  |  |
| Norwegian Hardanger Fiddle [25] | Audio, Annotations | 60 | Music Transcription |  |  |
| ORCHSET [56] | Audio, Annotations | 64 | Music Transcription (Melody Extraction) |  |  |
| AtinPiano [26] | Audio, Video |  | Piano Tutoring |  |  |
| Watanabe et al [27] | Lyrics, Audio Excerpts, Artist IDs | 433936 | Music Generation |  |  |
| MUSIC21 | Audio, Video | 365 | Music Generation |  Music Generation  |
| Poltronieri et al [28] | Audio, Annotations | 18 | Music Generation |  |  |
| **Music Similarity** | | | | | |
| Gu et al [29] | Audio, Video, IMU Data | 20 | Music Exploration and Discovery |  |  |
| Poliner et al | Audio, MIDI | 130 | Music Exploration and Discovery |  |  |
| Perez-Carillo et al [30] | Audio, 3D Motion Data, Musical Score Information | 10 | Music Exploration and Discovery |  |  |
| MSD | Audio, Text, Annotations | 1000000 | Music Exploration and Discovery |  |  |
| MSD-500 | Audio, Text, Annotations |  | Music Exploration and Discovery |  |  |
| Music4AllOnion [31] | Audio, Text | 109269 | Music Exploration and Discovery |  |  |
| MUSIC | Audio, Video | 685 | Song Retrieval |  |  |
| AudioSet [42] | Audio, Video, Text | 2084320 clips | Multi-Task | Multi-Task |
| Dagstuhl ChoirSet [45] | Audio, MIDI, Note Annotations | 81 | Multi-Task |  |
| Erkomaishvili Dataset [49] | Audio, Video, Scores, Annotations | 118 | Multi-Task |  |  |
| MusiCaps | Audio, Text | 5500 | Multi-Task |  |
| URMP | Audio, Video, Scores (MIDI, PDF), Annotations | 187 | Multi-Task |  |  |
| Groux et al | EEG, Audio, Video |  | Multi-Task |  |  |
| DALI [32] | Audio, Lyrics | 5358 | Multi-Task |  |  |
| ENST-Drums [33] | Audio, Video, Text, Music Scores, MIDI, Annotations | 187 | Multi-Task |  |  |
| IDMT-SMT [54] | Audio, Text (annotations) | 64702 | Multi-Task |  |  |
| MedleyDB [34] | Audio, Genre Labels, Note Annotations | 122 | Multi-Task |  |  |
| MTD [61] | Audio, Metadata, MIDI | 2048  | Multi-Task |  |  |
| NSynth [59] | Audio, Note Annotations | 305979 | Multi-Task |  |  |
| RWC [35] | Audio, Video, Text, Music Scores, MIDI, Annotations | 3544 | Multi-Task |  |  |
| SDD | Audio, Captions | 1100 | Multi-Task |  |  |
| Essid et al [36] | Audio |  | Multi-Task |  |  |

# Availability

![Distribution of available datasets across different music tasks.](Fig4.png)

## Pre-processing Guidelines

- Crossmodal alignment
- Handling missing data across modalities
- Integrated feature extraction
- Consistent data normalization
- Coordinated dataset splitting

## Construction and Evaluation Criteria

- Diversity and representation
- Data quality and consistency
- Annotation and ground truth
- Modality interplay
- Generalization and robustness
- Usability and accessibility
- Real-world impact

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

**References:**
- [1] Defferrard M, Benzi K, Vandergheynst P, et al (2017) FMA: a dataset for music analysis. 
- [2] Thao HTP, Roig G, Herremans D (2023) EmoMV: affective music-video correspondence learning datasets for classification and retrieval. 
- [3] Gómez-Cañón JS, Gutiérrez-Páez N, Porcaro L et al (2023) TROMPA-MER: an open dataset for personalized music emotion recognition. 
- [4] Koh EY, Cheuk KW, Heung KY et al (2022) MERP: a music dataset with emotion ratings and raters’ profile information. 
- [5] Zhang K, Zhang H, Li S, et al (2018) The PMEmo dataset for music emotion recognition. 
- [6] Hu X, Downie JS, Ehmann AF (2009) Lyric text mining in music mood classification. 
- [7] Laurier C, Grivolla J, Herrera P (2008) Multimodal music mood classification using audio and lyrics. 
- [8] Trochidis K, Tsoumakas G, Kalliris G, et al (2008) Multilabel classification of music into emotions. 
- [9] Turnbull DR, Barrington L, Lanckriet G, et al (2009) Combining audio content and social context for semantic music discovery. 
- [10]  Bertin-Mahieux T, Ellis DPW, Whitman B, et al (2011) The million song dataset. 
- [11] MSD-I, The Million Song Dataset
- [12] Mayer R, Rauber A (2010) Multimodal aspects of music retrieval: audio, song lyrics - and beyond?
- [13] Orio N, Rizo D, Miotto R, et al (2011) MusiClef: a benchmark activity in multimodal music information retrieval. 
- [14] Schindler A, Rauber A (2017) Harnessing music-related visual stereotypes for music information retrieval. 
- [15] Sarasúa Á, Caramiaux B, Tanaka A, et al (2017) Datasets for the analysis of expressive musical gestures. 
- [16] Chang X, Peng L (2022) Intelligent analysis and classification of piano music gestures with multimodal recordings. 
- [17] Deng Z, Zhou R (2023) Vocal92: multimodal audio dataset with a cappella solo singing and speech. 
- [18] Bogdanov D, Won M, Tovstogan P, et al (2019) The MTG-Jamendo dataset for automatic music tagging. 
- [19] Benetos E, Klapuri A, Dixon S (2012) Score-informed transcription for automatic piano tutoring. 
- [20] Cheng HT, Yang YH, Lin YC, et al (2009) Multimodal structure segmentation and analysis of music using audio and textual information. 
- [21] Hargreaves S, Klapuri A, Sandler M (2012) Structural segmentation of multitrack audio. 
- [22] Gregorio J, Kim YE (2016) Phrase-level audio segmentation of jazz improvizations informed by symbolic data. 
- [23] Calvo-Zaragoza J, Rizo D (2018) Camera-PrIMuS: neural end-to-end optical music recognition on realistic monophonic scores. 
- [24] Emiya V, Bertin N, David B et al (2008) MAPS - A piano database for multipitch estimation and automatic transcription of music. 
- [25] Lartillot O, Johansson MS, Elowsson A et al (2023) A dataset of Norwegian Hardanger fiddle recordings with precise annotation of note and beat onsets. 
- [26] Gan C, et al. (2020) Foley music: learning to generate music from videos. 
- [27] Watanabe K, Goto M (2019) Query-by-blending: a music exploration system blending latent vector representations of lyric word, song audio, and artist. 
- [28] Poltronieri A (2023) Knowledge-based multimodal music similarity. 
- [29] Gu X, et al., (2022) MM-ALT: A multimodal automatic lyric transcription system. 
- [30] Perez-Carrillo A, et al., (2016) Estimation of guitar fingering and plucking controls based on multimodal analysis of motion, audio and musical score. 
- [31] Moscati M, et al. (2022) Music4All-onion—a large-scale multi-faceted content-centric music recommendation dataset. 
- [32] Meseguer-Brocal G, et al., (2018) DALI: A large dataset of synchronized audio, lyrics and notes, automatically created using teacher-student machine learning paradigm.
- [33] Gillet O, Richard G (2006) ENST-Drums: an extensive audio-visual database for drum signals processing. 
- [34] Bittner R, et al. (2014). SMedleyDB: A multitrack dataset for annotation-intensive MIR research. 
- [35] Goto M, et al., (2002). RWC music database: music genre database and musical instrument sound database. 
- [36] Essid S, Richard G (2012) Fusion of multimodal information in music content analysis. 
- [37] G. Poliner, D. Ellis (2005). A Classification Approach to Melody Transcription. 
- [38] N. Takahashi, et al., (2016). "Deep Convolutional Neural Networks and Data Augmentation for Acoustic Event Recognition".
- [39] S. Tsuchida, et al., (2019). AIST Dance Video Database: Multi-genre, Multi-dancer, and Multi-camera Database for Dance Information Processing. 
- [40] A. Chen, et al., (2015). "The AMG1608 dataset for music emotion recognition." 
- [41] Foscarin, F., et al., (2020). ASAP: a dataset of aligned scores and performances for piano transcription. 
- [42] J. F. Gemmeke et al., (2017). "Audio Set: An ontology and human-labeled dataset for audio events.".
- [43] https://mtg.upf.edu/ismir2004/contest/tempoContest/node5.html
- [44] C. Wang, et al., (2019). CBFdataset: A Dataset of Chinese Bamboo Flute Performances (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.3250223
- [45] S. Rosenzweig, et al., (2020). Dagstuhl ChoirSet: A Multitrack Dataset for MIR Research on Choral Singing.
- [46] Soleymani et al., https://cvml.unige.ch/databases/DEAM/
- [47] https://cvml.unige.ch/databases/emoMusic/
- [48] A. Aljanaki, et al., (2015). Studying emotion induced by music through a crowdsourcing game. 
- [49] S.Rosenzweig, et al., (2020). Erkomaishvili Dataset: A Curated Corpus of Traditional Georgian Vocal Music for Computational Musicology
- [50] Karydis et al., (2015). The Greek Music Dataset. https://cir.di.ionio.gr/karydis/my_papers/MKarydisS2015%20-%20The%20Greek%20Music%20Dataset.pdf
- [51] Gillick et al., (2019). Learning to Groove with Inverse Sequence Transformations. https://magenta.tensorflow.org/datasets/groove
- [52] Q. Xi, et al., (2018). "​Guitarset: A Dataset for Guitar Transcription"
- [53] Homburg, Helge et al. (2005). A Benchmark Dataset for Audio Classification and Clustering
- [54] https://www.idmt.fraunhofer.de/en/publications/datasets.html
- [55] Bosch, J. J., et al., (2012). “A Comparison of Sound Segregation Techniques for Predominant Instrument Recognition in Musical Audio Signals”
- [56] Bosch, J., et al. (2016), “Evaluation and Combination of Pitch Estimation Methods for Melody Extraction in Symphonic Classical Music”, Journal of New Music Research 
- [57] Meléndez-Catalán, B., et al. (2019). https://doi.org/10.5281/zenodo.3381249
- [58] Humphrey, E. J., et al. (2018). OpenMIC-2018 (v1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.1432913
- [59] Engel, J. et al., (2017). "Neural Audio Synthesis of Musical Notes with WaveNet Autoencoders."
- [60] Schedl, M., et al., (2013). "A Professionally Annotated and Enriched Multimodal Data Set on Popular Music".
- [61] Zalkow, F., et al., (2020). "MTD: A Multimodal Dataset of Musical Themes for MIR Research".

For any inquiries or suggestions, please contact [a.m.christodoulou@imv.uio.no].
