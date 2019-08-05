## ChatSecure (僅 Apple 用家)
ChatSecure 為開放原始碼嘅通訊應用程式，使用基於 XMPP 嘅通訊協議，XMPP 前身係 Jabber，家下相當之多嘅通訊程式都係基於 XMPP 進行封裝，XMPP 使用咗 OTR 協議（不留記錄即時通訊協議）及 TLS 加密（RSA 非對稱加密），保證成個通訊過程都處於安全加密狀態。並且可以使用 Tor 網路（去中心化匿名通訊網路）進行 Proxy 通訊，係目前市面上安全性排頭嘅通訊 App。但 XMPP 都存在缺點，就係唔可以傳輸二進制（唔係毅進制），所以媒體內容係冇辦法 send 嘅。

### ChatSecure 使用方法：
App Store 直接 Download，打開之後選擇 Create New Account，Nickname 請唔好同自己真實個人資訊相同，Server 可以選擇帶有 .onion 標誌嘅 Tor 加密通訊伺服器，然後選擇 Show Advanced Options，開啟 Enable Tor，咁就可以保證通訊過程當中較高嘅安全系數，如果出現開啟 Tor 之後無法正常訪問伺服器嘅情況，請關閉該選項，iOS 目前使用 Tor 網路仍有一定嘅故障概率。

### 使用 ChatSecure 嘅安全 Tips：
#### 選用 Tor 網路進行 Proxy 通訊
選擇帶有 .onion 標誌嘅伺服器登入，或者直接使用 Enable Tor 開啟登入伺服器，最大程度保障通訊安全性。

#### 唔好使用真實個人資訊
Nickname 及群組內通訊唔好透露任何同自己真實身份有關嘅資訊，防止被人收集並社會工程學到你真實身份。
