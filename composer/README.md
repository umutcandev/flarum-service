### Note
Make sure you have all backups before running the commands.

### Code
Run with SSH-Composer:
```
composer update --prefer-dist --no-plugins --no-dev -a --with-all-dependencies
php flarum migrate
php flarum cache:clear
```
