# VSCodeで使うためのTIPS
* 環境変数に以下を追加した状態にする
  * PIPENV_VENV_IN_PROJECT=true
* VCCodeのワークスペース設定に以下を追加
  * "python.venvPath": ".venv"

# 開発環境の有効化
* pipenv shell

# 開発サーバのスタート
* python manage.py runserver

# アプリの作成
* アプリ作成、python manage.py startapp polls
* urls.pyの作成とメインのアプリのurls.pyに追加
* メインアプリのINSTALLED_APPSに作成したアプリを追加

# モデルの変更
* モデルを変更する (models.py の中の)
* これらの変更のためのマイグレーションを作成するために python manage.py makemigrations を実行します。
* データベースにこれらの変更を適用するために python manage.py migrate を実行します。
* 各モデルに独自メソッドを追加できる

# django Admin
* python manage.py createsuperuser(スーパーユーザの作成)(admin:password)

