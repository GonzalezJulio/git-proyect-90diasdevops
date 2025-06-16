# 🚀 Repositorio de Prácticas Git: Básico + Avanzado

Este repositorio contiene todos mis ejercicios prácticos de **Git y GitHub**, organizados para practicar desde lo básico hasta técnicas avanzadas. Es parte de mi entrenamiento intensivo para dominar flujos de trabajo reales de desarrollo y colaboración.

---

## 📁 **Estructura del Repositorio**

├── fundamentos/ # Desafíos y comandos básicos
│ ├── comandos-basicos/
│ ├── branching/
│ ├── merging/
│ ├── pull-requests/
│ ├── stash-tags/
│ ├── reset-revert-amend/
│ ├── resolucion-conflictos/
│
├── avanzado/ # Desafíos y técnicas avanzadas
│ ├── rebase-interactivo/
│ ├── cherry-pick/
│ ├── merge-conflict-avanzado/
│ ├── reset-revert-avanzado/
│ ├── amend-advanced/
│ ├── hooks/
│ ├── feature-rebase/
│ ├── squash/
│ ├── debugging-reflog-bisect/
│
└── README.md # Esta guía

markdown
Copiar
Editar

---

## ✅ **Cómo trabajar cada desafío**

### 1️⃣ **Crea una rama por cada bloque**

| Rama sugerida | Contenido |
|---------------|-------------------------------|
| `fundamentos/branching` | Práctica de ramas |
| `fundamentos/merging` | Práctica de merge |
| `fundamentos/pull-requests` | Crear PR |
| `fundamentos/stash-tags` | Stash y tags |
| `fundamentos/reset-revert-amend` | Reset, revert y amend |
| `fundamentos/resolucion-conflictos` | Conflictos básicos |
| `avanzado/rebase-interactivo` | Rebase interactivo |
| `avanzado/cherry-pick` | Cherry-pick entre branches |
| `avanzado/merge-conflict-avanzado` | Conflictos complejos |
| `avanzado/reset-revert-avanzado` | Reset y revert avanzados |
| `avanzado/amend-advanced` | Amend avanzado |
| `avanzado/hooks` | Git Hooks automáticos |
| `avanzado/feature-rebase` | Rebase de feature branch |
| `avanzado/squash` | Squash de commits |
| `avanzado/debugging-reflog-bisect` | Reflog, bisect y blame |

Ejemplo para crear:
```bash
git checkout main
git pull origin main
git checkout -b fundamentos/branching
2️⃣ Trabaja siempre dentro de su carpeta
Ejemplo:

bash
Copiar
Editar
cd fundamentos/branching
echo "Ejemplo de Branching" > branching.txt
git add .
git commit -m "feat: archivo de práctica de branching"
git push origin fundamentos/branching
3️⃣ Usa comandos clave para cada práctica
Técnica	Comandos clave
Branching	git checkout -b, git branch, git merge
Pull Requests	Crear rama, push, usar “Compare & PR” en GitHub
Stash & Tags	git stash, git stash pop, git tag -a
Reset/Revert/Amend	`git reset --soft
Rebase interactivo	git rebase -i HEAD~n
Cherry-pick	git cherry-pick <hash>
Conflictos	Modificar mismo archivo en ramas distintas, git merge, resolver marcadores
Hooks	Crear scripts en .git/hooks/, usar chmod +x
Squash	git rebase -i con squash
Reflog & Bisect	git reflog, git bisect start

4️⃣ Empuja tus cambios
Para ramas con historial modificado (rebase, amend o squash):

bash
Copiar
Editar
git push origin <branch> --force
⚡ Trucos útiles
✔️ Ver árbol de commits:

bash
Copiar
Editar
git log --oneline --graph --all
✔️ Recuperar algo borrado:

bash
Copiar
Editar
git reflog
git checkout <hash>
✔️ Resolver conflictos:

Edita archivo conflictivo

Elimina <<<<<<<, =======, >>>>>>>

git add archivo

git merge --continue o git rebase --continue

🎯 Mejores prácticas
✅ Una feature por rama
✅ Siempre pull antes de empezar
✅ Usa PR para unir a main
✅ Rebase para limpiar historial
✅ Hooks para automatizar chequeos
✅ Usa reflog para no perder nada

🚀 Meta de este repo
Este repositorio es mi laboratorio personal para consolidar habilidades en:

Control de versiones profesional

Resolución de conflictos reales

Estrategias de branching

Limpieza de historial con rebase

Automatización con hooks

Debugging de historial y recuperación

📌 Estado: En constante crecimiento 🚧
¡Cada carpeta y rama muestra mi progreso real con ejemplos prácticos, listos para revisarlos y compartirlos!



