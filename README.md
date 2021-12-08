# Chess-Piece-Threat-Detection
This project will be used to determine each chess piece's likelyhood of being in danger for the player.

In this file, there are five notebooks. Each has their own purposes.
1. Explore_Chess_Packages.ipynb was to explore the chess api (pip install python-chess), and seeing if I can load in the data into a keras model and train. No other real purpose to it.
2. Chess_Arrows.ipynb was to play around with visual arrows on the pgn chess board by the chess board api.
3. Parsing_Board_To_NP.ipynb was to parse the text file (data.txt) that is filled with FEN notation, and to convert them into interger representation of the boards.
4. Label_Creating.ipynb was used to create the testing labels for each board.
5. Training.ipynb was the actual training with all the data, comprised of two different CNN models