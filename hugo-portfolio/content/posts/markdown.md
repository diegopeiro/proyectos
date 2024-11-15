+++
title = 'Markdown'
date = 2024-10-28T19:08:37+01:00
draft = false
+++

# Guía de Markdown

Markdown es un lenguaje de marcado ligero que permite dar formato a texto de manera sencilla. Es ampliamente utilizado en plataformas como GitHub, blogs, y documentación.

## 1. Markdown Básico

### 1.1 Encabezados

Usa `#` para crear encabezados. La cantidad de `#` indica el nivel de encabezado.

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alt-H1
======

Alt-H2
------
```

### 1.2 Énfasis
Cursiva: usa *texto* o _texto_.

Negrita: usa **texto** o __texto__.

Negrita y cursiva: usa ***texto*** o ___texto___. 

### 1.3 Listas
Lista desordenada
* Elemento 1
* Elemento 2

Lista ordenada
1. Elemento 1
2. Elemento 2

### 1.4 Enlaces e Imágenes
```markdown
Enlace: [texto del enlace](URL)

Imagen: ![texto alternativo](URL de la imagen)

[Google](https://www.google.com)
![Logo de Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```


## Ejemplos

[Google](https://www.google.com)

![Logo de Spotify](https://loodibee.com/wp-content/uploads/Spotify-Logo-black-white-300x300.png)

### 1.5 Citas
Usa > para crear citas.

> Esto es una cita.


### 1.6 Código y notas
Para resaltar fragmentos de código, usa comillas invertidas (`).

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```

##  Notas
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```

## 2. Markdown Gráficos
Algunas versiones y extensiones de Markdown permiten gráficos y diagramas, como las extensiones de Mermaid y PlantUML.

### 2.1 Mermaid
Mermaid es una biblioteca que permite incluir diferentes tipos de gráficos, como diagramas de flujo, gráficos de Gantt, diagramas de secuencia, entre otros. Es compatible con varias plataformas como GitHub, GitLab y algunos editores como Visual Studio Code (con la extensión adecuada).

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### 2.2 Ejemplo de mapas GeoJson
Puedes usar la sintaxis GeoJSON o TopoJSON para crear mapas interactivos. Para crear un mapa, agrega GeoJSON o TopoJSON dentro de un bloque de código delimitado con el identificador de sintaxis geojson o topojson. 


```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

## 3. Markdown Extendido
Markdown extendido ofrece funcionalidades adicionales, dependiendo del editor o plataforma utilizada.

## 3.1 Tablas
| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Celda 1     | Celda 2      |
| Celda 3     | Celda 4      |

## 3.2 Listas de Tareas
- [x] Preparar el diseño
- [ ] Escribir la documentación
- [ ] Revisar el código
- [ ] Realizar pruebas finales

## 3.3 Definiciones de palabras
Markdown
: Un lenguaje de marcado ligero para formatear texto de manera sencilla.

Sintaxis
: La estructura o reglas que debe seguir el texto para ser interpretado correctamente en Markdown.

## 3.4 Emojis
Aquí hay un emoji de cohete: 🚀, o puedes escribirlo con `:rocket:`.

## 3.5 Fórmula matemática
La fórmula para la energía es \( E = mc^2 \).








