# Azure上にWebアプリをPythonで作る  

## how to run
```
python3 main.py
```
ブラウザで127.0.0.1:5000にアクセスすると、立ち上がっていることが確認できる。

## pip install
* numpy
* pandas
* flask
* plotly

## Reference
* [ウェブアプリケーションフレームワーク Flask を使ってみる](http://qiita.com/ynakayama/items/2cc0b1d3cf1a2da612e4)
* [Python Flask app on Azure App Service Web](https://github.com/Azure-Samples/python-docs-hello-world)

## 設定  
Azureポータルの自分が作ったアプリの「設定」の「アプリケーション設定」一番下の「仮想アプリケーションとディレクトリ」で  
「仮想ディレクトリ」 /post   
「サウトルートを基準とした物理パス」 site\wwwroot  
「アプリケーション」 にチェック  
で可能  

