線段樹
===
## 先備知識
* dfs
* 二元樹
* 前綴和
## 前導
想必各位應該已經學過前綴和了(? 但在用前綴和時雖然可以用$O(1)$的時間來做**查詢**但沒辦法修改\(~~當然你可以每次修改都把整個前綴和砍掉重做但這樣時間複雜度極糟~~\)
所以，如果我們需要可以支援修改操作、查詢範圍總和的結構時，我們可以考慮使用本篇的主角**線段樹**
## 介紹
![線段樹](https://hackmd.io/_uploads/HJTBpsCaJe.png)
這是一線段樹，來構建他吧！
## 構建
![a1.drawio](https://hackmd.io/_uploads/S1viN0061x.png)
![a2.drawio](https://hackmd.io/_uploads/SJAEVARaye.png)
![a3.drawio](https://hackmd.io/_uploads/B1GUNACTJx.png)
![build_pic-第 5 页.drawio](https://hackmd.io/_uploads/H1QDNCAaJl.png)
![build_pic-第 6 页.drawio](https://hackmd.io/_uploads/SJXDEAR6Jg.png)
![build_pic-第 7 页.drawio](https://hackmd.io/_uploads/Skxmw4006Je.png)
![build_pic-第 8 页.drawio](https://hackmd.io/_uploads/BJQD4C0p1x.png)
![build_pic-第 9 页.drawio](https://hackmd.io/_uploads/SkEDE0AT1e.png)
![build_pic-第 10 页.drawio](https://hackmd.io/_uploads/rJmvE006ye.png)
![build_pic-第 11 页.drawio](https://hackmd.io/_uploads/S1NPVACTJg.png)
![build_pic-第 12 页.drawio](https://hackmd.io/_uploads/r1NwN00Tke.png)
