# FlyAway FormNightMare

Simulador de compra de vuelos creado para mostrar problemas de usabilidad en formularios móviles y la importancia de diseñar mobile first.

## Aplicación publicada

La aplicación está disponible en:

https://cia2000.github.io/nightmare-forms/

## Código QR

Escanea este código para abrir la aplicación en un móvil:

![Código QR de FlyAway FormNightMare](qr-aplicacion.png)

## Instalar en un móvil

La aplicación es una PWA y puede instalarse como una aplicación independiente.

### Android

1. Abre la aplicación con Chrome.
2. Pulsa el menú de tres puntos.
3. Elige `Instalar aplicación` o `Añadir a pantalla de inicio`.

### iPhone o iPad

1. Abre la aplicación con Safari.
2. Pulsa el botón Compartir.
3. Elige `Añadir a pantalla de inicio`.
4. Confirma con `Añadir`.

## Descargar y ejecutar localmente

1. Clona el repositorio:

   ```bash
   git clone https://github.com/cia2000/nightmare-forms.git
   cd nightmare-forms
   ```

2. Inicia un servidor web local:

   ```bash
   python3 -m http.server 8000
   ```

3. Abre `http://localhost:8000` en el navegador.

El service worker de la PWA necesita un servidor web. No funcionará al abrir `index.html` directamente desde el sistema de archivos.

## Versiones de validación

- `index-validacion.html`: rellena todos los datos necesarios con una combinación válida.
- `index-validacion-parcial.html`: rellena solo datos personales, pago, necesidades alimentarias e información adicional.

## Publicación

El proyecto se publica automáticamente en GitHub Pages al enviar cambios a la rama `main`.
