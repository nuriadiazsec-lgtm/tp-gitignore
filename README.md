¿Para qué sirve el archivo .gitignore?
El archivo .gitignore sirve para indicarle a Git qué archivos o carpetas no debe seguir ni incluir dentro del repositorio. Es decir, le dice a Git qué cosas debe “ignorar”.
Esto es útil porque en un proyecto hay muchos archivos que no son necesarios guardar en el repositorio, como archivos temporales, de prueba o generados automáticamente. Gracias al .gitignore, esos archivos no aparecen en git status ni se suben a GitHub.

¿Qué tipo de archivos es conveniente ignorar?
Es conveniente ignorar todos los archivos que no son importantes para el funcionamiento del proyecto o que se generan automáticamente. Algunos ejemplos son: Archivos de log que solo guardan información de errores o procesos, archivos temporales o de prueba, carpetas de dependencias, archivos de configuración personal del usuario y archivos generados por programas o compilaciones.  Ignorar estos archivos ayuda a mantener el repositorio más limpio, organizado y liviano.

¿Un archivo ignorado se sube a GitHub?
No, un archivo ignorado no se sube a GitHub. Esto pasa porque Git no lo rastrea, es decir, no lo tiene en cuenta al momento de hacer un commit. Por lo tanto, al subir el repositorio a GitHub, esos archivos no se incluyen.
