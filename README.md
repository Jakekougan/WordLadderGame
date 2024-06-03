The Word Ladder Game 
By: Jake Kougan
Playing the Game:
Run all cells before playing the game, the last cell will run the game itself.

Rules:

1. Upon running the cell, you will be asked to input the legnth of words you want featured in the game.

2. Following step 1, you will be given a target word, start word, and a goal of how many words it will take to reach the target.

3. From there, try to build a path of same sized words from your start word to your target word. The only way to progress is to input words that share a one letter difference from the current word. If this is not followed you will be asked to try again.

4. Once the target word is reached, the game will end showing you a visualization of your path to the word and, if applicable, the quickest path from start word to target word.

Scoring:

All games begin with a score of 0 and a goal score. For each word added to the path, score is increased by 1. The goal is to try and reach the target word within the specified amount of steps.
If you fail to reach the target in the specified amount of steps the game will continue, you will just be shown the quickest path once your game has ended.

There are two versions of this project available in the repository:
1. A simple Python file
2. A Python Notebook file that can be run in either Google Collab and Jupyter Notebook

Disclaimer:
When playing it is best to choose word length anywhere from 3-6 characters for the best experience
Playing with anymore than 7 characters causes the game to fail
Will work on fixing this soon :)
