# Cómo subir esto a GitHub Pages

Nada cambió en cómo funciona el sitio (login con la contraseña fija como ya lo tenían, todo igual). Lo único distinto es que las imágenes ya no están "pegadas" dentro del HTML, así que tenés que subir **el HTML y la carpeta `img/` juntos**, manteniendo esta misma estructura en la raíz del repositorio:

```
tu-repo/
├── index.html
└── img/
    ├── logo.png
    └── hero-bg.jpg
```

Si en GitHub subís el `index.html` pero te olvidás de la carpeta `img/`, el logo y el fondo del hero no van a aparecer (se van a ver como ícono roto), así que asegurate de subir las dos cosas juntas, respetando los nombres tal cual están.

Eso es todo — el resto del sitio (la rifa, el panel admin, el contador, todo) funciona exactamente igual que antes. Cuando estén listos para encarar lo de la seguridad del panel admin, avisame y retomamos por ahí.
