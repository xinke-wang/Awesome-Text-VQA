# Awesome Text VQA

Text related VQA is a fine-grained direction of the VQA task, which only focuses on the question that requires to read the textual content shown in the input image.

## Datasets
- **Text-VQA** dataset (CVPR 2019) [[Project](https://textvqa.org/dataset)][[Paper](https://arxiv.org/abs/1904.08920)]
- **ST-VQA** dataset (ICCV 2019) [[Project](https://rrc.cvc.uab.es/?ch=11)][[Paper](https://arxiv.org/abs/1905.13648)]
- **OCR-VQA** dataset (ICDAR 2019) [[Project](https://ocr-vqa.github.io/)][[Paper](https://anandmishra22.github.io/files/mishra-OCR-VQA.pdf)]

## Papers

### 2019
- <a name="LoRRA"></a> **[Text-VQA/LoRRA]** Towards VQA Models That Can Read (**CVPR**) [[Paper](https://arxiv.org/abs/1904.08920)][[Code](https://github.com/facebookresearch/pythia)]
- <a name="ST-VQA"></a> **[ST-VQA]** Scene Text Visual Question Answering (**ICCV**) [[Paper](https://arxiv.org/abs/1905.13648)]
- <a name="Text-KVQA"></a>  **[Text-KVQA]** From Strings to Things: Knowledge-enabled VQA Modelthat can Read and Reason (**ICCV**) [[Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Singh_From_Strings_to_Things_Knowledge-Enabled_VQA_Model_That_Can_Read_ICCV_2019_paper.pdf)]
- <a name="OCR-VQA"></a> **[OCR-VQA]** OCR-VQA: Visual Question Answering by Reading Text in Images (**ICDAR**) [[Paper](https://anandmishra22.github.io/files/mishra-OCR-VQA.pdf)]


### Technical Reports

- <a name="M4C"></a> **[M4C]** Iterative Answer Prediction with Pointer-AugmentedMultimodal Transformers for TextVQA [[Report](https://arxiv.org/abs/1911.06258)]
- <a name="DiagNet"></a> **[DiagNet]** DiagNet: Bridging Text and Image [[Report](http://www-personal.umich.edu/~syqian/2019/diagnet/diagnet.pdf)][[Code](https://github.com/w-yi/DiagNet)]
- <a name="DCD-ZJU"></a> **[DCD_ZJU]** Winner of 2019 Text-VQA challenge [[Slides](https://drive.google.com/file/d/1EZ8jrLTPLLKfwi0K28zq89tTe3ZZ-X8j/view)]
- <a name="Schwail"></a> **[Schwail]** Runner-up of 2019 Text-VQA challenge [[Slides](https://drive.google.com/file/d/1xNiEHj6J42F3CFx6fYjS9KDTsYTqAlN0/view)]


## Benchmark
**Acc.** : Accuracy
**I. E.** : Image Encoder 
**Q. E.** : Question Encoder
**O. E.** : OCR Token Encoder
**Ensem.** : Ensemble

**Only methods that have public available paper/code/description are listed here**

### Text-VQA

| Y-C./J. | Methods| Acc. | I. E. |  Q. E. | OCR | O. E. | Output | Ensem. |
| ------------------- | ---------- | ----- | ------------ | --------------| ------ | ----------- | --------- | ---------- |
| 2019--CVPR | [LoRRA](#LoRRA) | 26.64 | Faster R-CNN | GloVe | Rosetta-ml | FastText | Classification | N |
| 2019--N/A| [DCD_ZJU](#DCD-ZJU) | 31.44 | Faster R-CNN | BERT | Rosetta-ml | FastText | Classification | Y |
| 2019--arXiv | [M4C](#M4C) | **40.46** | Faster R-CNN | BERT | Rosetta-en | FastText | Decoder | N |

### ST-VQA
**T1** : Strongly Contextualised Task
**T2** : Weakly Contextualised Task
**T3** : Open Dictionary

| Y-C./J. | Methods| Acc. (T1/T2/T3) | I. E. |  Q. E. | OCR | O. E. | Output | Ensem. |
| ------------------- | ---------- | ----- | ------------ | --------------| ------ | ----------- | --------- | ---------- |
| 2019--arXiv | [M4C](#M4C) | **na/na/0.4621** | Faster R-CNN | BERT | Rosetta-en | FastText | Decoder | N |

### OCR-VQA

| Y-C./J. | Methods| Acc. | I. E. |  Q. E. | OCR | O. E. | Output | Ensem. |
| ------------------- | ---------- | ----- | ------------ | --------------| ------ | ----------- | --------- | ---------- |
| 2019--arXiv | [M4C](#M4C) | **63.9** | Faster R-CNN | BERT | Rosetta-en | FastText | Decoder | N |

