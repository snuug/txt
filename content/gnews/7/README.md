###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---

## 番外課：記錄用戶真實IP的地方！
`2020-08-20 09:47 DT` [轉載自GNews](https://gnews.org/zh-hant/307346/)

【DT特戰旅安全課堂】

主講：DT特戰旅IT組小丸子

點擊鏈接自動進課堂群： [https://t.me/joinchat/Mo5ICRzZIRDYc3QZaHBCmw](https://t.me/joinchat/Mo5ICRzZIRDYc3QZaHBCmw)

**安全上網知識！安全翻牆知識！手機安全知識！電腦安全知識！**

下午我給大家講一下，大家使用的機場，哪些地方可以用來記錄用戶的真實IP。

算是番外篇了。

講完之後，請戰友們重視起來自己的隱私保護是多麼的重要啊！

現在的機場，基本上都是使用v2ray和trojan，兩種技術實現翻牆。

機場常見的有SSPanel Uim、v2board、vnetpanel 和v2-ui，四種後台管理，後台管理的代碼裡面可以記錄用戶的真實IP，其中以SSPanel Uim為例，SSPanel Uim的配置文件是.config.php。這裡涉及到代碼，大家不用理會，只需要知道127.0.0.1出現的位置，就是用來記錄用戶真實IP的地方。

127.0.0.1這個位置，本來是代碼，我將其替換成了127.0.0.1，達到從代碼裡面隱藏真實IP的目的。
[!\[\](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/b16277e1-2f6d-432a-be24-5ca28b080ec4.jpg?asset_id=611db354-35a9-4e70-a5bd-5e10e638fd1b&amp;img_etag=%229213c15ed065c431c7bfea01d3745a78%22&amp;size=2560)](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/b16277e1-2f6d-432a-be24-5ca28b080ec4.jpg?asset_id=611db354-35a9-4e70-a5bd-5e10e638fd1b&amp;img_etag=%229213c15ed065c431c7bfea01d3745a78%22&amp;size=1024)
這是不是就說明，機場主想要獲取用戶的真實IP非常容易？

當然是的！

為了實現翻牆，v2ray和trojan進行了偽裝，偽裝成了普通的網站，防火牆審查用戶的時候，發現是普通的網站，就放行了，通過偽裝來欺騙防火牆，放開用戶對網絡的訪問。

偽裝的本質，我個人理解為就是欺騙，瞞天過海，眼皮子底下搞事情，壞人也愛利用這一招， **隱藏的大灰狼太多了，戰友們務必要保護好自己啊！ ！ ！**

那麼用戶訪問網站的時候，如果沒有使用https加密以及瀏覽器的隱私設置，是不是防火牆、電信運營商輕輕鬆松知道我們在幹啥？當然可以輕鬆知道我們幹啥了！

戰友們還敢用沒有經過加密的機場節點麼？ ！

不管自建機場節點還是用別人的付費機場，用戶不了解這些東西，就永遠不知道如何在自己力所能及的範圍內去保護自己。

除了偽裝，還有一個就是混淆，大家都聽說過過九層妖塔的故事吧？裡面的妖怪把偽裝使用的爐火純青，達到了混淆視聽的境界，真真假假，假假真真，就連我們的很多老戰友都很容易被欺騙，這個九層妖塔給大家了解下：

[!\[\](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/466b5431-2e27-4717-95a0-ac9a5b99b502.jpg?asset_id=33aa56ca-5342-4d45-b682-8b94f8484c37&amp;img_etag=%22ec0a71b9dd0040e9086f1b12d7c13f98%22&amp;size=4681)](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/466b5431-2e27-4717-95a0-ac9a5b99b502.jpg?asset_id=33aa56ca-5342-4d45-b682-8b94f8484c37&amp;img_etag=%22ec0a71b9dd0040e9086f1b12d7c13f98%22&amp;size=1024)

有的機場使用了nginx，那麼nginx是啥？

不用管nginx是個什麼東西，就當作nginx是一個運行在電腦上的軟件就行了，那麼nginx怎麼獲取我們的真實IP呢？

nginx的主配置文件叫做nginx.conf，我們看看這個文件，大家只要看這個127.0.0.1 IP地址就行了，其他不管，本來這個位置是記錄用戶的真實IP，改成127.0.0.1就可以隱藏我們在nginx日誌記錄裡的真實IP了。
[!\[\](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/1a9ae174-ed53-4569-a099-145d13bb8b70.png?asset_id=7929c570-158c-4d39-8f4f-edf6e77ec3b1&amp;img_etag=%2232da4987c1c4f3649ecbebbe7487659f%22&amp;size=2560)](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/1a9ae174-ed53-4569-a099-145d13bb8b70.png?asset_id=7929c570-158c-4d39-8f4f-edf6e77ec3b1&amp;img_etag=%2232da4987c1c4f3649ecbebbe7487659f%22&amp;size=1024)
還有一些nginx的配置仍然可以記錄用戶的真實IP，這裡最後記錄127.0.0.1的地方，也是用來記錄我們的真實IP的地方。
[!\[\](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/c4834254-23f9-4b2a-8cce-a651280ffdd3.png?asset_id=c0d694a8-13a9-43ab-a63b-62ba59b788ab&amp;img_etag=%224035c05bc9ccd15fb9883f7e5e84d3c6%22&amp;size=2560)](https://spark.adobe.com/page/Kb2CCNKhsYp8T/images/c4834254-23f9-4b2a-8cce-a651280ffdd3.png?asset_id=c0d694a8-13a9-43ab-a63b-62ba59b788ab&amp;img_etag=%224035c05bc9ccd15fb9883f7e5e84d3c6%22&amp;size=1024)
用戶的真實IP無法在網絡上徹底抹去，最終會被記錄在某些地方，當戰友們知道自己的真實IP被記錄在哪里之後，作出一點修改，修改成其他IP，就能減少自己真實IP暴露的風險。

達到在自己能力範圍內，最大範圍減少自己真實IP記錄的目的。

總結一下：我們使用的機場節點，機場主分分鐘獲取我們的真實IP、分分鐘獲取我們訪問了哪些網站、分分鐘可以出賣我們。

國內公共場所，機場、高鐵站等，免費Wi-Fi也不是個好東西，想要連接這些地方的免費Wi-Fi？手機號驗證碼驗證呀！

手機號在國內都是實名的，你上網做了什麼，一清二楚的查到，不要使用網絡上公開放出來的機場節點、免費Wi-Fi，小心被釣魚！

戰友們，十有八九自己使用的機場節點，不是圈錢的，就是共匪用來釣魚的，他們都不是什麼好東西，要么隨時圈錢跑路，要么分分鐘共匪找你喝茶，怎麼辦呢？

我談談自己在這種情況下的解決辦法，我自己當時是找一些懂行的朋友，推薦給我了一些高速機場節點，開啟開全局模式或者手動模式，使用Tor瀏覽器配合socks代理去瀏覽牆內不能瀏覽的網站。

我為啥要將Tor瀏覽器和機場節點一起使用，因為如果不這樣的話，Tor翻牆太慢了，配合機場節點，起到一定的加速作用。直接使用Tor翻牆，也可以啊，瀏覽Gnews沒一點問題，就是有一個缺點，慢一點。

Tor瀏覽器的使用，我會在本週五的課堂上提到

補充一下：即使翻牆了，陌生網站不要亂點，陌生人發給你的文件，不要亂點，小心被釣魚！

我所了解的慢慢告訴大家，隱私保護靠大家

**課上小問：** SSD安全嗎？

**答：**沒有使用加密，談不上安全，使用了加密，提高了安全性

我現在翻牆，都是把v2ray機場節點配置到路由器裡面，然後手機連上Wi-Fi再開VPN，多重套用在一起。 。 。 。

他媽的，共匪的攝像頭都已經安裝到我們村口了，很多年以前就這樣了。

編輯： [【喜馬拉雅戰鷹團】](https://spark.adobe.com/page/Kb2CCNKhsYp8T/)

0
