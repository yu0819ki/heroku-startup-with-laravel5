heroku-startup-with-laravel5
========================

HerokuでLaravel5するアレ

## 使い方
cloneしてHerokuに突っ込んで下さい。以下、その手順です。

## 手順
1. `$ heroku login`

  Herokuにログイン

2. `$ heroku apps:create l5-yourapp -b https://github.com/heroku/heroku-buildpack-php`

  Heroku上にアプリケーションを作成。PHPを動かすためにbuildpackを指定。

3. `$ git clone git://github.com/yu0819ki/heroku-startup-with-laravel5.git`

  必要なファイルをまとめておきました！どうぞ持って行って下さいましー

4. `$ cd heroku-startup-with-laravel5`

  cloneしたディレクトリに移動

5. `$ git remote add heroku https://git.heroku.com/l5-yourapp.git`

  リモートリポジトリとしてherokuを登録

6. `$ git push heroku master`

  いつものデプロイ！welcome to l5！


これで、あなたのHerokuでLaravel5する準備ができました！存分にかわいがってあげて下さいXD


### 【関連URL】
* [HerokuでNodeするアレ](https://github.com/yu0819ki/heroku-startup-with-node)
* [HerokuでkoaなNodeするアレ](https://github.com/yu0819ki/heroku-startup-with-koa)
* [HerokuでkoaなNodeするアレだったんだけど、せっかくだからiojsに乗り換えて動かしてみた](https://github.com/yu0819ki/heroku-startup-with-koa-on-iojs)
