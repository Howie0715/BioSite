---
title: How Server
dateMonthYear: Feb 2023
description:  It's a Minecraft Server (maybe snapshot?)
type: page
topic: project
image: ""
---
# back-end
## Software
### Server
* Core
  * [Java build 18.0.2+9-61](https://www.oracle.com/tw/java/technologies/downloads/)
  * [fabric-server-mc.1.19.3-loader.0.14.14-launcher.0.11.1](https://github.com/FabricMC/fabric-loader)
  * [minecraft_server.1.19.3](https://www.minecraft.net/zh-hant/download/server)
* Plugin
  * [fabric-api](https://github.com/FabricMC/fabric)
  * [fabric-language-kotlin](https://github.com/FabricMC/fabric-language-kotlin)
  * optimize
    * [alternate-current](https://github.com/SpaceWalkerRS/alternate-current)
    * [c2me-fabric](https://github.com/RelativityMC/C2ME-fabric)
    * [carpet-fixes](https://github.com/fxmorin/carpet-fixes)
    * [fabric-carpet](https://github.com/gnembon/fabric-carpet)
    * [ferritecore](https://github.com/malte0811/FerriteCore)
    * [krypton](https://github.com/astei/krypton)
    * [lithium-fabric](https://github.com/CaffeineMC/lithium-fabric)
    * [starlight](https://github.com/PaperMC/Starlight)
  * function
    * [armor-stand-editor](https://github.com/Patbox/ArmorStandEditor)
    * [essential_commands](https://github.com/John-Paul-R/Essential-Commands)
    * [fabsit](https://github.com/fill1890/FabSit)
    * [goml](https://github.com/Patbox/get-off-my-lawn-reserved)
    * [holograms](https://github.com/Patbox/Holograms)
    * [InvView](https://github.com/PotatoPresident/InvView)
    * [ledger](https://github.com/QuiltServerTools/Ledger)
    * [LuckPerms-Fabric](https://github.com/LuckPerms/LuckPerms)
    * [MCDiscordChat](https://github.com/Xujiayao/MCDiscordChat)
    * [minimotd-fabric](https://github.com/jpenilla/MiniMOTD)
    * [PlanFabric](https://github.com/plan-player-analytics/Plan)
    * [server-hats](https://github.com/WerDei/Server-Hats)
    * [styledplayerlist](https://github.com/Patbox/StyledPlayerList)
    * [worldedit-mod](https://github.com/EngineHub/WorldEdit)

### Nas
* Backup-System：[Active Backupfor Business](https://www.synology.com/zh-tw/dsm/feature/active-backup-business/pc)
* DNS-Server：[AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)
## Hardware
### Server
* CPU：[Intel® Core™ i7-7700](https://www.intel.com.tw/content/www/tw/zh/products/sku/97128/intel-core-i77700-processor-8m-cache-up-to-4-20-ghz/specifications.html)
* RAM：24GB
* SSD：512GB

### Nas
* Model：[Synology DS220+](https://www.synology.com/zh-tw/products/DS220+)
* RAM：2GB
* Stroage：4TB\*2 (SHR)


# front-end
## ✅ 進入伺服器
### 版本 1.19.3 Server-IP：`mc.iehow.tw`｜[進入Discord](https://discord.gg/mHef42xbVu)

## 伺服規則
> Feb 16, 2023 Revise 我服保有最終解釋權
1. 禁止破壞、奪取他人所有物
2. 禁止以任何形式針對特定人(種)進行攻擊、騷擾
3. 禁止使用外掛、遊戲漏洞改變遊戲行為
4. 確保農場、紅石設施不致使伺服器卡頓

## 遊玩須知
1. 若服主有重大事務，伺服器將會進入休服，將會以公告提醒各位玩家
2. 本伺服器有安裝防透視插件，如遇偽礦物在面前消失的問題係屬正常現象
3. 伺服器將會有遊戲票券可兌換裝備、物品，可提供玩家自行交易
4. 如遇不服管理階層的判決，可以聯繫服主出面協調

## 指令介紹
### 特殊功能
🎩 可以將任何東西戴在頭上，直接在物品欄配置即可
💺 右鍵點擊半磚、階梯可以坐下

### 基本指令
#### 玩家互傳 
1. `/tpa <ID>`  請求傳送到該玩家身邊
2. `/tpahere <ID>`  請求該玩家傳送到身邊 

#### 傳點設定
1. `/home set <家名稱>`  設置傳送點 `(home點最多5個)`
2. `/home tp <家名稱>` 傳送至該點
3. `/home delete <家名稱>`  刪除該點
4. `/home list`  顯示已設置的傳點

#### 其他指令
1. `/back`  回到上一個位置
2. `/spawn`  回到重生點
3. `/warp tp <目的名稱>` (目前僅作為官方傳點)
4. `/afk` 暫離
5. `/gametime` 世界目前時間

### 領地教學
🚨 劃設領地前，建議戴上領地眼鏡，注意四周是否有他人領地，避免後續擴充重疊

📌 領地採用核心方式設置（一人在每一維度只能擁有一顆核心），擴充功能可以自行在合成表中探索:D
#### 核心使用介紹
1. 放置核心後，右鍵點擊核心調整設定
2. 依照核心等級對應半徑產生領地範圍（正方形）
3. 擴充功能需緊鄰核心放置

![](https://i.imgur.com/23CTUmH.png)

#### 核心製作、升級介紹
![](https://i.imgur.com/u2OChTH.png)
![](https://i.imgur.com/1TWXtwg.png)

## 伺服FAQ

👋 嗨大家！我是How服器的架設者，從14歲開始架設伺服器至今年即將邁入第五年，過去從私服到校服接著快照服再有目前的How服器，每個階段都是從0開始招生，但偶爾也會有前一階段的玩家發現我開了新服並且加入，很高興能再次遇見大家，也感謝新加入的玩家們！

以下分為兩部分呈現過去跟未來會被問到的問題（陸續補充），希望能夠一文以蔽之

> 關於各種卷
> 
1. 常駐卷可以換的東西太少/常駐卷很難得到
常住卷原先設計是為了鼓勵玩家多加參與伺服活動，且不可以成為伺服器的必要元素，目的是希望玩家可以多加探索世界，增加遊戲體驗，有仔細查看匯率的玩家應該有發現，兌換常駐卷的方式都需要您親自走訪世界，沒辦法定點掛機取得
2. 遊戲分流卷
遊戲分流卷未來會在遊戲分流發行，僅能透過參與伺服遊戲獲得、持有，未來商城也會有需要該卷的物品供大家兌換，會在遊戲分流結帳、主分流取貨，因此參加玩遊戲請記得把卷放入遊戲分流的終界箱中，以免遺失！

> 關於伺服營運
> 
1. 開學後是否繼續運作？
由於玩家組成有很大一部分是學生，也就意味著開學後人數會急劇下降，而伺服方目前規劃開學後繼續維持運作，除非學期中遊玩人數不甚理想，才會研擬至暑假才開服（不刪檔案）
2. 伺服器何時收場？
參與過快照服的玩家可能還還記得“閉服式”，這類慘劇未來不免再次上演，因此只能跟各位保證，若無重大變故，伺服器就會盡可能營運，希望玩家可以放心遊玩:D

以上若有其他疑問、建議歡迎私訊～

最後，敝人迄今未滿20，不要再臆測更老的年紀了plz