# Minimum Spanning Tree-Kruskal

## MST 簡介
- 在無向圖中，連通且不含環的圖稱為樹（Tree）。給定無向圖G=(V,E)，連線G中所有的點，且邊集是E的子集的樹稱為G的生成樹（spanning Tree），而權值最小的生成樹稱為最小生成樹（Minimal Spanning Tree，MST）。
 
## Kruskal
- Kruskal演算法是一種用來尋找最小生成樹的演算法，目的是找出可連結所有點且具最小權重總和的樹
  - 步驟1–>把所有的邊依照權重從小排到大  
  - 步驟2–>由最小權重的邊開始，在維持不導致環情況發生的條件下，把邊加入最小生成樹的集合內。  
  - 直到所有邊都被檢查過停止。  
  
![](https://i.imgur.com/dXpIrlS.gif)

## [程式碼](https://github.com/yulin871030/my-learning-note/blob/master/HW6/Dijkstra_06170131.py)

## 參考資料
- https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/483941/
- https://zh.wikipedia.org/wiki/%E6%9C%80%E5%B0%8F%E7%94%9F%E6%88%90%E6%A0%91
- http://wiki.csie.ncku.edu.tw/acm/course/MST
