# DWDM21
Data Warehouse &amp; Data Mining 2021

รหัสนักศึกษา 623020514-5

ชื่อกลุ่ม : Natasha Romanoff

1.623020514-5	จุฑากาญจน์ ชิงจันทร์

2.623021047-5	ฐิติวัฒน์ จันทรเสนา

3.623021042-5	ขนิษฐา ภูโสภา

4.623021043-3	จิตติยา ศิริธรรมจักร

5.623021046-7	ชนกานต์ พูลผล

#สารบัญเนื้อหา

วิชา Data Mining and Data Warehouse

* บทที่ 1 [Introduction ]

  > สไลด์สรุปบทที่ 1 [slide unit 1](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%9A%E0%B8%97-1.pdf)

* บทที่ 2 Data Object and Attribute Type

  > สไลด์สรุปบที่ 2 [slide unit 2](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B-chapter2.pdf)
  
* บทที่ 3 [Data Preprocessing](https://github.com/623020514-5/DWDM21/blob/main/Data_Preprocessing(Chapter3).ipynb)

  * Meta Data
  * การจัดการข้อมูลในตารางก่อนนำไปวิเคราะห์
    * การชี้ข้อมูลในตาราง
      * ชี้แบบธรรมดา
      * ชี้แบบ .iloc[
    * Missing Value
      * Handle Missing Value 1 (ลบค่า Missing)
      * Handle Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
      * Handle Missing Value 2
      * Handle Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handle Missing Value 4 (แทนด้วยค่ากลาง)
      * Handling Missing Value 5 (แทนด้วย column ใกล้เคียง)
    * PANDA
      * Select data by values [PD]
      * ใช้ & (and) และ | (or) ในการรวม list ของ boolean
    * Quiz 4
      * การต่อตารางแนวแกน Y [PD]
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
      * การเรียงข้อมูล[PD]
      * utlier
    * Quiz 5
      * Pandas' looping(.iterrows)
    * การรวม 2 ตารางโดยใช้ .merge()
      * Group by (pandas)
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD]การสร้างตาราง
      

  > สไลด์สรุปบทที่ 3 [slide unit 3](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%203.pdf)

* บทที่ 4 [Data Warehousing and On-line Anaalytical Processing]

  > สไลด์สรุปบทที่ 4 [slide unit 4](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%204.pdf)

* บทที่ 6 [Association_Rules](https://github.com/623020514-5/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
  * ความหมาย
  * Besic Concepts
    * Plot graph of Itemsets
    * การแก้ไขคอลัมน์ข้อมูล
    * Frequence Itemsets to Association Rule
  * Efficient Pattern Mining Methods
    * Apriori
    * Support

  > สไลด์สรุปบทที่ 6 [slide unit 6](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88-6.pdf)

* บทที่ 7 Classification ประกอบด้วยสามหัวข้อ ดังนี้
  * [Desition Tree](https://github.com/623020514-5/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    * Train Model
    * plot tree
    * Evaluation
    * Random
    * Advanced Tree
    * TEST
  * [KNN](https://github.com/623020514-5/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
    * Split Data
    * Train Model
    * Retrain & Evaluate
    * Neural Network
  * [Evaluation](https://github.com/623020514-5/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
    * Split Data หรือ แบ่ง Data
    * สร้าง Model ทำนาย
    * Evaluation
  
  > [สรุปย่อย และการบ้านบทที่ 7 ](https://github.com/623020514-5/DWDM21/blob/main/ch7.pdf)


  > สไลด์สรุปบทที่ 7 [slide unit 7](https://github.com/623020514-5/DWDM21/blob/93929a954ee7a6030f1264e5337772a9b4883195/%E0%B8%AA%E0%B9%84%E0%B8%A5%E0%B8%94%E0%B9%8C%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%207.pdf)

* บทที่ 8 [Clustering](https://github.com/623020514-5/DWDM21/blob/main/Chap_8_Clustering.ipynb)
  * K-means
    * Generate Data
    * Clustering
    * Example Application (Color Quantization)
    * การนับจำนวนสี

  > สไลด์สรุปบทที่ 8.1 [slide unit 8.1](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%AA%E0%B9%84%E0%B8%A5%E0%B8%94%E0%B9%8C%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%208.1.pdf)

  > สไลด์สรุปบทที่ 8.2 [slide unit 8.2](https://github.com/623020514-5/DWDM21/blob/main/%E0%B8%AA%E0%B9%84%E0%B8%A5%E0%B8%94%E0%B9%8C%E0%B8%8A%E0%B8%B5%E0%B8%97%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%208.2.pdf)

* โครงงานกลุ่ม [Project](https://github.com/623020514-5/DWDM21/blob/main/Project.ipynb)
  * สไลด์นำเสนอ [Slide Present](https://github.com/623020514-5/DWDM21/blob/main/Project.pdf)


