
[StackEdit](https://stackedit.io/)を使ってBloggerのコンテンツの作成を始めました。
イマイチ使い方が分っていないので今後改善したいと思います。
先人のノウハウを使わせて頂いております…

## 画像
Googleアカウントと関連付けしておけば、Google Photoにある画像を参照出来ます。
![enter image description here](https://lh3.googleusercontent.com/z3Oyp0-nFZ4BNEag22OQ3F4Sd9gCr9-PuaDGb24cx5iZODpifsYh68xFmgRvefHoporpGHHgeSlm "Coffee＆PC")

画像のリンク
![enter image description here](https://lh3.googleusercontent.com/WYpURKGjDK0VynLO3BqMv6xptgSvSexERSEWeLq3K36Oa9q4XieddpteKtcb1Z1xu6_2irrlNEAc "Coffee")
[enter link description here](https://lh3.googleusercontent.com/WYpURKGjDK0VynLO3BqMv6xptgSvSexERSEWeLq3K36Oa9q4XieddpteKtcb1Z1xu6_2irrlNEAc)

画像を選択してPopupさせたい場合
[
![Coffee](https://lh3.googleusercontent.com/WYpURKGjDK0VynLO3BqMv6xptgSvSexERSEWeLq3K36Oa9q4XieddpteKtcb1Z1xu6_2irrlNEAc "Coffee")](https://lh3.googleusercontent.com/WYpURKGjDK0VynLO3BqMv6xptgSvSexERSEWeLq3K36Oa9q4XieddpteKtcb1Z1xu6_2irrlNEAc)



## Link
[Microsoft MSDN Home](https://msdn.microsoft.com/ja-jp/dn308572.aspx?f=255&MSPPError=-2147217396)
[自分のブログ](https://kkoba-memo.blogspot.com/)

## 引用
CSSをBloggerのテーマに設定しています。

> **1.「名前付きインスタンス」のリモート構成手順**   名前付きインスタンスのリモート構成は以下の手順で行う。  
> 
> 1.  TCP/IPの有効化
> 2.  SQL Serverのサービス再起動
> 3.  TCP/IPのプロパティで動的ポートを使用可能にする
> 4.  ファイアウォールの受信の規則でUDP1434を許可
> 5.  ファイアウォールのアプリケーションルールの設定でSQL Serverの実体(Sqlservr.exe)に対して受信許可を設定する
> 6.  SQL Server Browserを有効化する

## Code
Bloggerのテーマを編集してCSSとJSを追加します。
[BloggerでMarkdownのシンタックスハイライト](https://djeeeno.blogspot.com/2018/01/20180113-01-blogger-markdown-highlight-01.html)
Syntax highlight for the Web
[highlight.js](https://highlightjs.org/)

    SELECT @@VERSION;
    
    Use[MyStockDB]
    
    DECLARE @Name varchar(100) = 'トヨタ'
    
    SELECT * FROM vwCodeList AS X
    WHERE X.Name Like '%' + @Name + '%'
    
    SELECT * FROM tblStockTradeJP AS X
    WHERE X.StockCode = '7201'
    ORDER BY X.TradeDate DESC

## Table
細かいスタイルの指定は知らない…ので下記を参考
[StackEditの表をBloggerできれいに表示](http://tsukiyomiloveseverything.blogspot.com/2017/01/stackeditblogger.html)

BloggerにCSSを追加する方法
[【Blogger】HTMLやCSSの編集方法、追加方法！](https://vaster2customtom.blogspot.com/2017/04/1.html)

|Item|Value|
|--|--|
|PC|Surface Laptop|
| CPU | Intel Core i5-7200U @2.5GHz |
| Memory| 8GB|
|OS|Windows 10 Pro 64bit <br/> Build: 17763|


# まとめ
以前の記事でTableタグを使って２段組みにしていた部分がすべて作り直しに… 面倒なのでdivタグのwith属性だけで何とかするか。
コード部分のCSSについてはダメダメなので改善したい…
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg0MzY2MTk5NiwxODU3Mzc0Mzk0LC0xND
YwNzMzOTQ1XX0=
-->