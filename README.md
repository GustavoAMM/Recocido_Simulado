# Recocido_Simulado

## ¿Qúe es?

Es un algoritmo de búsqueda por trayectoria. 
Es una metaheurística de optimización que trata mejorar la búsqueda local que permite en algunas ocasiones viajar a hacia soluciones peores.

Recocido: tratamiento térmico para agrandar materiales

- se eleve la temperatura alta
- se mantiene 
- se deja enfriar de manera lenta


- El parámetro de temperatura controla la aceptación 
- Una temperatura alta para que las soluciones sean mas aleatorias
- Cuando sean bajas intensifica la búsqueda y ya no se permiten subir


 ![imagen](rs.png)
 
- (abajo) temperatura
- (arriba) salto térmico

## fundamentos

- Algoritmo estocástico, procesos aleatorios para
no llegar a la misma solución

- Sin memoria para no regresar a soluciones anteriores


## Funcionamiento

- partimos de una solución
- iteramos, se genera un vecino (espacio de soluciones)
- si es MUCHO peor la probabilidad es baja
- si es POCO peor la probabilidad es alta

