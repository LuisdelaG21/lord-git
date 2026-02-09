<!--Esto es un comentatario en markdown-->
# Lord Git
## **Reglas estándar de markdown**
#### Esto es un archivo markdown (.md)

<!--Modificaciones de estilo de fuente-->
## Modificaciones de estilo de fuente
<!--Itálica-->
This is my *first* text 
<!--Negrita-->
This is my **first** text
<!--Tachado-->
This is my ~~first~~ text

## Listas
Desordenada **UL**

* Tomate
    * Jitomate
* Lechuga
    * Romana 
* Cebolla
    * Cebollina

Ordenada **OL**

1. First
    * Levantarse
2. Second
    * Comer
3. Third
    * Comer

## Enlaces URL
<!--Enlace a un sitio web-->
[MarvelRivals](https://www.marvelrivals.com/) 
<!--Enlace con un nombre al colocar encima el cursor-->
[MarvelRivals](https://www.marvelrivals.com/ "Ir al sitio")

## Citas
> Esto es una cita

> Esto es otra cita

## Lineas de división
Linea formada con --- (3)
___

Linea formada con ___ (3)
___

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

![Visual Studio Code](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/3840px-Visual_Studio_Code_1.35_icon.svg.png)
<!--
* Colocando la ruta local
![Visual Studio Code](./Images/logo_vscode.png)
-->

## **Reglas exclusivas para GitHub**
Estas reglas son inclusiones de GitHub para que los desarrolladores puedan agregar otros recursos útiles en la documentación de sus proyectos.

### Lista to-do

* [x] task 1
* [ ] task 1
* [ ] task 1
* [x] task 1

### Mencionar a un colaborador
Usando @ se puede hacer mención de un colaborador. Esto hará que reciba una notificación.

@LuisdelaG21

## Emojis
Puedes buscar el sitio oficial de emojis de **GitHub** y usar los caracteres propios de un emoji en específico (empiezan y terminan con :).
Ejemplos:

😃:    :+1:

[Lista de emojis md](https://gist.github.com/rxaviers/7360908 "Enlace al sitio web")

## Lista de recursos útilizables en Markdown
[Sintaxis de Markdown](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet "Enlace al sitio web")
