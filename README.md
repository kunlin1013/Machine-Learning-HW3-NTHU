# Machine-Learning-HW3-NTHU

假設資料的分布如下圖所示，則期望找到迴歸線的參數有斜率(W)及偏差(b)，此迴歸線根據課本將其表示成y(x,w)，其中x代表著特徵向量，而w則代表擬合的多項式參數，但擬合出來的曲線並不會完美的與資料的分布重疊，故在假設模型的函數時，會加上一個平均值為0、標準差為β^(-1)的高斯雜訊ϵ，即t=y(x,w)+ϵ，且雜訊的probability distribution則可以表達成p(t|x,w,β)=N(t|y(x,w),β^(-1))，詳細推導請見HW3_111061528_Programming.pdf。

![image](https://github.com/kunlin1013/Machine-Learning-HW3-NTHU/assets/78029945/7c6b337c-a39a-441f-8a37-30e8b7f4cb12)

## HW3.ipynb
HW3.py : HW3的程式檔案

## 函示庫版本
numpy                     1.17.0

pandas                    1.1.3

matplotlib                3.3.2

lightgbm                  3.3.5

scikit-learn              1.0.2

有了以上函示庫，還須將calories.csv、exercise.csv這兩個資料集放在與HW3.ipynb同個資料夾路徑下，即可執行程式碼。

## HW3_111061528_Programming.pdf
HW3詳細作法，裡面標題1、2、3、4分別對應到Part 2. Programming assignment中的1~4小題。

## HW3_111061528_Handwriting.pdf
HW3中證明題之詳細作法
