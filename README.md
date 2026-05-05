# Trabajo Práctico - Uso de .gitignore

## Comprobación

Se creó el archivo error.log antes de utilizar .gitignore.

Al ejecutar el comando `git status`, el archivo aparecía como no rastreado.

Luego se creó el archivo .gitignore con la regla:

*.log

Después de esto, al ejecutar otra vez `git status`, el archivo error.log dejó de aparecer, lo que muestra que está siendo ignorado correctamente por Git.

También se verificó creando un archivo llamado nuevo.log, el cual tampoco aparece en git status.