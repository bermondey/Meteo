# Meteo

App web de previsión del tiempo a 7 días, inspirada en el estilo de meteoblue: meteograma horario, viento con direcciones e isoterma de 0 °C. Es un único `index.html`, sin dependencias ni paso de compilación.

## Qué incluye

- Condiciones actuales, sensación térmica, UV, salida y puesta del sol
- Resumen de 7 días con rango de temperaturas
- Meteograma horario: temperatura, precipitación (lluvia y nieve), nubosidad y noche
- Viento medio, ráfagas y dirección
- Isoterma de 0 °C frente a la altitud del lugar
- Búsqueda de lugares, geolocalización y modo oscuro automático

## Publicarla en GitHub Pages

1. Crea un repositorio y sube `index.html` y este `README.md`.
2. En **Settings → Pages**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
3. En un minuto estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Para probarla en local basta con abrir `index.html` en el navegador.

## Datos

Usa [Open-Meteo](https://open-meteo.com), gratuita y sin clave de API para uso no comercial (licencia CC BY 4.0, hay que mantener la atribución). Para uso comercial, Open-Meteo tiene planes de pago.

## Próximos pasos

- Comparar varios modelos meteorológicos en el mismo meteograma
- Pictogramas propios en lugar de emojis
- Instalable como PWA y lugares favoritos
