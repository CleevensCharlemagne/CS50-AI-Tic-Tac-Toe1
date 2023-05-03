<h2>Week 0: Search</h2>


**Degrees (BFS)** [see directory](https://github.com/dtemir/harvard-CS50AI/tree/master/degrees):
    
* The assignment is about finding the shortest path between two nodes
* The database comes from IMDb, and the task is to tell how one actor is connected to another through their common movie casts
* The solution is based on Breadth-First Search (BFS) because the task requires the shortest path between nodes
* To implement the search, I used a Queue-based Frontier. The Frontier is filled with neighboring nodes that share the same parameter(movie)
* You can find the demonstration of how it works [here](https://www.youtube.com/watch?v=0bksDFskiRM&t=1s&ab_channel=DamirTemir)
* You can find my explanation on [**Medium**](https://damirtemir.medium.com/do-all-hollywood-actors-know-each-other-breadth-first-search-in-action-1b37df515928)


      $ python degrees.py large
      Loading data...
      Data loaded.
      Name: Emma Watson
      Name: Jennifer Lawrence
      3 degrees of separation.
      1: Emma Watson and Daniel Radcliffe starred in Harry Potter and the Chamber of Secrets
      2: Daniel Radcliffe and James McAvoy starred in Victor Frankenstein
      3: James McAvoy and Jennifer Lawrence starred in Dark Phoenix
    

**Tic-Tac-Toe (Minimax)** [see directory](https://github.com/dtemir/harvard-CS50AI/tree/master/tictactoe):

* The assignment is about writing an AI algorithm to play Tic-Tac-Toe optimally.
* The pygame module provided inside the <code>runner.py</code> file was outside the scope of the project.
* The solution is based on Minimax decision rule which perfectly works for games that clash two opponents against each other
    * The algorithm is all about calculating the best utility out of all possible solutions. 
    * The algorithm relies on calculating prospective steps that the opponent might take

* The <code>tictactoe.py</code> file (where the solution lies) consists of many minor functions that construct the game of Tic-Tac-Toe (finding out who is a winner, etc.)
I recommend paying better attention to the last function called <i>minimax</i>
    * The function determines which side AI plays for, and then finds the best optimal score that the AI can get

* You can find the demonstration of how it works [here](https://www.youtube.com/watch?v=jgmtzfJTEgY&ab_channel=DamirTemir)
* You can find my explanation on [**Medium**](https://medium.com/analytics-vidhya/minimax-algorithm-in-tic-tac-toe-adversarial-search-example-702c7c1030eb).



![tictactoe demo](demo/tictactoe.gif)
