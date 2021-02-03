# Data_Mining_2019_HW1
用 python 對 mushrooms.csv 進行 Supervised learning 中的 Naïve Bayes分析  
1.先讀取 mushrooms.csv，再來看檔案中共有多少筆資料、每個欄位的資料型態、是否有空值存在以及佔據多少記憶體 
![image](https://github.com/Alan-alan-Lin/Data_Mining_2019_HW1/blob/main/HW1/py_1.JPG)  
2.看資料集的平均值、分佈情況、是否有資料傾斜的問題，再來就是切分input和output
![image](https://github.com/Alan-alan-Lin/Data_Mining_2019_HW1/blob/main/HW1/py_2.JPG)  
3.將屬性轉為數字的label，再將屬性合併變成list，最後再轉為array
![image](https://github.com/Alan-alan-Lin/Data_Mining_2019_HW1/blob/main/HW1/py_3.JPG)  
4.訓練集訓練模型，再利用 metrics.classification_report()列出模型的準確率
![image](https://github.com/Alan-alan-Lin/Data_Mining_2019_HW1/blob/main/HW1/py_4.JPG)  
