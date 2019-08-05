## Telegram
Telegram 為開放原始碼嘅通訊程式，通訊原理分為兩種，⚠️Group 及 Direct Message 為非端對端加密，所以通訊記錄將會存儲係 Telegram 伺服器上，並且可以多平台瀏覽，呢種通訊方式並不安全，通訊安全建立係 Telegram係中立立場之上。✅另一種通訊原理為端對端加密：Secure Chat，通訊之前，需要雙方 Click 對方 Profile 下面嘅 Start Secure Chat 創建會話，每個用家嘅手提電話會生成一對密鑰：Public Key 及 Private Key，雙方交換 Public Key 之後，每條訊息使用該 Key 進行加密，使用邊個 Public Key 加密之後嘅訊息，只能用同一對 Key 裡面嘅 Private Key 去解密，而 Telegram 開放程式原始碼，所以呢種通訊方式可以得到較好嘅安全保證。

### 使用 Telegram 嘅安全 Tips：
#### 啟動二次認證密碼
打開 Telegarm，Setting>>Privacy and Security>>Two-Step Verification>>Set Additional Password，然後輸入高強度嘅密碼，⚠️唔好同自己其他網站以及 App 嘅密碼相同，有可能存在他人侵入其他目標並得知你嘅密碼，然後使用密碼進行“碰撞”，就可能會登入到你嘅戶口。Add a Hint 嘅環節建議大家唔好填寫真實嘅提示，直接 Skip，等侵入者無法得知密碼意義。Recovery Email 同樣唔建議進行設置，直接 Skip，若電郵戶口安全出現問題，Telegram 將會一齊出事。

#### 關閉電話簿同步
打開 Telegram，Setting>>Privacy and Security>>Data Settings，選擇 Delete Synced Contacts 及關閉 Sync Contacts 選項，當用家開啟電話簿同步，即使冇進行會話及添加，有你手提電話號碼嘅人都會係聯繫人列表睇到你個戶口。

#### 關閉手提電話號碼顯示
打開 Telegram，Setting>>Privacy and Security>>Phone Number，選擇 Nobody。咁樣人哋就冇辦法睇到你嘅手提電話號碼。

#### 使用 Proxy 服務
Telegram 自建有 Proxy 功能，既可使用 Telegram 獨有嘅 MTProto 協議，亦都可使用 Socks5 協議。用家可以選擇購買 NordVPN、ExpressVPN 等匿名 VPN 供應商嘅服務，佢哋都支持 Socks5 協議進行 Proxy，有相關 IT 技能嘅用家，推薦自行 Set up 伺服器架設 Proxy 服務，架設服務呢個會係後面嘅內容當中詳細講解。

#### 設置戶口銷毀時間
打開 Telegram，Setting>>Privacy and Security>>Automatically Delete My Account，If away For 可選擇最短嘅 1 個月，當 1 個月內不再登入，戶口將會被自動銷毀，屬於極端情況下嘅最佳應對方法。⚠️設置咗呢個之後務必要注意定期登入戶口。

#### 檢查會話情況
打開 Telegram，Setting>>Privacy and Security>>Active Sessions，如果發現存在自己未曾登入嘅會話，請立即雙向刪除消息記錄，並且將該會話登出，防止通訊內容被截取。

#### 關閉 Link Previews
打開 Telegram，Setting>>Privacy and Security>>Data Settings，關閉最下面嘅 Link Previews 功能。程式自動預覽 Link 有可能會係無留意嘅情況下，被精心構造嘅 XSS（Cross-site Scripting）跨網站指令碼漏洞追蹤到用家嘅個人資訊。
