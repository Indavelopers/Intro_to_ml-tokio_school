# SOLUCIONES PARA COMPLETAR Y ENVIAR LOS EJERCICIOS

## Descargar los ejercicios
Los ejercicios estarán disponibles en este repositorio remoto en GitHub, desde donde los descargaremos.

El repositorio es privado, por tanto debes crear una cuenta de usuario en GitHub y enviar tu nombre de usuario o email al profesor por mensaje en la plataforma.

Para descargar los ejercicios, tenemos 2 opciones:
- Usar las funcionalidades de Git para clonar el repositorio y actualizar posteriormente los archivos cada sesión.
- En Google Colab, busca el archivo en el repositorio y guarda una copia en tu Drive (preferiblemente) o en un repositorio de tu propiedad, **nunca en el repositorio original del curso**.
- Acceder a los archivos a través de la web de GitHub y descargarlos manualmente:
  - Accede a la versión raw del archivo
  - Click con botón derecho y "Descargar como"
  - En local, cambia su extensión a la adecuada, p. ej. ".ipynb"
  
Si tienes bastante manejo y soltura con Git, puedes utilizar la primera opción, pero cuidado, puesto que Git es complejo en ocasiones.

## Completar los ejercicios
**IMPORTANTE**: El repositorio remoto se actualizará constantemente durante el curso, por lo que cada vez que vayamos a realizar los ejercicios de una nueva sesión debemos asegurarnos de que los hemos actualizado.

Estas instrucciones son sólo aplicables si estamos trabajando con un repositorio local clonado del repositorio remoto. Si los descargamos por la web de GitHub o los copiamos desde Colab, no habrá problema.

Para asegurarnos de que no haya ningún problema, debemos proceder siempre en este orden para cada nueva sesión:
1. Actualizar mi repositorio local con las posibles nuevas versiones de los ejercicios con "git pull".
1. Copiar los archivos del directorio de la unidad actual a nuestro directorio "soluciones".
1. Trabajar sobre los archivos de dicho directorio.
1. **Nunca hacer un "git push" al repositorio remoto del curso.**

Si queremos usar un repositorio remoto de nuestra propiedad, teniendo suficiente soltura con Git, podemos tener varios repositorios remotos en Git, uno para "pull" y otro para "push" con "git remote".

Es importante copiar los archivos al directorio "soluciones" ya que así, si hacemos un "git pull" desde el diretorio remoto, no nos arriesgaremos a perder nuestro trabajo por "machacar" una nueva versión del archivo.

Por limitaciones temporales en el uso del respositorio remoto, les daremos a los alumnos un amplio acceso al mismo, lo cual lleva aparejado la posibilidad de que tengan permisos de modificación del mismo. Si lo modificaran por error, le producirían serios inconvenientes al resto de alumnos hasta que lo corrigiéramos, por lo cual pedimos **extremar las precauciones** con nuestras operaciones.

## Enviar los ejercicios
Para enviar los ejercicios, simplemente los subiremos desde local a la plataforma del curso, individualmente, en la unidad

## En resumen
- Si usas Colab, no trabajarás con un repositorio local, sino guardando tu trabajo en tu Google Drive o en un repositorio remoto de GitHub de tu propiedad.
- Si descargas los archivos desde GitHub, siempre los tendrás actualizados.
- Si vamos a usar un repositorio local en nuestro PC o VM, debemos asegurarnos de:
  - Actualizar el repositorio con "git pull" antes de comenzar con los ejercicios de la sesión.
  - Asegurarnos de copiar los archivos al directorio "soluciones" antes de modificarlos.
  - Asegurarnos de no hacer git push al repositorio remoto del curso.
- Por limitaciones de permisos, debemos extremar las precacuciones para evitar guardar nuestros cambios en el repositorio remoto del curso, lo que provocaría problemas al resto de alumnos.
