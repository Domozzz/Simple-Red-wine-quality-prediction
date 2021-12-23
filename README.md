# Simple-Red-wine-quality-prediction

![alt text](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/Images/red-wine.jpg)

## Overview

ในเวลาไม่นานมานี้อุตสาหกรรมไวน์แดงมีการเติบโตอย่างรวดเร็ว เนื่องจากการดื่มไวน์เพื่อเข้าสังคมกำลังเป็นที่นิยมเป็นอย่างสูง ปัจจุบันผู้ผลิตในอุตสาหกรรมจะใช้การรับรองคุณภาพผลิตภัณฑ์เพื่อโปรโมตผลิตภัณฑ์ของตนเอง ซึ่งเป็นกระบวนการที่ใช้เวลานานและต้องมีการประเมินโดยผู้เชี่ยวชาญที่เป็นมนุษย์ ทำให้กระบวนการนี้มีราคาที่สูงมาก หากผู้ผลิตต้องการที่จะลดต้นทุนที่มีราคาสูงจากกระบวนการข้างต้นที่กล่าวมาสามารถใช้ machine learning เข้ามาช่วยในการบวนการได้และยังลดต้นทุนได้อีกด้วย

## Dataset

dataset ที่ใช้สำหรับงานนี้ [ดาวน์โหลดไฟล์ที่นี่](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv) </br>
หมายเหตุ : dataset จาก link ข้างบนยังไม่สามารถที่จะนำไปใช้งานได้ ต้องผ่านขั้นตอนการทำ data preparation ก่อนที่จะนำไปใช้งาน หากต้องการไฟล์ dataset ที่พร้อมใช้งานเลย [ดาวน์โหลดไฟล์ที่นี่](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/RedWine-Dataset/Redwine.csv)

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
    pip install numpy
    pip install pandas
    pip install sklearn
```

## How to use this project

### 1. ทำการ clone repository นี้ไปยังเครื่องของคุณ

### 2. ทำการ pull request

### 3. ขอให้โชคดีกับการใข้การใช้งานโปรเจ็คนี้ Good Luck !!!

## Correlation Matrix

![alt text](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/Images/Correlation%20Matrix.jpg)

## Methodology (รอเพิ่มรายละเอียด)

### 1. Data preparation

### 2. Splitting the Features and Target

### 3. Splitting the Data into Training data & Test Data

### 4. Model Training

### 5. Model Evaluation

### 6. Testing Prediction system

## Accuracy Results

| Model Classification | Train data Accuracy | Test data Accuracy |
| -------------------- | ------------------- | ------------------ |
| Decision Tree        | 100.0               | 60.62499999999999  |
| K- Nearest Neighbor  | 63.95621579358875   | 48.4375            |
| Logistic Regression  |                     |                    |
| Naive Bayes          |                     |                    |
| Neural Network       |                     |                    |
| Random Forest        |                     |                    |

## Precision Results

| Model Classification | Train data Precision | Test data Precision |
| -------------------- | -------------------- | ------------------- |
| Decision Tree        | 100.0                | 60.677322686887244  |
| K- Nearest Neighbor  | 68.71773838978423      54.32444852941176               |                     |
| Logistic Regression  |                      |                     |
| Naive Bayes          |                      |                     |
| Neural Network       |                      |                     |
| Random Forest        |                      |                     |

## Recall Results

| Model Classification | Train data Recall | Test data Recall  |
| -------------------- | ----------------- | ----------------- |
| Decision Tree        | 100.0             | 60.62499999999999 |
| K- Nearest Neighbor  |                   |                   |
| Logistic Regression  |                   |                   |
| Naive Bayes          |                   |                   |
| Neural Network       |                   |                   |
| Random Forest        |                   |                   |

## F1 Results

| Model Classification | Train data F1 | Test data F1      |
| -------------------- | ------------- | ----------------- |
| Decision Tree        | 100.0         | 41.41571596451014 |
| K- Nearest Neighbor  |               |                   |
| Logistic Regression  |               |                   |
| Naive Bayes          |               |                   |
| Neural Network       |               |                   |
| Random Forest        |               |                   |
