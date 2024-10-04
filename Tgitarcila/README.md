# Pasos del TallerGit

1. Cree el repositrio local en el escritorio y lo nombre Tgitarcila (ya tenia cuenta de GititHub)
2. Navegue hasta el directorio que cree en este caso Tgitarcila
3. Configure mi nombre y correo desde la consola
4. Cree la rama feature y realice los tres commits, añadi el archivo, hice los cambios
5. Tuve que crear la rama master y fusione los cambios de la rama feature en master
6. Reveri el merge y realize el rebase de la rama feature sobre master
7. Cree la rama hotfix para agregar un cambio critico e hice un commit
8. Regrese a la rama master para aplicar el commit de hotfix
9. Explore el Reflog para encontrar el commit perdido y lo restaure
10. Despues relice un cambion en la rama feature y otro en la master para fusionarlos y crear un conflicto
11. Resolvi el conflicto manualmente desde visual studio code, abriendo el archivo txt desde la consola
de Gitbash con el comando (code conflicto.txt) y vi las marcas que indican las secciones en conflicto y 
edite el archivo para resolver el conflicto y guarde el archivo y volvi a la terminal para marcar el archivo
como resuelto con el comando (git add conflicto.txt)
12. Complete el proceso de fusion con el comando (git commit -m "Solucionando conflicto en conflicto.txt")

# Resultados Obtenidos

- Se logró fusionar la rama feature en master después de resolver el conflicto.
- El estado del repositorio es limpio y todos los cambios han sido comprometidos correctamente