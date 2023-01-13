## Bussiness Engineering 👋

<img src="https://developers.giphy.com/branch/master/static/api-512d36c09662682717108a38bbb5c57d.gif" width="1000" height="500" />

## Tabla de contenido
1. [Objetivo](#objective)
2. [Reglas](#rules)
3. [Ramas](#branches)
4. [Pasos a test o producción](#consider)

<a name="objective"></a>
### Objetivo
Éstas son las reglas y consideraciones que se deben tener en cuenta como equipo para el uso de los proyectos alojados en este Team.

<a name="rules"></a>
### Reglas repositorios
- Se debe crear un repositorio para cada fuente JAVA, Formas, SQL y Jasper
- Para los repositorios de las formas, se debe crear el repositorio con el nombre de la forma y se debe subir el txt generado por el object list report y la forma.
- El object list report se genera seleccionando la forma, y luego ir a la opción del menú ```File -> Administration -> Object List Report```, esto genera el txt en la misma ruta que está la forma. **Nota:** Se debe compilar y guardar el proyecto para que se visualicen los cambios en el object list report, no solo guardar".

<a name="branches"></a>
### Ramas
- Master: La rama master es la representación de la fuente que está en producción, esta fuente no debe tener desarrollos que no hayan sido aprobados.
- Develop: Es la representación de la fuente que está desplegada en test y que es estable.
- Feature\Consecutivo(Fuentes)_Iniciales(Desarrollador): Es la representación de los desarrollos que se estén llevando, ejemplo: ``` Feature\4491_JP ```
- Bug\Consecutivo(GERS)_Iniciales(Desarrollador): Es la representación de los soportes que se estén realizando, ejemplo: ``` Bug\13522_JP ```

<a name="consider"></a>
### Pasos a test o producción
- Una vez sea instalada en test/producción la versión del desarrollador, mediante el sistema de fuentes, se realizará el merge de la rama Develop (test) o Master (producción), en donde se tomarán los cambios del desarrollador y la de la base de la rama. Esto se hará mediante un pull request que será supervisada por el administrador o el ingeniero autorizado, y el desarrollador.
