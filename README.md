Para subir un proyecto a git, puedes hacerlo de dos formas: 
O bien creando el repositorio en github y clonandolo en el local. Para ello usas el comando git clone /URL/ y una vez copiado, puedes ir actualizando su contenido con git add . seguido de git commit -m "comentario" y por ultimo git push para subirlos al repositorio remoto
O puedes crear un repositorio local con git init y luego subirlo al remoto con los comandos 
git remote add origin 
git branch -M main
git push -u origin main