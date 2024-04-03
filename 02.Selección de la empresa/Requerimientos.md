## Requerimientos

### 1. Requerimientos funcionales

#### **Caso de uso N°1: Abastecimiento del almacén al área de producción**

| **Objetivo:** | Coordinar y gestionar el flujo de materiales desde el almacén hasta las líneas de producción, asegurando que se satisfagan las necesidades de producción de manera oportuna y eficiente. |
|------|--------|
| **Descripción:** | Este caso de uso describe el proceso de abastecimiento de materia prima desde la planificación de la producción y gestión del inventario hasta la distribución de la materia prima al área de producción. | 
| **Actor:** | Encargado de Adquisiciones | 
| **Precondiciones:** | El sistema de gestión de inventario se encuentra actualizado, asimismo se posee suficiente espacio para almacenar la materia prima. | 
| Paso | Acción |
| 1    | Se determinan los niveles de inventario tanto en el almacén como en el área de producción para determinar los materiales necesarios, así como el tiempo necesario para que dicha producción no se detenga. |
| 2    | Se gestionan las compras para adquirir los materiales necesarios para la producción. |
| 3    | Se lleva a cabo una selección y evaluación de proveedores para garantizar la calidad del producto y el tiempo de entrega, entre otros criterios. |
| 4    | Se recibe la materia prima de los proveedores y se verifica su calidad. |
| 5    | Una vez adquiridos los materiales, se gestiona la correcta recepción y almacenamiento de estos, la cual será guiado por un registro detallado. |
| 6    | Se distribuyen los materiales necesarios para el área de producción, que en este caso consiste en la confección de ropa. |
| 7    | Finaliza el caso. |

### 2. Requerimientos de atributos de calidad
* Seguridad: El sistema debe garantizar la confidencialidad e integridad de los datos almacenados y transmitidos. Para ello, el sistema solo permitirá acceso a los usuarios que están registrados y que cumplan un rol en la empresa, y solicitará que los usuarios proporcionen dos formas de autenticación: una contraseña y un código enviado a su dispositivo móvil.
* Escalabilidad: El sistema debe ser capaz de manejar grandes volúmenes de datos y usuarios en tiempo real.
* Fiabilidad: El sistema debe ser resistente a fallos menores y ser capaz de recuperarse automáticamente sin afectar significativamente la operación. En caso de fallos graves, el tiempo de recuperación no debe superar las 3 horas. Además, se realizará copias de seguridad diarias de los datos del sistema y mantener copias de seguridad históricas durante al menos 90 días.
* Usabilidad: El sistema debe ser fácil de usar y comprender, con una interfaz amigable para los usuarios.
* Compatibilidad: El sistema debe funcionar en múltiples dispositivos, así como en diferentes sistemas operativos y navegadores web.

### 3. Restricciones
* El Backend del sistema se implementará en PostgreSQL
       
[Selección de la empresa](SeleccionEmpresa.md)

[Regresar al índice](../README.md)
