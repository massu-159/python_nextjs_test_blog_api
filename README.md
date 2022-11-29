# python_nextjs_test_blog_api

pythonでapi作成。

フロントは、[python_nextjs_test_blog](https://github.com/massu-159/python_nextjs_test_blog)

認証、CRUDを、[Postman](https://www.postman.com/) でapiテスト

url はこちら
https://github.com/massu-159/nextjs-python-test-blog_api


## 1. アプリケーションの仕様

### 1-1. 仕様

- ブログ
  - ブログ作成
  - ブログ更新
  - ブログ削除
- タグ
  - タグ作成
  - タグ更新
  - タグ削除
- 認証
  - ユーザー登録
  - ユーザー削除
  - ログイン　
  - ログアウト

### 1-2. 構成技術

- python : 3.8.15
- Django : 3.1
- rest_framework
- djoser
- api.apps.ApiConfig
- corsheaders
