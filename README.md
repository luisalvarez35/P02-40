# Practica P02-40
____

En esta practica se han hecho dos commits en la carpetaCasa y se han subido al repositorio remoto, despues de ha creado un tag `git tag -a v1.0 -m "Primer tag"`
y se ha actualizado en el repositorio remoto con `git push --tags`. Des pues de esto se ha vuelto al primer commit con `git reset --hard`
para realizar cambios en el codigo he intentar subirlos al repositorio remoto donde ha dado el siguiente error.

` ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/luisalvarez35/P02-40.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details. `

Para "solucionar" esto se ha hecho un `push --force` lo cual ha causado que se actualice el repositorio remoto al estado actual perdiendose asi todos los cambios y 
commits realizados anteriormente.

Por ultimo se ha actualizado el repositorio en la carpetaInstituto y se ha comprobado que estaba el tag creado anteriormente con `git tag`.
