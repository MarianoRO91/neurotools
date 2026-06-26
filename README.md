# Herramientas de Neurología

Conjunto de herramientas clínicas locales (HTML autónomo, sin dependencias externas) para agilizar la documentación en consulta y guardia. Todo el procesamiento ocurre en el navegador: **ningún dato se transmite fuera del dispositivo**.

## Herramientas

| Herramienta | Archivo | Uso |
|---|---|---|
| ⚡ Guardia · Código Ictus | `guardia_ictus.html` | Móvil. Cronograma, NIHSS seriada, anamnesis, juicio y plan. Informe con estructura de la plantilla de Diraya. |
| Consulta de Neurología general | `consulta_neuro_general.html` | Escritorio. Informe, exploración, escalas, parser de tratamiento. |
| Consulta de Enfermedades desmielinizantes | `consulta_EM.html` | Escritorio. Informe inicial/evolutivo de EM, EDSS, tratamiento. |
| NIHSS | `NIHSS.html` | Móvil. Calculadora con formato de informe, instalable como icono. |

`index.html` enlaza las cuatro.

## Uso

- **En local**: abrir `index.html` (o cualquier archivo) directamente en el navegador. Funciona sin conexión.
- **Como web (GitHub Pages)**: activar Pages sobre la rama principal; la página de inicio será `index.html`.
- **En el móvil como app** (NIHSS y Guardia): abrir la URL en Safari (iOS) o Chrome (Android) → «Añadir a pantalla de inicio».

## Privacidad

- Procesamiento 100% local en el navegador. No hay servidor ni transmisión de datos.
- El guardado de pacientes usa el almacenamiento local del navegador (localStorage), que reside solo en ese dispositivo.
- En las herramientas de guardia/urgencias: usar etiquetas no identificativas y **borrar los casos al terminar la guardia**.

## Aviso

Herramientas de apoyo a la documentación clínica. No sustituyen el juicio del facultativo. Las dosis y pautas son orientativas y deben verificarse. El usuario es responsable del contenido que genera y vuelca en la historia clínica.
