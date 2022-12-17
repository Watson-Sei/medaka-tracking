# Labの実行環境の構築説明

Labは、「medaka-tracking」の個々の機能の実装に使われる機能の細かい解析方法などの確認などに使われるjupyter notebookを利用した解析環境である。

## Chrome Driverのダウンロード

自分が使っているChromeのバージョンに合わせてドライブをダウンロードしてください。
https://sites.google.com/chromium.org/driver/?pli=1

## Pipenvをインストール

```unix
Unix/macOS
python3 -m pip install --user pipenv

Windows
python3 -m pip install --user pipenv
```

## プロジェクト用のパッケージをインストールする

```unix
cd medaka-tracking
pipenv install requests
```

## Jupyter Notebookの起動

```unix
jupyter notebook
```
