# イメージの指定
FROM python:3.10

# 作業ディレクトリの指定
WORKDIR /usr/local/app

# pipのアップグレード
RUN pip install --upgrade pip

# イメージのビルド時にコマンド実行
RUN pip install flask==2.1.0

# コンテナの起動時にコマンドを実行
CMD ["flask", "run", "--host=0.0.0.0"]