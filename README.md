# Pase de visita · Nota de evolución

Herramienta web para redactar notas de evolución en formato SOAP durante el pase de visita en centros de larga estancia para personas adultas mayores.

## Qué hace

- Registro de identificación, signos vitales, examen por sistemas (Normal / Alterado), diagnósticos, impresión clínica y plan.
- Arma la nota en tiempo real e incluye solo lo que se llena o se marca.
- Alertas orientativas de signos vitales fuera de rango.
- Opciones de salida: solo ASCII (para plataformas como SEDIMEC), mayúsculas y rótulos S/O/A/P.
- Copiar, descargar en .txt o imprimir.

## Privacidad

Funciona completamente en el navegador. No envía datos a ningún servidor y no guarda información de residentes. Solo el nombre y el código del médico quedan guardados en el navegador del equipo que se use, para no digitarlos cada vez. El repositorio contiene únicamente la plantilla en blanco (Ley 8968, Protección de la Persona frente al Tratamiento de sus Datos Personales).

## Publicación en GitHub Pages

1. Crear un repositorio (por ejemplo, `visita-medica`).
2. Subir `index.html` y este `README.md` a la raíz.
3. Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)` → Save.
4. En uno o dos minutos queda disponible en `https://USUARIO.github.io/visita-medica/`.

## Aviso

Los umbrales de alerta son orientativos y no sustituyen el criterio clínico. La nota generada debe revisarse antes de incorporarse al expediente.

## Licencia

MIT.
