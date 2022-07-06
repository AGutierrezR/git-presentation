# Deshacer y Rehacer con Reset

Git nos permite ir atras y olvidar los cambios a partir de cierto punto con el comando `reset` (de manera destructiva para la historia)

```bash
git reset --hard HASH
```

Esto recuperar el estado de un commit dado, y borrar para siempre cualquier recuerdo de commits más nuevos.

El comando `reset` tiene 3 opciones

- `--hard`: Borra todos los commits y cambios que estaban después del commit seleccionado
- `--soft`: Borra todos los commits que estaban después del commit seleccionado, pero deja los archivos modificados en dichos commits en el **Staging Area**
- `--mixed`: Es similar que `--soft` pero en vez de dejar los archivos en el **Staging Area** los deja en el **Working Directory**