# Awesome Text VQA

Text related VQA is a fine-grained direction of the VQA task, which only focuses on the question that requires to read the textual content shown in the input image.

## Datasets
- **VisualMRC** dataset (AAAI 2021) [[Project](https://github.com/nttmdlab-nlp/VisualMRC)][[Paper](https://arxiv.org/abs/2101.11272)]
- **EST-VQA** dataset (CVPR 2020) [[Project](http://est-vqa.org/)][[Paper](https://arxiv.org/abs/2002.10215)]
- **DOC-VQA** dataset (CVPR Workshop 2020) [[Project](https://rrc.cvc.uab.es/?ch=17)][[Paper](https://arxiv.org/abs/2007.00398)]
- **Text-VQA** dataset (CVPR 2019) [[Project](https://textvqa.org/dataset)][[Paper](https://arxiv.org/abs/1904.08920)]
- **ST-VQA** dataset (ICCV 2019) [[Project](https://rrc.cvc.uab.es/?ch=11)][[Paper](https://arxiv.org/abs/1905.13648)]
- **OCR-VQA** dataset (ICDAR 2019) [[Project](https://ocr-vqa.github.io/)][[Paper](https://anandmishra22.github.io/files/mishra-OCR-VQA.pdf)]

| Dataset | #Train+Val Img | #Train+Val Que | #Test Img | #Test Que | Image Source | Language |
| ------- | -------------- | -------------- | --------- | --------- | ------------ | -------- |
| Text-VQA | 25,119        | 39,602         | 3,353     | 5,734     | [1]          | EN |
| ST-VQA   | 19,027        | 26,308         | 2,993     | 4,163     | [2, 3, 4, 5, 6, 7, 8] | EN |
| OCR-VQA  | 186,775       | 901,717        | 20,797    | 100,429   | [9]          | EN |
| EST-VQA  | 17,047        | 19,362         | 4,000     | 4,525     | [4, 5, 8, 10, 11, 12, 13] | EN+CH |
| DOC-VQA  | 11,480        | 44,812         | 1,287     | 5,188     | [14] | EN |
| VisualMRC| 7,960         | 23,854         | 2,237     | 6,708     | self-collected webpage screenshot | EN |


**Image Source**: <br>
[1] OpenImages: A public dataset for large-scale multi-label and multi-class image classification (v3) [[dataset](https://storage.googleapis.com/openimages/web/download.html)] <br>
[2] Imagenet: A large-scale hierarchical image database [[dataset](http://www.image-net.org/)] <br>
[3] Vizwiz grand challenge: Answering visual questions from blind people [[dataset](https://vizwiz.org/)] <br>
[4] ICDAR 2013 robust reading competition [[dataset](http://dagdata.cvc.uab.es/icdar2013competition/)] <br>
[5] ICDAR 2015 competition on robust reading [[dataset]()]<br>
[6] Visual Genome: Connecting language and vision using crowdsourced dense image annotations [[dataset](https://visualgenome.org/)] <br>
[7] Image retrieval using textual cues [[dataset](https://cvit.iiit.ac.in/research/projects/cvit-projects/image-retrieval-using-textual-cues)] <br>
[8] Coco-text: Dataset and benchmark for text detection and recognition in natural images [[dataset](https://vision.cornell.edu/se3/coco-text-2/)] <br>
[9] Judging a book by its cover [[dataset](https://github.com/uchidalab/book-dataset)] <br>
[10] Total Text [[dataset](https://github.com/cs-chan/Total-Text-Dataset)] <br>
[11] SCUT-CTW1500 [[dataset](https://github.com/Yuliang-Liu/Curve-Text-Detector)] <br>
[12] MLT [[dataset](https://rrc.cvc.uab.es/?ch=8)] <br>
[13] Chinese Street View Text [[dataset](https://rrc.cvc.uab.es/?ch=16)] <br>
[14] UCSF Industry Document Library [[dataset](https://www.industrydocuments.ucsf.edu/)] <br>

## Related Challenges



**ICDAR 2021 COMPETITION On Document Visual Question Answering (DocVQA)** Submission Deadline:  31st March 2021 [[Challenge](https://icdar2021.org/program-2/competitions/docvqa/)]<br>
**Document Visual Question Answering** （*CVPR 2020 Workshop on Text and Documents in the Deep Learning Era* Submission Deadline: ~~30 April 2020~~ [[Challenge]](https://rrc.cvc.uab.es/?ch=17)

## Papers

### 2022
- <a name="TAG"></a> **[TAG]** TAG: Boosting Text-VQA via Text-aware Visual Question-answer Generation (**arXiv**) [[Paper](https://arxiv.org/abs/2208.01813)][[Project](https://github.com/HenryJunW/TAG)]

### 2021
- <a name="VisualMRC"></a> **[VisualMRC]** VisualMRC: Machine Reading Comprehension on Document Images (**AAAI**) [[Paper](https://arxiv.org/pdf/2101.11272.pdf)][[Project](https://github.com/nttmdlab-nlp/VisualMRC)]
- <a name="SSBaseline"></a> **[SSBaseline]** Simple is not Easy: A Simple Strong Baseline for TextVQA and TextCaps (**AAAI**) [[Paper](https://arxiv.org/pdf/2012.05153.pdf)][[code](https://github.com/ZephyrZhuQi/ssbaseline)]

### 2020
- <a name="SA-M4C"></a> **[SA-M4C]** Spatially Aware MultimodalTransformers for TextVQA (**ECCV**) [[Paper](https://arxiv.org/pdf/2007.12146.pdf)][[Project](https://yashkant.github.io/projects/sam-textvqa)][[Code](https://github.com/yashkant/sam-textvqa)]
- <a name="LoRRA"></a> **[EST-VQA]** On the General Value of Evidence, and Bilingual Scene-Text Visual Question Answering (**CVPR**) [[Paper](https://arxiv.org/abs/2002.10215)]
- <a name="M4C"></a> **[M4C]** Iterative Answer Prediction with Pointer-Augmented Multimodal Transformers for TextVQA (**CVPR**) [[Paper](https://arxiv.org/abs/1911.06258)][[Project](https://ronghanghu.com/m4c/)]
- <a name="LaAP-Net"></a> **[LaAP-Net]** Finding the Evidence: Localization-aware Answer Prediction for TextVisual Question Answering (**COLING**) [[Paper](https://arxiv.org/abs/2010.02582)]
- <a name="CRN"></a> **[CRN]** Cascade Reasoning Network for Text-basedVisual Question Answering (**ACM MM**) [[Paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413924)][[Project](https://github.com/guanghuixu/CRN_tvqa)]


### 2019
- <a name="LoRRA"></a> **[Text-VQA/LoRRA]** Towards VQA Models That Can Read (**CVPR**) [[Paper](https://arxiv.org/abs/1904.08920)][[Code](https://github.com/facebookresearch/pythia)]
- <a name="ST-VQA"></a> **[ST-VQA]** Scene Text Visual Question Answering (**ICCV**) [[Paper](https://arxiv.org/abs/1905.13648)]
- <a name="Text-KVQA"></a>  **[Text-KVQA]** From Strings to Things: Knowledge-enabled VQA Modelthat can Read and Reason (**ICCV**) [[Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Singh_From_Strings_to_Things_Knowledge-Enabled_VQA_Model_That_Can_Read_ICCV_2019_paper.pdf)]
- <a name="OCR-VQA"></a> **[OCR-VQA]** OCR-VQA: Visual Question Answering by Reading Text in Images (**ICDAR**) [[Paper](https://anandmishra22.github.io/files/mishra-OCR-VQA.pdf)]


### Technical Reports

- <a name="TAP"></a> **[TAP]** TAP: Text-Aware Pre-training for Text-VQA and Text-Caption [[Report](https://arxiv.org/abs/2012.04638)]
- <a name="RUArt"></a> **[RUArt]** RUArt: A Novel Text-Centered Solution for Text-Based Visual Question Answering [[Report](https://arxiv.org/pdf/2010.12917.pdf)]
- <a name="SMA"></a> **[SMA]** Structured Multimodal Attentions for TextVQA [[Report](https://arxiv.org/pdf/2006.00753.pdf)][[Slides](https://drive.google.com/file/d/1tJ9yK6U6fNkMAV-vLzWPzihaKB80KnsH/view)][[Video](https://www.youtube.com/watch?v=61abzUHhmfw&feature=youtu.be)]
- <a name="DiagNet"></a> **[DiagNet]** DiagNet: Bridging Text and Image [[Report](http://www-personal.umich.edu/~syqian/2019/diagnet/diagnet.pdf)][[Code](https://github.com/w-yi/DiagNet)]
- <a name="DCD-ZJU"></a> **[DCD_ZJU]** Winner of 2019 Text-VQA challenge [[Slides](https://drive.google.com/file/d/1EZ8jrLTPLLKfwi0K28zq89tTe3ZZ-X8j/view)]
- <a name="Schwail"></a> **[Schwail]** Runner-up of 2019 Text-VQA challenge [[Slides](https://drive.google.com/file/d/1xNiEHj6J42F3CFx6fYjS9KDTsYTqAlN0/view)]


## Benchmark
**Acc.** : Accuracy
**I. E.** : Image Encoder 
**Q. E.** : Question Encoder
**O. E.** : OCR Token Encoder
**Ensem.** : Ensemble


### Text-VQA

[[official leaderboard(2019)](https://evalai.cloudcv.org/web/challenges/challenge-page/244/leaderboard/810)]
[[official leaderboard(2020)](https://evalai.cloudcv.org/web/challenges/challenge-page/551/leaderboard/1575)]

| Y-C./J. | Methods| Acc. | I. E. |  Q. E. | OCR | O. E. | Output | Ensem. |
| ------- | ------ | ---- | ----- | -------| --- | ----- | ------ | ------ |
| 2019--CVPR | [LoRRA](#LoRRA) | 26.64 | Faster R-CNN | GloVe | [Rosetta-ml](https://arxiv.org/pdf/1910.05085.pdf) | FastText | Classification | N |
| 2019--N/A| [DCD_ZJU](#DCD-ZJU) | 31.44 | Faster R-CNN | BERT | Rosetta-ml | FastText | Classification | Y |
| 2020--CVPR | [M4C](#M4C) | 40.46 | Faster R-CNN (ResNet-101)| BERT | Rosetta-en | FastText | Decoder | N |
| 2020--Challenge | Xiangpeng | 40.77 |  |  | | | | |
| 2020--Challenge | colab_buaa | 44.73 | | | | | | |
| 2020--Challenge | CVMLP(SAM) | 44.80 | | | | | | |
| 2020--Challenge | [NWPU_Adelaide_Team(SMA)](#SMA) | 45.51 | Faster R-CNN | BERT | [BDN](https://arxiv.org/pdf/1912.09629.pdf) | Graph Attention | Decoder | N |
| 2020--ECCV| [SA-M4C](#SA-M4C) | 44.6* | Faster R-CNN (ResNext-152) | BERT | [Google-OCR](https://cloud.google.com/products/ai/) | FastText+PHOC | Decoder | N |
| 2020--arXiv| [TAP](#TAP) | 53.97* | Faster R-CNN (ResNext-152) | BERT | [Microsoft-OCR](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/concept-recognizing-text) | FastText+PHOC | Decoder | N |
| 2022--arXiv| [TAG](#TAG) | 53.63 | Faster R-CNN (ResNext-152) | BERT | [Microsoft-OCR](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/concept-recognizing-text) | FastText+PHOC | Decoder | N |

\* Using external data for training.


### ST-VQA

[[official leaderboard](https://rrc.cvc.uab.es/?ch=11&com=evaluation&task=1)] <br>
**T1** : Strongly Contextualised Task
**T2** : Weakly Contextualised Task
**T3** : Open Dictionary

| Y-C./J. | Methods| Acc. (T1/T2/T3) | I. E. |  Q. E. | OCR | O. E. | Output | Ensem. |
| ------- | ------ | --------------- | ----- | -------| --- | ----- | ------ | ------ |
| 2020--CVPR | [M4C](#M4C) | na/na/0.4621 | Faster R-CNN (ResNet-101) | BERT | [Rosetta-en](https://arxiv.org/pdf/1910.05085.pdf) | FastText | Decoder | N |
| 2020--Challenge | SMA | **0.5081**/**0.3104**/0.4659 | Faster | BERT | [BDN](https://arxiv.org/pdf/1912.09629.pdf) | Graph Attention | Decoder | N |
| 2020--ECCV | [SA-M4C](#SA-M4C) | na/na/**0.5042** | Faster R-CNN (ResNext-152) | BERT | [Google-OCR](https://cloud.google.com/products/ai/) | FastText+PHOC | Decoder | N |
| 2020--arXiv | [TAP](#TAP) | na/na/**0.5967** | Faster R-CNN (ResNext-152) | BERT | [Microsoft-OCR](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/concept-recognizing-text) | FastText+PHOC | Decoder | N |
| 2022--arXiv | [TAG](#TAG) | na/na/**0.6019** | Faster R-CNN (ResNext-152) | BERT | [Microsoft-OCR](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/concept-recognizing-text) | FastText+PHOC | Decoder | N |

### OCR-VQA

| Y-C./J. | Methods| Acc. | I. E. |  Q. E. | OCR | O. E. | Output | Ensem. |
| ------- | ------ | ---- | ----- | -------| --- | ----- | ------ | ------ |
| 2020--CVPR | [M4C](#M4C) | **63.9** | Faster R-CNN | BERT | Rosetta-en | FastText | Decoder | N |

