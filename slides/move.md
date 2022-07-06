# ¿Qué pasa cuando movemos archivos?

Otros sistemas de control de versiones tienen problemas a la hora de que se mueven archivos.

En Git renombrar y mover son la misma cosa, la idea basica es que se tiene un trozo de contenido que se ha movido de una ruta a otra.

Para mover un archivo solo hacer falta usar el comando `mv`

```bash
git mv <ruta-actual> <nueva-ruta>
```

Este comando hace que Git sepa (y no intuya) que un archivo ha sido movido.

Si se han movido muchos archivos y se quieren agregar al Staging Area se recomienda usar el siguiente comando:

```bash
git add -A .
```
