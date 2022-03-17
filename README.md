
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: 
Con el comando siguiente: git config --global user.email "mail@ejemplo.es"

2. ¿Qué es un Pull Request?
Respuesta: 
Es una solicitud dirigida al dueño de un repositorio, para que revise el codigo de un fork y lo fusione con el suyo.

3. ¿Para qué sirve HEAD en GIT?
Respuesta: 
Es el commit en el que se esta posicionado actualmente.

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: 
En 3: commit, modified, y staged.

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: 
Cada commit tiene un hash sha unico.

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: 
git reset --hard HEAD~3

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: 
Podria surgir si dos personas modifican el mismo archivo en la misma rama.

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: 
git rm

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta:
git remote add origin "url"

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta:
Ocurriria por que no estamos asociados a ninguna rama.
