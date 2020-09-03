# GUÍA RÁPIDA DE REFERENCIA PARA PHP

PHP es un lenguaje interpretado en el lado del servidor orientado a aplicaciones web. Generalmente es utilizado junto a HTML.

## Sintáxis básica

Php utiliza tags de apertura `<? php` y cierre `>`, todo el código al interior de estas etiquetas será interpretado por PHP.

**Ejemplo:**

```php
<?php

echo 'Hola mundo!'; // esto imprime "Hola mundo!" en el navegador.

// aquí el resto del código a ser interpretado

?>
```

**Comentarios**

```php
<?php

// esto es un comentario

/* este es un comentario
   y esta otra línea de comentario */
   
# también se puede utilizar el simbolo gato

?>
```

## Tipos de variables

1. Escalares

```php
<?php

# Escalares

$var_1 = TRUE;      // es boolean
$var_2 = "doggo";   // es string
$var_3 = "café";    // es string
$var_4 = 8;         // es integer

echo gettype($var_1); // devuelve : boolean
echo gettype($var_2); // devuelve : string

# Compuestos
- array
- objeto
- callable
- iterable

?>
```

2. Compuestos
- array
- objeto
- callable
- iterable

> Especiales
- resource
- NULL

> Pseudo tipos
- mixed
- number
- callback
- array|object
- void

**pseudo variable** : `$`

Funciones relacionadas con variables:

- Cast
- settype()
- var_dump()
- gettype()


## Referencias

[Manual PHP (en inglés)](https://www.php.net/manual/en/)

