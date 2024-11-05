 Lenguaje Makdown :
Objetivo:Proporcionar una herramienta para documentar codigo,
o aspectos tecnicos para compartirlos o tenerlos de referencia en Git U
Otra plataforma  


Makdown es un lenguaje de mercado ligero creado en el 2004
John Gruber, trata de conseguir la maxima legibilidad y .....


El objetivo de su creador fue hacer que la gente pudiera escribir usando
un formato de texto palno facil de leer, facil de escribir y con la 
posibilidad de convertir su documento en HTML valido

La gran simpleza de su sintaxis hizo que tuviera una rapida
adaptacion y popularidad en la comunidad de desarrolladores.

Actualmente aparte de permitir generar codigo HTML de forma
dinamica, tambien se emplea (casi deforma estandar) para la creacion
de documentacion tecnica y con la proliferacion de la arquictectura



Conocer sintaxis Mardown
1.-Parrafos [Parrafo 1...]
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.


_cursiva_
**negrita**

~ tachado~
**_cursiva y negrita:_**

Encabezado

# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6


Divisiones

Un bloque de contenido
----
Este es otro bloque

Listas:
podemos utilizar las listas ordenadas y listas desordenadas
1. html5
1. ccs
1. javascript
1. ajax
1. json

- html5
- ccs
- javascript
- ajax
- json

citas
Podemos dar formato de citA de texto, anteponiendo la linea
de texto en un caracter mayor que (>).

la IA en el futuro reemplazara muchas profesiiones TI.

Chatgpt debe potenciar mi aprendizaje, no suprimir mi estado autodidacta

enlaces
[youtube]
[Chrome](https://www.google.com/)

imagenes
![texto alternativo](URLimagen)

tablas
|Columna 1| columna 2| columna 3|
|---------| ----- -  | -----    |
|A        |b         |c         |
|D        |e         |f         |
|g        |h         |i         |


Codigo 
podemos dar formato de codigo a un texto para ello se usa el acento grave( `).

esto es `codigo` en linea
en _javascript_ una variable se define asi;
`let saludo= "Hola mundo"`;

pero si queremos sacar un bloque completo se codigo utilizamos':
```js
let estudiante="Alexander"
let edad=20;
let isEstudiante=true;
let calificacion=92.3


// Operadores aritmeticos
let a=10;
let b=3;
    console.log(a+b)
    console.log(a-b)
    console.log(a*b)
    console.log(a/b)
    console.log(a%b)

    //operadores se asignacion
    let x=10;
    x+=5; //x=15
    x-=2;//x=13
    x*=3;//x=39
    x/=3;//x=13
    x%=5;//x=3

    //valores de comparacion

    let a1=5; let b1=`5`;
    console.log(a == b);
    console.log(a === b);
    console.log(a != b);
    console.log(a !== b);
    console.log(a > 3);
    console.log(a <=5 );

    // Operadores logicos
    let d=true;
    let f=false;

    console.log(d &&f);
    console.log(d || f);
    console.log(!d);

// Estructuras de control if/else anidado

    let Cargo=200;

    if(Cargo >=100 && Cargo<=150){
        alert("Impuesto bajo")
    }else if(Cargo>=151 && Cargo<=200 ){
        alert("Impuesto medio")
    }else{
        alert("Revisar el tabulador")
    }
```




