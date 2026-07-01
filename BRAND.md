# Conmuta · Landing page y sistema visual

Este repo contiene una primera landing estática para `conmuta.cl` y un set de iconos SVG editables para los productos del ecosistema Conmuta.

## Estructura

```txt
index.html
CNAME
icons/
  conmuta-symbol.svg
  portico-symbol.svg
  rewind-symbol.svg
  koi-flow-symbol.svg
  opennodex-symbol.svg
```

## Lenguaje visual

La familia de iconos usa una estética inspirada en koi-flow:

- núcleo circular azul petróleo profundo;
- corrientes circulares cian y coral;
- brillos suaves y sombras livianas;
- formas técnicas simplificadas dentro del círculo;
- símbolo propio para cada producto, pero paleta común.

## Productos representados

### Conmuta
Marca madre del ecosistema. El símbolo mezcla corrientes, nodos y flujo de información.

### Portico + Nodex
Pre/post procesador FEM + motor avanzado. El símbolo usa un pórtico, nodos, diagonales y una curva de resultado/deformada.

### ReWind
Monitoreo de salud estructural para parques eólicos. El símbolo usa turbina, torre y trazas de sensores/diagnóstico.

### Koi-Flow
Hidrología, hidráulica, socavación y estructuras hidráulicas. El símbolo usa corrientes, sedimento y líneas de contorno.

### OpenNodex
Capa abierta/tooling del ecosistema Nodex. El símbolo mezcla brackets de código, malla FEM y nodos.

## Recomendación de implementación

Mantener esta landing como sitio estático simple mientras la marca y los productos siguen cambiando. Más adelante se puede migrar a Astro, Vite o Next, pero por ahora un `index.html` sin build evita fricción y permite publicar rápido en GitHub Pages o Cloudflare Pages.

## Próximos pasos sugeridos

1. Activar GitHub Pages desde la rama `master` y carpeta `/root`.
2. Verificar DNS de `conmuta.cl` hacia GitHub Pages o Cloudflare Pages.
3. Reemplazar enlaces privados cuando `nodex-code`, `nodex-compiler` y `nodex-mesher` estén públicos.
4. Agregar capturas reales de Portico, ReWind y Koi-Flow.
5. Crear versiones PNG 192/512 para PWA y redes sociales.
