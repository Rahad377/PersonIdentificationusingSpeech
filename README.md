# <p align=center> This repository complements our research paper [Bangla Speech-Based Person Identification Using LSTM Networks](https://link.springer.com/chapter/10.1007/978-3-031-34619-4_29), published in Springer.
**Rahad Khan, Saddam Hossain, Akbor Hossain, Fazlul Hasan Siddiqui & Sabah Binte Noor**
---
This repo is the official implementation of **Bangla Speech-Based Person Identification Using LSTM Networks**.

## Abstract
The Iris, face, fingers, conduct, voice, and other things of the human body are employed for security and identification since they are unique in each person. Biometric systems are popular and widely used in Bangladesh to identify people, e.g. in cybercrime. Apart from biometrics, a person can be identified by their voice. Since each person’s speech has a distinct timbre, vocal pattern, and frequency spectrogram. A human can easily identify the voice of a known person, but it is difficult for a machine. As a result, researchers are interested in processing human voices and recognizing them by machines. To predict the human voice, various traditional machine learning models such as GMM, HMM, SVM, and MLP are used. Voice data is a complex time-series signal and massive datasets are required to train ML models. As a result, traditional ML has low accuracy and takes a long time to train. In contrast, LSTM neural networks, which are the branch of ML, require less time to train a model with high accuracy. This paper focuses on an LSTM network for identifying a person based on Bangla speech because the Bangla language has 50 alphabets and their pronunciation differs from other languages such as English and Chinese. We extracted features from Bangla Voice using MFCCs. Our proposed model’s performance is measured using the K-fold validation, accuracy, precision, recall, and F1 score. Experimental results of our proposed model achieved a high recognition accuracy of 99.98%.

## Citation
If you find this project useful in your research, please consider cite:
```
@inproceedings{khan2022bangla,
  title={Bangla Speech-Based Person Identification Using LSTM Networks},
  author={Khan, Rahad and Hossain, Saddam and Hossain, Akbor and Siddiqui, Fazlul Hasan and Noor, Sabah Binte},
  booktitle={International Conference on Machine Intelligence and Emerging Technologies},
  pages={358--370},
  year={2022},
  organization={Springer}
}
```
