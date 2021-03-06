# Simple-Red-wine-quality-prediction

![alt text](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/Images/red-wine.jpg)

## Overview

ในเวลาไม่นานมานี้อุตสาหกรรมไวน์แดงมีการเติบโตอย่างรวดเร็ว เนื่องจากการดื่มไวน์เพื่อเข้าสังคมกำลังเป็นที่นิยมเป็นอย่างสูง ปัจจุบันผู้ผลิตในอุตสาหกรรมจะใช้การรับรองคุณภาพผลิตภัณฑ์เพื่อโปรโมตผลิตภัณฑ์ของตนเอง ซึ่งเป็นกระบวนการที่ใช้เวลานานและต้องมีการประเมินโดยผู้เชี่ยวชาญที่เป็นมนุษย์ ทำให้กระบวนการนี้มีราคาที่สูงมาก หากผู้ผลิตต้องการที่จะลดต้นทุนที่มีราคาสูงจากกระบวนการข้างต้นที่กล่าวมาสามารถใช้ machine learning เข้ามาช่วยในการบวนการได้และยังลดต้นทุนได้อีกด้วย

## Dataset Sources

- Wine Quality Data set. ทางผู้จัดทำได้ dataset มาจากเว็บไซต์นี้ (https://archive.ics.uci.edu/ml/datasets/wine+quality)

## Dataset Description

- fixed acidity : เป็นกรดไม่ระเหย(non-volatile acids) ที่ไม่ระเหยโดยง่าย
- volatile acidity : เป็นกรดอะซิติกสูงในไวน์ซึ่งนำไปสู่รสเปรี้ยวที่ไม่พึงประสงค์
- citric acid : เป็นกรดอินทรีย์อ่อน พบในผลไม้รสเปรี้ยวตามธรรมชาติ
- residual sugar : คือปริมาณน้ำตาลที่เหลืออยู่หลังจากการหมักสิ้นสุดลง โดยกุญแจที่คือสำคัญต้องมีความสมดุลระหว่างความหวานและความเปรี้ยว หากพบว่าในไวน์มีปริมาณน้ำตาลดังกล่าวมากกว่า 45 กรัมต่อไวน์ 1 ลิตร จะทำให้ไวน์นั้นมีรสชาติที่หวาน
- chlorides : ปริมาณเกลือในไวน์
- free sulfur dioxide : ช่วยป้องกันการเจริญเติบโตของจุลินทรีย์และการเกิดออกซิเดชันของไวน์
- total sulfur dioxide : ซัลเฟอร์ไดออกไซด์ทั้งหมดที่มีอยู่ในไวน์
- density : ไวน์ที่หวานมักจะมีความหนาแน่นที่สูงกว่า
- pH : ระดับความเป็นกรด
- sulphates : ซัลไฟต์ที่เพิ่มเข้ามาช่วยรักษาความสดและปกป้องไวน์จากการเกิดออกซิเดชันและแบคทีเรีย
- alcohol : เปอร์เซ็นต์ของแอลกอฮอล์ที่มีอยู่ในไวน์

## Install Dependencies

```
    pip install numpy==1.19.5
    pip install pandas==1.1.5
    pip install sklearn==0.24.2
```

## How to use this project

### 1. ทำการ clone repository นี้ไปยังเครื่องของคุณ

### 2. ทำการ pull request

### 3. ขอให้โชคดีกับการใข้การใช้งานโปรเจ็คนี้ Good Luck !!!

## Accuracy Results

| Model Classification | Train data Accuracy | Test data Accuracy |
| -------------------- | :-----------------: | :----------------: |
| Decision Tree        |       `100.0`       | 60.62499999999999  |
| K- Nearest Neighbor  |  63.95621579358875  |      48.4375       |
| Logistic Regression  | 59.030492572322125  | 55.00000000000001  |
| Naive Bayes          |  55.98123534010946  |      57.1875       |
| Neural Network       |  60.2814698983581   | 58.12500000000001  |
| Random Forest        |       `100.0`       |     `69.6875`      |

## Precision Results

| Model Classification | Train data Precision | Test data Precision |
| -------------------- | :------------------: | :-----------------: |
| Decision Tree        |       `100.0`        | 60.677322686887244  |
| K- Nearest Neighbor  |  68.71773838978423   |  54.32444852941176  |
| Logistic Regression  |  70.97354843839106   |  65.88249655330883  |
| Naive Bayes          |  55.45985682390634   |  56.49724264705882  |
| Neural Network       |  69.39642267139773   |  67.96734260110293  |
| Random Forest        |       `100.0`        | `73.29771752450979` |

## Recall Results

| Model Classification | Train data Recall  | Test data Recall  |
| -------------------- | :----------------: | :---------------: |
| Decision Tree        |      `100.0`       | 60.62499999999999 |
| K- Nearest Neighbor  | 63.95621579358875  |      48.4375      |
| Logistic Regression  | 59.030492572322125 | 55.00000000000001 |
| Naive Bayes          | 55.98123534010946  |      57.1875      |
| Neural Network       |  60.2814698983581  | 58.12500000000001 |
| Random Forest        |      `100.0`       |     `69.6875`     |

## F1 Results

| Model Classification |   Train data F1    |    Test data F1     |
| -------------------- | :----------------: | :-----------------: |
| Decision Tree        |      `100.0`       | `41.41571596451014` |
| K- Nearest Neighbour | 40.05819219760352  | 20.444080940264143  |
| Logistic Regression  | 22.315537953781217 |  20.17310989436425  |
| Naive Bayes          | 36.204571545566296 |  32.4281622614489   |
| Neural Network       | 26.500368627827132 | 23.366858352782653  |
| Random Forest        |      `100.0`       |  41.31967622764521  |

## References

1. [Heart Disease Prediction](https://colab.research.google.com/drive/1FYGPRSEGvd0urNlZmRJHx-gq6ANn3IpX?usp=sharing#scrollTo=OHmcP7DJsSEP)

2. [Red Wine Quality Prediction Using Regression Modeling and Machine Learning](https://towardsdatascience.com/red-wine-quality-prediction-using-regression-modeling-and-machine-learning-7a3e2c3e1f46)

3. [Wine Quality Prediction Using Machine Learning](https://www.analyticsvidhya.com/blog/2021/04/wine-quality-prediction-using-machine-learning/)

4. [HeartDisease-NaiveBayes-SVM](https://github.com/arnavgarg123/HeartDisease-NaiveBayes-SVM)
