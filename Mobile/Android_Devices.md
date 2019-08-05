## Android
非特指手提電話，所有搭載 Android 嘅裝置都係範圍之內。
⚠️⚠️⚠️所有手提電話同 SIM 都帶有 IMEI 號碼，只要你登入廣播塔，就有機會記錄低你 Number，如果上咗台，就好容易 Check 到你係邊個。如果要去野餐，最好都唔好帶手提電話。

### Android 裝置嘅安全 Tips:
#### 開啟手提電話加密
Android 係 5.0 之後，就自帶有 Encrypt device 功能，可以保證成個手機 Flash Chip 嘅 Data 都 Encryption 咗。因為各品牌嘅電話 OS 唔一樣，呢度只能講大概嘅位置。
打開電話嘅 Settings，搵 Lock Screen and Security 或類似字眼，點開之後搵 Encrypt Device 功能。成個加密過程時間較長，用家要保證手機電池電量足夠，加密期間電話可能會重啟數次，用家唔需要擔心。加密完成之後，電話開機嘅時候，係 Load OS 之前，需要輸入 Password，並且冇辦法直接讀出數據。

#### 關閉 ADB Debug。
有部分用家嘅 Android 開啟咗 Developer options，如果開咗 ADB Debug，就可能存在電話被控制嘅風險。
打開電話嘅 Settings>>Developer options，將 USB Debugging 關閉，並選擇 Revoke USB Debugging Authorizations。

#### 關閉生物認證
打開電話嘅 Settings，選擇 Lock Screen and Security，輸入 Passcode 之後，關閉所有生物認證相關選項，如 Fingerprints。

#### 開啟自動抹除數據
打開電話嘅 Settings，搵 Lock Screen and Security，輸入 Passcode 之後，開啟最下面嘅 Erase Data 選項。⚠️開啟之後，輸錯指定次數就會 Delete 曬所有嘢，注意安全。

#### 關閉 Wi-Fi
如果唔需要使用 Wi-Fi 網路時，請直接關閉 Wi-Fi，使用 Aircrack 套件，係可以 Scan 到手機曾經 Joined 過嘅 Wi-Fi 名。⚠️並且唔推薦任何用家係野餐嘅使用使用公共 Wi-Fi 上網，會俾 Router 記低你個 MAC 地址。
打開電話嘅 Settings>>Connections>>Wi-Fi，將 Wi-Fi 關閉。

#### 關閉藍芽
藍芽存在洩漏手提電話名稱嘅可能性，最好就關閉。
打開電話嘅 Settings>>>>Connections>>Bluetooth，關閉 Bluetooth 選項。

#### 關閉個人熱點 
有部分巴打絲打平時 Share 網絡俾朋友用，冇留意關到個人熱點功能，都可以俾人 Scan 到。
打開電話嘅 Settings>>Connections>>Mobile hotspot and tethering，關閉 Personal Hotspot 選項。

#### 設置 SIM PIN
所有 SIM 都有 PIN 功能，作用係防止其他人以特殊方法獲取到 SIM 之後，使用其他電話盜用 SIM 號碼。
唔同電話，Menu 會有唔同，一般都係打開電話嘅 Settings>>Security 或者 Connections >>SIM PIN，Change PIN，絕大部分 PIN 默認係 1234 或 8888，具體要睇妳個 ISP，可以 Google 下，⚠️注意 PIN 只有三次機會，輸錯三次就會 Lock SIM。改好之後就開啟 SIM PIN 功能。

#### 使用 KNOX 功能保護程式（僅 Samsung 用家）
Samsung 獨有 KNOX 可以將程式單獨放到 KNOX TPM 上面保存，呢個功能可以保證程式 Data 唔會俾外界直接讀取到，務必將通訊程式全部放入 KNOX 中️。

### 當出現緊急情況時應急措施：
#### 法律問題
⚠️切記，警察冇權叫你開電話，你可以拒絕，保持緘默，手提電話內容涉及個人私隱，警察都冇權直接睇！

#### Reset 電話
當大家出現咩緊急情況嘅時候，可以緊急 Reset 手提電話，注意唔好嘗試掟電話，掟爛係冇用嘅，有 Chip 就可以讀返啲 Data 出嚟。
打開電話嘅 Settings>>Lock Screen and Security，搵到 Reset 或 Erase 相關選項，將電話內容抹除。
