# ng花園修整術 - 談AngularJS的Styleguide & Design Patterns

### Table of Contents
- **園丁的話**

---
## 關於園丁（About Author）

大家好！歡迎來到AngularJS花園，我是ng小園丁，但我工作絕不ng喔！XD

有鑑於偉大的網際網路上已有許多精闢的AngularJS相關教學文章，所以這裡主要會把焦點放在撰寫風格與架構議題上，並分享AngularJS的一些拙見與經驗。

---
## 關於花園（About AngularJS）

AngularJS是個充滿驚豔的美麗花園，在Google揮汗播種下，如今已在前端領域中佔有不小的一席之地，它將JavaScript經過嫁接、改良、美化後以MVC的樣貌呈現於世，世人對於JavaScript的神祕刻板印象，已漸漸從誤解轉化為諒解（咦？）。

話說在Web Application應用越來越廣泛的這個時代，MVC是當今最火紅的Web架構之一，既然AngularJS以架構為導向的設計已展現出它的許多優點，那麼我們就它的架構面來探討更多的延伸議題，這其中綜合了小園丁在專案中碰過的問題和一些個人觀點，這不是唯一原則，也沒有最佳原則，純粹以分享的角度撰文。

關於AngularJS的種種，您可以參考...
- [AngularJS官方文件][linkAngularOfficial]（by Google）
- [學習AngularJS資源總整理][linkAngularResource]（by jmcunningham）
- [AngularJS入門教學][linkAngularTutorial]（by 男丁格爾）
- [AngularJS相關教學影片][linkAngularVideo]

---
## 修整術（Refactoring）

小園丁在帶著各位大大參觀AngularJS花園的同時，分享一些園裡花木的修剪（重構）、種植（開發）和維護經驗，並探討一些有趣的設計架構與細節，盡可能地以一天一單元的短篇形式進行。希望小園丁能在忙碌之餘持續不間斷的完成這系列。

這裡所謂的修整術廣義而言，不只是指重構，而是嘗試調整Angular程式碼和改良撰寫的風格來提昇軟體維護的品質，小園丁在這30天將由下列這些方向做切入面來探討：
- 撰寫風格
- 設計模式
- 程式碼管理
- 效能
- 測試
- 應用
- 資源

---
## 小園丁碎碎念

往後的逛花園途中若發現小園丁的碎碎念，表示該段落是個人觀點（有時只是自言自語的搞笑），不須過於嚴肅地閱讀，希望大大們是放鬆心情來享受這趟不太一樣的小小旅程喔！

---
下一篇小園丁就帶著大家參觀參觀花園嘍～


[linkAngularOfficial]: https://angularjs.org "Google AngularJS"
[linkAngularTutorial]: http://abgne.tw/category/angularjs/angularjs-getting-stared "男丁格爾的AngularJS入門教學"
[linkAngularResource]: https://github.com/jmcunningham/AngularJS-Learning/blob/master/ZH-TW.md "學習AngularJS"
[linkAngularVideo]: https://www.youtube.com/user/angularjs "AngularJS on YouTube"