Los atributos items y precioBase son private, por eso no se pueden acceder directamente desde App.
Si estuvieran dentro de Pedido e ItemMenu respectivamente, sí podrían accederse porque private permite acceso dentro de la misma clase.
getPrecioBase() es protected y casado.getPrecioBase() sí compila en App porque ambas clases están en el mismo paquete uam.prog3.tarea03.
Esto demuestra que private limita el acceso a la propia clase, mientras protected también permite acceso desde el mismo paquete.
