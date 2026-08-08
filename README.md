# EXPLORA Francia

Sitio informativo sobre visados VVT, Saisonnier y Salarié para Francia, vivienda (Visale) y comparador de seguros de viaje, orientado a hispanohablantes latinoamericanos.

## Estructura

```
/
├── index.html              → Home
├── assets/
│   └── styles.css          → Estilos compartidos por todo el sitio
├── visados/
│   ├── vvt.html
│   ├── saisonnier.html
│   └── salarie.html
├── vivienda/
│   └── index.html          → Visale
├── seguros/
│   └── index.html          → Comparador (monetización)
└── faq/
    └── index.html          → FAQ completa
```

## Cómo publicarlo en GitHub Pages

1. Subí todo el contenido de esta carpeta a la raíz de tu repositorio.
2. En el repo: **Settings → Pages → Source** → elegí la rama (ej. `main`) y la carpeta `/ (root)`.
3. Guardá — GitHub te va a dar una URL tipo `https://tuusuario.github.io/tu-repo/`.
4. Como todos los links del sitio son **relativos** (`visados/vvt.html`, `../assets/styles.css`, etc.), funciona igual estés en la raíz del dominio o en un subpath de GitHub Pages — no hace falta tocar nada.

## Pendientes de contenido antes de publicar

- Completar precios/nombres reales en la tabla comparadora de `seguros/index.html`
- Confirmar cifra exacta de tope de renta Visale vigente (se revaloriza periódicamente)
- Resolver la pregunta pendiente de la ventana turno→viaje (3/6/90 días) con el consulado y actualizar `visados/vvt.html`
- Cargar el PDF real del eBook y linkearlo desde los CTAs correspondientes
