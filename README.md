# 熊本震災情報地図化作業

## 避難所位置情報地図化

 <http://kumamoto-jishin.info/>   
  こちらのサイトに投稿された避難所情報を地図上で表示するためのデータです


### 元データ
 <https://docs.google.com/spreadsheets/d/14mJE_jmy2Jg9QNDyD0qVuqHNRn5WgYWKi40kWvwQvks/edit#gid=1336152339>

### 避難所位置情報です。
住所からのジオコーディング東京大学空間情報科学研究センターのアドレスマッチングサービスを利用しています　
  http://newspat.csis.u-tokyo.ac.jp/geocode/



### 作業用データ　（19日11時30分時点ぐらいの元データでやっています）
 <https://docs.google.com/spreadsheets/d/14e-jP6SuGkg2Eics88hn8JmJtZPPhpgG1JBt3XrqrtI/edit#gid=0>


*kumamoto_hinanjyo.csv  ジオコーディング前のCSVファイル
*kumamoto_hinanjyo_r.csv　　ジオコーディング後のCSVファイル
*kuamoto_hinanjyo.geojson　 ジオコーディング後CSVファイルをQGISでgeojson に変換したもの

###  QGIS
 <http://qgis.org/ja/site/>
 
*座標付きCSVファイルをQGISのレイヤとして読み込む（デリミテッドテキストレイヤとして取り込む）
*作成されたレイヤを選択して「名前をつけて保存」を行う。このときダイアログで保存形式をgeojsonにする。文字コードをUTF-8に指定しておく必要あり

### Google MyMap上での表示
 <https://www.google.com/maps/d/u/0/edit?mid=zTITpaHM4Qn8.kkz8LVwMWFTE>
