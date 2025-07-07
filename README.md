Integrante 1: Analista y Diseñador Principal
Este rol se encargará de la planificación general y la estructura del programa.

Definición de Estructura de Datos: Diseñar cómo se almacenarán las excursiones (lista de diccionarios, clases, etc.) incluyendo nombre, cupo total y cupos disponibles.

Flujo del Programa: Dibujar un diagrama de flujo o pseudocódigo que muestre la secuencia de interacción del usuario (mostrar excursiones, reservar, verificar cupo, etc.).

Manejo de Errores y Validaciones: Definir las condiciones de error (excursión llena, entrada inválida, etc.) y cómo se manejarán.

Integración Final: Una vez que los demás módulos estén listos, este integrante se encargará de ensamblar todas las partes y asegurar que el programa funcione como un todo.

________________

Integrante 2: Desarrollador de Funcionalidades Principales
Este integrante se enfocará en la lógica central del sistema.

Función mostrar_excursiones(): Implementar la lógica para listar las excursiones disponibles con sus cupos actualizados.

Función reservar_cupo(): Desarrollar la función principal de reserva, que solicite el nombre del usuario y la excursión deseada.

Validación de Cupos: Integrar la lógica para verificar si hay cupos disponibles antes de confirmar una reserva.

Actualización de Cupos: Asegurar que los cupos se reduzcan correctamente tras una reserva exitosa.

__________________

Integrante 3: Desarrollador de Interacción y Control de Flujo
Este rol se centrará en la interacción con el usuario y el control del programa.

Menú Principal y Ciclos: Implementar un bucle principal que permita al usuario interactuar con el sistema (mostrar excursiones, reservar, salir).

Manejo de Entradas del Usuario: Validar las entradas del usuario (ej: que el número de excursión sea válido, que el nombre no esté vacío).

Uso de break y continue: Aplicar estas sentencias para optimizar el flujo del programa, por ejemplo, para salir de un bucle de reserva si no hay cupo o para solicitar nuevamente una entrada inválida.

Mensajes al Usuario: Diseñar y programar los mensajes claros y útiles para el usuario (confirmación de reserva, error de cupo, etc.).

_________________

Integrante 4: Desarrollador de Persistencia y Estructura Inicial
Este integrante se encargará de la configuración inicial y el manejo de los datos.

Definición de Datos Iniciales: Crear la estructura de datos inicial para las excursiones (ej: una lista de diccionarios) con sus nombres y cupos.

Simulación de Persistencia (Opcional si el tiempo lo permite): Si el tiempo lo permite y quieren ir un paso más allá, podrían explorar cómo cargar/guardar los datos de las excursiones en un archivo simple (ej: CSV o JSON) para que las reservas se mantengan entre ejecuciones. Si no, simplemente la estructura en memoria será suficiente para la duración de la jornada.

Comentarios y Documentación: Asegurar que el código esté bien comentado y que las funciones tengan docstrings claros explicando su propósito.


____________________________


Integrante 5: Tester y Documentador
Este rol es crucial para la calidad y la entrega final.

Creación de Casos de Prueba: Diseñar diferentes escenarios para probar el programa: reservas exitosas, intentos de reservar en excursiones llenas, entradas inválidas, etc.

Ejecución de Pruebas: Ejecutar el programa exhaustivamente, registrando cualquier error o comportamiento inesperado.

Informe de Errores: Documentar cualquier bug encontrado y comunicarlo al equipo para su corrección.

Preparación del Archivo de Entrega: Encargarse de comprimir el archivo EcoViaje_grupoX.py en formato .RAR o .ZIP y asegurar que el nombre del archivo sea correcto.

Revisión de Código: Hacer una revisión final del código para asegurar la legibilidad, coherencia y el cumplimiento de los requisitos.

Consideraciones Adicionales para el Equipo
Comunicación Constante: Establezcan canales de comunicación efectivos para resolver dudas y compartir avances.

Control de Versiones (Opcional pero Recomendado): Si tienen familiaridad con Git, les recomiendo usarlo. Facilitará la colaboración y evitará conflictos al integrar el código. Si no, asegúrense de que una persona sea responsable de fusionar los cambios de manera controlada.

Modularización: Fomenten que cada función realice una tarea específica. Esto hará el código más fácil de entender, probar y mantener.

Pruebas Incrementales: A medida que cada función esté lista, pruébenla. No esperen a tener todo el programa terminado para empezar a probar.
