# bdffta  
BDF フォントをC言語の配列に変換するツール  
**変換する前にBDFフォントの改行コードをCR+LFにしておく必要があります。**  
***
#### 使い方  
コマンドプロンプトでパラメーターを付けて実行します。  
 bdftta `*.bdf` `*.c` `*.h` `ArrayName` `Width` `Height` `Include File Name`  
  
 `*.bdf` : 変換するBDFファイルパス  
 `*.c` `*.h` : 出力するソースコードの名前  
 `ArrayName` : 配列変数の名前  
 `Width` `Height` : 半角のフォントの幅高さ  
 `Include File Name` : ソースファイルに挿入するインクルードファイル名(_省略可_)  
 　例) <windows.h> を指定した場合、出力するソースコードの頭に、`#include <windows.h>`が挿入されます。  
  
 ●処理は2分から15分ほどで終わります。(PCのスペックによる)  
