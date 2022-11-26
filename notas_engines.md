 # Comparación rapida de motores de ajedrez
 
 - la evaluación va de -inf a inf dónde el 0 representa que ningun jugador tiene una ventaja
 - se muestran las evaluaciones de dos jugadas de esta [partida](https://lichess.org/xTbGG2VQ)
 - para cada jugada se muestra la sugerencia del modulo en lugar de la jugada realizada y la evaluación de la posición si se hubiese realizado
 - cada modulo analizó por 5 segundos cada jugada

| jugada | komodo 12 human programmed | komodo 13 MTCS | stockfish 15 NNUE | lc0 GPU |
|--------|-----------|-----------|--------------|-----|
| 5      | - 0.96    | - 0.71    |- 0.79 |- 0.32| 
| 5 sugerida | + 1.11 exf5  | + 0.65 O-O|+ 1.25   exf5   |+ 0.96 exf5|
| 9      | - 2.99    | - 2.72    |-6.21|- 4.17 |
| 9 sugerida   | - 1.85  Dc5   |- 1.19 Dc5 |-4.81 Dc5 |- 3.14 Dg5|
