# Voting-Systems
This project explores 5 major voting systems in a theoretical context, assessing and comparing how successful each voting system is at electing the best candidate, defined as the person that yields the best voter satisfaction. The project first looks at the results yielded when voters vote to their true preferences and when voters vote in a strategic manner. 

# Summary
The project was done in R, and here's a rundown of what's in each of the files: 
  1. Plurality: code that simulates how a voter would vote in a plurality voting system strategically and non-strategically. 
  2. best_candidate: function that determines the best candidate for a single voter given their utility value for a specific candidate.
  3. borda: code that simulates how a voter would vote in a borda voting system strategically and non-strategically. 
  4. boxplots: code that creates visualizations of the percentage of times that the voting system yields the best candidate 
  5. condorcet: code that simulates how a voter would vote in a condorcet voting system. 
  6. data_generator: code that generates our voter profile for our candidates 
  7. func_satisfaction: code that returns the satisfaction score of the winner and whether or not the winner is the most satisfied candidate of an election 
  8. pivot_prob: calculates the pivot probability for a candidate
  9. runoff: code that simulates how a voter would vote in a runoff voting system strategically and non-strategically
  10. scoring: code that simulates how a voter would vote in a scoring voting system non-strategically. 
  11. scoring_strategic: code that simulates how a voter would vote in a scoring voting system strategically

# Assumptions 
We made some strong assumptions when performing our analysis. This included: 
  1. The distribution of a candidate's voter satisfaction score comes from a normal distribution.
  2. Strategic voters knew the distributions of private utility values for each candidate and thus knew the probability that the voter will be the deciding vote between a given candidate pair. 
  
