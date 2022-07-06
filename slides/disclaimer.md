# Aclaratoria

Antes de la version 2.23 de Git se podia viajar entre committs, ramas y stashes con medio del `checkout`

```bash
git checkout <commit-hash>
```

Luego de la version 2.23 de Git se agregaron nuevos comandos como `switch` y `restore`

```bash
git switch --detach <commit-hash>
```

El comando `restore` vino a sustituir

```bash
git checkout -- <file>
```

Por

```bash
git restore --staged <file>
```
