# laravel 11

> php8.2 8.3

> 这是Laeavel11 和 dcatadmin2 laravel11分支的实例，安装成功，直接可用

issuse to [dongasai/dcat-admin2](https://github.com/dongasai/dcat-admin2)

composer create-project --prefer-dist laravel/laravel laravel11-app "11.*"


composer require dongasai/dcat-admin2

php artisan admin:publish
php artisan admin:install

echo "# laravel11_dcatadmin2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:dongasai/laravel11_dcatadmin2.git
git push -u origin main

docker exec -it laravel11dcat2 bash
composer require dongasai/dcat-admin2