# lara9-sample

## 環境構築
`$cd プロジェクト`
`$ docker compose up -d`
`$ docker compose exec app bash`
`[app] $ chmod -R 777 storage bootstrap/cache`
`[app] $ composer install`
`[app] $ cp .env.example .env`
`[app] $ php artisan key:generate`
`[app] $ php artisan storage:link`
`[app] $ php artisan migrate`

## GUIのDB接続例

