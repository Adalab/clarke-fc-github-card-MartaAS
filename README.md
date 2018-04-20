Especificaciones:
 -Antes de empezar tendréis que hacer una pequeña planificación del trabajo, en texto, sin nada de código:
 -Un esquema del funcionamiento
 -Qué acciones necesitaremos realizar y pasos concretos para realizarlas
 -Qué acciones son de ejecución obligatoria y cuales responderán a eventos
 -Esta vez no os daremos la dirección, tendréis que buscarla en la documentación de la API de GitHub
 -La prioridad 1 es que funcione
 -La prioridad 2 es acercarse lo más posible al aspecto propuesto en el prototipo
 -El dato de "Miembro desde hace X años/meses" ES OPCIONAL. Si ya has terminado todo se trata de indicar cuánto tiempo
  lleva dicho usuario siendo miembro de Github
 -Por defecto, la API nos devolverá 20 resultados, más que suficiente para el ejercicio. Si nos venimos arriba y queremos
  sacar a todo el mundo, en Adalab somos 68 criaturas, añadiendo ?per_page=68 a la url de la petición y estaremos todas.
  
Planificacion:
-Lo primero sería crear a estructura del HTML basica con lo que se nos pide.
-Despues comenzaría con la funcionalidad de la página:
  *Crear un select que guarde el valor para poder mosrar la informacion que se pide en cada tarjeta.
  *Acceder a la documentación de la API para poder acceder a los datos que se nos pide en cada tarjeta.
  *Acceder a los datos y pintarlos.
-Una vez que tengamos toda la funcionalidad, maquetaría.

Funcionamiento:
 -Seleccionar a la persona que queremos mostrar y pintar los datos.
 
Ejecución obligatoria y eventos:
 -Lo que corresponde a eventos seria el click del select para mostar la tarjeta.
 -Los que son de ejecución obligatoria sería el cargar los datos del select y los de la tarjeta.
  
