# Merge Sort(合併排序法)
## 簡介
- Merge Sort屬於Divide and Conquer演算法，把問題先拆解成子問題，並在逐一處理子問題後，將子問題的結果合併，如此便解決了原先的問題。

## 流程
![](https://github.com/alrightchiu/SecondRound/blob/master/content/Algorithms%20and%20Data%20Structures/Sorting%20series/ComparisonSort_fig/MergeSort/f1.png?raw=true)
- 以上圖為例，要把數列{5,3,8,6,2,7,1,4}排序成{1,2,3,4,5,6,7,8}，Merge Sort的方法為：

  - Divide：把數列「對半拆解」成兩個小數列。
    - 先把{5,3,8,6,2,7,1,4}分成{5,3,8,6}與{2,7,1,4}。
    - 再把{5,3,8,6}分解成{5,3}與{8,6}。
    - {2,7,1,4}分解成{2,7}與{1,4}。
    - 依此類推，直到每個數列剩下一個元素。
  - Conquer：按照「由小到大」的順序，「合併」小數列。
    - 考慮數列{5}與{3}，比較大小後，合併成數列{3,5}。
    - 考慮數列{8}與{6}，比較大小後，合併成數列{6,8}。
    - 考慮數列{3,5}與{6,8}，比較大小後，合併成數列{3,5,6,8}。
    - 依此類推，最後，考慮數列{3,5,6,8}與{1,2,4,7}，比較大小後，合併成數列{1,2,3,4,5,6,7,8}。
- 即完成Merge Sort。

## [程式碼](https://github.com/yulin871030/my-learning-note/blob/master/HW2/mergesort_06170131.py)

## 參考資料
- https://alrightchiu.github.io/SecondRound/comparison-sort-merge-sorthe-bing-pai-xu-fa.html
- https://emn178.pixnet.net/blog/post/87965707
