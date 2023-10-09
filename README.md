# NoActive2-Mod
在NoActive v3正式發佈前體驗更好的NoActive

## 目前與NoActiveV2原版的區別
1. 流暢度增加
2. 修復MiPush通知無法喚醒進程
3. FCM推送臨時解凍
4. 網絡解凍(僅限MIUI)
5. 進程音視頻播放解凍
6. Android 14 兼容性更新
7. 支持多開應用凍結
8. 支持關閉日誌

## 提示
與最新版NoActiveV2和內測版NoActiveV3配置文件不兼容

## 下載地址
https://github.com/Nep-Timeline/NoA-Mod/releases

https://123pan.com/s/h1szVv-FKV1H.html

## 更新日誌

21.0 -> 21.5
1. 更新凍結邏輯，提高穩定性和成功率

20.0 -> 21.0
1. 嘗試修復某些進程不凍結

19.0 -> 20.0
1. 嘗試解决卡解凍
2. 修復廣播bug

18.5 -> 19.0
1. 更新凍結判斷邏輯
2. 增强兼容模式體驗，修復一些兼容模式bug

18.0 -> 18.5
1. 更新解凍邏輯

17.5 -> 18.0
1. 優化臨時解凍
2. 優化息屏doze

17.0 -> 17.6
1. 修復幾個重大bug

16.0 -> 17.0
1. 添加兼容模式開關
2. 增強凍結

15.0_T -> 16.0
1. 修改息屏Doze邏輯
2. 修復日誌報錯

14.0_M -> 15.0_T
1. 修復廣播bug
2. 修復进程bug

13.0_N -> 14.0_M
1. 修復一些解凍bug以及凍結bug

12.9_Q2 -> 13.0_N
1. 修復解凍bug
2. 兼容性更新

12.8_L2 -> 12.9_Q
1. 再次嘗試修復不凍結bug

12.8_L -> 12.8_L2
1. 修復息屏Doze潜在bug

12.7_P -> 12.8_L
1. 再次修復某些进程不凍結的bug
2. 更新視頻播放檢測

12.6_S3 -> 12.7
1. 嘗試修復某些进程不凍結的bug

12.6_S2 -> 12.6_S3
1. 修改檢測邏輯來修復一些bugs

12.6_S1 -> 12.6_S2
1. 再次嘗試修復进程凍死問題

12.6_S -> 12.6_S1
1. 修復嘗試凍結系統框架的bug

12.5_R3 -> 12.6_S
1. 修復日誌報錯
2. 可能修復进程凍死問題
3. 修復FCM解凍獲取UserID

12.0 -> 12.5_R
1. 重寫进程獲取及解凍凍結邏輯
2. 修改息屏Doze邏輯
3. 增强前後臺算灋嘗試修復強制凍結bug

11.9 -> 12.0
1. 修改凍結及解凍邏輯
2. 添加檢測Binder狀態開關（默認無需開啟）

11.85 -> 11.9
1. 減少兼容性衝突
2. 修改廣播HOOK邏輯

11.8 -> 11.85
1. 修復解凍bugs

11.7 -> 11.8
1. 修復bug

11.6 -> 11.7
1. 修復bug，提升穩定性

11.3 -> 11.6
1. 嘗試提高解凍速度
2. 修復日誌uid not found警告

11.2 -> 11.3
1. 降低臨時解凍時長

11.1 -> 11.2
1. 修復凍結以及解凍的潛在bug
2. 添加檢測以防app在同一時間解凍或凍結多次

11.0 -> 11.1
1. 調整後台播放解凍延遲為3s
2. 優化binder解凍

10.9 -> 11.0
1. 提高解凍速度

10.7 -> 10.9
1. 修復bugs

10.5 -> 10.7
1. 將後台播放選項移動至後台級別中

10.0 -> 10.5
1. 修復binder解凍bug
2. 在應用內添加凍結binder開關
3. 修復UI的一個bug

9.2 -> 10.0
1. 優化binder凍結邏輯

9.1 -> 9.2
1. 修復後台播放UID分割錯誤及判斷錯誤

9.0 -> 9.1
1. 修復UI頁面開啟後台播放後會顯示其他配置

8.6 -> 9.0
1. 支持關閉日誌

8.5 -> 8.6
1. 添加息屏doze開關（以前強制開啟）

8.2 -> 8.5
1. 修復一些潛在漏洞
2. 修復FCM喚醒檢測
3. 修復音視頻解凍的一個bug

8.1 -> 8.2
1. 嘗試修復音視頻APP不會凍結的bug

8.0 -> 8.1
1. 嘗試修復QQ循環解凍凍結的bug

7.66 -> 8.0
1. 支持多開應用

7.65 -> 7.66
1. 修復網絡解凍bug

7.55 -> 7.65
1. 修復凍結bug及解凍速率

7.5 -> 7.55
1. 修復系統自帶app不凍結的bug

7.15 -> 7.5
1. 修復一個因為自己笨蛋而導致的後台播放無法凍結視頻APP

7.1 -> 7.15
1. 修復解凍bug

7.0 -> 7.1
1. 提高解凍效率
2. 嘗試修復音視頻app停止播放但不凍結的bug

6.0 -> 7.0
1. 更改凍結和解凍邏輯
2. 將網絡解凍開關移動至應用內選項

5.2 -> 6.0
1. 修復潛在bug
2. 修復舊版安卓系統日誌報錯
3. 優化凍結及解凍

5.1 -> 5.2
1. 優化凍結

5.0 -> 5.1
1. 優化凍結

4.0 -> 5.0
1. 修復不凍結的bug

3.1 -> 4.0
1. 優化凍結速度
2. 優化凍結算灋

3.0 -> 3.1
1. 修復Android 10的一些bug
2. 嘗試提高凍結速度

2.2 -> 3.0
1. 修復舊版安卓機型FCM解凍Hook報錯
2. 流暢度增加
