# 初始化網格

HFSS解題的第一步便是根據結構自動產生初始網格(initial mesh)，使用者可以針對弧形結構調整網格來提高準確度。HFSS網格種類有以下幾種：

* Classical
* Tau

<figure><img src="../.gitbook/assets/image (2) (3) (1) (1).png" alt=""><figcaption></figcaption></figure>

### 物件網格

如果使用者事先知道哪一部分的網格需要較密集，可以在模擬之前手動針對該處設定較密集的網格，如此可以縮短網格迭代進一步降低模擬時間。
