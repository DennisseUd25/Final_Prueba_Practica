# Informe Final Prueba Práctica 
## Resumen de Correcciones
### PRÁCTICA 1
Sin necesidad de correcciones.

### PRÁCTICA 2
Sin necesidad de correcciones.

### PRÁCTICA 3
#### Problema:
La presente práctica presentaba un error con respecto al archivo .env que se encontraba dentro del devcontainer, este cada vez que se realizaba una actualización o era abierto en un nuevo codespaces se borraba generando conflicto en la ejecución del código del archivo markdown.
#### Solución:
Para el error presentado sobre el archvio .env se ha realizado lo siguiente:
 * Como el repositorio cuenta con el archivo .gitignore cuya función es excluir archivos temporales, configuraciones locales o generados automáticamente que no deben formar parte del repositorio.
 * Se busca dentro del archivo donde hace referencia al nombre del archivo .env y se borra esa línea, para que cuando se cree un nuevo codespace este archvio este presente dentro del directorio.
 * Una vez realizado lo mencionado se puede crear un codespace a partir del repositorio y el error no aparecerá.
 * Antes de ejecutar el código se debe escoger el kernel para el entorno de python, se instalará o activara las extenciones necesarias en este caso (Python + Jupyter).
 * Después escogemos el entorno base (env conda) 
 * Procedemos a ejecutar el código del notebook (Practica3GR5.ipynb).


### CONCLUSIONES 
**Clase 1**
* El análisis de un repositorio en **GitHub** centrado en ciberseguridad no solo nos permitió conocer la plataforma y sus herramientas, sino que también nos enseñó cómo trabajar de manera eficiente en equipo, gestionar versiones. Esta experiencia es fundamental para entender cómo el uso adecuado de plataformas de control de versiones como GitHub es clave en la creación y mantenimiento de proyectos de ciberseguridad, ya que permite asegurar la calidad y seguridad del código a lo largo del ciclo de vida del proyecto.

**Clase 2**
* Kaggle es un herramienta proactiva en el análisis de datos debido a que permita el aprender, practicar, aportar y colaborar en las distintas comunidades existentes, siendo una de las ventajas la fuente de datasets públicos que posee, con la cual es posible el análisis y el tratamiento de datos en un entorno integrado mediante el uso de diversos lenguajes de programación como Python, R, entre otros, que pueden ser de utilidad en procesos de extracción, preprocesamiento y procesamiento de información, la clave en esta herramienta es el saber aplicar las librerías adecuadas en el respectivo proceso.
  
**Clase 3**
* El uso de devcontainer en GitHub Codespaces ofrece varias ventajas:
  * Aseguran que todos los miembros del equipo trabajen en un entorno idéntico, evitando problemas de "funciona en mi máquina" 
  * GitHub Codespaces despliega el contenedor preconfigurado en la nube sin ocupar recursos de nuestro equipo local.
