# ios平台代理軟件的基本功能講解，建議零基礎的用戶閱讀。 軟體包括： Shadowrocket / QuantumultX / Quantumult / Loon

- Quantumultx
- Quantumult
- Loon
- Shadowrocket

## 基本信息
1. 作用為突破防火牆的限制實現外網的自由。
2. 適配於：shadowsocks / shadowsocksr / v2ray / trojan /訂閱
3. Quantumult X有防共享機制，第12台設備下載的就是盜版的

### 專業術語

- **PAC模式**：即禁止訪問的網站走VPN，國外的網站走內部網路：Wi-Fi /數據
- **全局模式（Global）**：國內的網站跟國外的網站全部走VPN，特點為訪問國內網站速度會變慢

1. PAC流量： 訪問國內的網站不扣VPN流量，訪問禁止的網站扣流量
2. 全局模式：訪問國內外網站全部要扣流量

怎麼看自己國內外的訪問的IP情況：
> 連結：https://ip125.com/


#### 軟體下載：香港APP STORE

- [Quantumultx 售價 HKD58.00](https://apps.apple.com/hk/app/quantumult-x/id1443988620)
- [Quantumult 售價 HKD78.00](https://apps.apple.com/hk/app/quantumult/id1252015438)
- [Loon 售價 HKD38.00](https://apps.apple.com/hk/app/loon/id1373567447)
- [Shadowrocket 售價 HKD23.00](https://apps.apple.com/hk/app/shadowrocket/id932747118)

## Quantumultx功能介紹 ｜ Version ： Quantumult X 1.0.30-707

1. **流量走向** ： 長按右下角的三菱圖標 - 橘黃色為PAC模式，藍色為全局模式
2. **訂閱添加** ： 點擊右下角的三菱圖標 - 點擊 【**節點**】里的【**引用（訂閱）**】 - 【右上角📎圖標】 - 添加機場訂閱即可
3. **QuantumultX解析器** ：點擊三菱圖標 - 點擊 【**配置文件**】裡的【**編輯**】 - 點擊第一個圖標 定位到General - 去點resource_parser_url前面的冒號 - 將下方解析器的連結粘貼近來即可
> https://github.com/KOP-XIAO/QuantumultX/blob/master/Scripts/resource-parser.js
4. **MitM** : 點擊三菱圖標 - 點擊【**MitM**】- 【**配置證書**】- 允許Safari瀏覽器下載描述文件 - 進入手機的設置，安裝描述文件 - 點擊【**關於本機**】-下滑到【**證書信任列表設定**】- 信任剛剛下載的配置文件
5. **重寫功能** ： 點擊三菱的圖標 - 在【**重寫**】那邊開啟即可
6. **節點ISP的查詢** ： 任選一個節點，在左上角會自動顯示
7. **正版與盜版檢測** ： 點擊右下角的三菱圖標 - 下滑到【**其他設置**】- 下滑到最底部 

![image](https://github.com/hkjswong/ios-proxy-tool-basic-knowledge/blob/main/quantumultx.jpeg)


> 藍色標誌就是正版的，能使用所有功能

> ❌就是盜版的，所有功能全部不能使用


## Quantumult功能介紹 ｜ Version ： 2.2.13 

1. **流量走向** ： 點擊右下角的正方形 - 可選擇全局代理 / 自動分流/全局直連三種模式
2. **訂閱添加** ： 點擊主頁的 【**節點**】里的【**➕號**】- 添加專屬訂閱即可
3. **節點ISP的查詢** ： 任選一個節點，在下方會自動顯示

## Loon功能介紹 ｜ Version ： 2.2.1 （😭我自己也不怎麼會用就不做諸多介紹）

1. **流量走向** ： 點擊左上角 - 可選擇全局代理 / 自動分流/全局直連三種模式
2. **訂閱添加** ： 點擊 【**設置**】里的【**訂閱**】 - 【**➕號**】 - 【**服務器**】- 添加專屬訂閱即可
3. **使用** ： 點擊 【**策略**】選擇自己想使用的節點 - 返回主頁 - 點擊 【**啟動**】

## Shadowrocket功能介紹 ｜ Version ： 2.2.18 

1. **流量走向** ： 點擊第二行的【**全域路由**】 - 可選擇配置（PAC） / 代理（Global）/直連等等
2. **訂閱添加** ： 點擊右上角 【**➕號**】- 類別選擇【**Subscribe**】 - 【**URL**】粘貼自己的連結 - 【**完成**】
3. **更新訂閱** ： 右滑添加進來的訂閱 - 點擊【**更新**】即可

![image](https://github.com/hkjswong/ios-proxy-tool-basic-knowledge/blob/main/%E8%A8%82%E9%96%B1%E6%9B%B4%E6%96%B0.jpeg)

### 聯繫方式 :bell:

- Telegram：https://t.me/xwring :point_left:
- 個人telegram:https://t.me/kwaong 👈
- Telegram Channel:https://t.me/chryax_offical
- 我的博客（新的,舊的被封了):https://kwaon.wordpress.com/ 👈
- email: hello@lwky.com.hk :point_left:
- Facebook粉專：https://www.facebook.com/jsrwon :point_left:
- 微信公眾號 :point_down:

![image](https://github.com/hkjswong/shadowsocksR-setup/blob/master/%E5%BE%AE%E4%BF%A1%E5%85%AC%E7%9C%BE%E8%99%9F.jpg)
