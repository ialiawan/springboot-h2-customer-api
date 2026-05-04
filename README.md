# 顧客管理API（Spring Boot + H2）

## 📌 概要

このプロジェクトは、Spring Bootを使用したシンプルなCRUD APIです。
H2データベースを使用して顧客情報を管理します。

## 🛠 使用技術

* Java
* Spring Boot
* Spring Data JPA
* H2 Database
* REST API

## 📂 機能一覧

* 顧客の登録（POST /customers）
* 顧客一覧の取得（GET /customers）
* 顧客詳細の取得（GET /customers/{id}）
* 顧客情報の更新（PUT /customers/{id}）
* 顧客の削除（DELETE /customers/{id}）

## ▶️ 実行方法

1. プロジェクトをクローン
2. IntelliJまたはIDEで開く
3. アプリケーションを起動
4. PostmanでAPIをテスト

## 🧪 APIテスト例

### POST /customers

```json
{
  "name": "Ali",
  "age": 25,
  "location": "Saitama"
}
```

## 📊 データベース

H2コンソール：
http://localhost:8080/h2-console

## 👨‍💻 作成者

ハリド　モハメド　アリ
