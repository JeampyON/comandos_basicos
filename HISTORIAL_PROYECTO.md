# Historial del proyecto FISEI

## 1. Descripción general

Este proyecto corresponde a la página principal de FISEI. La página está construida con HTML, CSS y Bootstrap, y su contenido principal se encuentra en `index.html`.

La página incluye actualmente:

- Barra de navegación principal.
- Carrusel de presentación.
- Información de las carreras de Software, Industrial y Robótica.
- Sección de servicios institucionales y estudiantiles.
- Selector de tema claro, oscuro o automático.
- Pie de página.

## 2. Estado actual de Git

- Rama activa: `develop`
- Commit actual: `05e0282`
- Etiqueta actual: `v0.5.0`
- Rama `master`: apunta a `c64740f` (`v0.4.0`)
- Rama `hotifx`: contiene el commit `8ca348d`, creado para un cambio de eliminación anterior.

La rama `develop` contiene los cambios más recientes de los servicios de la página.

## 3. Estructura relevante

```text
comandos basicos/
|-- index.html
|-- carousel.css
|-- carousel.rtl.css
|-- indicaciones.info
|-- HISTORIAL_PROYECTO.md
|-- assets/
|   |-- brand/
|   |-- dist/
|   |-- js/
|-- img/
    |-- software.png
    |-- industrial.png
    |-- robotica.png
    |-- bibliotecaFisei.png
    |-- redes.png
    |-- asosecuelita.jpg
    |-- secretaria.png
```

## 4. Historial de commits

### `905ec1f` - Modifica los menús de navegación

Commit: `feat(navbar): Modifica menus en ingles a espaniol`

Cambios realizados:

- Se adaptaron los textos de la barra de navegación al español.
- Se incorporaron elementos como Inicio, Carreras y Servicios.
- Se ajustaron textos relacionados con la búsqueda y los controles de la página.

Archivo principal modificado:

- `index.html`

### `ccdd606` - Modifica la información del carrusel

Commit: `feat(home): modifica informacion del carousel`

Cambios realizados:

- Se actualizó el contenido textual del carrusel de la página de inicio.
- Se ajustaron los mensajes de presentación de FISEI.

Archivo principal modificado:

- `index.html`

### `35f97cc` - Agrega la carrera de Software

Commit: `feat(home): agrega imagen (.png) y asegurar texto de la carrera de Software`

Cambios realizados:

- Se agregó la imagen de Software.
- Se incorporó el título `Carrera de Software`.
- Se añadió una descripción sobre desarrollo de soluciones tecnológicas y aplicaciones.
- Se mantuvo la imagen dentro de una tarjeta circular de Bootstrap.

Archivos modificados:

- `index.html`
- `img/software.png`

### `7d76ac9` - Agrega la carrera Industrial

Commit: `feat(home): agrega imagen (.png), titulo y descripcion para la carrera Industrial`

Cambios realizados:

- Se agregó la imagen de Ingeniería Industrial.
- Se incorporó el título `Carrera Industrial`.
- Se añadió información sobre procesos productivos, calidad, seguridad y mejora continua.

Archivos modificados:

- `index.html`
- `img/industrial.png`

### `1572c42` - Agrega la carrera de Robótica

Commit: `feat(home): agregar imagen (.png), titulo y descripcion para la carrera de Robotica`

Cambios realizados:

- Se agregó la imagen de Robótica.
- Se incorporó el título `Carrera de Robótica`.
- Se añadió información sobre diseño, construcción, programación y automatización de sistemas robóticos.

Archivos modificados:

- `index.html`
- `img/robotica.png`

### `2bc9668` - Agrega detalles mínimos

Commit: `feat: agregar detalles minimos`

Cambios realizados:

- Se completaron detalles de contenido y presentación de la página.
- Se consolidó la estructura visual de las secciones iniciales.

### `f3a97f2` - Agrega `.gitignore`

Commit: `chore(git): agrega el archivo .gitignore`

Cambios realizados:

- Se creó el archivo `.gitignore` para excluir archivos que no deben versionarse.

### `d389016` - Ajusta `.gitignore`

Commit: `chore(git): modifica archiv .gitignore onmitiendo archivos nodejs`

Cambios realizados:

- Se modificó `.gitignore` para omitir archivos relacionados con Node.js.

### `c64740f` - Agrega el servicio de Biblioteca

Commit: `feat(home): agrega informacion del servicio de biblioteca`

Etiqueta: `v0.4.0`

Cambios realizados en la página de inicio:

- Se reemplazó un bloque placeholder de Bootstrap por el apartado `Biblioteca`.
- Se agregó el subtítulo `Libros fisicos y digitales.`
- Se incluyó información sobre solicitar libros físicos y digitales y acceder a ellos virtualmente.
- Se reemplazó la imagen de ejemplo por la imagen real de la biblioteca.

Archivos modificados:

- `index.html`
- `img/bibliotecaFisei.png`

### `f492453` - Agrega el préstamo de equipos de redes

Commit: `feat(home): agrega seccion de prestamo de equipos`

Cambios realizados en la página de inicio:

