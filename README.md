# ARSW-LAB02

1. Control de hilos con esperar / notificar. Productor / consumidor
Verifique el funcionamiento del programa y ejecútelo. Mientras esto ocurre, ejecute jVisualVM y verifique el consumo de CPU del proceso correspondiente. 
![img](img/1a.PNG)

**¿Por qué es este consumo?**

Tanto el consumidor como el productor estan realizando operaciones sobre la memoria añadir y quitar elementos de una pila.

**¿Cuál es la clase responsable?**

Son responsables tanto el consumidor como productor dado a que ambos acceden a los mismos datos.

2. 