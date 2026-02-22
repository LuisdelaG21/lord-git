<!--Esto es un comentatario en markdown-->
# Lord Git H1
## **Reglas estándar de markdown** H2
### Esto es un archivo markdown (.md) H3
#### Encabezado H4
##### Encabezado H5
###### Encabezado H6

Alternativa de H1
Hola GitHub
Comenzaremos a crear cosas en Python y Js
===

Alternativa de H2
---
<!--guión-->
--- 

<!--Modificaciones de estilo de fuente-->
## Modificaciones de estilo de fuente
<!--Énfasis: Itálica-->
This is my *first* _text_ <!--Dos formas * o _ bajo-->
<!--´´Enfasis fuerte: Negrita-->
This is my **first** __text__ <!--Dos formas ** o __ bajo-->
<!--Énfasis combinado-->
This is my **first _text_** <!--Negritas y cursiva-->
<!--Tachado-->
This is my ~~first~~ text <!--Dos formas * o _ bajo-->

## Listas
Desordenada **UL**

* Tomate
    * Jitomate
+ Lechuga
    * Romana 
- Cebolla
    * Cebollina

Ordenada **OL**

1. First
    1. Despertar
    2. Levantarse
2. Second
    * Comer
3. Third
    * Comer

## Sangría de textos
1. Tema

   **Dejar 3 espacios antes de iniciar el párrafo**.  
   Este es un mensaje de prueba. 

   Para poder hacer un salto de línea en el mismo párrafo  
   debes dejar **dos espacios al final de la oración**  
   y luego dar ENTER.
   

## Enlaces URL
Hay dos maneras de crear enlaces

<!--Enlace a un sitio web-->
* Enlace de estilo en línea

[MarvelRivals](https://www.marvelrivals.com/) 
<!--Enlace con un nombre al colocar encima el cursor-->
Enlace de estilo en línea con título  
[MarvelRivals](https://www.marvelrivals.com/ "Ir al sitio")

* Enlace de estilo con referencia

[Netflix][Esto es una referencia]

Puedes hacer una referencia a un repositorio remoto [Midudev hellogit]

También puedes colocar la URL entre corchetes angulares <https://www.example.com/> o en su versión estándar https://www.example.com/

[Puedes simplementa colocar un número como referencia][1]

Las referencias se colocarán al final de este archivo

## Citas
> Esto es una cita

> Esto es otra cita

## Lineas de división
Linea formada con --- (3+)
___

Linea formada con ___ (3+)
___

Lineas formadas con *** (3+)
***

## Bloques de código
Individual o pequeño ``

`console.log("Hola mundo")`

Bloque de código con ```
```
def analizar_estructuras(codigo_lineas):
    """
    Analiza if, else, while, switch, for y las reglas de case/break.
    """
    errores = []
    pila_llaves = [] 
    necesitan_parentesis = ["if", "while", "switch", "for"]
    
    # Variables para rastrear el estado del switch
    dentro_de_switch = False
    ultimo_case_linea = -1
```
Escribir el nombre del lenguaje hace que adopte los diseños y colores del lenguaje específico

```python
print("Hola python")
```

```html
<h1>Hola html</h1>
```

## Tablas de contenido
Se crean usando los símbolos |, -

| Título       | Tema        | Descripción  |
|--------------|-------------|--------------|
|Cálculo I     |Matemáticas  | Introducción |
|Cálculo I     |Matemáticas  | Introducción |
|Cálculo I     |Matemáticas  | Introducción |
|Cálculo I     |Matemáticas  | Introducción |

## Imagenes locales y online
El signo ! indica que es una imagen y no un enlace

* Colocando la dirección web de la imagen

Logotipo con título

![Visual Studio Code](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/3840px-Visual_Studio_Code_1.35_icon.svg.png "Logo Visual Studio Code")
<!--
* Colocando la ruta local
![Visual Studio Code](./Images/logo_vscode.png)
-->

Imagen usando referencia

![Git][logo]

[logo]: https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png "Logotipo Git"


Imagen usando HTML

<img src="https://www.dexerto.com/cdn-image/wp-content/uploads/2025/03/11/President-Loki-Marvel-Rivals.jpg" alt="Loki presidente" width="300" title="best support" border="2" />

## **Reglas exclusivas para GitHub**
Estas reglas son inclusiones de GitHub GMF para que los desarrolladores puedan agregar otros recursos útiles en la documentación de sus proyectos.

### Lista to-do

* [x] task 1
* [ ] task 1
* [ ] task 1
* [x] task 1

### Mencionar a un colaborador
Usando @ se puede hacer mención de un colaborador. Esto hará que reciba una notificación.

@LuisdelaG21

## Html en línea
También puedes usar HTML sin formato en tu Markdown y, en general, funcionará bastante bien.  
Ejemplo de lista descriptiva en HTML.

<dl>
  <dt>Definición de lista</dt>
  <dd>Es una cosa que las personas usan a menudo.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

<!--
<dl> (Description List): Contenedor principal de la lista.
<dt> (Description Term): Define el término o nombre a explicar.
<dd> (Description Definition): Proporciona la descripción o valor correspondiente al término. 
-->

## Videos de YouTube
No se pueden agregar directamente, pero puedes agregar una imagen con un enlace al video como este:

 **Recurso HTML**

<a href="https://youtu.be/Rbo81UB8eQQ?si=IK0PutBzGbHGsQA5
" target="_blank"><img src="https://img.youtube.com/vi/Rbo81UB8eQQ/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

* href = link del video
+ target = _blank, indica que se debe abrir una pestaña nueva para mostrar el video
- src = link del frame inicial del video, generalmente solo cambian los números del final
* alt = título de la imagen 
+ width, height y border son propiedades de ancho, alto y borde la imagen respectivamente.

**Otra manera más usada de agregar un enlace a un video:**

**Markdown puro**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Rbo81UB8eQQ/0.jpg)](https://youtu.be/Rbo81UB8eQQ?si=IK0PutBzGbHGsQA5)

Funciona similar a las imagenes importadas, solo que esta vez agregamos un par de corchetes extras para agregar un link a un video.

* Los corchetes [muestran el título de la imagen].
+ El primer paréntesis contiene el enlace a la imagen
- El segundo paréntesis contiene el enlace al video.

Este método tiene la desventaja que pierde el tamaño y el borde de la imagen, poco personalizable.

## Emojis
Puedes buscar el sitio oficial de emojis de **GitHub** y usar los caracteres propios de un emoji en específico (empiezan y terminan con :).
Ejemplos:

😃:    :+1:

[Lista de emojis md](https://gist.github.com/rxaviers/7360908 "Enlace al sitio web")

## Notas al pie
Esta es una simple nota al pie[^1].

Una nota al pie puede tener múltiples líneas[^2].

También puedes usa palabras para adaptarse mejor a su estilo de escritura[^flag]

## Lista de recursos útilizables en Markdown
[Sintaxis de Markdown](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet "Enlace al sitio web")

---------------------------
<!--Referencias con enlaces a sitios web y repositorios-->
[Esto es una referencia]: https://www.netflix.com/mx/

[Midudev hellogit]: https://github.com/mouredev/hello-git

[1]: https://www.dc.com/comics

<!--Referencias de notas al pie-->
[^1]: Mi referencia

[^2]: Cada nueva línea debe tener 2 espacios  
como prefijo para hacer un salto de línea corto.

[^flag]: Las notas al pie con nombre se seguirán  
representando con números en lugar de texto.
