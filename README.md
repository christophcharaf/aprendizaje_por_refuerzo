
# Desafío Final - FrozenLake 5x5

## Integrantes

- Azul Villanueva
- Christopher Charaf

## Introducción
Se diseñó un entorno cuadrado 5x5 en el cual un agente inicia en la posición (0,0) y debe llegar a la posición (4,4). El entorno contiene casillas seguras (F), pozos (H) y una meta (G). El agente puede moverse en cuatro direcciones y recibe +1 al alcanzar la meta, y -1 en otros casos. El episodio termina si cae en un pozo o si llega al objetivo. La política se aprende mediante Q-Learning.

## Algoritmo utilizado
Q-Learning con política ε-greedy, tasa de aprendizaje 0.1, factor de descuento 0.99, y epsilon decayado desde 1.0 hasta 0.01.

## Estructura
- `FrozenLake_Q_Learning_5x5.ipynb`: notebook completo con entrenamiento, gráfico de convergencia y política aprendida.
- `desafio_ar1_qlearning_frozenlake.docx`: documento del informe en formato Word.
- `README.md`: este archivo.
