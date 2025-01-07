FROM node:18-alpine

# 作業ディレクトリを設定
WORKDIR /frontend/app

# プロジェクトの初期化と依存関係のインストール
COPY ./app/package*.json ./
RUN npm install

# ソースコードをコンテナにコピー
COPY ./app .
