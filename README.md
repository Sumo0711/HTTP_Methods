# HTTP Methods   
HTTP 請求（HTTP Methods）定義了客戶端對伺服器資源的操作方式，最常見的方法有：  
- `GET`：取得資料  
- `POST`：傳送資料  
- `PUT`、`DELETE`：（進階）用於更新與刪除資料  
## GET  
用來從伺服器「取得資料」，例如搜尋、瀏覽網頁。  
資料附加在 URL 後方，例如： https://example.com/search?keyword=apple  
- 適合查詢類行為（不更動資料）  
- 安全性較低，資料顯示於網址  
- 有長度限制（URL 通常限制約 2048 字元）
  
## POST  
用來向伺服器「提交資料」，例如註冊、登入、留言。  
- 資料放在 request body 中，不顯示在網址列  
- 安全性較高，資料藏於封包中   
- 沒有明確的資料大小限制（受伺服器限制）  
- 可改變伺服器的資料狀態（新增、修改等）
＃# 範例  
https://sumo0711.github.io/HTTP_Methods/  