🔹 Comandos Git básicos

git --version → Muestra la versión de Git instalada.

git config --global user.name "Tu Nombre" → Configura tu nombre de usuario en Git.

git config --global user.email "tu@email.com" → Configura tu correo en Git.

git init → Crea un nuevo repositorio Git en la carpeta actual.

git status → Muestra el estado de los archivos (cambiados, listos o no listos).

git add . → Agrega todos los archivos al área de preparación.

git add archivo.html → Agrega solo un archivo específico.

git commit -m "mensaje" → Guarda los cambios con un mensaje.

git log → Muestra el historial de commits.

git log --oneline → Muestra el historial resumido (una línea por commit).

🔹 Conexión con repositorios remotos

git clone https://github.com/usuario/repo.git → Copia un repositorio remoto a tu PC.

git remote -v → Lista las direcciones remotas del repo.

git remote add origin https://github.com/usuario/repo.git → Conecta el repo local con uno remoto.

git push origin main → Sube los cambios a la rama main del remoto.

git pull origin main → Descarga cambios del remoto a la rama main.

🔹 Ramas

git branch → Muestra las ramas disponibles.

git branch nueva-rama → Crea una nueva rama.

git checkout main → Cambia a la rama main.

git checkout -b nueva-rama → Crea y cambia a una nueva rama.

git merge nombre-rama → Une una rama con la actual.

🔹 Otros comandos útiles

git diff → Muestra los cambios en los archivos.

git reset HEAD archivo.html → Quita un archivo del área de preparación.

git reset --hard commit-hash → Regresa el proyecto al estado de un commit específico.
