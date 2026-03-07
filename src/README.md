# ![西瓜荷蘭梅花](favicon-7b08738f.svg)

作者自從讀了 Jan Eric Larsson 的 *Good, Better, Best*
之後，開始認真研究橋牌叫牌制度。為了推廣橋牌運動，以及方便台大橋藝社乃至台灣的橋牌愛好者參與各級賽事，我特地設計西瓜荷蘭梅花。本叫牌制度有以下特點：

1. 自然制，符合 [WBF Systems Policy](https://www.worldbridge.org/systems/) 當中的綠色分類。
2. 考慮社員可能前往美國發展，順便也符合 [ACBL Basic+ Chart](https://web2.acbl.org/documentLibrary/about/Convention-Charts.pdf)
   的要求。
3. 主流自然制不擅長處理 18 點以上不特定牌組的強牌。本制度通常開叫 1♣，然後 1♣-1♦ 混入不必含有方塊的弱牌。
4. 其他方面則盡量符合主流自然制的習慣，讓使用者容易上手。

綜合以上特點的，就是荷蘭梅花（Dutch Doubleton）。荷蘭梅花的精髓在於將波蘭梅花的人為迫叫 1♣
調整為保證 2 張、不迫叫，雖然損失 2♣ 的阻塞性，但在法規上較不受限，能參與更多基層賽事。

## 牌值

- **HCP**: Milton Work 眾所皆知的 4321 點力
- **總牌值**: HCP + 牌形點（缺門 3 點、單張 2 點、雙張 1 點、短門有大牌折 1 點）
- **Zar**: 6-4-2-1 + Zar 式牌形點（a + b + a &minus; d，字母代表每門由長到短的張數）
- [**Fifths**](https://bridge.thomasoandrews.com/bridge/valuations/cardvaluesfor3nt.html):
  4.0--2.8--1.8--1.0--0.4，為了無王合約尤其是 3NT 所調整的 HCP
- **BUM-RAP**: 4.5--3--1.5--0.75--0.25，為了花色合約所調整的 HCP
- **NLTC**: 每門缺失的 AKQ 分別計為 1.5--1.0--0.5 失磴

NLTC 評估一手牌還不錯，但是可加性有疑慮。比較適合開叫、競叫，但是不適合直接用於支持同伴。我有一篇[部落格文章][nltc]說明這個議題。

[nltc]: https://jdh8.org/nltc-a-good-single-hand-evaluator/

### 擋張

在此借用 [GIB] 的定義

- **虛半擋[^半]**：長度 + HCP = 4
- **實半擋[^半]**：長度 + HCP = 5
- **一擋**：A、QJx、或長度 + HCP ≥ 7
- **兩擋**：長度 + HCP ≥ 8

[GIB]: https://www.bridgebase.com/doc/gib_descriptions.php

[^半]: 除了搭配同伴的半擋，實半擋也能藉由出牌順序（莊位、偷牌）升級為擋張，故作此譯。

## 叫品的描述方式

便於各級賽事使用，本制度的叫品以簡短的中英文描述。為了讓叫品描述更簡潔，我使用 [WBF 建議的縮寫][abbr]。此外，為了符合自然閱讀習慣，我使用常見的標點符號來連接條件：

[abbr]: http://www.worldbridge.org/wp-content/uploads/2017/04/Guidetocompletion.pdf

- **逗號 (,)** 作為**且**。
- **分號 (;)** 作為**或**。
- **冒號 (:)** 緊接叫品的大致描述。

範例：本制度的[開叫](Opening.md) 1♣ 及 2♣。

## 參考資料

- Jan Eric Larsson.  *Good, Better, Best: A comparison of bridge bidding
  systems and conventions by computer simulation*.  ISBN 978-1771402415
- Thomas Andrews.  [Thomas's Bridge Fantasia](https://bridge.thomasoandrews.com/bridge/valuations/)
- Bridge Base.  [GIB Bid Descriptions][GIB]

### 荷蘭梅花

- Dan Neil.  [Professional Dutch Doubleton Bidding System](https://bridgewithdan.com/product/professional-dutch-doubleton-bidding-system/)
- [Sjoert Brink & Bas Drijver](https://www.bridge.nl/wp-content/uploads/2023/01/Lb1_Brink-Drijver.pdf).
  (WBF convention card)
- Rosalind Hengeveld.  [Dutch Doubleton](https://rosalind.home.xs4all.nl/bridge/2-over-1/index.htm)

### 波蘭梅花

- 何震邦.  [Strawberry Polish Club](https://polish.club)
- Krzysztof Jassem & Tomek Brus.  *Polish Club 2020: Expert*.  ISBN 978-1771402248
- Krzysztof Jassem.
  [Wspólny Język 2020 Standard](https://web.archive.org/web/20260129184409/https://jassem.pl/wp-content/uploads/2019/12/wj2020-25-59.pdf)
- Krzysztof Jassem.
  [Polish Club International 2010](https://web.archive.org/web/20240302061840/https://jassem.pl/wp-content/uploads/2016/08/Polish_Club-2010.html)
