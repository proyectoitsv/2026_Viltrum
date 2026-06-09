```markdown

# Reunión 8/6/26

##Falta de división de tareas:

El profesor compara la dinámica del grupo con niños jugando al fútbol, donde "todos van atrás de la pelota", criticando que los cuatro integrantes intenten hacer las mismas actividades al mismo tiempo, como comprar componentes o armar el diagrama de Gantt.

##Asignación de responsabilidades:
Recalca que es fundamental desglosar las tareas (como definir el sensor, la fuente de alimentación o la carcasa) y asignar un responsable directo a cada una.

##Separación física del grupo: Al notar que los cuatro estudiantes están sentados juntos trabajando en lo mismo, el profesor obliga a dos de ellos a tomar una computadora y trasladarse a otra mesa para forzarlos a trabajar de manera independiente.

##Uso del tiempo en clase: Finalmente, les llama la atención por estar realizando trabajos prácticos de otra materia durante su horario, indicándoles que deben resolver esos pendientes en su tiempo libre durante el fin de semana.

---------------------------------------------------------------------------------------------------------------

# El problema central: estabilidad del sensor

El equipo enfrenta dificultades técnicas para lograr que un **sensor óptico** apunte siempre verticalmente hacia el suelo.

## Principales dificultades

- **Rotación de la barra:** durante ejercicios como la sentadilla, la barra tiende a girar sobre su propio eje. Esto desvía la orientación del sensor y afecta la medición.
- **Limitaciones de hardware:** se descartaron soluciones basadas en acelerómetros debido al *drift* o desviación acumulada en las señales, lo que reduce la precisión en el cálculo de velocidad y distancia.

## Alternativas de diseño propuestas

Se discutieron distintas estrategias para mantener la verticalidad del sensor o modificar el enfoque de medición.

### 1. Mecanismo de estabilización

Se propuso un diseño con **rodamientos y contrapesos**, similar al principio de un *gimbal* o *spinner*, para que el sensor apunte hacia abajo por efecto de la gravedad, independientemente del giro de la barra.

### 2. Sensores de proximidad en el suelo

Otra alternativa consiste en colocar el sensor en el piso y ubicar un elemento reflectante liviano en la barra. Esto permitiría evitar los problemas asociados a la rotación de la barra.

### 3. Sensores de ultrasonido o radar

También se mencionó el uso de radares con efecto Doppler, aunque se cuestionó su precisión en comparación con los sensores láser.

## Propuesta del tutor: “Nacho”

El profesor sugirió simplificar el sistema mediante una **referencia de altura fija**.

La idea consiste en colocar sensores en la estructura de la máquina o *rack* para detectar puntos de paso conocidos:

- inicio del recorrido, por ejemplo, a la altura de los hombros;
- final del recorrido.

Con esta información, se podría medir el tiempo entre pulsos y calcular fuerza y velocidad sin depender de la orientación de un dispositivo móvil colocado en la barra.

## Conclusiones y próximos pasos

- **Validación:** realizar pruebas físicas con el mecanismo de contrapeso para evaluar cuánto tarda en estabilizarse después de un movimiento brusco.
- **Sincronización:** definir una señal de **“equipo listo”** para que el usuario comience el ejercicio únicamente cuando el sensor esté correctamente alineado.
- **Gestión del proyecto:** elaborar un **Diagrama de Gantt** para organizar los tiempos y las etapas restantes del proyecto.
```

