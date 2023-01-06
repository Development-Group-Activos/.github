## Bussiness Engineering 👋

<img src="https://developers.giphy.com/branch/master/static/api-512d36c09662682717108a38bbb5c57d.gif" width="1000" height="500" />

## Table of Contents
1. [Objetivo](#objective)
2. [Reglas](#rules)
3. [Ramas](#branches)
4. [Pasos a test o producción](#consider)

<a name="objective"></a>
### Objetivo
Éstas son las reglas y consideraciones que se deben tener en cuenta como equipo para el uso de los proyectos alojados en este Team.

<a name="rules"></a>
### Reglas repositorios
- Se debe crear un repositorio para cada fuente JAVA
- Para las fuentes (SQL, Formas y Jasper) se debe crear un repositorio que las englobe en un proyecto. Ejemplo: Fuentes_GestorDocumental

<a name="branches"></a>
### Ramas
- Master: La rama master es la representación de la fuente que está en producción, esta fuente no debe tener desarrollos que no hayan sido aprobados.
- Develop: Es la representación de la fuente que está desplegada en test y que es estable.
- Feature\Consecutivo(Fuentes)_Iniciales(Desarrollador): Es la representación de los desarrollos que se estén llevando, ejemplo: ``` Feature\4491_JP ```
- Bug\Consecutivo(GERS)_Iniciales(Desarrollador): Es la representación de los soportes que se estén realizando, ejemplo: ``` Bug\13522_JP ```

<a name="consider"></a>
### Pasos a test o producción
- Una vez sea instalada en test/producción la versión del desarrollador, mediante el sistema de fuentes, se realizará el merge de la rama Develop (test) o Master (producción), en donde se tomarán los cambios del desarrollador y la de la base de la rama. Esto se hará mediante un pull request que será supervisada por el administrador o el ingeniero autorizado, y el desarrollador.
