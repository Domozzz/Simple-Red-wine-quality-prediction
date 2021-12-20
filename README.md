# Simple-Red-wine-quality-prediction

![alt text](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/Images/red-wine.jpg)

## ภาพรวม

ในเวลาไม่นานมานี้อุตสาหกรรมไวน์แดงมีการเติบโตอย่างรวดเร็ว เนื่องจากการดื่มไวน์เพื่อเข้าสังคมกำลังเป็นที่นิยมเป็นอย่างสูง ปัจจุบันผู้ผลิตในอุตสาหกรรมจะใช้การรับรองคุณภาพผลิตภัณฑ์เพื่อโปรโมตผลิตภัณฑ์ของตนเอง ซึ่งเป็นกระบวนการที่ใช้เวลานานและต้องมีการประเมินโดยผู้เชี่ยวชาญที่เป็นมนุษย์ ทำให้กระบวนการนี้มีราคาที่สูงมาก หากผู้ผลิตต้องการที่จะลดต้นทุนที่มีราคาสูงจากกระบวนการข้างต้นที่กล่าวมาสามารถใช้ machine learning เข้ามาช่วยในการบวนการได้และยังลดต้นทุนได้อีกด้วย

## Dataset

dataset ที่ใช้สำหรับงานนี้ [ดาวน์โหลดไฟล์ที่นี่](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv) </br>
หมายเหตุ : dataset จาก link ข้างบนยังไม่สามารถที่จะนำไปใช้งานได้ ต้องผ่านขั้นตอนการทำ data preparation ก่อนที่จะนำไปใช้งาน หากต้องการไฟล์ dataset ที่พร้อมใช้งานเลย [ดาวน์โหลดไฟล์ที่นี่](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/RedWine-Dataset/Redwine.csv)

## คำอธิบายของ Dataset

- fixed acidity : เป็นกรดไม่ระเหย(non-volatile acids) ที่ไม่ระเหยโดยง่าย
- volatile acidity : เป็นกรดอะซิติกสูงในไวน์ซึ่งนำไปสู่รสเปรี้ยวที่ไม่พึงประสงค์
- citric acid : เป็นกรดอินทรีย์อ่อน พบในผลไม้รสเปรี้ยวตามธรรมชาติ
- residual sugar : คือปริมาณน้ำตาลที่เหลืออยู่หลังจากการหมักสิ้นสุดลง โดยกุญแจที่สำคัญต้องมีความสมดุลระหว่างความหวานและความเปรี้ยว (wines > 45g/ltrs are sweet)
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

## Accuracy Results

| Model Training      | Train data accuracy | Train data accuracy |
| ------------------- | ------------------- | ------------------- |
| Logistic Regression | 0.581704456606724%  | 0.6%                |
| Neural Network      | 0.6012509773260359% | 0.5625%             |
| Decision Tree       | 100%                | 0.640625%           |

d
