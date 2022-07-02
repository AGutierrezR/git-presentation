
# Configuración

La forma en que Git puede rastrear quien hizo que cambios es por medio del nombre y del email, para configurar estos usamos los siguientes comandos en la terminal:

```bash {all|1|2|all}
git config --global user.name "Bruce Wayne"
git config --global user.email "mrwayne@wayneenterprises.com"
```

Esta configuracion es la configuracion **Global** que todos los proyectos de nuestro ordenador tendra. Sin embargo si queremos configurar de manera diferente un proyecto especifico lo podemos hacer con los comandos:

```bash {all|1|2|all}
git config user.name "Batman"
git config user.email "batman@darkknight.com"
```

**Nota**: Al quitar la opcion `--global` la configuración queda limitada a ese repositorio.
