# 活動まとめ 2017/12/10

* やったこと（何行でも）：

  * re:Invent 出張
  * ちょっとだけ WSA 研のための前調査

* これからやること（TODO）

  * Advent Calendar の準備
  * WSA 研準備

# 活動まとめ 2017/11/23

* やったこと（何行でも）：

  * 文フリの原稿執筆完了&無事に発行

    * https://github.com/syucream/bun25

* これからやること（TODO）

  * Advent Calendar の準備

# 活動まとめ 2017/11/11

* やったこと（何行でも）：

  * 少し早く処理する uniq コマンドっぽいものを作った

    * https://github.com/syucream/quniq
    * http://syucream.hatenablog.jp/entry/2017/11/04/225147

  * 文フリの原稿ラフに仕上げた

    * https://github.com/syucream/bun25

* これからやること（TODO）

  * とりあえず文フリの原稿リファクタリング

# 活動まとめ 2017/10/28

* やったこと（何行でも）：

  * デバッグほんのちょっとだけ(1hくらい)やってた
  * あとは ISUCON 参加などちょっと忙しめ

* これからやること（TODO）

  * 淡々とテスト通らない箇所修正

# 活動まとめ 2017/10/14

* やったこと（何行でも）：

  * 前回から引き続きデバッグ
  * 最近業務繋がりで GCP 周り調べててそちらに費やした時間が多い。。。

* 学び・失敗したこと：

  * 集中力がだいぶ削がれてしまった

* これからやること（TODO）

  * 淡々とテスト通らない箇所修正

* K(keep)：

  * 今回はとくになし

* P(problem)：

  * 若干燃え尽きかけているので持ち直す方法考えるか別の案にピボットするか考えてもいいかも

* T(try)：

  * デバッグ続き。ある程度怪しいところを絞りこむ

# 活動まとめ 2017/09/30

* やったこと（何行でも）：

  * テストが通らない箇所がありその修正を試みる
  * ngx_mruby を Mac で ssl 有りでビルドするもうまくいかずトラブルシュートしたり

* 学び・失敗したこと：

  * あまり本質的でない箇所に時間と気力を使ってしまい、燃え尽きてしまった

* これからやること（TODO）

  * 淡々とテスト通らない箇所修正

* K(keep)：

  * 着実には進んでるし、本筋とは外れるけどアウトプットもできている

* P(problem)：

  * 失敗したことに書いたけど途中で燃え尽きてしまった感がある。

* T(try)：

  * 知識が実装がというより、気力やペース配分に気をつけるようにした方がいいのかも
  * 趣味プロジェクトとはいえもう少し計画を立てて実行してもいいかもしれない。 Problem の再発防止も意識しつつ

# 活動まとめ 2017/09/17

## テーマ

https://github.com/suma/hobby-programming-record/blob/master/syucream/note.md

## やったこと

* fiber で mruby のコードを動かす
* ノンブロッキング sleep の実装を行なう
* PR を送る
  * https://github.com/matsumotory/ngx_mruby/pull/312

## KPT

### KEEP

* 予め TODO を起こしておいたのは良かった
* 一応進捗が出た

### Problem

* 一部気合を入れすぎたタイミングがあった
* 初歩的なミスが多かった

### Try

* 新しいアイデアが思いついたので試してみる

## これからやること

* PR の粗を色々修正？
* "thread pool を使ったブロッキング処理のオフロード" をやるかも
