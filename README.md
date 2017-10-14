# 用 <a> 下載檔案

要使瀏覽器下載檔案有幾種方式：
- 使用者自己右鍵，另存
- 在 server 端特定加 HTTP header (see https://developer.mozilla.org/zh-TW/docs/Web/HTTP/Headers/Content-Disposition)
- 在前端使用 `<a href="data.csv" download>data.csv</a>`

如果要指定檔案名稱可以用：`<a href="data.csv" download="filename.csv">data.csv</a>`


DEMO網址： https://iampaul83.github.io/download/
