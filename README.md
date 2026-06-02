# eloquent-app-practice

## 概要
Laravel Tutorial 9-4 Eloquent ORM

## 使用技術
- PHP 8.x
- Laravel 10.x
- Eloquent ORM
- MySQL

## 学んだこと
- make:modelコマンドでモデルを作成する、オプションをつけてマイグレーションファイルも作成できる
- モデルはLaravel側でデータを扱い、マイグレーションはデータベース側で扱う
- Modelで$fillableを設定することで、代入可能な項目を設定する
- モデルを使ったデータの登録や取得の方法
- kinterを使ってデータを実際に登録する
- ブラウザからputとdeleteのリクエストを送る設定をする
- ルートパラメータを使ってコントローラーにデータを渡す方法

## 動作確認
コンテナを起動
```bash
./vendor/bin/sail up -d
```
http://localhost/posts にアクセス
