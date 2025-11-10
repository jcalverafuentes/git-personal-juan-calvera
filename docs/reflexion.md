# ENTREGA EJERCICIO 2 — Proyecto propio

## Autor
**Juan Calvera Fuentes**

---

## Repositorio
**Repositorio:** [jcalverafuentes/git-personal-juan-calvera](https://github.com/jcalverafuentes/git-personal-juan-calvera)

---

## Clonación del repositorio personal
Una vez creado el repositorio, se descarga en el directorio deseado el proyecto **git-personal-juan-calvera** para comenzar el desarrollo.

![Clone](/img/1_git_clone.png)

---

## Estructura inicial del proyecto personal
Se crean las carpetas y archivos base del proyecto, replicando la metodología utilizada en el primer ejercicio.

![Structure](/img/2_structure.png)
![Create Structure](/img/2_create_structure.png)

---

## Guardar cambios (Estructura inicial)
Se guardan los cambios de la estructura inicial creada:  
- `src/index.html`  
- `src/style.css`  
- `docs/reflexion.md`  

![Changes](/img/3_save_changes.png)

---

## Crear rama proyectos
Se crea la rama **feature/proyectos** y se cambia a ella para comenzar a realizar modificaciones.

![Branch](/img/4_create_branch_proyectos.png)

---

## Cambiar estructura
Se abre el proyecto en Visual Studio Code y se edita el archivo `index.html`, añadiendo la siguiente estructura justo antes del cierre del `</body>`:

`<section>`
  `<h2>Mis proyectos</h2>`
  `<ul>`
    `<li>Proyecto 1: Web de gestión de empresas</li>`
    `<li>Proyecto 2: Aplicación de tareas</li>`
  `</ul>`
`</section>`

---

## Guardar cambios (proyectos) 
Guarda, añade y confirma los cambios iniciales mediante git add, git commit y git push

![Changes](/img/5_save_changes_proyectos.png.png)

---

## PR Proyectos 
Se realiza el pull request para fusionar los cambios de la rama feature/proyectos con la principal. 

![PR](/img/6_PR_proyectos.png)

---

## Crear rama contacto 
Se crea una nueva rama destinada a la sección de contacto del proyecto. 

![Branch](/img/7_create_branch_contacto.png)

---

## Guardar cambios (contacto) 
Se confirman los cambios realizados dentro de la rama feature/contacto. 

![Changes](/img/8_save_changes_contacto.png)

---

## Crear conflictos 
Se modifica el mismo archivo en dos ramas diferentes para provocar un conflicto. 

![Conflict](/img/9_conflict_creation.png)
![Conflict](/img/10_conflict_creation.png)
![Conflict](/img/conflicto.png)


---

## Resolver conflictos 
Se unifican manualmente las diferencias entre ramas y se realiza un nuevo commit con la solución. 

![Resolve](/img/11_resolve_conflict.png)

---

## Pull request contacto 
Se sube la rama corregida y se solicita la fusión con la rama principal. 

![PR](/img/12_PR_contacto.png)

---

## Release v2.0.0 
Se genera una nueva versión estable del proyecto que incluye todas las funcionalidades completadas.

![Release](/img/13_version.png)

---