# Day 01

ローカル開発環境の設定

説明では conda を使うように書かれているが、  
Anacondaの商用での利用が有償化されたこともあり使わずに対応する。

venvで仮想環境作成してそこにstreamlitをインストール

``` powershell
python -m venv env
.\env\Scripts\Activate.ps1
pip install streamlit
```

デモアプリを起動
``` powershell
streamlit hello
```
