# Gradebook-App

Gradebook-App es una aplicación simple en JavaScript que calcula el promedio de calificaciones de una clase y determina la calificación y el estado de aprobación de un estudiante.

## Funciones

- `getAverage(scores)`: Calcula el promedio de un array de calificaciones.
- `getGrade(score)`: Devuelve la calificación correspondiente a un puntaje.
- `hasPassingGrade(score)`: Determina si una calificación es aprobatoria.
- `studentMsg(totalScores, studentScore)`: Genera un mensaje con el promedio de la clase, la calificación del estudiante y si aprobó o no.

## Uso

Para ejecutar la aplicación, simplemente abre el archivo `script.js` en un entorno que soporte JavaScript (por ejemplo, un navegador web o Node.js).

```javascript
console.log(studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37));
