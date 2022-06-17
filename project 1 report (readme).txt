
Project 1


Lisa Xu “Developer” 
Mikenson Peirre “Architect” 
Gamalie Dulcio Haldas “Reporter”   


The concept of the Checkers game was visualized by Mikenson.  The design and implementation were constructed by Lisa. Gamalie assisted with the development of the make_move() function, debugging, and the final report of Project 1.
This is the process that we took to make the checkers project:
There were (4) functions that needed to be implemented for the checker’s game.  The make_move (), lose (), scoring () and is_over().  In the make_move function, we use self. Players[self.current_player-1].pos= self.get_piece_pos_from_table(pos) self.board, to allocate pieces in the index of the different positions in the array to the current player position.  We use the lose () function to establish which player loses their piece. We used a “for” loop Boolean to determine whether the black piece capture a white piece in the black territory or whether the white piece capture a black piece in the white territory. The is_over() function decides when the game is over. We used return (self.possible _moves()== []) or self.lose()  looks are all the possible moves and verify that the game is over. The last function we need to implement was scoring (). We just used this function to return (0 if self.lose () the score of the game. 
