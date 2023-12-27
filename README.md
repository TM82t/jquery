# jQuery
## jQueryについてまとめていく
### jQueryの読み込み
jQueryを使用するにはjQueryライブラリを読み込む必要がある。  
ライブラリはインターネット経由で読み込むのが一般的。  
<head>タグの中でURLを読み込むことで、jQueryが使用できるようになる。
  
jQueryは、.js形式のファイルにコードを書く。  
HTMLファイルで、<script  ="ファイルのURL"></script>と書くことで、jQueryのコードを記述するファイルが読み込まれる。  
<script>はCSSファイルの読み込みのように<head>タグの中にも書けるが、<スラッシュbody>の直前に書くことで、WEBページの表示速度をより早めることが出来る。  
  
jQueryはHTMLの中身を操作するため、HTMLの読み込みが完了してからjQueryによる操作を開始するようにする。  
そのためにはreadyイベントを使用。  
  
### モーダル
モーダルとはclickイベントなどに基づいて、表示/非表示が行われる要素のこと。  
手順は以下の3つ。  
①モーダルをcssで非表示に。  
②scriptでログインボタンにclickイベントを設定。  
③clickイベントでモーダルを表示。  
