# TechBookBaysianChocoball

本リポジトリは、チョコボール統計研究所が作成するテキスト「エンゼル出現確率を題材にベイズモデリングにより運の量を定量化する」(技術書典8, Day1「か25」)のサポートページです。

テキスト内で紹介するソースコードをまとめています。

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
- data
  - 本書で実際に利用したデータ
- basic_distribution.ipynb
  - 3章で紹介する確率分布の可視化コード
- analyze_luck.ipynb
  - 4章で実際にエンゼル出現確率の推論に利用したコード
- appendix_estimate_angel_rate.ipynb
  - 付録A
- sample_pymc3.ipynb
  - 付録B
  - PyMC3の基本的な書き方
  - 正確には、[公式ドキュメント](https://docs.pymc.io/)を参照



