1: Ubicacion actual
➜ pdw
    /home/camaazul

2,3: Crear carpeta, cambiar ubicacion
➜ mkdir ejercicios;cd ejercicios
    ejercicios

4: Abrir con VSCode

5: Creo carpeta "ejercicio1" con VSCode

6 Creo archivo "REAME.md" con VSCode

7: Nombre e Email configuracion
➜ git config --global user.name "Jeison Rosario"
➜ config --global user.email "developer@jeisonrosaridev.com"

8: Inicializo repositorio git
➜ git init
    Initialized empty Git repository in /home/camaazul/ejercicios/.git/

9: Primer commit
➜ git add ejercicios/README.md (Agrego el archivo al staging area para posterior commit)
➜ git status (muestra el estado del repositorio)
    new file:   ejercicio1/README.md (existe el archivo)
➜ git commit -m "Versión Inicial"  (Commit)
    [master (root-commit) a6be581] Versión Inicial
    1 file changed, 0 insertions(+), 0 deletions(-)
    create mode 100644 ejercicio1/README.md

