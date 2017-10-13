[　製品名　] BDF フォントをC言語の配列に変換 Ver.1.0
[ファイル名] bdffta.exe
[バージョン] 1.0
[　 作者 　] いののて
[　連絡先　] InoueSoftware@excite.co.jp、https://twitter.com/inonote
[　　HP　　] http://inoueeee.mitarashidango.com/

BDFフォントをC言語の配列に変換するツールです。
BDFフォントの改行コードをCR+LFにしておく必要があります。

●使用方法
　コマンドプロンプト名でパラメーターを付けて実行します。
　
　bdftta [*.bdf] [*.c] [*.h] [Array Name] [Width] [Height] [Include File Name]
　・[*.bdf]　・・・・・・・・・　変換するBDFファイルです。
　・[*.c]　　・・・・・・・・・　出力するソースコードの名前です。
　・[*.h]　　・・・・・・・・・　出力するヘッダーファイルの名前です。
　・[ArrayName]　　・・・・・・　配列変数の名前です。
　・[Width]　・・・・・・・・・　フォントの半角幅です。(4以上8以下)
　・[Height] ・・・・・・・・・　フォントの高さです。　(8以上16以下)
　・[Include File Name]　・・・　ソースファイルに挿入するインクルードファイル名を指定します。(省略可)
　　
　処理は2分から15分ほどで終わります。(PCのスペックによる)

[EOF]