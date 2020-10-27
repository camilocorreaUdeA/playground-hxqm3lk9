# Entrada y salida estándar de datos para aplicaciones de consola en C++

Generalmente, las aplicaciones de software están diseñadas para que puedan interactuar de forma directa con usuarios. Por ejemplo, las aplicaciones web le permiten a un usuario agregar datos en campos y luego enviar esa información al presionar un botón.
En el caso de las aplicaciones de consola desarrolladas con C++, solo hay dos tipos de interacción directa entre la aplicación y el usuario: 
<ol>
<li>Mediante mensajes que la aplicación imprime en pantalla para que el usuario los lea.</li>
<li>A través de información ingresada por el usuario a la aplicación usando el teclado de la computadora.</li>
</ol>

En esta lección veremos las funciones de uso más extendido que ofrece C++ para la impresión de información en pantalla y para capturar datos ingresados por el teclado.
Al ingreso de datos por teclado y la impresión de información en pantalla se le conoce como entrada y salida estándar respectivamente en el argot del desarrollo de aplicaciones de consola en C++.
Para poder utilizar correctamente las fuciones que permiten controlar la entrada y salida estándar en C++ es necesario agregar como un par de líneas de código como requisito indispensable.

## 

This C template lets you get started quickly with a simple one-page playground.

```C runnable
#include <stdio.h>

int main() {
	printf("Hello World!");
}

```

# Advanced usage

If you want a more complex example (external libraries, viewers...), see the [official documentation](https://tech.io/playgrounds/408/tech-io-documentation).
