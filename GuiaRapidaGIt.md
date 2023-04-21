# Como iniciar

1. Configura tus credenciales 
git config --global user.name 
git config --global user.email
2. Inicializar un repo
git init nombre_de_la_carpeta
3. Add changes
git status
git add carpeta
git add archivo
git add archivo1 archivo2
4. Ver diferencias
git diff
git diff hash_commit
5. Guardar cambios
git commit -m "mensaje del commmit"
6. Ver tu historial
git log

## Viajar en el tiempo y ramas

### Git checkout

`git checkout num_commit`

```
git checkout rama_a_moverte
git branch rama_nueva
git branch 
```
### Ramas en git
![ramas_git](hero.svg)