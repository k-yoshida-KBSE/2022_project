# django_appを使ってdjangoの練習をする
<!-- ［Ctrl］＋［Shift］＋［V］キー　押下でVScode上でプレビュー -->
## 【django_appフォルダーを開く】
1. VScodeを開く
1. ターミナルを開く
1. `cd OneDrive - 学校法人 日本工業大学\ドキュメント\07.Django入門\django_app`を実行

## 【webサーバーを起動】
1. `python manage.py runserver`を実行

## 現在作成中のローカルページのリンク
- `http://127.0.0.1:8000/hello/`
- `http://127.0.0.1:8000/admin/`

### CSSが反映されないとき
1. サーバーが開いていることが原因と思われる
1. [Ctrl] + [C] キー押下でサーバーを終了
1. もう一度`python manage.py runserver`を実行

#### ☆djangoコマンド☆
1. Djangoのプロジェクトを作る
    - `django-admin startproject` プロジェクト名
1. Webサーバーを起動
    - `python manage.py runserver`
1. アプリケーションを追加
    - `python manage.py startapp` プロジェクト名
1. マイグレーションファイルを作る
    - `python manage.py makemigrations` プロジェクト名
1. マイグレーションを実行
    - `python manage.py migrate`
1. 管理者の作成
    - `python manage.py createsuperuser`
    - Username:admin
    - Email:119I219@stu.nit.ac.jp
    - Password:password