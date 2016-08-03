## Backend Skeleton

This app contains the basic application structure for backend development to work in PHP Storm.
Project will contain [Laravel 5 IDE Helper](https://github.com/barryvdh/laravel-ide-helper)

## Prerequisites

    - PHP Web Storm
    - PHP Mess Detecter https://phpmd.org/
    
## Usage

 1) Clone/Download this repository. <br />
 
 2) Run composer install command inside the project directory, to know more about [composer](https://getcomposer.org/doc/)<br />
 
 3) Configure the [environment file](https://laravel.com/docs/5.1/installation#environment-configuration) according to your project.<br />
 
 4) You need to ENABLE [PSR-2 coding styles](https://confluence.jetbrains.com/display/PhpStorm/PHP+Mess+Detector+in+PhpStorm)

##Note
 after composer install, go to _config/app.php_ and uncomment the __Line 139__
 //Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider::class,
#### Optional

if you want more control, [follow up this guide](https://confluence.jetbrains.com/display/PhpStorm/Laravel+Development+using+PhpStorm)
## Contributors

    Mubin and Asad 
Good suggestions are appreciated.

### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
