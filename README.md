# 生のスパムメールを回帰分類する。
<br> 生のスパムメールのデータを機械学習に適したデータに変換してから回帰分析をした。</br>
## 説明
生のスパムメールのデータをTF-IDFを使って機械学習に適した数値データに変換をしてからロジスティック回帰分類器で分類した。

### 実行した環境
<br>mac os</br>
<br>python 3.6.2</br>
<br>numpy 1.13.1</br>
<br>pandas 0.20.3</br>
<br>matplotlib 2.0.2</br>
<br>scikit-laern 0.19.0</br>
## 今後の方針
学習曲線からモデルが過学習していることがわかった。TF-IDFを細かいパラメータを調整をすれば過学習は抑えることができたかもしれない。また、試した回帰分類器がロジスティック回帰だけだったので別のモデルも試そうと思う。
## データの参照
<br>UCI Machine-Lerning Repository  http://archive.ics.uci.edu/ml/machine-learning-databases/00228/smsspamcollection.zip</br>
### 参考文献
Pyhon機械学習プログラミング　達人データサイエンティストによる理論と実践
<br>著者:Sebastian Raschka  監訳者：福島慎太郎</br>



