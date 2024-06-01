# Logisim-Minesweeper

Logisim Evolution으로 구현한 지뢰찾기

## OPCODE

- `0000(0)` None
- `0001(1)` Clear Screen
- `0011(2)` Draw Grid
- `0011(3)` Reset RAM
- `0100(4)` Set Mines
- `0101(5)` Jump
- `0110(6)` Standby for Selection
- `0111(7)` Render Screen
- `1000(8)` Uncover
- `1001(9)` Game Over
- `1010(A)` Flagging

## Game Data Code for RAM

- `0000(0)` Empty Square
- `0001(1)` Mine Square
- `0010(2)` Uncovered Mine Square
- `0011(3)` Square with Flag
- `0100(4)` Uncovered Empty Square
- `0101(5)` Uncovered Empty Square with 1
- `0110(6)` Uncovered Empty Square with 2
- `0111(7)` Uncovered Empty Square with 3
- `1000(8)` Uncovered Empty Square with 4
- `1001(9)` Uncovered Empty Square with 5
- `1010(A)` Uncovered Empty Square with 6
- `1011(B)` Uncovered Empty Square with 7
- `1100(C)` Uncovered Empty Square with 8
- `1101(D)` Mine Square with Flag
