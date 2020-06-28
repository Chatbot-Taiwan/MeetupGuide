![](https://i.imgur.com/bnjhvyRl.png)

# KKTIX 建立報名活動

https://kktix.com/dashboard/organizations/chatbots
至 KKTIX 建立活動，建立時可以參考過往活動去選樣板，要注意：

- 講者時間
- 票卷的時間
- 地點
- 人數
- 網址名稱
- 上傳大頭照

大致上的樣子為這樣

![](https://i.imgur.com/xMbNS53l.png)

## 至少要擁有兩種票卷

1. 一般會眾
2. 閃電秀 (5 分/人)
3. 講者票 (Optional)

---

kktix 開完之後至 [Chatbot Developer Taiwan](https://www.facebook.com/groups/chatbot.tw/events/) 開**活動**宣傳會發通知給所有社群使與用者
![](https://i.imgur.com/ru8J1yC.png)

> 開 `社團活動` 會對所有社群成員下通知，若像 COSCUP 之類推廣活動也可開活動通知

# 共筆

先到 [HackMD](https://hackmd.io/team/chatbot-tw?nav=overview) 開團隊筆記，選擇範本

![](https://i.imgur.com/xSuKkSrl.png)

---

裡面已經有我建立的範本部分，如果覺得有比較好的部分可以直接改

![](https://i.imgur.com/oSYxgQQ.png)

共筆也需要建立以及注意`網址`的部分，`不可以`用亂碼傳出去(hackmd 預設)

![](https://i.imgur.com/HTxyt78.png)

# 基本推廣途徑

- [Chatbot Developer Taiwan](https://www.facebook.com/groups/chatbot.tw/)
- [LINE Developer Groups Taiwan](https://www.facebook.com/groups/linebot/)➡️ 建議有 LAE or LINE 相關
- [Facebook Developer Circle](https://www.facebook.com/groups/DevCTaipei/)➡️ 建議 Messenger 相關
- LINE 上有兩三個群組(`Chatbot TW`、`Chatbot Taiwan`、`線上讀書會`...)
- Telegram 也有群組

一般來說我會在 2.5 個禮拜前先開活動，在這時間中安排時間去其他各大社團轉發(有些需問管理者‼️)

# 場地

天瓏書局: 收費 100/每位會眾，場地約能容下 50 人左右，地點於火車站附近。
五倍紅寶石: 可協調到 50/ 人 的收費，場地是教室風格，擠一點也差不多 50 人，地點於火車站附近。
台北商業大學: 免費，需先聯絡 [溫教授](https://www.facebook.com/don.wen)，之後會有相關人員接洽。
Dcard: 後面收費似乎總共 4000/場，需要有相關朋友去協調，地點在國父紀念館附近

# 講者

## Keynote

Keynote 通常會邀請`兩位講者`，可用`聊天室`或`群組`集結大家一起發通知，若真的當月找不到講者也可以`一位`搭配多個`閃電秀`，並請講者於活動`前一個禮拜`提供簡報。

在發布內容上若講者尚未提供題目，先放上講者大名並且在之後再麻煩提供。

## 閃電秀

參考：https://hackmd.io/@chatbot-tw/meetups-020
講者們報名後透過 kktix 寄信告知他們需要在這提供`姓名`、`題目`、`簡報連結`，在活動時`主持人`才有項目可以叫號上台。

# 活動開始前

需要安排人員

- 主持人
- 驗票(1~2 人)
- 協調講者(keynote & lighting talk)
- 直播錄影

> 協調會眾去問講者問題

# 活動結束

要記得跟講者要簡報，請講者分享簡報於社團中，工作人員需整理並 push 至 meetups Github，依照月份好整理為主。

> [連結](https://github.com/Chatbot-Taiwan/meetups)

請到 Github 上**更新小聚資訊**(PR, Commit)去更新，

- KKTIX
- Video
- 講者簡報
- 閃電秀
- 共筆連結

範例為下圖，左上角有一個連結的部分，點下去後網址會把 id 放上去，將網址貼到社群上分享給大家點選(會直接到這部分)

![](https://i.imgur.com/3aCjthF.png)

- 更新完講者們的資訊去 github 之後邀請講者與閃電秀講者於社團分享
- 閃電秀可透過 KKTIX 去寄信邀請分享

# 直播系列

## 線下小聚直播

最簡單可以先使用`手機`，若有相關設備的話就使用 webcam+OBS 來直播。

> 這邊以 Apple 系統為範例

- 腳架
- iPhone XR
- 外接麥克風 (強烈建議)

iOS 到 APP store 下載 Streamlabs
參考我之前的文章 - [第一次直播就上手 (1)】使用 Streamlabs 在 Youtube 上直播](https://nijialin.com/2020/03/21/%E3%80%90%E7%AC%AC%E4%B8%80%E6%AC%A1%E7%9B%B4%E6%92%AD%E5%B0%B1%E4%B8%8A%E6%89%8B%E3%80%91%E4%BD%BF%E7%94%A8-Streamlabs-%E5%9C%A8-Youtube-%E4%B8%8A%E7%9B%B4%E6%92%AD/)

登入 chatbot taiwan 的 youtube 帳號

XR 的畫質目前是不錯，只缺收音部分需要有獨立**_麥克風_**來讓收音更好，`筆電`與`手機`的內建麥克風不推薦使用

## 使用電腦直播(線上/線下)

- 硬體
  - 筆電(建議桌電)
  - 外接麥克風 (不推內建)
    - 講者一定要有麥克風，否則很容易遇到回音問題而流失觀眾。
  - 外接攝影機 (同上)
    - 如果有面對面跟講者的話建議就是開視訊鏡頭調整 OBS 的輸出部分即可。
- 軟體
  - OBS
    - Mac 需要安裝 SoundFlower(x64): 因為一般筆電都只有單音軌，一個解法是買硬體混音器(Mixer)，另一個就是安裝這個軟體去建立虛擬的雙音軌來模擬。
  - Youtube
    - 直播影片儲存位置，可以拉下來再剪成講者片段
  - Google meet (因疫情免費了！)
  - Zoom

## 直播影片

因為直播後會有 VOD 存在 youtube 上，以下會有兩種方法：

### 剪影片

使用 [youtube-dl](https://github.com/ytdl-org/youtube-dl) 下載影片後，用 iMovie 簡單將每位講者的部分剪下來後再重新上傳 youtube 上，並且把活動資訊都放上去。

範例：

```
簡報: https://docs.google.com/presentation/...
GitHub: https://github.com/Chatbot-Taiwan/mee...
臉書社團: https://www.facebook.com/groups/chatb...
共筆: https://hackmd.io/@chatbot-tw/meetups...

#LINE #Google #LIFF #Firebase
```

> 參考： https://www.youtube.com/watch?v=U_nPlkTuk9s

### 標時間

Youtube 中可以使用時間區段來區分，如此一來也能讓使用者透過點時間區間前往想看的講者上。

# 開 meetup issue

管理者開當月社群日的 issue 讓其他人可以透過 Pull Request 來貢獻社群頁面，如此一來也可降低工作人員的 loading 並可詢問該貢獻者是否願意加入社群幫忙。

# 最後

若有什麼問題每位管理員都可去詢問，大家都很樂意會幫忙，藉由社群把大家凝聚在一起，鼓勵會眾與工作人員把握機會
與大家交流，這些機會真的都很難得(畢竟免費的活動)，希望你/妳能夠創造不同風格的社群風格，並藉由社群發展出不一樣的自己的路，加油！
