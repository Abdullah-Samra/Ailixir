cd backend
composer install
cp .env.example .env
php artisan key:generate
# إعداد قاعدة بيانات وتهيئتها
php artisan migrate
