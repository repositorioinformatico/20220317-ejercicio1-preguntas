
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: git config --global user.email xxxxxxxxx@xxxxxxx.xxx

2. ¿Qué es un Pull Request?
Respuesta: es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork

3. ¿Para qué sirve HEAD en GIT?
Respuesta: se refiere al commit en el que está tu repositorio posicionado

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: tres estados principales en los que se pueden encontrar tus archivos: confirmado (committed), modificado (modified), y preparado (staged)

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: Un hash SHA-1 

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: git reset --hard HEAD~3

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: sale cuando dos personas han cambiado las mismas líneas de un archivo 

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: Borrando la carpeta oculta .git con rm -rf 

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: git clone https://github.com/xxxxxxxxx/xxxxxxx.git

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta: Rebase funciona creando un estado HEAD separado temporalmente mientras se ejecuta.
