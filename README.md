
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: Con el comando git config --global user.email daniel@lozano.com

2. ¿Qué es un Pull Request?
Respuesta: Un pull request es cuando tu hacer modificaciones a un fork y luego le pides al dueño original del repositorio que las añada al original. El autor original puede declinar o decidir incorporar tus cambios.

3. ¿Para qué sirve HEAD en GIT?
Respuesta: Para marcar la rama en la que estas en cada momento en el commit.

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: En tres, modificado, preparado(staged) y commiteado.

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: El hash SHA.

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: Con un git checkout <hash> donde el en el hash pondria el de hace 3 commits.

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: Un conflicto es cuando mergeas o rebaseas una rama con la rama main y los archivos de cada rama son versiones distintas. Cuando esto ocurre debemos decidir como queremos solucionarlo, adaptando el codigo o eliminando una parte.

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: Puede borrar la carpeta oculta que almacena el git con el comando rm -rf .git

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta:Con el comando  git remote add origin <url del git>

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta: Seguramente hayamos hecho un git checkout "hash de un commit" en vez de hacer un checkout a una rama. Esto hace que los cambios que hagamos aqui puedan ser perdidos a menos que guardemos el hash de el nuevo commit. Es mejor crear una rama nueva y crear los cambios ahi si lo que pretendemos es guardar los cambios.
