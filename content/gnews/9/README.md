###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---

## SWIFT的前世今生
`2020-08-14 08:08 DT` [轉載自GNews](https://gnews.org/zh-hant/296773/)

DT特戰旅金融課堂第五課

*作者：長工Satoshi ｜文章整理：西川Stanly；*

點擊加入👉 [DT特戰旅金融課堂](https://t.me/joinchat/MWJuBVQnmImYI1p9U0iXDg) 👈

今天主要是走近SWIFT粗粗看一下，這個東西對於大家很神秘。其實, 沒有那麼玄乎。 SWIFT於1973年在創始人兼CEO的領導下成立於比利時的布魯塞爾，首任首席執行官Carl Reuterskiöld ，做了10年。 SWIFT：是Society for Worldwide Interbank Financial Telecommunication的縮寫。翻譯一下是環球同業銀行金融電訊協會。注意: 做通訊的，專門用於銀行之間的通訊。在1973年成立, 成立的的時候有來自15個國家的239個銀行的支持，可以說響應度非常好。

大家回放一下歷史, 那幾年發生了什麼。布林頓森林體係就在那時候差不多完蛋的, 美金在1972年和黃金脫鉤。背後法國人沒有少插刀子，題外話。所以，外貿結算在當時是大問題。這裡面最重要一個底層建設：也就是銀行之間怎麼溝通，怎麼下單，怎麼確認。

[!\[\](https://spark.adobe.com/page/boJOqAWuuNuak/images/3681f383-b20d-4389-a22a-54bf3c316aac.jpg?asset_id=44ef1ffd-4f6c-43aa-80e3-0f4f578ef293&amp;img_etag=%2298c481dca5f119c3bf7c00e617d7d808%22&amp;size=2560)](https://spark.adobe.com/page/boJOqAWuuNuak/images/3681f383-b20d-4389-a22a-54bf3c316aac.jpg?asset_id=44ef1ffd-4f6c-43aa-80e3-0f4f578ef293&amp;img_etag=%2298c481dca5f119c3bf7c00e617d7d808%22&amp;size=1024)

SWIFT的總部在比利時布魯塞爾旁邊一個小鎮，不到10000人口，但是卻深遠影響著人類，影響力的大小很多時候和樓的高度沒有關係。這個組織當時成立的目的是設立一套金融機構之間的安全可靠的通訊標準和手段；（通訊不安全那後果是很可怕的，想想我假冒聯儲局主席下一個訂單打款到我賬戶，然後抹去通訊和打款記錄，這會多可怕）

\* 這套安全通訊系統主要是由美國Burroughs Corporation研發；—— 這家公司一直不出名, 現在被併購了, 當時應該是做電腦的：

\* 通訊規則作業流程和以及對應的責任1975年完成，第一條SWIFT電文於1977年發出；

\* SWIFT在美國數據處理中心開始於1979年的維吉尼亞

這些就是一個簡單的背景。

SWIFT 是一個公司化的社團，一般社團是非盈利, 但是比利時法律允許這類公司化的社團存在，會員都是股東。剛才說了歷史背景，這個SWIFT的屬性是社團，而且是公司化的社團。社團就有會員，公司就有股東。他們會員就是股東。當然, 這個股份怎麼分, 我們今天不討論。

申請正式會員的前提是你首先是銀行，正式會員你有股份，有選舉權，可以提名董事；另外還有口袋不那麼深的：有子用戶（Sub）和參與者(Participants）。超過90%的用戶是子用戶（Sub）類型，他們能夠全權訪問整個系統，但是不具備股份和選舉權；後者通常是其他類型的金融機構，他們能夠受限訪問系統，沒有任何所有權。所以, 這裡面你看大銀行和小銀行肯定話語權不同了。參與者(Participants）這類多數是非銀行金融機構，比如交易所，比如儲備局，比如信託服務公司。目前全世界使用和參與的金融機構超過11000家。

好，我們歸納一下。 SWIFT 做了銀行之間通訊標準，會員都必須是銀行，根據大小講數(股份)，全世界的金融機構很多使用SWIFT。

SWIFT的董事局, 有25名董事。

[!\[\](https://spark.adobe.com/page/boJOqAWuuNuak/images/af8d1dd8-4934-4f20-8c5d-15b6e26e9a74.jpg?asset_id=b12273cb-36c0-47ce-a5ce-0307b1f88759&amp;img_etag=%22af588dc29561ecb09d0daed8f16b0c39%22&amp;size=2560)](https://spark.adobe.com/page/boJOqAWuuNuak/images/af8d1dd8-4934-4f20-8c5d-15b6e26e9a74.jpg?asset_id=b12273cb-36c0-47ce-a5ce-0307b1f88759&amp;img_etag=%22af588dc29561ecb09d0daed8f16b0c39%22&amp;size=1024)

現任主席是這位, 來自美國花旗銀行。大家猜一下這位大哥是哪里人?

[!\[\](https://spark.adobe.com/page/boJOqAWuuNuak/images/ebe1345f-5297-4c78-a2ef-23d4874ede26.jpg?asset_id=7bb682cf-62b1-4f37-a892-67a316bfe0d5&amp;img_etag=%22d9b1f5337f37626d575e118ad3080f1c%22&amp;size=2560)](https://spark.adobe.com/page/boJOqAWuuNuak/images/ebe1345f-5297-4c78-a2ef-23d4874ede26.jpg?asset_id=7bb682cf-62b1-4f37-a892-67a316bfe0d5&amp;img_etag=%22d9b1f5337f37626d575e118ad3080f1c%22&amp;size=1024)

這位大哥是巴基斯坦人

[!\[\](https://spark.adobe.com/page/boJOqAWuuNuak/images/d4cdd2ac-2498-48dd-8a56-76c781ba13f2.jpg?asset_id=c42190bc-aef6-4598-89c3-e4ff13e909e7&amp;img_etag=%22e0eff3e7d560dac84b94acd5d0c95317%22&amp;size=2560)](https://spark.adobe.com/page/boJOqAWuuNuak/images/d4cdd2ac-2498-48dd-8a56-76c781ba13f2.jpg?asset_id=c42190bc-aef6-4598-89c3-e4ff13e909e7&amp;img_etag=%22e0eff3e7d560dac84b94acd5d0c95317%22&amp;size=1024)

這位是天朝的，中國也有一位董事。

現在董事局成員，可以參考[鏈接](https://www.swift.com/about-us/organisation-governance/swift-board-directors)

有興趣的戰友可以去看看其他23位，歷史背景。屬性和管理層簡單說到這裡。大家具體可能更關心如何轉錢的

SWIFT 如何轉錢

先說賬戶系統—— 你看回到前面的課程了。賬戶系統是金融領域最基礎的元素。這幾乎決定了一切。 SWIFT/BIC Code 就是銀行在SWIFT的ID，8位/11位。為什麼差3位，最後3位是標示銀行的分行的。比如在新加坡的巴克萊銀行BARCSGSG 如果一定要寫成11位，巴克萊在新加坡只有一個分行，最後就用XXX結尾。那8個字母代表什麼都有特定規定，畢竟SWIFT就是做通訊標準的嘛。

SWIFT 和BIC (Bank Indentifier Code) 意義不同，但在實際操作上基本可以互換，都是一致的。所以有些地方的銀行打款表格寫SWIFTCODE, 有些寫BIC , 你可以當作一回事。就是銀行的識別碼, 俗稱名字—— 跨境匯款的時候銀行的標準化名字!

這個很容易理解，這個是簡易的打款流程圖

[!\[\](https://spark.adobe.com/page/boJOqAWuuNuak/images/791d2db3-93e1-45f9-85aa-9a4e97d4eca1.jpg?asset_id=9fe7f983-72c3-4aae-94eb-4f9b20c3db32&amp;img_etag=%22cacff3ee270784cefe13912a3ff916ef%22&amp;size=2560)](https://spark.adobe.com/page/boJOqAWuuNuak/images/791d2db3-93e1-45f9-85aa-9a4e97d4eca1.jpg?asset_id=9fe7f983-72c3-4aae-94eb-4f9b20c3db32&amp;img_etag=%22cacff3ee270784cefe13912a3ff916ef%22&amp;size=1024)

Person1 是打款人, Person2 是收款人。 1去銀行打款要寫清楚收款人銀行的BIC 代碼, 然後寫上收款人名字和賬號。 BIC正確, 就會正確到達對方的收款行, 名字和賬號正確, 就會準確無誤進對方賬戶。那麼打款的銀行按照標準下單, 對方就嚴格執行, 那麼這一單就完成執行了。這個是簡化的圖, 一般實際跨境還有一個大銀行做中間行。比如我今天通過新加坡華僑銀行給美國一個小銀行打款, 華僑銀行和對方銀行無法結算, 那麼華僑就找花旗, 花旗在美國和那個小銀行算賬, 在新加坡和華僑銀行算賬。這個就是結算和清算。

銀行之間涉及到信用/保證金，不是現貨買賣。現貨買賣，一手交錢，一手交貨，拜拜了。結算清算同時完成。在信用制度下不是這樣，所以成本高，效率低。銀行之間互相開賬戶做結算清算也是常見的手法。

中國境內的玩法是大額通過央行記賬，大小額通道不同，中國銀行間我印象里大致有5條渠道做跨行，其實很複雜的。銀行之間當然不光光轉錢, 還有很多其他業務。 SWIFT電文根據銀行的實際業務運作分為十大類，其中第一類格式代碼為MT1xx，用於客戶匯款與支票業務，如MT199通常用於電匯業務；第七類格式代碼為MT7xx，用於跟單信用證及保函業務，如開立跟單信用證的格式代碼為MT700/ MT701， MT710是通知由第三家銀行開立的跟單信用證報文格式，我們個人常見的都是MT1XX。

SWIFT日均處理大約4000萬筆, TPS 400左右。 TPS: transaction per second, 每秒筆數。萬事達和Visa 比這個高, 但是萬事達是處理個人消費為主的, 都是小額；Visa的處理能力其TPS峰值大約7000-10000這個區間。

[!\[\](https://spark.adobe.com/page/boJOqAWuuNuak/images/a212ce91-7044-4294-9840-b58bd44cda30?asset_id=86bc42ee-ea51-47fb-a305-5eb30c94bcf5&amp;img_etag=%229a7ff68ee194ad53d3c93332bccdb171%22&amp;size=2560)](https://spark.adobe.com/page/boJOqAWuuNuak/images/a212ce91-7044-4294-9840-b58bd44cda30?asset_id=86bc42ee-ea51-47fb-a305-5eb30c94bcf5&amp;img_etag=%229a7ff68ee194ad53d3c93332bccdb171%22&amp;size=1024)

有興趣的可以研究一下SWIFT 電文格式和比特幣區塊傳播的格式—— 這是一個重要的提示！所以最牛逼的偷錢方式不是搶銀行，是破解SWIFT電文下指令給你打錢；然後再抹去痕跡。偷信用卡資料什麼都是弱雞的。當然這個不是今天的彩蛋, 彩蛋放最後。比較出名的案件是巴基斯坦的幾千萬美元不見了， 大家有興趣可以去查。我認為這不是一般普通的案件，甚至是否和“沉船有關”的一次測試和演練，因為SWIFT是一般的黑客組織幹不動的。大家注意，中國的逆向工程能力是很強的。巴基斯坦那次誰在背後？誰是主謀？如果沉船計劃存在, 應該不會漏掉SWIFT。

另一方面，SWIFT雖然是起源於歐洲，但是國際貿易美元比重最大。美國政府可以乾預所有美元交易，發生過一系列的事情。歐盟的美元交易也是被監視的，毫無疑問。有個比利時商人買古巴雪茄，打給德國人，結果錢被美國政府劫到美國了。

因為美國NSA干預的非常多，北歐5國的INSTEX機構搞了一個SPV，Special Purpose Vehicle，特殊通道車。名義上，主要是為了解決伊朗的人道主義事業比如救濟糧食和藥品，我認為是一種演練和測試技術，去SWIFT化。中國的，CIPS，Cross-Border Inter-Bank Payments System，人民幣跨境支付系統。 CIPS 採用的是SWIFT標準，對外宣傳是人民銀行開發的，其實就是white label，SWIFT 的人民幣版本。截至2019年5月23日，已經有865間銀行接入，2018年交易額為26萬億。俄羅斯的SPFS，System for Transfer of Financial Messages，其實也是俄羅斯版本的山寨SWIFT，出現的背景是2014年俄羅斯被美國威脅踢出SWIFT。第一筆執行的交易是2017年12月，去年開始，老毛子簽約很多協議，SPFS與中國，印度，伊朗以及計劃直接使用SPFS的歐亞經濟聯盟(EAEU 東歐中亞西亞)這些國家進行支付系統鏈接，其實就是為萬一被迫脫鉤做準備。所以, 其實大家可以嗅到味道, 全世界在為萬一打群架做準備。由此可見，世界上最難的事情就是製定標準…..

SWIFT呢, 就大致介紹到這裡, 揭開一點神秘的面紗，最後說一點輕鬆的啊。我在前幾周說了一些東西，比如區塊鏈，比如賬戶體系，比如記賬權，比如小世界和博弈論。 SWIFT 說白了就是建立一個賬戶體系, 方便銀行做跨境結算。其實比特幣的偉大之處就在於其在沒有第三方記賬的情況下解決雙花的問題。信息可以無限複製，比如我一張照片, 我複制333份, 我們群裡每人一份，我自己那份還在。但是錢, 10美元，我不能複制333 份, 每人發一份。我今天發給DT10美元，我那一份就沒有了；如果我試圖發給兩個人, 一筆錢花兩次，那就是雙花，double spend。那麼, 問題來了, 我今天一本書, 一首歌, 放在網上讓人下載, 能不能也像錢一樣, 他下載之後只有一份?

如果通過硬件實體什麼的, 那個成本很高。一個比特幣可以分割成一億聰（聰，Satoshi，比特幣的一個單位名稱，就和每一元錢可以分割成一百分錢一樣）, 任何一聰的來龍去脈都可以追溯，任何一聰互相之間也都是獨立的，而且價值一樣。就好像錢，所有的10塊錢都是10塊錢，但是還有不同編號。如果我今天下載一本書, 我綁定某個token, 就說一聰好了。那麼對於這本書我在電腦裡, 如果是常規文件, 就可以無限複製了。但如果，我把複製變成一筆交易,——- 雖然我可以構造無限筆數的交易, 但是最終只有一筆交易被承認有效合法。如果我複制1萬份, 最後9999份都非法然後消失了, 那最後還是只有一份。

如果這一點能實現——我想肯定可以實現——那麼, 現在的出版業, 無論是書籍, 還是音像, 都要重新定義。每一個創作者, 就可以直接作品上鍊了。這一點發現是我最近兩週的感悟，送給DT挖掘團隊，當作一點小禮物。我知道世界上還沒有人這麼做, 但是我自己想做扥事情和領域也不在這方面, 所以就在這裡說一下，這就是我所說的彩蛋。要是誰以後拿這個申請專利, 我這裡的講課記錄就可以拿出來對薄公堂。下週的講堂, 將是一位神秘嘉賓。

編輯[【喜馬拉雅戰鷹團】](https://spark.adobe.com/page/boJOqAWuuNuak/)

1
