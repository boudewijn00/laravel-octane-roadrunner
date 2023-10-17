a simple laravel octane example using roadrunner

1. composer install
2. php artisan key:generate
3. php artisan octane:install
4. ./vendor/bin/rr get-binary
5. chmod +x ./rr
6. php artisan octane:start --server=roadrunner --host=0.0.0.0 --rpc-port=6001 --port=80

for more information see https://laravel.com/docs/10.x/octane#roadrunner or https://www.packtpub.com/product/high-performance-with-laravel-octane/9781801819404
