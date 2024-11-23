# LocalChatMessenger

## 概要
LocalChatMessengerは、Pythonで実装されたシンプルなクライアントサーバーアプリケーションです。クライアントはユーザーからの入力をサーバに送信し、サーバはフェイクデータを生成してクライアントに返します。

## 特徴
- クライアント: コマンドラインからユーザー入力を受け取り、サーバーへ送信
- サーバ: クライアントからのリクエストを受け取り、フェイクデータを生成して返送

## このプロジェクトを通して学べること・習得できること
- Pythonのネットワーキング
- クライアントサーバーアーキテクチャの理解
- フェイクデータ生成ライブラリ（Faker）の使用方法

## 必要条件
- Python 3.x

## インストール手順
1. リポジトリをクローンします:
    ```bash
    git clone https://github.com/ksk-aiko/LocalChatMessenger.git
    ```
2. 必要な依存関係をインストールします:
    ```bash
    pip install -r requirements.txt
    ```

## 使用方法
1. サーバーを起動します:
    ```bash
    python server.py
    ```
2. クライアントを起動します:
    ```bash
    python client.py
    ```

## 機能一覧
- クライアントからの入力をサーバーに送信
- サーバーからのフェイクデータをクライアントに返送

## 技術スタック
- Python
- Faker

## 追加資料
- [プロジェクト設計図](design_docs/)

## 貢献方法
1. フォークリポジトリ
2. 新しいブランチを作成:
    ```bash
    git checkout -b feature/your-feature
    ```
3. 変更をコミット:
    ```bash
    git commit -m 'Add some feature'
    ```
4. プッシュ:
    ```bash
    git push origin feature/your-feature
    ```
5. Pull Requestを送信

## ライセンス
このプロジェクトはMITライセンスの下で公開されています。