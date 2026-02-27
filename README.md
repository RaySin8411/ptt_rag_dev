## 專案簡介
本專案整合下列技術模組：
模組                | 功能 
-------------------------|------	
PTT 爬蟲	      | 定時抓取特定看板最新文章
RAG 架構	      | 結合檢索 + 生成提升問答準確率
Celery + Redis	| 實現爬蟲排程與非同步處理
MariaDB	        | 儲存爬取文章與紀錄任務 log
DRF	            | 提供 REST API 查詢與問答
Pinecone	      | 向量儲存與語意搜尋
Gemini API	    | 以上下文生成自然語言回答
Docker	        | 開發與部署一鍵完成

## 系統架構圖
![系統架構圖](https://ithelp.ithome.com.tw/upload/images/20250522/20172834K6rthNvWvg.png "System Architecture")


## Reference
[2025 iThome 鐵人賽 - 一起來打造 PTT 文章智慧問答系統](https://ithelp.ithome.com.tw/users/20172834/ironman/8156)
