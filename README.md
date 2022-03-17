
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: mediante el comando git config --global user.email "dirección de email"

2. ¿Qué es un Pull Request?
Respuesta: es una petición que realiza el propietario de un fork de un repositorio al propietario del repositorio original para que este último incorpore los commits que están en el fork

3. ¿Para qué sirve HEAD en GIT?
Respuesta: es el puntero que apunta a la rama actual y el último commit donde se está trabajando (es el presente)

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: comiteado, modificado y stageado

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: un código HASH hexadecimal de 6 dígitos

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: git reset --hard HEAD~3

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: se produce al intentar fusionar dos ramas cuyo código no coincide y por lo tanto debe solucionarse modificándolo manualmente

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: rm -rf .git/

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: git remote add origin URL

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta: se produce al mover el puntero HEAD a un commit anterior en el tiempo
