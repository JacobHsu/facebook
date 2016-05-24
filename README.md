# facebook

[facebook for developers](https://developers.facebook.com/)  

設定 / 網站 / 網站網址
`http://localhost:20081/mysite`

# share-button

[facebook for developers](https://developers.facebook.com/)  

應用程式審查 / 是否發佈 project？

是 (須設定email)

[「分享」按鈕](https://developers.facebook.com/docs/plugins/share-button?locale=zh_TW)  

### Facebook 分享網址的 Cache 清除

主要原因在於 Facebook 會將此網址的內容預先抓一份 Cache 起來, 一段時間內都會用此 Cache, 所以, 這段時間內都不會再去抓取最新的資料, 所以 解法就是要清除 Facebook 的 Cache, 可依照下述解法來作:

1. 到此網頁: [Sharing Debugger](https://developers.facebook.com/tools/debug)
2. 貼上目前 Cache 舊資料的網址, 執行`Scrape Again`, 再去 Facebook 的頁面貼貼看, 就會抓到新資料了.
