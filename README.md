

---


# **Search Tree Hex Game**
Hex is a two player abstract strategy board game in which players attempt to connect opposite sides of a rhombus-shaped board made of hexagonal cells.It is traditionally played on an 11×11 rhombus board, although 13×13 and 19×19 boards are also popular. The board is composed of hexagons called cells or hexes. Each player is assigned a pair of opposite sides of the board, which they must try to connect by alternately placing a stone of their color onto any empty hex. Once placed, the stones are never moved or removed. A player wins when they successfully connect their sides together through a chain of adjacent stones. Draws are impossible in Hex due to the topology of the game board.



---


***Rules of Hex***


---



* Players take turns placing their pieces on an empty hex.

* One player connects top to bottom (Red), while the other connects left to right (Blue).

* Pieces remain on the board once placed and cannot be moved.

* A player wins by forming an unbroken path of their pieces connecting their assigned sides.

* The swap rule allows the second player to swap colors after the first move for balance (optional and not used in this project as I will be using endgame scenario).



---

# **Logic decided when creating the game.**


---


In Order to apply the search tree algorithm i will use a 6x6 board and create an endgame scenario as when trying to create a full game the branching factor was too big and i was unable to sort out the branch pruning properly so seeing as the full game branching factor was too big i decided to create the endgame board to have 10 moves remaining on the board with both players in a relatively equal position with the abillity to win in 2 moves if not blocked.

This choice was made after many failed attemptds created in the roughwork file led to the generate children leading to resurce timeouts or the AI just always choosing to pick the next open spot, the closest to succesful full game model that was made was one trhat blocked a player one move before they would win but this wonuldnt work in a game like hex as a player ccan still connect the piece down diagonally and win.


---


***Rough Work Notebook:*** https://colab.research.google.com/drive/1k-vLdMC9edieHrxMm-gpuuu6juAdIzVV?usp=sharing


---

