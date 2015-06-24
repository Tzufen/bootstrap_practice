14119105 行銷一甲 張慈芬
<OL>
環境安裝：
<LI>搜尋Bootstrap網站
<LI>Download Bootstrap
<LI>解壓縮
<LI>	將CSS、fonts、js這三個資料夾丟到Sublime Text 3
<LI>建立新檔案index.html
<OL/>

小小偷吃步
1.	搜尋Sublime Text 3 package control→ ctrl+C 到sublime
2.	套件安裝：Sublime→ ctrl + ` →ctrl+V
3.	安裝完成 ctrl+shift+P →install → emmet (語法)
4.	Ctrl+shift+p → install→html 找 HTML Beautify→ ctrl+Alt+shift+F (排版)

Bootstrap：
Html+ tab鍵
 <!DOCTYPE html>
   <html lang="utf-8">
  <head>  
<title> 大標題  </title>
Link+Tab ↓
    路徑<link rel="stylesheet" type="text/css" href="css/bootstrap.css"> 
    連結<link rel="stylesheet" type="text/css" href="css/main.css">                         
  </head>
  <body> 
頁面導覽列<div class='navbar navbar-default navbar-static-top '> 
      <div class="container" >
        顯示在標題下<div class='navbar-header'> 
          標題<a href='index.html' class='navbar-brand'>TED talk</a> 
          <button type='button' class='navbar-toggle'  螢幕縮小時按鈕(手機版)
          data-toggle='collapse'
          data-target='.navbar-collapse'>
          <span class='sr-only'> 選項 </span> 
          <span class='icon-bar'></span>   一行一條線
          <span class='icon-bar'></span>
          <span class='icon-bar'></span>
          </button>
        </div>
        <ul class='nav navbar-nav navbar-right collapse navbar-collapse'> 
          <li><a href='index.html'> </a></li>副標項目
        </ul>
      </div>
    </div>
   <div class="container">
     <div class= row> </div> 建立類別
    <div class="col-md-4"> 顯示4格(最多12)
    <div class='col-md-offset-1 '></div> 間格
    <h1></h1> 、<h2></h2>  字體大小 
   <p></p> 段落內文
     <h3 class=" well"></h3>  well小框框
<button type='button'> </button>按鈕
<i class=" "></i> 到bootstrap的components裡選想要的符號
<img src=" " style=" ">照片，後面是顯示大小
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
  <script src="js/bootstrap.js"></script>
  </div>
 </body>
</html>

欄位: class=’col-md-4’大螢幕所顯示格數  ‘col-sm-4’ 小螢幕所顯示格數
隱藏: hidden-(xs/md/sm/lg) 顯示: visible-(xs/md/sm/lg)
行高: line-height
字型: font-family字體大小: font-size
置中: text-center
顏色: color背景顏色: background-color
按鈕大小: .btn-xs .btn-sm .btn-lg
按鈕顏色: class="btn btn- "紅色Danger白色Default綠色Success藍色primary橘色Warning  沒有方框會顯示藍色底線Link
導覽列顏色: 黑色.navbar-inverse白色.navbar-default
頂端橫幅會移動.navbar-static-top不會移動.navbar-fixed-top
.nav 整個導覽列.navbar
