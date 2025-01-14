# SkyLink
## Integrantes:
- Aramayo Gonzales Tatiana Jael
- Camargo Orozco Luciana Fernanda
- Quisbert Moya Patricia Andrea
- Sonco Villegas Melany Andrea
- Vacaflor Nina Leonardo Emanuel
## ¿De qué se trata el proyecto?
Hoy en día, una de las principales problemáticas que existen dentro de la ciudad de La Paz es hallar un modo de movilizarse a lo largo de toda la urbe paceña. Cada persona tiene el tiempo contado y, por estadística, tenemos que la mayoría de la población no cuenta con un automóvil propio para poder movilizarse, tanto dentro como fuera de la ciudad, por lo que se implementaron nuevos tipos de transporte acorde a las distintas necesidades de la población, habilitando con ello el servicio de transporte público "Mi Teleférico".

Este resultó ser uno de los mejores transportes para el momento, novedoso y rápido, que era lo que a la gente le angustiaba. 

Contrario a lo que se esperaría de un nuevo e innovador tipo de transporte, este paso rápidamente a ser uno más del montón, así como el PumaKatari u otros. Se empezó a hacer una especie de comparación entre cada uno de los transportes disponibles para poder elegir el más adecuado. Con esa idea en mente es que decidimos crear "SkyLink", una aplicación que considera tanto el tiempo que se emplea en llegar de un destino a otro como el precio a pagar por el servicio. 

Con SkyLink buscamos encontrar el camino más cómodo posible para poder transportarse en el teleférico en cualquiera de las líneas habilitadas, esto de una manera rápida y sencilla para que cada usuario pueda comparar sus opciones en un instante. Con esto buscamos tener en cuenta la comodidad del pasajero tanto en cuestión de tiempo como en cuestión de dinero, buscando la ruta menos compleja para que el usuario pueda llegar a su destino de la mejor manera posible.


## Instalación del Programa
Para instalar el programa adecuadamente se deben seguir los siguiente pasos:
### 1. Instalar Visual Studio Code
Visual Studio Code es un editor de código fuente que fue desarrollado por Microsoft. Es gratuido y de código abierto, además de multiplataforma, por lo que está disponible para Windows, macOs y Linux.

Instalaremos esta aplicación para ejectuar el programa propuesto en este repositorio.

Para instalar Visual Studio Code puede ver el siguiente [video guía](https://youtu.be/X_Z7d04x9-E?si=_RdSWXTya-nPbU4I) o dirigirse a la [Página oficial de Visual Studio Code](https://code.visualstudio.com/).
### 2. Instalar el compilador de Java
El programa propuesto se encuentra escrito en Java, por lo que será necesario tener instalado un compilador de Java para poder ejecutar el código desde su ordenador. Para esto puede seguir el siguiente [video guía](https://www.youtube.com/watch?v=5voE8tvtVV8)
### 3. Descargar los archivos del proyecto
Para finalizar, debemos descargar los archivos de este repositorio a su ordenador. Esto puede hacerse de manera manual, descargando los archivos uno por uno y colocandolos en una carpeta que luego se abrirá con Visual Studio Code, o incluso copiando el texto que se encuentra dentro de los archivos y pasarlos a archivos creados desde su computadora. Pero la manera más sencilla es haciendo uso de Git. Para esto, puede instalarlo desde la [Página oficial de Git](https://git-scm.com/).

Una vez haya instalado correctamente Git abra la terminal de comandos, dirijase a una carpeta de su preferencia (donde guardará el programa) y ejecute los siguientes comandos:
```
git init
git clone https://github.com/LeonardoVNC/SkyLink.git
```
Esto clonará todos los archivos y ramas del repositorio en su ordenador. Basta con arrastrar esta carpeta a Visual Studio Code para añadirla a su Espacio de Trabajo. Una vez ahi, abra todos los archivos para comprobar que se hayan descargado correctamente. 
## ¿Como ejecutamos el programa?
Cuando esté seguro de que se han descargado correctamente todos los archivos del repositorio, dirijase a la clase "Menu.java" y ejecute el programa con el boton _Run Java_ ubicado en la esquina superior derecha. Esto debería abrir una terminal de comandos donde se dispondrá de toda la información necesaria para que siga el uso del programa, contamos con un menú sensillo y amigable.

En caso de que no comprenda el uso del menú, explicamos a continuación su funcionamiento:
### Primer menú
Al iniciar el programa se le dará la bienvenida y se le presentarán 4 opciones, cada una enumerada desde 1, puede elegir cualquiera de estas opciones para seguir con el programa. 

La primera opción abrirá el menú para optimizar el tiempo de viaje, es decir, que abrirá un proceso para que pueda calcular cual es la ruta más rápida entre 2 nodos.

La segunda opción hará un proceso similar, pero este se orienta a la búsqueda del camino más barato entre 2 nodos.

La tercera opción termina la ejecución del programa.

La cuarta opcion abrirá un menú orientado a desarrolladores, muestra opciones para ver el estado actual del grafo empleado.
### Menú Tiempo
Este menú esta orientado a buscar el recorrido en teleférico más rápido entre 2 estaciones. Al ingresar se le pedirán 2 números, estos número corresponden a las estaciones que desea ingresar al algoritmo del programa, al lado de cada estación disponible se muestra el número que la identifica.

Una vez ingresadas las estaciones a buscar el programa dará inicio a los algoritmos necesarios para hallar la respuesta deseada. Esta respuesta se le mostrará dentro de la misma terminal, indicando el tiempo estimado y el recorrido que debe seguirse.

Al ingresar cualquier caractér el programa volverá a su menú principal.
### Menú Precio 
Este menú es bastante similar al menú anterior, con la diferencia de que al inicio se le pedirá una entrada más, indicando si usted es un cliente estándar o si cuenta con tarjeta de Estudiante o de Adulto Mayor. Esto se hace para calcular de manera correcta el costo de la ruta.
### Menú Dev
Este es un menú orientado a la visualización del estado actual del grafo y del set que contiene las líneas a las que pertenece cada nodo. Su función radica en hacer seguimiento del estado de estas estructuras de datos, es especialmente útil cuando se hacen modificaciones al input, cambios tales como adición de nuevas líneas, estaciones o conexiones.


Con esto acaba la guía de uso de SkyNet, espero que disfrutes explorando por nuestro menú viendo las funciones que tiene y que te sea de gran ayuda.
