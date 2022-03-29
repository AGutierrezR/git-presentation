---
theme: default
highlighter: shiki
class: text-center
monaco: dev
fonts:
  mono: MonoLisa
  local: MonaLisa
---

<h1 class="flex items-center justify-center gap-4">
  <GitIcon class="h-40 inline-block"/>
  <Git class="h-35"/>
</h1>
<br>
Version Control System

---
layout: center
---

<div class="grid grid-cols-[1fr,2fr] gap-4">
  <div class="text-center">
    <GitIcon class="h-50 inline-block"/>
  </div>

  <div class="border-l border-gray-400 border-opacity-25 !all:list-none my-auto">

  - Git está definido oficialmente como un sistema de control de versiones distribuido (VCS).
  - Un VCS es un sistema puede ser usado por varias desarrolladores en donde cada desarrollador puede tener su propia versión del proyecto, distribuido en su ordenador

  </div>
</div>

---
layout: image-right
image: ./assets/img/library.jpg
---

<div class="flex h-full flex-col items-center justify-center">

## ¿Qué problemas resuelve Git?
<br>

  <div>

  Supongamos que estás editando en un archivo, quieres guardar los cambios pero no quieres borrar el archivo anterior, por lo que usas **"Guardar Como..."** para guardar la nueva versión en un nuevo archivo y mantener la versión vieja.

  Ahora si tienes una gran cantidad de archivos que van juntos, como un proyecto de desarrollo, para mantener la versión antigua debes archivar todo el directorio. Tener varias versiones puede ser costoso en tiempo y espacio.

  </div>

</div>

---
layout: image-left
image: ./assets/img/git-history.jpg
---

<div class="flex h-full flex-col items-center justify-center gap-4">

## ¿Cómo Git resuelve este problema?

Al iniciar un repositorio de se crea una directorio **.git/** en el que se van a guardar archivos con los cambios que se han generado, estos archivos *no son copias de los archivos que modificamos, sino que son referencias de los cambios que realizamos*

</div>

---

# **¿Cómo usar Git?**
<br>

Git puede ser usado de dos maneras, una por medio de la Terminal o Línea de Comando, y la otra es por medio de una Interfaz Gráfica

<div class="grid grid-cols-2 mt-20">
  <div>

  ## Terminal o CLI
  
  <div class="flex items-center gap-4 h-50">
    <BashIcon class="h-20" />
    <GitBashIcon class="h-20" />
    <PowerShellIcon class="h-15" />
    <WindowTerminalIcon class="h-15" />
  </div>
  </div>

  <div>

  ## GUI

  <div class="flex items-center gap-4 h-50">
    <GitHubIcon class="h-20" />
    <SourceTreeIcon class="h-20" />
    <GitKrakenIcon class="h-20" />
    <TowerIcon class="h-20" />
  </div>
  </div>
</div>
