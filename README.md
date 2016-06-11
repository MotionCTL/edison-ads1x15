# edison-ads1x15

弊社Henryボード用のリポジトリです。  
Intel様のupmからADS1015関係だけ抜き出しました。  
Henryボードは拡張スルーホールのi2cのバス接続は6へ接続しているのでサンプルやヘッダファイルの調整もしてあります。  
残念ながらupmの方でexamplesのpythonが対応していないの外しています。  
手順は下記の通りです。  
`git clone https://github.com/MotionCTL/edison-ads1x15.git`  
`cd edison-ads1x15`  
`cmake .`  
`make`  
`make install`  