# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
* リポジトリ
  * ファイルやディレクトリの状態を記録する場所
* リモートリポジトリ
  * ネット上に配置して複数人で共有するためのリポジトリ
* ローカルリポジトリ
  * 開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ


## プッシュとマージの違いは何でしょうか？
* プッシュ
  * ローカルリポジトリの内容をリモートリポジトリに反映する
* マージ
  * 別のブランチの作業内容(変更履歴)をブランチに取り込むこと


## コミットとプッシュの違い
* コミット
  * 変更履歴を残し過去のコードも確認できる
* プッシュ
  * 作業しているブランチの変更内容をリモートリポジトリのブランチに反映させる

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
* どの部分を変更したかを分かりやすく書く
* プレフィックス
  * コミットメッセージの、先頭につける接頭辞のこと（例：fix、add、change など）

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
* ローカルでマージ
  * ローカルでworkingブランチをmasterブランチにマージし、リモートのmasterブランチにプッシュして変更内容が反映されていた
* プルリクエストでマージ
  * ローカルでworkingブランチをリモートのworkingブランチにプッシュし、プルリクエストを作成し、コードレビューをしてからマージする
  

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
* 先にマージされた変更内容を取り込む
* 後にマージしようとしている変更内容を取り込む
* どちらの変更内容も取り込む
*  自分と他の開発者の変更点がコンフリクトを起こしている場合、どちらを優先するかはどのように判断するか
  * そのソースコードを書いた人と相談しながら作業を進める