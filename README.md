# Checklist de Seguridad — GitHub Pages

Página web interactiva para la checklist «Tapa de conexiones de generador».

## Publicarla en GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo, `checklist-seguridad-generador`).
2. Sube el archivo `index.html` a la raíz del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)` y pulsa **Save**.
6. Espera a que termine la publicación. GitHub mostrará la URL pública de la página en la sección **Pages**.

La dirección suele tener esta forma:
`https://TU-USUARIO.github.io/checklist-seguridad-generador/`

Sustituye `TU-USUARIO` por tu nombre de usuario de GitHub y el nombre del repositorio por el que hayas elegido.

## Funciones

- Campos editables: Equipo, N.º, Fecha, OT y Responsable.
- Estados seleccionables por punto: OK/FAIL, OK/FAIL/N/A u OK/NOK/N/A según la sección.
- Cada punto permite cambiar la selección o desmarcarla.
- Aviso dinámico de estado de la checklist.
- Guardar y recuperar datos en el navegador del mismo dispositivo.
- Imprimir o guardar como PDF desde el navegador.

## Importante sobre el guardado

La página no envía datos a un servidor. El botón **Guardar en este dispositivo** usa el almacenamiento local del navegador; no comparte la checklist con otros operarios y no sincroniza entre dispositivos. Para conservar o enviar una instancia completada, usa **Imprimir / Guardar PDF** y comparte ese PDF mediante el canal aprobado por tu organización.

## Prueba local

Abre `index.html` en un navegador moderno. No requiere instalar dependencias ni configurar un servidor.
