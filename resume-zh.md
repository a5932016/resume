# 曾子言 (Zih Yan Tseng)

📧 Email: a5932016@gmail.com  
📱 Phone: +886-910-925-272  
🌐 GitHub: https://github.com/a5932016  
💼 LinkedIn: https://linkedin.com/in/a5932016  

---

## 專業簡介

經驗豐富的 Golang、C# 開發工程師，專注於高效能系統設計、資料處理與網路通訊。在網路通訊、醫療等多個產業擁有超過 6 年後端研發經驗，並參與過政府專案，具備政府資料串接與跨系統整合的實務經驗。熟悉 Golang 與 C#，能在高併發與跨網路環境中設計穩定、可擴展的解決方案。擅長從系統架構、資料庫優化到效能調校的完整開發流程，致力於打造可靠且高效的後端服務  

---

## 技能
- **程式語言**: Golang, .Net, JavaScript, Python, Bash  
- **框架與工具**: Gin, Django, React, Vue3, Flutter(基礎)  
- **資料庫**: MySQL, PostgreSQL, SQL Server, Oracle  
- **其他**: Git, Docker, GCP, Linux  

---

## 經歷

### 後端工程師 - 詮隼科技股份有限公司 (2022/09 - 2026/01)

- 使用 Golang + Postgresql 設計並開發 Edge Controller，負責核心業務邏輯與高併發網路處理  
- 將 5G CPE 網路功能從 Python 重構成 Golang，提高併發能力與系統響應速度  
- 設計並實作自動化裝置發現與接管機制，解決跨網段與 NAT 環境下的裝置管理問題
- 參與 VPN 開發，設計具 NAT Traversal 與 P2P/Relay fallback 的混合 VPN 系統，並透過 traffic shaping + packet batching 優化傳輸效能  
- 使用 RAUC + Golang 開發基於 LVM 的 A/B Boot OTA 升級機制，提升系統可靠性  
- 建立任務排程批次處理框架（Cron + Golang 實現），支援高併發任務調度  
- 設計高效資料查詢架構（Keyset Pagination + Sharding），將億級資料查詢速度提升至毫秒級  
- 開發 Edge Controller 測試工具（Golang + Container + Linux Namespace），模擬大規模 Edge 負載與 VPN 環境，並整合 Apache Bench 進行壓測  

技術: Golang, Python, PostgreSQL, Docker, Linux, VPN, RAUC  

---

### 軟體工程師 - 諾亞克科技股份有限公司 (2020/11 ~ 2022/02)

- 使用 C# + SQL Server + Bootstrap 設計並開發線上派車與後台管理系統  
- 負責 Android 派車預約系統 開發，實作訂單、行程管理與即時派單功能  
- 開發定時批次任務（C# + Schedule），自動化排程作業  
- 實作 JWT 驗證與 RBAC 權限控制，提升系統安全性與維護性  
- 設計並開發 跨平台即時通知系統，整合 Firebase Notification 與消息隊列，支援分組與預約推送，並透過重試機制確保高併發下消息可靠送達  
- 建立單元測試、自動化測試與壓力測試流程，並修正安全性漏洞，確保產品品質  

技術: C#, SQL Server, Bootstrap, Android, Batch  

---

### 初級開發工程師 - 東元醫療社團法人東元綜合醫院 (2018/04 ~ 2020/05)

- 使用 C# + .NET + Oracle 開發醫院 HIS 系統  
- 分析並解決資料庫 Deadlock 問題，顯著提升交易處理效能與穩定性  
- 成功執行 DB2 → Oracle 資料庫遷移，確保數據一致性與業務不中斷  
- 主導醫院掛號系統 RWD 化後端開發，提升跨裝置相容性  
- 建立快取管理機制（LRU + TTL），降低資料庫負載並提升響應效能  

技術: C#, .Net, SQL Server, Oracle, Web Form, Win Form, Batch  

---

## 學歷
**資訊管理學士** — 私立銘傳大學 (2014 – 2018)  

---

## 語言
- 中文 (母語)  
- English   

---

## 自傳

目前在 詮隼科技 擔任後端工程師，主要負責 Edge Controller 的設計與開發，使用的語言是 Golang。  

我先是完成5G CPE的Python 到 Golang的移轉，提升將近30%的效率；再來的任務是Edge Controller的開發，這個產品對我來說最大挑戰是保持Edge端的穩定性，在網路不穩的環境下對Edge管理和VPN網路，在這部分我有設計一套延遲處理的機制，確保設備的最終一致。  

我也參與 VPN 系統開發，設計具備 NAT 穿透 與 P2P/Relay fallback 的混合架構，並透過流量管控，區分大小封包後控制發送的先後順序，封包批次處理去優化效能，設計低延遲或高吞吐量的模式。  

在 資料處理方面，我設計過 keyset pagination 搭配 sharding 的查詢架構，把億級資料的查詢時間壓到毫秒級。  

並且為了增加產品的可靠度，還開發了 A/B Boot 線上升級機制，建立壓測工具模擬大規模 Edge 與 VPN 的流量，確保系統能穩定支撐實際場景。  

在這之前，我在 諾亞克科技 擔任軟體工程師，使用C#，工作是後端和後台管理系統和一些Android。
負責派車系統專案和其他政府專案。這份工作主要的挑戰是如何在網路不穩定的情況下記錄司機的位置、里程數、計費，以及通知管理機制，和串接政府資料。  

再早一些，我在 東元醫院 擔任軟體工程師，使用C#，開發HIS系統。  
在這份工作最大的挑戰是解決公司Deadlock的問題，這部分主要是流程的改善和資料庫優化，包括統一邏輯寫dll檔，因為公司有意把資料庫DB2到Oracle，所以重新設計資料庫的Index，並且平滑的移轉。  
因為公司的網路掛號是我負責的，考慮到系統畫面老舊，響應時間很差，我主動和主管提議改善，並且主導網路掛號的優化和RWD，優化完成後提升將近50%的反應速度。  

---
