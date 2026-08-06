# Quarto

## 1. Previsualizar en local

Desde la carpeta del proyecto:

```         
quarto preview
```

## 2. Completar contenido

- `index.qmd` — página de inicio / bio
- `research.qmd` — líneas de investigación
- `teaching.qmd` — cursos y láminas (sube tus PDFs a `slides/`)
- `publications.qmd` — lista de publicaciones
- `cv.qmd` — CV (puedes subir un `cv.pdf` a la raíz y enlazarlo)
- `figures/foto.jpg` — agrega tu foto aquí

## 3. Renderizar el sitio

```         
quarto render
```

## 4. Publicar en GitHub Pages

1.  Crea un repositorio en GitHub.

2.  Sube el proyecto:

    ```         
    git init
    git add .
    git commit -m "Sitio inicial"
    git remote add origin https://github.com/tu_usuario/tu_repo.git
    git push -u origin main
    ```

3.  En GitHub: Settings → Pages → Source → selecciona la carpeta `docs/` en la rama `main`.

4.  Tu sitio quedará en [`https://tu_usuario.github.io/tu_repo/`](https://tu_usuario.github.io/tu_repo/) (o en la raíz si el repo se llama `tu_usuario.github.io`).
