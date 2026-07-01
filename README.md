# Conmuta landing page

Landing page estática para `conmuta.cl`, marca madre del ecosistema de software de ingeniería:

- **Portico + Nodex** — pre/post procesador FEM y motor avanzado.
- **ReWind** — monitoreo de salud estructural para parques eólicos.
- **Koi-Flow** — hidrología, hidráulica, socavación y estructuras hidráulicas.
- **OpenNodex** — tooling abierto para FEM, DSL, mallado y `portico-core`.

## Publicación

El sitio no requiere build. Basta servir la raíz del repositorio:

```bash
python -m http.server 8765
```

Luego abrir:

```txt
http://localhost:8765
```

Para GitHub Pages, publicar desde la rama `master` y carpeta `/root`.

## Archivos principales

```txt
index.html        Landing completa con CSS embebido
CNAME             Dominio personalizado: conmuta.cl
BRAND.md          Guía visual y descripción de iconos
icons/*.svg       Iconos editables estilo koi-flow
```

## Iconos

Todos los iconos son SVG editables y comparten:

- azul petróleo;
- cian/turquesa;
- coral;
- forma circular con corrientes;
- símbolo técnico simplificado por producto.