- Se reemplazó otro bloque placeholder de Bootstrap por el apartado `Préstamo`.
- Se agregó el subtítulo `Equipos de redes.`
- Se documentó el proceso de solicitar equipos para prácticas y proyectos académicos.
- Se incluyeron indicaciones sobre disponibilidad, registro del préstamo y devolución.
- Se agregó la imagen de los equipos de redes.

Archivos modificados:

- `index.html`
- `img/redes.png`

### `8af79d5` - Crea la sección de Secretaría

Commit: `feat(home): agrega informacion de servicio de secretaria`

Cambios realizados en la página de inicio:

- Se creó el apartado `Secretaría`.
- Se agregó el subtítulo `Trámites académicos.`
- Se incluyó información sobre consultas, certificados, documentación y procesos administrativos.
- Se agregó la imagen de Secretaría.

Archivos modificados:

- `index.html`
- `img/secretaria.png`

Este cambio se realizó inicialmente en la rama `feature/secretaria`.

### `24d6676` - Crea la sección de ASO Escuela

Commit: `feat(home): agrega informacion de la asociacion de estudiantes`

Cambios realizados en la página de inicio:

- Se creó el apartado `ASO Escuela`.
- Se agregó el subtítulo `Servicios para estudiantes.`
- Se documentaron los servicios de billar, venta de comida y bebidas.
- Se agregó la información de un espacio para descansar entre clases y actividades académicas.
- Se agregó la imagen de ASO Escuela.

Archivos modificados:

- `index.html`
- `img/asosecuelita.jpg`

### `05e0282` - Fusiona los servicios de ASO Escuela y Secretaría

Commit: `feat(home): fusiona servicios de secretaria y aso fisei`

Etiqueta: `v0.5.0`

Cambios realizados:

- Se integraron los cambios de Secretaría en `develop`.
- Se conservaron simultáneamente los apartados `ASO Escuela` y `Secretaría`.
- Se organizó cada servicio en su propio bloque `featurette`.
- Se conservaron las imágenes correspondientes de ambos servicios.
- Se resolvió el contenido para que los dos apartados aparezcan en la página sin reemplazarse entre sí.

Archivos relacionados:

- `index.html`
- `img/asosecuelita.jpg`
- `img/secretaria.png`

## 5. Estado funcional actual de `index.html`

Los servicios institucionales aparecen en este orden dentro de la sección de featurettes:

1. **Biblioteca**
   - Libros físicos y digitales.
   - Imagen: `img/bibliotecaFisei.png`

2. **Préstamo**
   - Equipos de redes para prácticas y proyectos académicos.
   - Imagen: `img/redes.png`

3. **ASO Escuela**
   - Billar.
   - Venta de comida y bebidas.
   - Espacio para descansar entre clases.
   - Imagen: `img/asosecuelita.jpg`

4. **Secretaría**
   - Trámites académicos.
   - Certificados y documentación.
   - Orientación sobre procesos administrativos.
   - Imagen: `img/secretaria.png`

Cada apartado utiliza la estructura Bootstrap `row featurette`, con una columna para el texto y otra para la imagen.

## 6. Imágenes de las carreras

Las imágenes de las carreras están ubicadas en la fila de tres columnas de la página principal:

- `img/software.png` - Carrera de Software.
- `img/industrial.png` - Carrera Industrial.
- `img/robotica.png` - Carrera de Robótica.

Estas imágenes se muestran con formato circular mediante las clases de Bootstrap y una dimensión de `140 x 140` píxeles.

## 7. Flujo de ramas utilizado

El flujo aplicado hasta ahora fue:

1. Se trabajó inicialmente sobre `develop` para incorporar servicios.
2. Se creó la rama `feature/prestamo-equipos-redes`.
3. La rama de préstamo fue fusionada mediante fast-forward en `develop`.
4. La rama `feature/prestamo-equipos-redes` fue eliminada después de integrar sus cambios.
5. Se creó la rama `feature/secretaria` desde `develop`.
6. Se desarrolló allí el apartado de Secretaría.
7. Se fusionaron los cambios de Secretaría nuevamente en `develop`.
8. Se verificó que ASO Escuela y Secretaría permanecieran como secciones independientes.
9. El estado actual quedó etiquetado como `v0.5.0`.

## 8. Comandos útiles para revisar el proyecto

Consultar el estado actual:

```bash
git status
git branch -vv
git log --graph --oneline --decorate --all
```

Revisar los cambios de la página principal:

```bash
git diff master..develop -- index.html
```

Ver los archivos modificados por un commit:

```bash
git show --stat <commit>
```

Agregar y confirmar la documentación:

```bash
git add HISTORIAL_PROYECTO.md
git commit -m "docs: documenta historial y cambios del proyecto"
```

## 9. Próximos pasos sugeridos

- Confirmar que la documentación sea agregada y confirmada en Git.
- Revisar la página en el navegador en escritorio y móvil.
- Verificar que las rutas relativas de todas las imágenes funcionen.
- Reemplazar textos o botones placeholder que todavía permanezcan en otras áreas de la página.
- Actualizar el pie de página si debe mostrar información real de FISEI.
