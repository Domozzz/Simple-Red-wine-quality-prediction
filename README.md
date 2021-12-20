# Simple-Red-wine-quality-prediction

![alt text](https://github.com/Domozzz/Simple-Red-wine-quality-prediction/blob/main/Images/red-wine.jpg)

## ภาพรวม

อุตสาหกรรมไวน์แดงแสดงให้เห็นถึงการเติบโตแบบทวีคูณเมื่อเร็ว ๆ นี้เนื่องจากการดื่มเพื่อเข้าสังคมกำลังเพิ่มขึ้น ปัจจุบันผู้เล่นในอุตสาหกรรมจะใช้การรับรองคุณภาพผลิตภัณฑ์เพื่อโปรโมตผลิตภัณฑ์ของตนนี่เป็นกระบวนการที่ใช้เวลานานและต้องมีการประเมินโดยผู้
เชี่ยวชาญที่เป็นมนุษย์ซึ่งทำให้กระบวนการนี้มีราคาที่สูงมาก

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

## Dependencies
