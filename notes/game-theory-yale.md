## Game Theory @ Yale | [Full Course](https://oyc.yale.edu/economics/econ-159) | [Videos](https://www.youtube.com/playlist?list=PL6EF60E1027E1A10B)

### Lecture 1: Introduction: First Five Lessons | [Video](https://www.youtube.com/watch?v=nM3rTU927io&list=PL6EF60E1027E1A10B&index=1)
    - What is Game Theory?
        A method of studying strategic situations.
    - What is strategic?
        A setting, where the outcome does not depend only on you, but also on the actions of others.
    - What are the applications of Game Theory?
        Business, politics, sports, etc.
    - What are the modatilities of a game?
        Actors, Actions, Strategies, Outcomes & Payoffs.
    - What is a strictly dominating strategy?
        A strategy which produces a strictly greater payoff than another strategy regardless of what others do.
    - What is a strictly dominated strategy?
        A strategy which produces a strictly smaller payoff than another strategy regardless of what others do.
    - Lesson 1: Never play a strictly dominated strategy!
    - Lesson 2: Rational choice can lead to outcomes that suck!
    - Lesson 3: You can not get what you want unless you know what you want! (Payoffs matter. Different payoffs lead to different games.)
    - Lesson 4: Put yourself in other's shoes and try to guess what are they going to do!
    - Lesson 5: Yale students are evil! :)


### Lecture 2: Putting yourself into other people's shoes | [Video](https://www.youtube.com/watch?v=qQ3kFydI_xQ&list=PL6EF60E1027E1A10B&index=2)
    - What are the formal ingredients of a game?
        - Players/Actors - i, j
        - Strategies
            - si - strategy of the ith player
            - Si - set of possible strategies of the ith player
            - s - a particular play of the game (a strategy profile)
            - s-i - a choice for all except the ith player
        - Payoffs - ui(s) = ui(si, s-i) payoff for the ith player based on the plays of all actors
    - What is a weakly dominated strategy?
        - Player i's strategy si' is weekly dominated by the strategy si if
            - ui(si, s-i) >= ui(si', s-i') for all s-i
            - ui(si, s-i) > ui(si', s-i') for at least one s-i
    - Iterative deletion of dominated strategies
    - Common Knowledge - I know that you know that I know that you know ...
    - Mutual Knowledge != Common Knowledge

### Lecture 3: Iterative deletion and the median-voter theorem | [Video](https://www.youtube.com/watch?v=kqDu0RVWTYw&list=PL6EF60E1027E1A10B&index=3)
    - What is iterative deletion of dominated strategies?
        - Putting yourself into somebody else's shoes in order to exclude strategies which would be dominated based on the subset of decision the other actor(s) might take.
        - The downfall is that it might lead to overthinking of the game.
  
    - Model of politics
        - 2 candidates which will choose their political stance on a political spectrum (1-10)
        - Voters vote for the closest candidate. If there is an overlap, voters split for each candidate
        - Payoffs: Candidates aim to maximize their share of the vote.
        - Most dominated strategies will be 1 and 10. Both of them are dominated by the remaining 9 positions.
        - Iterative deletion leads to deletion all but 5 and 6.
  
    - Median voter theorem
        - The MVT predicts that political candidates crowd the center (5 & 6).
        - Application in economics (e.g. product placements)
  
    - Problems with MVT
        - Voters are not evenly distributed.
        - Not all groups are voting equally much.
        - Multiple votes are not accounted for.
        - Politics is not one-dimensional. People vote for things like character, as well.
        - Model does not account for multiple candidates.
        - Voters might not believe candidates and their policies.
  
    - Robustness of MVT
        - Although it is true that the voters are not equally distributed, even a normally distributed voters will lead to the same results.
        - MVT is generally robust.
  
    - Best Response
            |   | L    | R    |
            |---|------|------|
            | U | 5, 1 | 0, 2 |
            | M | 1, 3 | 4, 1 |
            | D | 4, 2 | 2, 3 |