# Ejercicio: Obtener y agregar la imagen del Pokémon a tu Pokédex

Este ejercicio sirve como primera interacción con AngularJS, para familiarizarse con los conceptos vistos en la sesión 3. 

## Instrucciones

1. Con una CMD/Terminal úbicate en la carpeta angular del repositorio e instala las dependencias:
  `npm i`
  * Recuerda que las dependencias de un proyecto de NodeJS/AngularJS viven en package.json
2. Ejecuta el proyecto
  `npm start` o `ng serve -o`
3. Abre tu navegador e ingresa la url de `localhost:4200`
4. En la página ubica la subsección de `*ngFor` de la sección `#Directivas`
5. Dentro de `Mi Pokedex` se encuentran los pokémones que **requieren que incluyas la imagen**
6. Haz clic en cualquier pokémon para que veas su información
7. Dirígite hasta abajo de la información del pokémon para encontrar la propiedad `"sprites"` del objeto
8. En `"sprites": { ... }` podrás encontrar otra propiedad `"front_default": "url_de_la_imagen.png"`
  * Esta es la imagen que **se requiere incluyas en el código**
  * Puedes visitar la [PokéAPI](https://pokeapi.co/) para más información del servicio

## Consejos
* Revisa los comentarios en el componente `app`
  * `app.component.html` -> Línea 101
  * `app.component.ts` -> Línea 65
