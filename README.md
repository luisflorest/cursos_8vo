# cursos_8vo

Cuadernillos de estudio de 8° básico 2026 para las pruebas de síntesis del segundo semestre (unidades 3 y 4).

## Estructura

| Carpeta | Contenido |
| --- | --- |
| `index.html` | Portal con los 4 ramos y las 8 unidades |
| `ciencias/`, `historia/`, `lenguaje/`, `matematica/` | Un cuadernillo interactivo por unidad (`u3/`, `u4/`), versión v2 |
| `descargas/` | Apuntes y guías con solucionario en Word |
| `proyecto/` | Copia completa del proyecto de estudio: temarios por unidad, bitácora, instrucciones del tutor y versiones anteriores de los cuadernillos. No se publica en el sitio (`.vercelignore`). |

## Publicación

Sitio estático sin compilación, publicado en Vercel desde la rama `main`. Los cuadernillos no usan recursos externos y guardan el avance en el navegador (`localStorage`).

Para actualizar: reemplazar el HTML de la unidad (por ejemplo `matematica/u3/index.html`) y hacer push a `main`.
