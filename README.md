<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

# Test Laravel
## Php unit
Es un framework para hacer pruebas de código. Es decir que podemos probar nuestros scripts y detectar errores que se nos hayan pasado por alto.

**Creamos un proyecto nuevo de laravel:**
> laravel new TestLaravel

**Entramos en el archivo ya creado**
> cd TestLaravel

**Luego instalamos el composer**
> composer install

## Utilizando Php unit
### Test generales
> php artisan test

**Creamos un nuevo archivo de test**
> php artisan make:test UserTest

**Se encuentra en esta carpeta **
> test -> feature -> UserTest

**Volvemos a realizar un nuevo test con el comando php artisan test**
> php artisan test

**Pero si realizamos un cambio en el archivo UserTest**

**Devolverá un error**

## Ahora crearemos test unitarios
**1.**
> php artisan make:test UserTest

#### Vamos a realizar otros ejercicios
**1)	Ejecutamos este comando para crear una ui
**
> composer require laravel/ui

**2)	Creamos una interfaz de autenticación reactiva:**
> php artisan ui react --auth

**3)	Luego ejecutamos estos comando en el cmd de Windows  ya que en el de visual studio podría generar errores **
> npm install and npm run dev

**4)	En el cmd los ejecutamos así:**
> npm install
> npm run dev

**Creamos una base de datos manualmente en phpmyadmin llamada así:**
> testlaravel

**No creamos tablas aun**

**Luego nos ubicamos en el archivo .env de laravel y nos aseguramos de que el nombre de la database concuerde con el que creamos anteriormente**
> DB_DATABASE=testlaravel

**Corremos la migración en la terminal de VSC**
> php artisan migrate

#### Nos ubicamos en la carpeta unit y luego entramos en el archivo UserTest.php y hacemos las siguientes modificaciones

**1)	Se quita la función que está allí se crea esta nueva:**

**2)	En los use se hace la siguiente modificación:**

**Ejecutamos el test en el terminal**
> php artisan test

**Volveos a ejecutar el test con php artisan test. Vemos que pasa:**
>  php artisan test