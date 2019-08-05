## WhatsApp
WhatsApp 通訊模式為端對端加密，每個用家嘅手提電話會生成一對密鑰：Public Key 及 Private Key，係通訊之前，對話雙方會交換 Public Key，使用邊個 Public Key 加密之後嘅訊息，只能用同一對 Key 裡面嘅 Private Key 去解密，通訊模式上不存在安全問題。但由於 WhatsApp 係私有程式，原始碼並冇開放，並且東家 Facebook 曾多次承認向中共公司提供用戶數據，冇辦法保證 WhatsApp 真係冇將 Private Key 一齊 Upload 到伺服器上。在此‼️強烈不建議‼️使用 WhatsApp 傾反送中相關部署計劃，但日常使用係冇問題嘅。

### 使用 WhatsApp 嘅安全 Tips:
#### 啟動二次認證密碼
打開 WhatsApp，Setting>>Account>>Two-Step Verification，選擇 Enable，然後輸入 6 位數嘅 PIN Code，恢復電郵換屆建議選擇 Skip 跳過，如果唔可以保證電郵安全，就存在比人通過電郵解除嘅可能性。
開啟二次認證嘅作用係，防止班狗或者中共，通過 ISP 截取手提電話認證號碼，以達到登入任意用家嘅 WhatsApp 戶口，事實上通過 Osmocom 等開放原始碼嘅 SDR 程式，可以實現自行部署 GSM 基站，劫持周邊手提電話網路，都可以非常輕鬆實現截取訊息。

#### 檢查會話情況
打開 WhatsApp，Setting>>WhatsApp Web/Desktop，如果存在自己未曾登入嘅會話，請立刻將該會話登出，防止被他人截取通訊內容。

#### 關閉消息記錄 Backup
打開 WhatsApp，Setting>>Chat>>Chat Backup，將消息記錄 Backup 關閉，Android 用家 Backup 會上傳至 Google Driver，而 Apple 用家則會上傳至 iCloud，若唔可以保證 Google Account 及 Apple ID 嘅安全，就會增加通訊內容洩漏嘅風險

### 當出現緊急情況時應急措施：
立即 Delete 自己嘅 WhatsApp 戶口，打開 WhatsApp，Setting>>Account>>Delete My Account，⚠️注意，戶口 Delete 之後所有記錄將會丟失，請謹慎操作。
