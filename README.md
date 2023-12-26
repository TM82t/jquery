# jQuery
## jQueryについてまとめていく
### jQueryの読み込み
jQueryを使用するにはjQueryライブラリを読み込む必要がある。  
ライブラリはインターネット経由で読み込むのが一般的。  
<head>タグの中でURLを読み込むことで、jQueryが使用できるようになる。
```
<head>
 
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
  
</head>
```
   
jQueryは、.js形式のファイルにコードを書く。  
HTMLファイルで、<script src="ファイルのURL"></script>と書くことで、jQueryのコードを記述するファイルが読み込まれる。   
<script>はCSSファイルの読み込みのように<head>タグの中にも書けるが、</body>の直前に書くことで、WEBページの表示速度をより早めることが出来る。
```
<body>
  <script src="script.js"></script>
</body>
```
  
jQueryはHTMLの中身を操作するため、HTMLの読み込みが完了してからjQueryによる操作を開始するようにする。    
そのためにはreadyイベントを使用し、「$(document).ready()」の中身にjQueryの処理を書いていく。  
この構文には省略形も用意されており、$(function(){ });と書くことも出来る。右の図の書き方を覚えておきましょう。
