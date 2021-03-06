# Insertion Sort
## 概念
* 想像手上有一副撲克牌，若想要將紙牌從左到右按照「小到大」排序。
  Insertion Sort的方法為：將第i張紙牌加入「前i−1張排序過」的紙牌組合，得到i張排序過的紙牌組合。
  
  
## 步驟
1. 第一個(最左邊)的數字直接做為已排序的頭。
1. 將下一個值(右邊)作為基準值。
1. 與所有已排序中的數字比對(右->左)。
1. 移動所有比基準值大的數字。
1. 插入基準值。
1. 回到第2個步驟。

![](images/insertionsort.png)

## [程式碼](code/Insertion_Sort.py)


## 參考資料
- http://alrightchiu.github.io/SecondRound/comparison-sort-insertion-sortcha-ru-pai-xu-fa.html
- http://notepad.yehyeh.net/Content/Algorithm/Sort/Insertion/1.php
