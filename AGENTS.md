# Reglas para agentes en este repo

Rol: guardar las capturas y videos de prueba que se embeben en los PRs de los repos de `robert-flo`. No hay código.

- **Público.** Nada que venga de un repo privado (`sura-*`, `ceo`, labs privados) ni capturas con datos personales, tokens o sesiones autenticadas.
- **Ruta:** `<repo>/pr-<número>/<archivo>` (por ejemplo `reel/pr-18/portada.png`). Nombres en minúsculas y con guiones.
- **Solo agregar.** No se borran ni se reemplazan archivos, ni se reescribe historia: los PRs ya publicados enlazan a estas rutas.
- **Enlace para el body del PR:** `https://raw.githubusercontent.com/robert-flo/assets/main/<repo>/pr-<número>/<archivo>`.
- Git: rama auxiliar → PR a `main` → rebase → merge → borrar la rama. Sin trailers `Co-authored-by`.
- Idioma: español en este archivo y en el README; nombres de archivo descriptivos.
