# DWDM21
Data Warehouse &amp; Data Mining 2021

นายวิฆเนศ เกียรติเกามสุข 623021055-6

Group Name : Numberone

1 **_นายวิฆเนศ เกียรติเกษมสุข 623021055-6_**

2 นางสาวเบญญาภา ระภูเขียว 623020527-6

3 นายศิริวัฒน์ ภูลำสัตย์ 623020765-0

4 นายธนิก พิมภิบาล 623021049-1

5 นางสาววนิสรา จงใจ 623021054-8

# สารบัญเนื้อหาวิชา Data Warehouse and Data Mining 2021

รายละเอียดของวิชา Data Warehouse & Data Mining คือ การกำหนดข้อมูลที่เหมาะสมในการ mining ดังนั้น Data mining จึงต้องการแหล่งข้อมูลที่มีการจัดเก็บและรวบรวมข้อมูลไว้อย่างดีและมีความมั่นคง เหตุผลที่ต้องมี Data warehouse ที่มีการจัดเก็บข้อมูลที่ดีสำหรับเตรียมข้อมูลเพื่อทำการ mining ก็คือ Data warehouse จะทำการจัดเก็บข้อมูลที่มีความมั่นคงและข้อมูลที่ได้ทำความสะอาดแล้ว ซึ่งการจัดเตรียมและรวบรวมข้อมูลเป็นสิ่งที่จำเป็นสำหรับการ mining ที่ต้องการความแน่ใจในความแม่นยำของ predictive models

## ทฤษฎี (เนื้อหา)

### 1. Chapter 1 [Introduction](https://github.com/Wikanes-k/DWDM21/blob/main/HW1.pdf)
* นิยามของ Data Mining
* ทำไมจึงต้องมี Data Mining
* เทคนิคในการทำ Data Mining
* ตัวอย่างของข้อมูล

