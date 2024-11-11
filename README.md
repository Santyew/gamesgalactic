# recordvideogames

## Descripción del proyecto: Empresa de videojuegos

En este proyecto tiene como cometido hacer videojuegos para cualquier plataforma en el cuál están clasificados con un **software** de gestión para reuniones, *salas de coferencia*, *catálogo* de los juegos,información general de sus proyectos, *nombre* de los desarrolladores importantes, incluido directores de proyecto, fechas de salida de los *próximos desarrollos*, estado de los videojuegos, fases de la *etapa de desarrollo*, *productos de venta*, *estadísticas generales de ventas* en las diferentes plataformas. En esta aplicación está limitada por capas donde el ```desarrollador``` puede visualizar las reuniones y salas de coferencias, fechas de salida y el estado pero su proyecto es decir si un desarrollador tiene ```un proyecto o dos cómo máximo a la vez```. El **director** puede ver todo excepto la información de el estado de los videojuegos. Por otro lado los **gestores de marketing** puedenver únicamente los desarrolladores, productos de venta y las estadísticas generales de ventas en diferentes plataformas. Por último el **CEO** puede visualizar todo sin excepción alguna.

## Crear una nueva rama
### Crear una nueva rama en tu repositorio de Git llamado version-v2 

```code
git fetch
git pull origin main
Desde https://github.com/Santyew/recordvideogames
 * branch            main       -> FETCH_HEAD
Ya está actualizado.
git checkout -b version-v2
Cambiado a nueva rama 'version-v2'
```

#### Definir actores y operaciones

**ACTORES** 

**Desarrolladores:** Usuario con registro que puede visualizar parte de los contenidos de la aplicación y que necesita la aprobación del director y CEO.

**Director:** Usuario que puede visualizar casi todo el contenido menos el estado de desarrollo y que puede manipular contenido pero con permisos.

**CEO:** Usuario maestro que puede visualizar cualquier contenido y modificarlo sin necesidad de permisos.

### Opreciones por Actor

```Desarrollador```

i. Visualizar sus proyectos

ii. Leer notas de otros desarrolladores.

iii. Ver las próximas reuniones y su sala.

iv. Visualizar fecha de salida.

v. Visualizar el estado de proyectos.

vi. Crear cuenta de usuario.

vii. Iniciar sesión en la aplicación

```Director```

i. Visualizar proyectos.

ii. Visualizar las fechas de salida.

iii. Ver las próximas reuniones y su sala.

iv. Iniciar sesión en la aplicación.

v. Visualizar el estado de proyectos.

vi. Crear cuenta de usuario.

vii. Ver catálogo de juegos.

viii. Visualizar información de los videojuegos.

ix. Ver el nombre de los desarrolladores y directores.

x. Visualizar los productos.

``CEO``

i. Visualizar proyectos.

ii. Visualizar las fechas de salida.

iii. Ver las próximas reuniones y su sala.

iv. Iniciar sesión en la aplicación.

v. Visualizar el estado de proyectos.

vi. Crear cuenta de usuario.

vii. Ver catálogo de juegos.

viii. Visualizar información de los videojuegos.

ix. Ver el nombre de los desarrolladores y directores.

x. Visualizar los productos.

xi. Información de la fase de desarrollo de los videojuegos.



