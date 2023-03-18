# Docker

## Docker Composeを使用してGitLabを構築する手順

このドキュメントは、Docker Composeを使用してGitLabを構築する手順を説明したものです。

### 必要なもの

- Docker: https://docs.docker.com/get-docker/
- Docker Compose: https://docs.docker.com/compose/install/

### 手順

1. Docker Composeファイルを作成する

プロジェクトのルートディレクトリに`docker-compose.yml`というファイルを作成し、以下の内容を記述します。

- src/gitlab 参照

2. Docker Composeを起動する

以下のコマンドを実行し、Docker Composeを起動します。

`docker-compose up -d`

3. GitLabの初期設定を行う

- ブラウザから`http://localhost`にアクセスします。
- 初回アクセス時に、GitLabの初期設定を行うためのフォームが表示されます。
- 必要な情報を入力し、設定を完了します。

### まとめ

以上の手順で、Docker Composeを使用してGitLabを簡単に構築することができます。Docker Composeを使用することで、GitLabを簡単に起動・停止することができます。また、設定ファイルを編集することで、GitLabの設定をカスタマイズすることもできます。
