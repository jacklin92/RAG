## 執行流程

1. 去.env 設定要串 RAG 的帳號，密碼要用 app password 申請不然會被擋 
2. 執行 collect.ipynb 產生供檢索的資料 
3. 確認 config.yaml 的模型沒問題 
4. 執行 email-rag.ipynb
