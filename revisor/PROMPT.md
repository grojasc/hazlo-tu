# Hazte el tuyo: el prompt

Pega esto en Claude, ChatGPT o Gemini. Si tiene vista previa (Artefactos en Claude, Canvas en ChatGPT y en Gemini), puedes verla en el mismo chat. Si la vista previa no lee tu Excel, guarda la respuesta como `revisor.html` y ábrela con tu navegador.

```
Crea una página web de un solo archivo HTML que revise una planilla antes de pasársela a una IA.
- Que me deje arrastrar un archivo CSV o Excel (.xlsx) y lo revise en el mismo navegador, sin subirlo a ningún servidor.
- Que marque, columna por columna: celdas vacías, filas duplicadas, espacios de más, números guardados como texto, fechas escritas de formas distintas, filas de total o subtotal en medio de los datos, códigos que pudieron perder los ceros de la izquierda y RUT chilenos con dígito verificador inválido.
- Que explique cada problema en palabras simples y cómo arreglarlo en Excel.
- Al final, que arme un resumen de las columnas sin ningún dato de las filas, listo para copiar y pegar en una IA.
Incluye un botón para probarla con una planilla de ejemplo inventada que tenga esos problemas.
```

Después, pídele cambios en el mismo chat. Algunos que sirven:

- «Agrega una revisión para correos mal escritos.»
- «Que también marque montos negativos en la columna de ventas.»
- «Explica cada problema con un ejemplo de mi rubro: logística.»

Probé este prompt «en frío» con Claude, sin más instrucciones: la página que salió revisó bien una planilla de ejemplo, un CSV y un Excel.

La versión de esta carpeta (`index.html`) es la mía, con más pruebas y una revisión extra que salió de un comentario en LinkedIn: los códigos largos que Excel redondea. Para sumarla a la tuya, pídele:

- «Agrega una revisión de códigos largos que Excel redondeó: más de 15 dígitos, o en notación científica como 7,8E+18.»
