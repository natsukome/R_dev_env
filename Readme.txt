■Requirements:
・Python 3.10
・pipがインストール済み
・venvがインストール済み
・python(, pip)にPATHが通っている。
===================================
■初期化
1．このディレクトリでshellを起動。
2．shellで`python -m venv _env`を実行。
3．shellで`_env\Scripts\activate`を実行。
4．shellで`pip install -r requirements.txt`を実行。
5. shellで`jupyter-notebook`を実行。
===================================
■2回目以降、作業時にすること。
1．このディレクトリでshellを起動。
2．shellで`tool\Scripts\activate`を実行。
3．shellで`jupyter-notebook`を実行。
4. ブラウザが開くので、そこで作業をする。
===================================
■ディレクトリ説明
/
 ┗┳━ DataSource/
  ┃   ┗ <CSV FILE 等のリソース保存場所>
  ┃
  ┣━ Readme.txt
  ┃  // このファイル．いろんな説明．
  ┣━ requirement.txt
  ┃  // pipでインストールするモジュール．
  ┗━ test.ipynb
     // ipynbのサンプルファイル．