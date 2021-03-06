# Dijkstra、Kruskal原理說明

## Dijkstra

其基本原理是：每次新擴展一個距離最短的點，更新與其相鄰的點的距離。當所有邊權都為正時，由於不會存在一個距離更短的沒擴展過的點，

所以這個點的距離永遠不會再被改變，因而保證了演算法的正確性。不過根據這個原理，

用Dijkstra求最短路的圖不能有負權邊，因為擴展到負權邊的時候會產生更短的距離，有可能就破壞了已經

更新的點距離不會改變的性質。

Dijkstra演算法的輸入包含了一個有權重的有向圖G，以及G中的一個來源頂點S。 我們以V表示G中所有頂點的集合。  

每一個圖中的邊，都是兩個頂點所形成的有序元素對。(u,v)表示從頂點u到v有路徑相連。 我們以E所有邊的集合，而邊的權重則由權重函數w: E → [0, ∞]定義。  

因此，w(u,v)就是從頂點u到頂點v的非負花費值(cost)。 邊的花費可以想像成兩個頂點之間的距離。任兩點間路徑的花費值，就是該路徑上所有邊的花費值總和。   

已知有V中有頂點s及t，Dijkstra演算法可以找到s到t的最低花費路徑(i.e. 最短路徑)。 這個演算法也可以在一個圖中，  

找到從一個頂點s到任何其他頂點的最短路徑。  

![](/images/Dijkstra.png)

## Kruskal
Kruskal演算法是一種用來尋找最小生成樹的演算法，目的是找出可連結所有點且具最小權重總和的樹  

步驟1–>把所有的邊依照權重從小排到大  
步驟二–>由最小權重的邊開始，在維持不導致環情況發生的條件下，把邊加入最小生成樹的集合內。  
直到所有邊都被檢查過停止。  
![](https://i.imgur.com/dXpIrlS.gif)

# 流程圖
![](/images/IMG_1730.jpeg)

# 學習歷程
這是這學期最後一個功課，經過這學期的磨練，我覺得我自己有程式碼建立朋友的關係。以前只要看到程式碼就覺得很排斥，尤其是在前幾份作業的時候，邏輯都不難啊，但是要把它轉成程式碼就覺得很痛苦，認為只給兩個星期實在是太短了，因為對python不熟。在前幾次寫作業的時候，一直寫寫改改，而且常常會寫到壓線交出去。有幾次是比較早寫完，交出去後，看到執行的測值有錯誤，心情真的覺得很糟。在一度想放棄的時候，看到周圍的朋友以前寫程式跟我差不多的人，都可以執行程式後拿滿分，我就想「他們都可以，為什麼我不能夠做到！沒有道理我做不到。」於是當我在第四次作業執行測值拿到滿分時，真的很高興，一則慶幸自己的努力，二則感謝自己願意堅持下去。雖然我在班上進步的速度，可能比不上我的好友簡大為跟蘆煒中，但是我確實有感覺到我在進步，以前我只對Mechanical engineering跟Finance有興趣，現在開始有點後悔自己為什麼不早一點對程式碼感到興趣了。資料結構與演算法這門課除了讓我程式碼有進步外，我覺得它有幫助我進行思考，想事情變得有邏輯條理。謝謝老師教導我如何自己學習

參考資料：
[https://www.youtube.com/watch?v=uRfSsu4zYW0](https://www.youtube.com/watch?v=uRfSsu4zYW0)   
[https://www.youtube.com/watch?v=NLp9C7AvJhk](https://www.youtube.com/watch?v=NLp9C7AvJhk)  
[https://www.itread01.com/content/1548612012.html](https://www.itread01.com/content/1548612012.html)  
 
