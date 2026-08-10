# api-setup-practice

## 概要
COACHTECH 教材 Tutorial 11-1「API開発環境の構築と疎通確認」で作成した成果物です。


## 使用技術
- PHP 8.x
- Laravel 10.x
- REST API（JSONレスポンス）
- Postman（動作確認）


## 学んだこと
- LaravelでのAPIルートの書き方、Webとの違い
- Postmanでのリクエスト送信とレスポンスの確認
- 

## 動作確認
Postmanにて
Postmanを起動する
「+」タブをクリックして新しいリクエストを作成
メソッド: GET
URL: http://localhost/api/hello
「Send」ボタンをクリック

→ステータスコードが「200　OK」になっているか
→{
  "message": "Hello, API!"
}
が表示されるか
