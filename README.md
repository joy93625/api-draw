# apidraw
api 抽獎活動
API 的網址：https://dvwhnbka7d.execute-api.us-east-1.amazonaws.com/default/lottery

用 GET 即可，API 會回傳一個 JSON 格式的物件，內容為：

`{
  prize: "獎項名稱"
}`

API 會按照機率回傳不同的獎項名稱，請你針對不同的獎項名稱做處理。

獎項名稱一共有四種：FIRST、SECOND、THIRD 以及 NONE。

1.FIRST，頭獎，在網頁上顯示字樣：「恭喜你中頭獎了！日本東京來回雙人遊！」，並且把背景改成這張圖片。

2.SECOND，二獎，在網頁上顯示字樣：「二獎！90 吋電視一台！」，並且把背景換成這張圖片。

3.THIRD，三獎，在網頁上顯示字樣：「恭喜你抽中三獎：知名 YouTuber 簽名握手會入場券一張，bang！」，並且在網頁上放這張圖片。

4.NONE，銘謝惠顧，在網頁上顯示字樣：「銘謝惠顧」，並且把圖片的部分變成黑底，文字顏色變成白色。

