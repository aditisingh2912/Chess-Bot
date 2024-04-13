# Chess-Bot
This repository contains an AI chess Bot which was implemeted using MinMax Algorithm
# Implementation Details
 Built using Python-chess Library
 
 It involves two  Heuristic based optimization techniques to calculate the evaluation scores

 
      - Material Score Heurestics
      - Piece Square Table Heuristics 
      
# Material Score Heuristics
      -We assign scores(their valuability) and calculate material score based on number of pieces of each type.
      -The material score is calculated by the summation of all respective piece’s weights and  multiplied by the difference between the number of that respective piece between white and black.
# Piece Square Table Heuristcs
      -The individual pieces score is the sum of piece-square values of positions where the respective piece is present at that instance of the game.
      -we subract white score - black score to get total individual score
