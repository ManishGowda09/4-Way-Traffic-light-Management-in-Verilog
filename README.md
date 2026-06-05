# 4-Way-Traffic-light-Management-in-Verilog
This Verilog code implements a 4-Way Traffic Light Controller using a Finite State Machine (FSM). It manages the traffic flow at an intersection by rotating the "Green" light clockwise through four directions: North $\rightarrow$ West $\rightarrow$ South $\rightarrow$ East, with a "Yellow" transition state between each
[North Green]  (16 cycles)
      │
      ▼
[North Yellow] (4 cycles)
      │
      ▼
 [West Green]  (16 cycles)
      │
      ▼
 [West Yellow] (4 cycles)
      │
      ▼
[South Green]  (16 cycles)
      │
      ▼
[South Yellow] (4 cycles)
      │
      ▼
 [East Green]  (16 cycles)
      │
      ▼
 [East Yellow] (4 cycles)
      │
  (Loop back to North Green)
