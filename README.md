# GetSharedSQL
Import Google spreadsheet data into Unity editor. (SQLite)
tags: C# Unity gas spreadsheet sqlite  

# 前提
- unity 2018.4.1f1
- C#スクリプティング
- Googleスプレッドシート (ブラウザーで使うグーグル製エクセル ※世間一般の理解です。)
- Googleアカウント
- 「[Googleスプレッドシートを使ったUnityコラボ開発](https://qiita.com/tetr4lab/items/4d04e46ac503f19fe1e7)」のSQLite版です。
- [SQLiteUnityKit](https://github.com/tetr4lab/SQLiteUnityKit) (GitHub)

# できること
- テキストや数値などをGoogleスプレッドシートで共同編集できます。
- 編集結果は、Unityエディターへ任意のタイミングで取り込むことができます。
- 「シナリオやユーザー向けメッセージなどの編集者」や「各種の初期値を設定する担当者」がプログラマーでない場合に共同制作が容易になります。
- 多言語対応のテキストと、言語に依存しない固定値 (int、float、string、bool)を扱えます。

# スプレッドシートの雛形
[スプレッドシートの雛形](https://docs.google.com/spreadsheets/d/1fm81xrC1qh4-yAnGVocDa6iqj-xDocZUMOTModalxzw/edit?usp=sharing)が異なります。
元記事の雛形は使えませんのでご注意ください。
