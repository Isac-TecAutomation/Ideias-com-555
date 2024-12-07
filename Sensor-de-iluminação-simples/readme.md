- #           Sensor Luminosidade Simples para o 555 

- https://www.tinkercad.com/things/jvxUyFHeprM-exemplo-circuito-monoestavel-555

- # Sobre 

- O ciruito do sensor se baseia no modo Monoestável:

- Nesse modo ao se detectar um pulso no treeshold,
equivalente a 1/3 do vcc, ele irá acionar a saida 
por um tempo determinado.

- para se obter o 1/3 de vcc, utilizamos um circuito divisor de
  tensão onde um resistor é de 10k, e outro é o LDR.

- Os Materiais usados no Exemplo:

- 1 - Protoboard
- 1 - CI NE555
- 2 - Resistor de 10k Ω
- 1 - Resistor de 220 Ω
- 1 - LDR (sensor de luminosidade resistivo)
- 1 - fonte 127v AC
- 1 - fonte de 5V
- 1 - Capacitor de 100 uF
- 1 - Capacitor Unipolar de 10 nf
- 1 - lampada de sua preferência
- 1 - relé de 5v (modulo)
- 1 - transistor bc-337
- 1 - resistor 220 Ω
- 1 - diodo comum


- se o relé for módulo desconsiderar:
  
- 1 - transistor bc-337
- 1 - resistor 220 Ω
- 1 - diodo comum

- # Cálculos Importantes 

- Tempo (delay):

- t [s] = 1,1 * R1 [Ω] * C [F]

- t - tempo 
- R1 - Resistor
- C - Capacitor 

- No exemplo:

- t = 1,1 * 100k * (100 * 10E-6) = 11 [s]

- # Importante 

- Sempre montar o circuito sem ligar-lo a fonte, pode ocorrer de queimar o CI

- # Referências

- https://www.youtube.com/watch?v=5NQoLX7Ff1Q
