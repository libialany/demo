##  Paso 0: Ingresar a nuestro editor

![create an editor](https://editor.raspberrypi.org/en/projects/welcome-to-antarctica-starter)

## Paso 1: Crear un navbar 

## Descripcion:

En el archivo **index.html** y crea 2 etiquetas <a> en la parte de href cambia a **wild.html y climate.html**.

```html
   <header>
      <nav>
        <div>
            <a href="index.html">Home</a>
            <!-- ESCRIBE 2 ETIQUTAS MAS -->
        </div>
      </nav>
    </header>
```


### Paso 2: Dar estilo a nuestro navbar

En el archivo **style.css** da estilo al **navbar**.

```
nav {
  padding: 0 15px;
  height: 60px;
  font-size: 22px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--nav-colour);
}
```

### Paso 3: Dar estilo a los elementos del navbar

Los elementos del navbar son:

```
<a>index</a>
```

```
nav {
  padding: 0 15px;
  height: 60px;
  font-size: 22px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--nav-colour);
}
```

### Paso 4: Crea la Imagen central

```
 <header>
      <div class="hero-image"></div>
    </header>
```

### Paso 5: Adicion estilo a  la imagen central

```
.hero-image {
  min-height: 50vh; /* 50% of the visible area of the page */
  background-image: url('antarctic-lights.jpg');
  background-size: cover;
  background-position: center;
}
```

### Paso 6: Crear grids

un grid es un elemento como las tablas en html.

```
  <section>
    <div class="fact-holder">
      <span>
        <p>
          Antarctica is the coldest continent, but it ...
        </p>
      </span>
    </div>
</section>
```

### Paso 7: adicion estilo a el grid

```
.fact-holder {
  display: grid;
  height: 50vh;
  grid-template-rows: 50% 50%;
  grid-template-columns: 50% 50%;
}
```

### Paso 8: Dar detalles a los cada cuadro del grid con html

```
  <section>
    <div class="fact-holder">
      <span class="fact-card sun">
        <p>
          Antarctica is the coldest continent, but it ...
        </p>
      </span>
    </div>
</section>
```

### Paso 9: Dar detalles a los cada cuadro del grid con css

```
.fact-card {
  width: 100%;
  display: flex;
  background-size: cover;
  background-position: center;
}
```