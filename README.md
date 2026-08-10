# Documentos RR.HH. — CSAH

Suite de herramientas HTML autocontenidas para generar documentos institucionales del Colegio San Alberto Hurtado (Red Educacional Santo Tomás de Aquino). Pensadas para funcionar 100% offline y embeberse en Google Sites (por ejemplo, dentro de un `<iframe>` o como página enlazada).

## Estructura

```
index.html                 → Portada con acceso a cada herramienta
carta_amonestacion.html    → Carta de amonestación por atrasos de marcaje
acta_entrevista.html       → Acta de entrevista (estudiante / apoderado / docente)
```

## Características

- Cada archivo es **autocontenido**: HTML + CSS + JS + librería `html2pdf.js` embebidos en un solo archivo, sin dependencias externas ni conexión a internet.
- Panel de datos a la izquierda + previsualización del documento a la derecha.
- Exportación a **PDF** lista para imprimir (tamaño carta).
- Estilo visual institucional consistente (colores azul/dorado CSAH) en las tres páginas.

## Uso

1. Abrir `index.html` en el navegador (o publicarlo como página principal en Google Sites).
2. Elegir la herramienta deseada desde las tarjetas.
3. Completar los campos del panel izquierdo — la previsualización se actualiza en tiempo real.
4. Usar el botón **Guardar como PDF** para exportar el documento final.

## Despliegue en Google Sites

Al ser archivos HTML autocontenidos, se pueden:
- Alojar en GitHub Pages y embeber la URL en un bloque "Insertar → Insertar código" de Google Sites, o
- Subir directamente como archivos adjuntos/enlaces según la configuración del sitio.

## GitHub Pages (opcional)

Si se activa GitHub Pages sobre la rama principal, `index.html` quedará disponible como portada en:

```
https://<usuario>.github.io/<nombre-repo>/
```