### 2. Chapter 2 Getting to Know Your Data ประกอบด้วย 3 ส่วน ดังนี้
* [1 Data Objects and Attribute Types](https://github.com/Wikanes-k/DWDM21/blob/main/HW2.1.pdf)  
  * คุณสมบัติ, ตัวอย่างข้อมูล, ขนาดของข้อมูล, ชนิดของข้อมูล
* [2 Measuring Data Similarity and Dissimilarity](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%202.2.pdf)
  * ความเหมือน ความแตกต่าง และความใกล้เคียง ระหว่างระยะห่างของจุดสองจุด
  * ตัวอย่างในการคำนวณหาระยะห่างระหว่างจุดของข้อมูล
* [3 Binary Distance](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%202.3.pdf)
  * การวัดความใกล้เคียงสำหรับ Binary Attributes, ตัวอย่างความแตกต่างระหว่างตัวแปร Binary Variables, การวัดความแตกต่างสำหรับ Categorical Attributes,, สูตรการคำนวณ Symmetric binary และ Asymmetric binary

### 3. Chapter 3 Data [Preprocessing](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter3%20Data%20Preprocessing%20.pdf)
* Data Cleaning คืออะไร
* Data Integration คืออะไร
* Data Reduction and Tranformation คืออะไร
* Dimensionality Reduction คืออะไร

### 4. Chapter 6 [Mining Frequent Patterns, Association and Correlations:Basic Concepts and Methods](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%206.pdf) ประกอบด้วย 2 ส่วน ดังนี้
* 1.Besic Concepts 
  * Plot graph of Itemsets
  * การแก้ไขคอลัมน์ข้อมูล
  * Frequence Itemsets to Association Rule
* 2.Efficient Pattern Mining Methods
  * Apriori
  * Support

### 5. Chapter 8 Classification:Basic Concepts ประกอบด้วย 3 ส่วน ดังนี้
* [1 Classification: Basic Concepts](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%208.1.pdf)
  * การสร้างโมเดลแบบมีผู้สอน/การสร้างโมเดลแบบไม่มีผู้สอน
  * Classification (การสร้าง model เพื่อนำ feature มาใช้ในการทำนายคำตอบ)
  * Decision Tree Induction (การทำนายโดยใช้วิธีต้นไม้ตัดสินใจ)
  * ตัวอย่างการคำนวณ
* [2 Lecture Decision Tree](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%208.2.pdf)
  * Decision Tree Induction: Algorithm
  * Overfitting and Tree Prunning (ตัดแต่งกิ่งต้นไม้)
* [3  Bayes Classification](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%208.3.pdf)
  * วิธีการ Training Datasets ของ Naïve Bayes Classifier
  * ตัวอย่างการคำนวณ
  * Chapter 9 Lazy Learner:Instance-Based Mathods
  * Lazy Learner คืออะไร?
  * วิธีการหาค่า K-NN (K-nearest neighbors)

### 6. Chapter 9 [Neural Network](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%209.pdf)
* องค์ประกอบของ Perceptron
* ตัวอย่าง และผลการเรียนฟังก์ชัน AND และ XOR ด้วยกฏ Perceptron
* การหาค่า Procision, Recall and F-measures
* ตัวอย่างการคำนวณ

### 7. Chapter 10 [Cluster Analysis:Basic Concepts and Methods](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter%2010.pdf)
* K-Means คืออะไร
* ตัวอย่างการคำนวณหาค่า K-Means
* Dendrogram (การทำ Clustering แบบลำดับชั้น)
* วิธีการวัดแบ่งออกเป็น External & Internal
* Internal Measures: BetaCV Measure (กรณีที่ไม่รู้คำตอบ)

## ปฏิบัติ (Google Colab)

### 1. Chapter 2 ประกอบด้วย 4 ส่วน ดังนี้
* [Basic Python](https://github.com/Wikanes-k/DWDM21/blob/main/Data101(Chapter2).ipynb)
  * Basic Python
    * variables
  * Casting
    * int() float() str()
  * Data Structure
    * list()
  * Loop
  * Condition
    * เงื่อนไข if statement
  * Function
* [Data Exploration](https://github.com/Wikanes-k/DWDM21/blob/main/Data102(Chapter2).ipynb)
  * Besic Data
  * การตรวจสอบตารางข้อมูลโดยใช้ .head()&.tail()
  * Boxplot
  * Time Series Plot
* [Data Visualization](https://github.com/Wikanes-k/DWDM21/blob/main/Data_Visualization.ipynb)
  * Scatter plot
  * Plot
  * Bar chart
    * Grouped Barchart
    * Stacked Barchart
  * Histogram
* [Distance_Numpy](https://github.com/Wikanes-k/DWDM21/blob/main/Distance_Numpy.ipynb)
  * Numpy Array
    * สร้าง numpy array (matrix)
    * สร้าง matrix เริ่มต้น (zeros, ones)
    * สร้าง matrix random
    * matrix properties
    * Useful functions
    * วนลูปเอง
    * summation
    * Distance Matrix
    * Euclidean Distance (L2-norm)
    * Distance function
    * Manhattan Distance (L1-norm)
    * Distance of Binary Value

### 2. Chapter 3 [Data Preprocessing](https://github.com/Wikanes-k/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb)

* Meta Data (Data ที่ใช้อธิบาย Data)
  * การชี้ข้อมูลในตาราง
    * ชี้แบบธรรมดาใช้ [ชื่อคอลัมน์][index]
    * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
  * Missing Value
    * Handle Missing Value 1 (ลบค่า Missing)
    * Handle Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
    * Handle Missing Value 2
    * Handle Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
    * Handle Missing Value 4 (แทนด้วยค่ากลาง)
    * Handling Missing Value 5 (แทนด้วย column ใกล้เคียง)
  * Select data by values [Pandas]
    * ใช้ and(&) และ or (|) ในการรวม list ของ boolean
    * การต่อตารางแนวแกน Y [PD]
    * การเรียงข้อมูล[PD]
    * Outlier
  * การรวม 2 ตารางโดยใช้ .merge()
  * Group by (pandas)
  * [PD] save ตารางเอาไปใช้ที่อื่น
  * [PD]การสร้างตาราง

### 3. Chapter 5 [Association Rules](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
* การลบ records ที่ถูก cancel ออก
* การเตรียม Data สำหรับ (Fequence Pattern) Association Rule
* Apriori
* หา K-Itemsets

### 4. Chapter 6 Classification ประกอบด้วย 3 ส่วน ดังนี้
* [1. Classification Decision Tree](https://github.com/Wikanes-k/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
  * Load data
  * Train Model
  * Plot tree
  * Evaluation
  * Advanced Tree
  * Test
* [2 Classification k-Nearest Neighbor & Neural Networks](https://github.com/Wikanes-k/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
  * Load data
  * Split data
  * Train Model
    * Import
    * KNN1
    * KNN2
    * KNN3 
  * Retrain & Evaluation
  * Neural Network
    * mport
    * Define
    * Train-Test
    * ANN2
    * ANN3
* [3 Classification Evaluation](https://github.com/Wikanes-k/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
  * Load data
  * การแบ่ง data
  * สร้าง Model ทำนาย
    * Import
    * Define
    * Train
    * Evaluation

### 5. Chapter 7 [Clustering](https://github.com/Wikanes-k/DWDM21/blob/main/Chap8_Clustering.ipynb)
* K-Means
  * Generate data
  * Explore data
  * Clustering
    * import
    * Define
    * Fit-Predict
    * 3 Cluster
    * 4 Cluster
    * 5 Cluster
  * Example Application(Color Quantization)
    * นับจำนวนสี
    * จัดกลุ่มสี
    * ใช้ Centroid เป็นตัวแทนสี
* Hierachicla Clustering (เว็บไซท์เพิ่มเติม)
* Clustering Evaluation (เว็บไซท์เพิ่มเติม)

## Mid Term 
* [MiniExam](https://github.com/Wikanes-k/DWDM21/blob/main/MiniExam.ipynb)

## Project
* [Project1](https://github.com/Wikanes-k/DWDM21/blob/main/Project1.ipynb)
* [Project Final](https://github.com/Wikanes-k/DWDM21/blob/main/Project_Final.ipynb)
* [ไฟล์นำเสนอ Group Project](https://github.com/Wikanes-k/DWDM21/blob/main/Project_NUMBERONE.pdf)

## [เพิ่มเติม](https://docs.google.com/document/d/1gxgPQU0sq0pV34_oa4qslCBHmpNDDQ9nwIbFotZvpX8/edit?usp=sharing)

## FINISH 
