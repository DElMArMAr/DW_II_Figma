# Nexcent — Sass

Sass es el lenguaje de extensión de CSS más maduro, estable y potente del mundo.

## Instalación

Instala node.js https://nodejs.org/en/ y luego instala las dependencias:

```bash
npm i
```

## Uso

Compilar en modo watch (desarrollo):
```bash
npm run sass
```

Compilar para producción (minificado):
```bash
npm run sass-build
```

## Estructura

```
sass/
  _settings.scss        # colores, tipografía, breakpoints
  styles.scss            # punto de entrada, importa todo
  partials/
    _clearfix.scss
    _general.scss        # reset + base
    _header.scss
    _navegation.scss
    _titles.scss
    _products.scss        # hero, clientes, segmentos, stats, testimonial, blog, cta
    _footer.scss
    _responsive.scss
css/
  styles.css              # generado, no editar a mano
  styles.css.map
img/
  img-1.png … img-7.png   # ilustraciones usadas en el contenido
index.html
```

## Contributing

http://zetcode.com/javascript/nodesass/

## License

[MIT](https://choosealicense.com/licenses/mit/)
