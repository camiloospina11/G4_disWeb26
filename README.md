# G4_disWeb26

## Ramas del proyecto

```
main
 └── develop
      ├── feature/menu-layout
      ├── feature/carrusel
      ├── feature/multimedia
      └── feature/footer-responsive
```

- `main`: version estable.
- `develop`: rama de integracion del equipo.
- `feature/menu-layout`: encabezado y barra de navegacion (`css/menu.css`).
- `feature/carrusel`: carrusel de imagenes (`carrusel.html`, `css/carrusel.css`).
- `feature/multimedia`: contenido multimedia y menu lateral "Explora" (`css/multimedia.css`, `mosaico.html`).
- `feature/footer-responsive`: pie de pagina y ajustes responsive (`css/footer.css`).

## Flujo de trabajo

**Antes de comenzar a trabajar:**

```bash
git checkout develop
git pull origin develop
git checkout TU-RAMA
git merge develop
```

**Cuando terminen una funcionalidad:**

```bash
git add .
git commit -m "feat: descripcion del cambio"
git push
```
