<h1>Super Tic Toe in Python </h1>

<h2>Details </h2>

<p>
Super Tic-Tac-Toe is an advanced version of the traditional Tic-Tac-Toe game. This project combines the simplicity of Tic-Tac-Toe with strategic depth and complexity,
making it more challenging and engaging.
The AI uses the Minimax algorithm with alpha-beta pruning and iterative deepening to provide a formidable opponent.
</p>

<h2> 
Features
</h2>
<p>
<li>9x9 Main Board: The game consists of a 9x9 grid, divided into nine 3x3 sub-boards.
Sub-Board Wins: Win individual 3x3 boards to control that section of the main board.
Minimax Algorithm with Alpha-Beta Pruning: Ensures efficient and competitive AI moves.
Iterative Deepening: Allows the AI to make decisions within a specified time limit, enhancing performance.
Graphical User Interface (GUI): Built using Tkinter, providing an intuitive and interactive game experience.
</li>
</p>

<h2>Code Over View</h2>
<p>
  Code Overview
Main Components
SuperTicTacToe: The core logic of the game, including the board state, move validation, and the Minimax algorithm.
SuperTicTacToeUI: The Tkinter-based GUI, handling user interaction and displaying the game state.
Key Methods
make_move(board_index, cell_index, player): Validates and makes a move on the specified cell.
update_small_boards(): Updates the status of each 3x3 sub-board based on the current state.
check_tris(player, board): Checks if the specified player has won on the given board.
game_tie(): Checks if the game has ended in a tie.
minimax(max_turn, depth, alpha, beta, start_time, time_limit): Implements the Minimax algorithm with alpha-beta pruning.
iterative_deepening(time_limit): Implements iterative deepening to find the best move within a time limit.
GUI Components
create_widgets(): Initializes the game board and status label.
on_button_click(board_index, cell_index): Handles user moves and updates the UI.
ai_move(): Calculates and executes the AI's move.
update_ui(): Refreshes the game board based on the current state.
draw_cross(board_index_x, board_index_y, winner): Draws a cross on the winning sub-boar
</p>
