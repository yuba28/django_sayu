FROM python:3.9-bullseye

ENV PYTHONUNBUFFERED 1

RUN mkdir /home/mycode

# 作業ディレクトリの設定（以後の RUN は WORKDIR で実行）
WORKDIR /home/mycode
ADD mycode /home/mycode

RUN pip install -r requirements.txt

# 参考
# https://qiita.com/Ryo-0131/items/522c4e9c0cb4c539eb37