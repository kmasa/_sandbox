matharea-js
===========

HTML5 のキャンバス機能を使い、数式の表示・編集機能を提供します。


Install
---------

1. <url> からファイルをダウンロード
2. HTML に script タグを追加
3. ```<object class="matharea">``` タグを追加




TODO
----

 * MathML 入出力
 * LaTeX 入出力

開発環境構築
------------

1. node.js をインストール

2. ソースコードをクローンして、依存ライブラリのインストール

	```
	git clone <url>
	cd <projename>
	npm install
	```

3. grunt コマンドの実行

	```
	grunt
	 ```

4. src/ 以下のcoffee ファイルを変更すると public/js/matharea.js, public/js/matharea.min.js が更新されます。

LICENSE
-------

MIT License


Home Page
---------

[http://media-plus.co.jp/](http://media-plus.co.jp/)
