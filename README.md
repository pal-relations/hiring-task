# フロントエンドエンジニア採用課題

## 概要

- このリポジトリはフロントエンドエンジニア採用のための課題を提供する。
- 課題内容は、提供された API を使用して、現在の投票数を取得し、ユーザーが投票できる機能を JavaScript で実装すること。

## 課題の詳細

`public/index.html` 下部の「記事のフィードバック」に、以下の機能を実装すること。

1. **各項目の現在の投票数の表示**  
   API を使用して、現在の投票数を取得する処理を実装する。

2. **現在の合計数の表示**  
   API を使用して、現在の合計数を取得する処理を実装する。

3. **投票の実施**  
   各項目に対して投票を行う処理を実装する。
   投票後に、各投票数がリアルタイムに更新されるようにする。

## API ドキュメント

必要な API の詳細は以下の URL に記載されている。

- [API ドキュメント](https://content-api-docs.palr.link/)
- エンドポイントやリクエスト形式、レスポンスの構造については、このドキュメントを参照
- 本件で使用する API の CORS の制限は解除されている

## 前提

- 言語は JavaScript とする
- ライブラリ/フレームワークの使用は自由 (使用しなくてもよい)
- コンパイルやトランスパイルが必要な場合、誰でも環境を構築できるように手順を記載すること
  - 手順の提示は、下記「提出方法」の手順で作成したリポジトリに `docs/README.md` を追加し、環境設定やビルド手順を記載すること。
- 必要なパラメータは以下の通り
  - `serviceId` は `hiring-task2024` とする。
  - `contentId` は別途連絡する。
  - 投票対象の `type` の値は、各ボタンの属性 `data-type` に設定されている値を使用する。

## 提出方法

1. **このリポジトリを自身の非公開リポジトリに複製する**

   自身の GitHub アカウントに **非公開** リポジトリを作成し、このリポジトリを複製して下さい。

2. **機能を実装**

   複製した非公開ポジトリで課題の機能を実装し、push する。

3. **成果物の提出**

   - リポジトリの URL を提出する。
   - 提出前に、弊社メンバーアカウントの Github ID: `kusafuka`, `uzura8` にリポジトリへのアクセス権を付与する。
   - 動作する状態のものが確認できる URL の提示が可能なら、提出時に一緒に提出すると望ましいが、必須ではない。

4. **提出期限**

   一次面接日の前営業日の午後 0 時とする
