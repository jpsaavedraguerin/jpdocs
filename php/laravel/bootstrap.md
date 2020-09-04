Pasos para integrar bootstrap en Laravel:

1. Instalar libreria Laravel/UI

```pwsh
composer require laravel/ui
```

2. Installar Bootstrap en Laravel

```pwsh
php artisan ui bootstrap
```

3. Instalar dependencias

```pwsh
npm install
```

*En desarrollo*

```pwsh
npm run dev
```

*En producción*

```pwsh
npm run dev
```

Una vez terminado el proceso deberíamos ver este resultado:

```pwsh
Asset			Size		Chunks			Chunk Names
/css/app.css		178 KiB		/js/app  [emitted]  	/js/app
/js/app.js		1.07 MiB  	/js/app  [emitted]  	/js/app
```

Para utilizar bootstrap se debe llamar de la siguiente forma:

```html
<!DOCTYPE html>
<html>
 <head>
  <!-- Scripts -->
  <script src="{{ asset('js/app.js')}}" defer></script>
  <!-- Styles -->
  <link rel="stylesheet" type="text/css" href="{{ asset('css/app.css')}}">
  <title> Title </title>
 </head>
 <body>
  <!-- body -->
 </body>
</html>
```
