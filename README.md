# PyData.Tokyo Tutorial & Hackathon #1

[PyData.Tokyo](https://pydata.tokyo/)では毎月開催している中上級者向けの勉強会に加え、初心者の育成を目的としたチュートリアルイベントを開催します。今回のイベントでは下記の項目にフォーカスします。

- データの読み込み
- データの前処理・整形
- 集計・統計解析
- データの可視化
- 機械学習を使った分類モデルの生成
- モデル分類結果の検証

このチュートリアルでは実際のデータを使ったコーディングを行うことで実践力をつけることを目的とします。扱う事例はタイタニックの乗客データを使った生存者推定モデルの生成です。乗客の年齢、性別、その他の情報を機械学習アルゴリズムに学習させることで、初心者でも80％に近い精度で生存者を当てることができるようになります。

### イベント詳細
[PyData.Tokyo Tutorial & Hackathon #1](http://pydatatokyo.connpass.com/event/11860/)

### 使用するデータ

タイタニックの乗客データ： [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic-gettingStarted/data)

### 使用するパッケージ

- Python 3.4.3
- IPython 3.0.0
- numpy 1.9.2
- pandas 0.15.2
- matplotlib 1.4.3
- scikit-learn 0.15.2

### パッケージ導入方法

以下のいずれかの方法をお試しください。

1. Anacondaを導入する（初心者向け）
[Anaconda](https://store.continuum.io/cshop/anaconda/)は、データ分析に利用できるPythonパッケージをまとめて配布しているディストリビューションです。Win / Mac / Linux いずれにも導入可能です。[Anacondaダウンロードページ](http://continuum.io/downloads)にアクセスして、インストーラーのダウンロードとインストールを行って下さい。Anacondaダウンロードページにデフォルトで表示されているのはPython2.7系のインストーラーのため、「I WANT PYTHON3.4」を選択して、Python3.4系のインストーラーを入手できるよう切り替えて下さい。

2. 各パッケージをpipインストールする
[Python3.4](https://www.python.org/downloads/release/python-343/)の導入後、次のコマンドで各パッケージをインストールしてください。

    pyvenv pydata-t1
    source pydata-t1/bin/activate
    pip install numpy
    pip install scipy
    pip install pandas
    pip install scikit-learn
    pip install ipython[notebook]
    pip install matplotlib

## チュートリアル第1部 - データハンドリング

テキストは[こちら](https://pydata.tokyo/ipynb/tutorial-1/dh.html)

### 目的

- IPythonの使い方について学びます
- 第二部で利用するチュートリアル用のデータについて学びます。
- Pandasを使ったデータの前処理について学びます。
- matploblibを利用したデータの可視化について学びます。

### 講師
PyData.Tokyoオーガナイザー 池内 孝啓（[@iktakahiro](https://twitter.com/iktakahiro)）

## チュートリアル第2部 - 機械学習

テキストは[こちら](https://pydata.tokyo/ipynb/tutorial-1/ml.html)

### 目的

- 機械学習を使った分類モデルの生成
- 分類結果の検証

### 講師
PyData.Tokyo オーガナイザー 田中 秀樹（[@atelierhide](https://twitter.com/atelierhide)）
