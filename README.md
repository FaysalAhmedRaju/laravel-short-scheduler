# laravel-short-scheduler
Laravel short scheduler project can be able to execute less than one minute. For example every second it can execute schedule.
========================================= Laravel Short Schedule ===================
1. composer require spatie/laravel-short-schedule
2. php artisan make:command TrapDataCommand
php artisan TrapData:Update
php artisan short-schedule:run //test at local to run short scheduler.
* * * * * cd /srv/www/api.xx.xx.io/www/public/scheduler && php artisan schedule:run >> /dev/null 2>&1 // crontab run at server
