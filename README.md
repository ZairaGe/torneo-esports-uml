# torneo-esports-uml

Actividad 3 de Entornos de desarrollo

# Sistema de Gestión de Torneos de eSports
## Autor: Zaira González Encabo

Perfil de GitHub: ZairaGe (https://github.com/ZairaGe)

## Descripción del Proyecto:
Este proyecto implementa un sistema de gestión de torneos de eSports
utilizando UML para el modelado y Java para la implementación.

Link al repositorio del proyecto: https://github.com/ZairaGe/torneo-esports-uml

## Diagrama UML: 
En el diagrama se identifican los Actores GESTOR y JUGADOR que representan las interacciones con el sisyema.
Casos como registrar equipos, inscribir equipos en torneo, generar emparejamientos y registrar resultados.
Se han empleado relaciones include para indicar dependencias entre acciones, como por ejemplo, no se podría
inscribir equipos sin antes la creación de un torneo.
Y también se han empleado relaciones extends entre la acción entregar premios y jugador, ya que es una 
acción que no sería indispensable, pero probable.

### Diagrama de Casos de Uso:
En el diagrama se pueden ver las entidades: JUGADOR, EQUIPO, TORNEO y GESTOR, que es el que tiene los métodos
y une TORNEO con EQUIPO.

![Diagrama de casos de uso](diagrams/casos-uso.png)
### Diagrama de Clases
![Diagrama de clases](diagrams/clases.png)
## Estructura del Proyecto
torneo-esports-uml/ ├── src/
│ ├── es/empresa/torneo/
│ │ ├── modelo/
│ │ ├── control/
│ │ ├── vista/
│ │ ├── Main.java
├── diagrams/
│ ├── casos-uso.png
│ ├── clases.png
├── README.md
├── .gitignore
├── LICENSE (opcional)
## Instalación y Ejecución
1. Clonar el repositorio:
`git clone https://github.com/usuario/torneo-esports-uml.git`
2. Compilar y ejecutar el proyecto:
`cd src javac es/empresa/torneo/Main.java java es.empresa.torneo.Main`
## Justificación del diseño
Por qué se eligió esa estructura y cómo se organizan las clases.

## Conclusiones
Sobre el aprendizaje obtenido.
Conclusión y sincera opinión de la actividad: 
Esta actividad me ha resultado bastante complicada de entender. Siento que no tuvimos suficientes clases prácticas para poder explicarla
a fondo, y me ha costado saber si he cumplido exactamente con todos los puntos.
Aun así, el trabajo de investigación que hice por mi cuenta me ayudó a entenderlo mejor poco a poco.
En cuanto al uso de Java, en algunos apartados parecía opcional, pero en otros se daba a entender que era obligatorio, lo cual me confundió un poco.
He intentado cumplir con lo que entendí como obligatorio dentro de mi tiempo disponible, aunque me queda la duda si lo he entendido y hecho todo bien