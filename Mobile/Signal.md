## Signal
Signal 係 Snowden 推薦嘅一款開放原始碼嘅通訊應用程式，WhatsApp 協議前身就係出自 Signal，Signal 為端對端加密，並且唔係伺服器上儲存任何通訊記錄，所以當網路環境唔係咁好嘅時候，就有一定機率出現訊息丟失或者無法投遞嘅情況。並且因為程式原始碼由社區維護，所以程式穩定性較差，易用性亦都一般，推薦非常重視安全問題嘅用家使用。

### 使用 Signal 嘅安全 Tips：
#### 開啟登記保護
打開 Signal，點左上角進入 Setting>>Privacy>>Registration Lock，輸入數字組成嘅 PIN Code，長度隨意。開啟之後可以防止狗或者內地公安通過 ISP 或者自建 GSM 基站截取手提電話驗證碼以達到登入戶口嘅目的。

#### 關閉 Link 預覽功能
打開 Signal，點左上角進入 Setting>>Privacy>>Link Previews，關閉此功能，程式自動預覽 Link 有可能會係無留意嘅情況下，被精心構造嘅 XSS（Cross-site Scripting）跨網站指令碼漏洞追蹤到用家嘅個人資訊。

#### 檢查登入會話
打開 Signal，點左上角進入 Setting>>Linked Devices，如果發現存在自己未曾登入嘅會話，請立即將該會話登出，防止通訊內容被截取。

### 當出現緊急情況時應急措施：
#### 銷毀 Signal 戶口
Signal 所有通訊記錄依賴用家手機存儲，註銷後恢復非常困難，打開 Signal，點左上角進入 Setting，最下面嘅大紅色條 Link: Delete Account，即可銷毀戶口。
