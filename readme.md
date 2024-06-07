Udemy向けFastAPI基本講座で扱ったコードです。

## ダウンロードしインストールする手順

git clone https://github.com/aokitashipro/udemy_fastapi_basic.git

cd udemy_fastapi_basic # フォルダ移動

. .venv/bin/activate # 仮想環境 有効化

pip install -r requirements.txt # パッケージインストール

## uvicornの起動

uvicorn main:app --reload
