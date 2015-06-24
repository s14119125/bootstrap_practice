# s14119125 筆記

至sites新增資料夾 (ex:bst) 拉到sublime      
在bst裡新增檔案index.html 內容打html按Tab鍵      
改`<html lang="utf-8">`      
在`<body>`裡新增`<h1>`文字`</h1>`.`<p>`.`<h2>`.`<p>`.`<button>`.`<button>`.`<h3>`.`<p>`      
在`<head>`裡打link按Tab鍵 . 至bootstrap下載. 把三個檔案(css.fonts.js)拉到bst裡. 再至link這行後面改href="css/bootstrap.css"      
在`<body>`行上面,去bootstrap網站 . Getting strat . 右邊Basic template . 複製這兩行,貼上      
`<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->`      
`<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>`      

`<div class="row">`  增加可讀性(    
加間隔  在分欄位後打col-md-offset-1 (左右各縮1)      
(ex: class="cd-md-10 col-md-offset-1"      
後面再加class="cd-md-0 , 拉大就可正常      

`<div class="row text-center">`  文字置中      
◎font-family 選字體之網頁      
改字體 另開一個css(new file) 名字main.css 存檔      
打body{ 　 font-family: "字體"; }      
在index.html 的分欄位後打 features (接關聯      
`<div class="lead">` 凸顯字      

改圖示大小顏色 在main.css打 .features .glyphicon { font-size:32px; color:red; }      

在最下面做頁腳      
`<footer class="container-fluid">`      
到main.css打footer{ background-color:顏色; }      
`<div class=".....">`      
`<h4>`Links`</h4>`    
`<ul class="list-unstyle">` (加了就無點      
`<li><a href="網址">`home`</a></li>` (連結網址      
`<li><a href="網址">`contact`</a></li>`       
`<li><a href="網址">`news`</a></li>`        
