# movie-review-analysis

## 設計メモ


### 構成
* WebはRuby(Rails） & 分析はPython(FastAPI)
* MySQLを使う
* それぞれ全部docker-composeで起動する
* 最初はEC2運用
* フロントエンドはNuxt3

### 機能

* URL入力したら、クローラーが動く仕組み用意
    * クローラーは・・・・Pythonでもい
* 収集した記事を元に分析する
    * 最初はワードクラウドでいいやe
    * 本当は先にやってた人がいるけど、レビューした映画一覧作ったり、ジャンルチャートとか作りたい

## 画面

* トップページ(レビュー一覧)
* URL入力モーダル
* お問い合わせ（GoogleForm）
