# TechBookBayesianChocoball

本リポジトリは、「チョコボールのエンゼル出現確率をベイズ推定する」(技術書典7, 2F「く29D」)のサポートリポジトリです。

書籍内で紹介するソースコードをまとめています。


## 実行環境
動作確認済みの環境は以下の通りです。
バージョンは多少前後しても問題ないはずです。

### Pythonバージョン
- Python==3.7.3

以下、requirements.txt参照

### 環境構築
- Google Colabの利用(推奨)
  - [参考記事](https://learning-with-machine.hatenablog.com/entry/2019/05/31/010459)

- ローカルに環境構築
```
$ pip install -U pip
$ pip install -r requirements.txt
```


## 構成
- sample_pymc3.ipynb
  - PyMC3の基本的な書き方
  - 正確には、[公式ドキュメント](https://docs.pymc.io/)を参照
- basic_distribution.ipynb
  - 3章で紹介する、確率分布の可視化コード
- tech_book_choco.ipynb
  - 4章で実際にチョコボールのエンゼル出現確率を推定するコード
