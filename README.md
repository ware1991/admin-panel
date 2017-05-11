# 後台管理套件串接簡介

>現在有許多開源的後台管理套件，依據不同使用情境採用最適合自已的套件。
>
>亦有相當多的 Bootstrap 開源框架，依據各自需求編輯區塊。

Base on：Laravel 5.4

Use Package： tcg/voyager

### 專案配置
* 將專案 clone 下來後，至專案目錄底下執行底下命令:
```
composer install
composer update
```
* 新增檔案: .env 並寫入專案相關配置,資料庫等
* 新增 Table: ```php artisan migrate```
* 設定 .env 的 application key: ```php artisan key:generate```

### 練習筆記 GitBook
* https://ware1991.gitbooks.io/laravel_login/content/

### 參考資源：
* Voyager 官網：https://laravelvoyager.com/
* Voyager 文件：https://the-control-group.github.io/voyager/docs/0.11/
* 權限綁定教學：http://laravelacademy.org/post/6613.html

### 其他後台資源推薦：
* Laravel Admin Panel Generators：https://laravel-news.com/13-laravel-admin-panel-generators

* 65+ Best Free Bootstrap Admin Templates：http://www.cssauthor.com/bootstrap-admin-templates/
