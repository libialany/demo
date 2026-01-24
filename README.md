##  Ingresar a nuestro editor

[editor](https://editor.raspberrypi.org/en/projects/welcome-to-antarctica-starter)

- En el archivo index.html marcar todo y borrar.
- copiar este codigo y pegar.

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>My link tree</title>
  </head>
  <body>
  
  </body>
</html>

```

- En el archivo **style.css** borrar todo y pegar.
```
body {
    font-family: 'Arial', sans-serif;
    background-color: #f2f2f2;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}
```


## Crear un div 

## Descripcion:

En el archivo **index.html** y crea 2 etiquetas  div <div>.

```html
   <div>
        <div>
            <!-- estoy dentro de un div -->
        </div>
        <!-- AQUI CREA OTRO DIV COMO EL DE ARRIBA -->
    </div>
```


### Dar estilo a nuestro primer div con class

Al primer div adiciona esto  la clase container como este ejemplo: `<div class="container">`

```html
   <div AQUI>
        <div >
            <!-- estoy dentro de un div -->
        </div>
        <!-- AQUI CREA OTRO DIV COMO EL DE ARRIBA -->
    </div>
```



### Dar estilo a nuestro primer div con CSS

Despues nos vamos al archivo **style.css**

```
.container {
    width: 300px;
    background-color: CAMBIA;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    text-align: center;
}
```

### Cambiar de color al fondo

En el archivo **style.css**

La propiedad 

```
background-color: ;
```

### Dar estilo a nuestro segundo div con class

Adicion la class llamada **bio** como el en primer div ejemplo:
``<div class="AQUI">``

```html
   <div class="container">
        <div AQUI>
            <!-- estoy dentro de un div -->
        </div>
        <div>
        </div>
    </div>
```

### Dar estilo a nuestro segundo div con css

en **style.css**

```
.bio {
    margin-bottom: 200px;
}
```

### Crear un imagen y un titulo con html

crea una etiqueta img `<img>`

En la imagen adicion la class **profile-img**. `<img class="AQUI" src="AQUILINK">`

crea una etiqueta h3 ejemplo`<h1>AQUI</h1>`

```html
   <div class="container">
        <div class="bio">
            <!-- CREA UN IMG -->
            <!--  CREA UN TITULO H3 -->
        </div>
        <div>
        </div>
    </div>
```

### Dar estilo al titulo y a la imagen

en **style.css**

```
.profile-img {
    width: 0px;
    height: 0px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}

h3 {
    font-size: 0px;
    margin: 0;
    font-weight: bold;
}
```
### Arregla la imagen y el texto

Imagen:

```
width: ;
heigth: ;
```

Texto:
```
font-size: ;
```

# DESCANSO

### Crear nuestro tercer div 

```html
   <div class="container">
        <div class="">
            <!-- estoy el segundo div-->
        </div>
          <!-- CREAR NUESTRO TERCER DIV AQUI -->
    </div>
```


### Dar estilo a nuestro tercer div con class

Al tercer div adiciona la class **links**:

```html
   <div class="container">
        <div class="bio">
            <!-- NO CAMBIES NADA AQUI -->
        </div>
        <div AQUI>
            <!-- estoy dentro de un div -->
        </div>
    </div>
```

### Crear una lista dentro del tercer div

Adiciona los items con <li> dentro de la etiqueta   `ul(<ul>)`.

```html
   <div class="container">
        <div >
            <!-- NO CAMBIES NADA AQUI -->
        </div>
        <div AQUI>
            <ul>
            <!-- AQUI ITEM1 -->
            <!-- AQUI ITEM2 -->
            </ul>
        </div>
    </div>
```

### Dar estilos a la lista con CSS

En el archivo **style.css**

Dar estila a la lista, reemplazar la palabra AQUI por **none**.

```
.links ul {
    list-style-type: AQUI;
    padding: 0;
}
```

### Dar estilos a los items con CSS

En el archivo **style.css**

Dar estilo al item cambia de tamanio.

```
.links li {
    margin-bottom: 0px;
}
```

### Crear links dentro de cada item

Dentro de la etiqueta item <li>

Adiciona una etiqueta link, la etiqueta link es esta:

```
<a href="#">Tienda</a>
```

Vamos a tucodigo.

```html
   <div class="container">
        <div class="links">
            <ul>
             <li>
                <!-- AQUI ADICIONA -->
             </li>
            </ul>
        </div>
    </div>
```

### Dar estilos a las etiquetas link(<a>) con CSS.

- Da color a las etiquetas a.
- Cambia de tamanio las letra en **font-size**
- Cambia de la propiedad **text-decoration** con el valor none.

```
.links a {
    text-decoration: AQUI;
    color: AQUI;
    font-size: 0px;
    font-weight: bold;
    transition: color 0.3s ease;
}

.links a:hover {
    color: AQUI;
}
```

### DESCANSO

### Adicionando logica

## Funciones definidas en JAvascript

```

setInterval(() => {}, 1000);

```

* `1000` = **1000 milliseconds**
* `1000 ms = 1 segundo`


### Creando una variable de fecha

```
let now = new Date();
```

```
  let time = now.toLocaleTimeString("en-US", {
    timeZone: "Asia/Tokyo",
    hour: "2-digit",
    minute: "2-digit",
    second: "2-digit"
  });



.hover-text {
  color: black;        /* normal text color */
  transition: color 0.3s;  /* smooth color change */
}

.hover-text:hover {
  color: red;          /* color when hovered */
  text-decoration: underline; /* optional effect */
}
```


### Integrando a nuestro HTML

```
  document.getElementById("time").innerHTML = time;
```
