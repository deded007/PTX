# 【URI命名原則】


開放資料可透過URL方式取得資料。

Web API (application programming interface) 的表現方式，分為網站根目錄(App Root)、資源路徑(Resource Path)和查詢選項(Query Options) ![ ](https://ptx.transportdata.tw/PTX/Content/Images/sample_06.jpg)



- 網站根目錄：應用服務的基本網址，主要組成為(Domain)網域名稱和(App)應用程式名稱，並且透過 HTTP 協定連結而形成服務的基本網址。

    Domain: ptx.transportdata.tw

     App : MOTC或PTX
     
- 資源路徑：指定資源項目路徑名稱。
 

| 目錄結構 |  意義  |
| :--: | :--------: |
|  Version(版本)|提供服務的版本號。目前提供 v1(第一版)，若沒有輸入，則預設最新版本 |
| Service(服務)|依據載具本身提供的服務，例如:鐵道:台鐵(TRA)、高鐵(THSRC)，空運:航空(Aviation)，道路:公車(Bus)等等。|
| Application(應用內容))| 根據每個服務而提不同的應用內容，例如:航空:航班資訊(FIDS)和機場資訊(Airport)等。|


- 查詢選項：指定欲取得資料的範圍或查詢的條件。

- PTX API URI說明文件詳見連結請詳見[連結](http://ptx.transportdata.tw/ptx/Download/API_URI_Convention文件_v1.pdf)。