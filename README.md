# LocalChatMessenger
このリポジトリは、Pythonで実装されたシンプルなクライアントサーバーアプリケーションです。クライアントはユーザーからの入力をサーバに送信し、サーバはそれに基づいてフェイクデータを生成して応答します。このアプリケーションは、ネットワークプログラミングの基本を学ぶため、またはデベロッパーがネットワークアプリケーションをテストする際の模擬的なデータ生成に使用することを目的としています。

## 機能
* クライアント: コマンドラインからユーザー入力を受け取り、サーバーへ送信します。
* サーバ: クライアントからのリクエストを受け取り、Fakerを使用してフェイクデータを生成し、それをクライアントに送り返します。
