# 3.5.1 Módulo de Control de Producción 

## **Caso de uso #1: Visualizar solicitudes de producción**

| **ID**               | CU-01                                                                   |
|----------------------|-------------------------------------------------------------------------|
| **Actor(es)**        | Jefe de Producción                                            |
| **Descripción**      | Permite al jefe de producción consultar las solicitudes de producción generadas por el área de almacén de productos, visualizando número de solicitud, producto, cantidad, fecha requerida y estado.          |
| **Precondiciones**   | El usuario debe estar logueado en el sistema.           |
| **Flujo Principal**  | 1. El usuario accede al módulo de producción  <br> 2. Selecciona la opción "Solicitudes".  <br> 3. El sistema muestra la lista de solicitudes con sus respectivos detalles.  |
| **Requerimientos Especiales** | Existencia previa de solicitudes registradas.    |
| **Frecuencia de Uso**| Frecuentemente, depende de la demanda de la producción.   |

## *Prototipo:*
![Solicitudes de Producción](Prototipos.1/Solicitud-Producción.png)