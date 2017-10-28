## 2017/10/28

* 進捗ないです
  * 開発環境をUbuntu 16.04 → 17.10 へアップグレード
  * 虐殺器官を鑑賞したりしてインスピレーションを補給していたら平日が過ぎ去った
* 進捗報告会でわいてきたアイディア・メモなど
  * VHDL parserでも書いて機能拡張して出力みたいなのやりたい
  * APFSは  copy on writeとかあって研究対象的に良い https://developer.apple.com/library/content/documentation/FileManagement/Conceptual/APFS_Guide/FAQ/FAQ.html#//apple_ref/doc/uid/TP40016999-CH6-DontLinkElementID_17


## 2017/09/30

* やったこと（何行でも）：
  * ruse-fuse examplesのひとつであるhello.rsをビルドして動作確認した
  * "Systems Performance" のファイルシステムの章を読み終わった
* 学び・失敗したこと：
  * Rustでシングルバイナリのアプリを作ろうとして失敗した http://twitter.com/suma90h/status/913744106911711232
  * 稼働時間2日（平日）のみ、少しはましになったが...
  * 自宅のキーボードが配置が遠くて打ちづらい
* これからやること（TODO）
  * ruse-fuseで管理する対象のファイルに対して、ファイルシステムらしきものを作り、メタデータの管理をやってみる
* K(keep)：
  * rust-fuseを続ける
* P(problem)：
  * Rust/Cargo力が弱い
* T(try)：
  * Rust/Cargoの使い方を鍛える
  * ファイルシステムらしきもの作りとfuseのAPI呼び出し

## 2017/09/17

報告会の記録はこのスタイルで。
必要があれば項目を追加・削除する。

* やったこと（何行でも）：
  * Rust exampleを試してRustを入門した
* 学び・失敗したこと：
  * 時間配分（平日出張が一度入って）
  * 自宅だと遊びの誘惑が
* これからやること（TODO）
  * ファイルシステムの作り方（具体的に）を調べる
* K(keep)：
  * Rust学習を続ける
* P(problem)：
  * ファイルシステム作成の一歩も踏み出せてない
* T(try)：
  * FUSEでもデバイスドライバでも何でもいいので、スケルトンのプログラムを書いてみる

### 追加参考資料
FS的に
* https://news.ycombinator.com/item?id=15261318
