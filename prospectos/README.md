# Panel de prospección ElHub

Dirección de uso: https://prospectos.elhub.cl/

Cloudflare Pages publica esta carpeta (`root_dir: prospectos`) desde la rama `main`.
Proyecto: `elhub-prospectos`. No requiere build ni dependencias.

La ruta anterior `/servicios/panel/` de GitHub Pages se conserva por compatibilidad.
No es un enlace para enviar a prospectos: es el panel operativo de Rubén.

## Actualización

Las fuentes y el generador están en el proyecto privado `catalogos-elhub`:

```bash
python3 scripts/publicar_servicios.py
python3 scripts/preparar_panel_prospectos.py
```

Después revisar los cambios de esta carpeta, hacer commit y push a `main`.
No copiar la BD, exportaciones de seguimiento ni notas privadas al repositorio público.

## Seguimiento

Los estados y notas se guardan en el navegador bajo `elhub-servicios-v1`.
Cambiar de dominio cambia el almacenamiento del navegador: no hay traslado automático
ni sincronización entre dominios o dispositivos. Descargar seguimiento y enviarlo a Zod
permite consolidar la BD privada. No confundir el panel con un CRM alojado en el servidor.
