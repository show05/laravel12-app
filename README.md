<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Laravel12 App

Laravel 12 と Docker (Laravel Sail) を使った学習用プロジェクトです。
このプロジェクトを通じて、PHP/Laravel の基礎から環境構築、バージョン管理までを学びます。

---

## 🚀 セットアップ手順（再現可能）

```bash
curl -s "https://laravel.build/laravel12-app?with=mysql,redis,mailpit,meilisearch" | bash
cd laravel12-app
./vendor/bin/sail up -d
```

## 🔧 使用技術

- Laravel 12.x
- PHP 8.3
- Docker（Laravel Sail）
- MySQL / Redis / Mailpit / Meilisearch

---

## 🛠 開発コマンド例

```bash
# アプリ起動
./vendor/bin/sail up -d

# アプリ停止
./vendor/bin/sail down

# マイグレーション実行
./vendor/bin/sail artisan migrate

# Laravelコマンド実行（例: route一覧表示）
./vendor/bin/sail artisan route:list
```


### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
