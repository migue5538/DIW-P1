# Diseño de AuraPlay

## Fase 1: mapa de navegación

```text
index.html (bienvenida)
└── apodo.html (primer acceso)
    └── lobby.html (menú principal)
        ├── tienda.html
        ├── personaje.html
        └── configuracion.html
            └── index.html (cerrar sesión o borrar cuenta)
```

Las cuatro pantallas principales (`lobby.html`, `tienda.html`, `personaje.html` y `configuracion.html`) usan la misma barra superior y navegación. La página activa se identifica mediante el modificador BEM `navegacion__enlace--activo`.

## Pendiente para las siguientes fases

- Fase 2: completar el comportamiento adaptativo y la navegación fija en móvil.
- Fase 3: añadir `tienda-tailwind.html` y la comparativa con Tailwind.
- Fase 4: migrar los estilos a Sass, incluir temas y enlazar la validación CSS.
