# このチュートリアルについて

このチュートリアルでは実際のデータを使ったコーディングを行うことで実践力をつけることを目的とします。扱う事例はタイタニックの乗客データを使った生存者推定モデルの生成です。乗客の年齢、性別、その他の情報を機械学習アルゴリズムに学習させることで、初心者でも80％に近い精度で生存者を当てることができるようになります。

### 使用するデータ

タイタニックの乗客データ： [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic-gettingStarted/data)

### 使用するパッケージ

下記バージョンでの動作検証を行っております。

- IPython 3.6.0
- numpy 1.12.1
- pandas 0.20.1
- matplotlib 2.1.0
- scikit-learn 0.15.2

### パッケージ導入方法

以下のいずれかの方法をお試しください。

1. Anacondaを導入する（初心者向け）<br>
[Anaconda](https://store.continuum.io/cshop/anaconda/)は、データ分析に利用できるPythonパッケージをまとめて配布しているディストリビューションです。Win / Mac / Linux いずれにも導入可能です。[Anacondaダウンロードページ](http://continuum.io/downloads)にアクセスして、インストーラーのダウンロードとインストールを行って下さい。

2. 各パッケージをpipインストールする<br>
[Python3.5](https://www.python.org/downloads/release/python-352/)の導入後、次のコマンドで各パッケージをインストールしてください。<br>
     <br>
     pyvenv pydata-t1<br>
     source pydata-t1/bin/activate<br>
     pip install numpy<br>
     pip install scipy<br>
     pip install pandas<br>
     pip install scikit-learn<br>
     pip install ipython[notebook]<br>
     pip install matplotlib

