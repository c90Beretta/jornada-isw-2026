# Jornada de Ingeniero en Software 2026

Sitio web estatico (solo HTML) para la Jornada de Ingeniero en Software 2026.

**Reto integrador** — EC2 F3 A9: Diseno de un sitio web utilizando HTML5

## Descripcion

Mini-sitio de 2 paginas:

- **index.html** — Inicio / promocion del evento + formulario de registro
- **programa.html** — Agenda completa en tabla

## Estructura del proyecto

```
jornada-isw-2026/
  index.html
  programa.html
  img/
    ues-logo.png
    foto-propia.jpg
  README.md
```

## Agenda oficial

| Inicio | Fin   | Actividad                                          | Tipo                |
|--------|-------|----------------------------------------------------|---------------------|
| 11:00  | 12:00 | Conferencia 1                                      | Conferencia (1 h)   |
| 12:00  | 13:00 | Conferencia 2                                      | Conferencia (1 h)   |
| 13:00  | 13:30 | Entrega de reconocimientos                         | Ceremonia           |
| 13:30  | 14:30 | Conferencia 3                                      | Conferencia (1 h)   |
| 14:30  | 16:30 | Evento cultural: Grupo musical norteno (por confirmar) | Evento cultural (2 h) |

**Fecha del evento:** Lunes 27 de abril de 2026

## Requisitos cumplidos

### Pagina index.html

- [x] Estructura HTML5 completa (`<!doctype html>`, `<html lang="es">`, meta charset, viewport)
- [x] Secciones semanticas: `<header>`, `<nav>`, `<main>`, `<footer>`
- [x] Titulo visible: "Jornada de Ingeniero en Software 2026"
- [x] Fecha visible: "Lunes 27 de abril de 2026"
- [x] Logo UES en `img/ues-logo.png` con alt descriptivo
- [x] Menu de navegacion (Inicio, Programa, Registro)
- [x] Agenda rapida en lista (`<ul>` o `<ol>`)
- [x] Seccion de registro con `id="registro"`
- [x] Formulario con validacion HTML

### Pagina programa.html

- [x] Estructura HTML5 completa
- [x] Mismo menu de navegacion
- [x] Tabla con `<caption>`, `<thead>`, `<tbody>`, `<th scope="col">`
- [x] Columnas: Fecha, Inicio, Fin, Actividad, Tipo, Lugar

### Formulario de registro

- [x] Nombre completo (`required`)
- [x] Correo institucional UES (`required` + `pattern="([0-9]{8}|[0-9]{11})@ues\.mx"`)
- [x] Tipo de asistencia ISW (`<select>`: Alumno ISW / Docente ISW)
- [x] Evento principal (`<input type="radio">`, `required`)
- [x] Comentarios (opcional)
- [x] Accesibilidad: cada campo con `<label for="...">` e `id` correspondiente

### General

- [x] Nombres de archivos en kebab-case (sin espacios, acentos ni mayusculas)
- [x] 1 imagen propia adicional con alt
- [x] Repositorio publico en GitHub
- [x] Sitio publicado con URL publica

## Publicacion

El sitio se publica con **GitHub Pages** desde la rama `main`, carpeta raiz (`/`).

