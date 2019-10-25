# 成功電研33rd網管資格測驗 伺服器組 實作題 #
規則請看[說明](../README.md)  

## 題目開始 ##
### 1. virtualbox ###
請安裝virtualbox並新增一個虛擬機然後裝好ubuntu server 18.04

### 2. Apache ###
請於virtualbox VM（以下簡稱VM）中新增一個使用者並成功安裝apache2 server

### 3. web server ###
請於VM中架設一個簡單的網站，網頁至少三頁，內容可以只有標題和其他頁的連結
tips:這裡你可能需要更改本機的`/ect/hosts`設定（Linux）`C:\WINDOWS\system32\drivers\etc\hosts`(windows)

### 4. vhost ###
請於VM中架設三個簡單的網站（包含上題的網站），網頁要求同上題，要求如下
1. 三個網站使用不同的subdomain(例如：web1.localhost, web2.localhost)
2. 三個網站的根目錄不得重複
3. 盡量維持apache server 的可擴展性

### 5. vbox ip forward ###
請將VM的網路設定改成NAT，並讓你的電腦本身可以用瀏覽器連到VM內的網站

### 加分題 ###
這題需要研究，如果作不出來就先不要嘗試了  
架設一個網頁服務在同一台機器（gitlab, OnlineJudge, wikipedia等）  
並使用vhost + reverse proxy來達成只使用一個port存取多個網路應用程式（包括你本來的web server）


---

試題結束，請將VM匯出成.ova檔，上傳github
