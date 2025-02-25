# イメージの指定
FROM python:3.10

# 作業ディレクトリの指定
WORKDIR /usr/src/app

# pipのアップグレード
RUN pip install --upgrade pip

# イメージのビルド時にコマンド実行
# 「Werkzeug」のバージョンアップに対応
RUN pip install flask==2.3.0

# コンテナの起動時にコマンドを実行
# --debugオプションを指定してデバッグモードで起動
CMD ["flask", "run", "--host=0.0.0.0", "--debug"]