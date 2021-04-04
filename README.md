### How to test

1. Clone this repo
1. Run `composer install`
1. Run `php artisan key:generate`
1. Run `php artisan serve`
1. Open http://127.0.0.1:8000/ in your browser
1. See the icons on your screen :tada:

### Steps for installation

1. Run `composer create-project --prefer-dist laravel/laravel blade-icons`
1. Run `php artisan config:clear`
1. Run `composer require blade-ui-kit/blade-icons`
1. Run `php artisan vendor:publish --tag=blade-icons`
1. Update the config file and comment out the `default` config
1. Go to https://heroicons.com/
1. Search for the camera icon and copy the SVG value
1. Create a new file in the `resources/svg` directory called `camera.svg`
1. Put the icon in the `welcome.blade.php` template using the following tag `<x-icon-camera/>`
1. Run `php artisan serve`
1. Open http://127.0.0.1:8000/ in your browser
1. See the icons on your screen :tada: