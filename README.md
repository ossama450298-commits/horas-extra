# Horas extra del año

Calculadora web de horas extra a partir del PDF de fichajes de un trabajador.

**Abrir:** https://ossama450298-commits.github.io/horas-extra/

![Captura](captura.jpg)

## Cómo se usa
1. Sube uno o varios PDF de fichajes (o pega el texto si el PDF es un escaneo).
2. Elige la jornada diaria: 4 h, 5 h, 8 h u otra.
3. Elige el criterio: saldo neto (los días cortos restan) o solo excesos.

Muestra el total de horas extra, el resumen por mes con gráfico y el detalle día a día. Marca los fichajes a revisar (sin salida, tramos de 0 min, un solo tramo) y permite corregir horas, contar un día como jornada completa o excluirlo. El botón «Copiar para Excel» copia la tabla.

### Trabajador automático
Al subir el PDF detecta el nombre y apellidos del trabajador (cabeceras como «Trabajador:», «Empleado:», «Nom i cognoms:», títulos tipo «Fichajes de …» o el nombre repetido en las filas) y lo rellena en el campo bajo la zona de subida. Avisa si un PDF parece de otra persona y se puede corregir a mano.

![Trabajador](captura-trabajador.jpg)

### Días libres
Convierte las horas extra en días libres: 1 día por cada 8 h extra (se puede cambiar). Permite descontar los días ya disfrutados, indica las horas que sobran para el siguiente día y muestra los días libres acumulados mes a mes.

![Días libres](captura-dias-libres.jpg)

### Notas del PDF
Lee las notas escritas en los fichajes y las muestra en cada día. Si una nota indica horas («he hecho de 8 a 13:30», «salí a las 17:30») calcula las horas reales del día sin duplicar tramos ya fichados; si indica una ausencia justificada (médico, vacaciones, permiso, formación) propone contar jornada completa. Las sugerencias se aplican día a día o todas de golpe, y el total muestra cuánto cambiaría.

![Notas](captura-notas.jpg)

El PDF se procesa en el navegador; no se envía a ningún servidor.
