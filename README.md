# Genfy

We had an idea... so we're giving it a try

## webapp

### Install
1. Clone repository
```
cd /var/www
git clone git@github.com:aigarsild/genfy.git
```
2. Install Composer dependencies
```
cd /var/www/genfy/webapp
composer install
```
3. Copy env configurations
```
cp .env.example .env
```
4. Generate app key (in .env file)
```
php artisan key:generate
```
