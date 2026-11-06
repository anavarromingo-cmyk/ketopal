# KetoPal

Herramienta web de apoyo clínico para el manejo de pacientes con dieta cetogénica.

**Web:** https://anavarromingo-cmyk.github.io/ketopal/

## Secciones

1. **Fármacos**: buscador y listado de fármacos sin hidratos de carbono o con baja proporción (Tabla 43), con detector de excipientes con hidratos de carbono.
2. **SRO y glucosa**: cálculo de Sueroral Hiposódico® y Glucocemin 50%® para igualar los hidratos de carbono diarios de la dieta (por gramos, por ratio y kcal, o por edad).
3. **Hipercetosis**: guía de actuación, bolo de suero fisiológico y déficit de bicarbonato (Astrup).
4. **Hipoglucemia**: guía de actuación con cálculo de dosis oral e IV según peso y CHO diarios.

## Uso

Página HTML única, sin servidor ni dependencias. Abrir `index.html` en el navegador. Adaptada a móvil con navegación inferior fija al estilo del sistema PEDPAL. No guarda datos de pacientes.

## Instalación como aplicación (PWA)

KetoPal es una Progressive Web App: se puede instalar en el teléfono y abrir como una app más, con icono propio en el escritorio y funcionamiento sin conexión.

- **Android (Chrome)**: abrir https://anavarromingo-cmyk.github.io/ketopal/ → menú ⋮ → «Instalar app» (o «Añadir a la pantalla de inicio»).
- **iOS (Safari)**: abrir la página → botón Compartir → «Añadir a la pantalla de inicio».

Tras la primera carga, el service worker guarda los archivos y la app funciona sin red.

## Fuentes

- *Manual para la práctica de la dieta cetogénica*, 2.ª edición.
- Fichas técnicas AEMPS: Sueroral Hiposódico (n.º reg. 59.877) y Glucocemin 50% (n.º reg. 74.781).

> Herramienta de apoyo. No sustituye el juicio clínico ni la prescripción individualizada.

## Licencia

© 2026 Álvaro Navarro. Distribuido bajo licencia [Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.es). Texto completo en [LICENSE](LICENSE).
