# Agente QA - Prototipo funcional

Prototipo web del Agente QA: evaluación de criterios de aceptación, generación de casos de prueba, revisión humana, publicación simulada en Azure Test Plans y métricas.

## Ejecución

No requiere instalación.

1. Descomprima `agente-qa-prototipo.zip`.
2. Abra `index.html` con Google Chrome, Microsoft Edge o Firefox (doble clic).

Opcional, con servidor local (requiere Python 3):

```
python -m http.server 8000
```

y abra `http://localhost:8000` en el navegador.

## Tecnología

HTML5, CSS3 y JavaScript (ES2022) con programación orientada a objetos. Sin dependencias ni base de datos: los datos de la sesión se guardan en el almacenamiento local del navegador.

## Alcance

Autenticación, lectura de Azure DevOps, servicio de IA y publicación en Test Plans están simulados con datos ficticios.
