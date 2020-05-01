## Game Theory @ TUM

### Lecture 2: Preferences over Lotteries & the Prisoner's Dilemma
    - Preferences under Uncertainty
        - In many cases, the outcomes of decisions are not deterministic, but stochastic.
        - The outcomes represent a probability distribution (lottery ticket), rather than a single deterministic point.
        - As a result of that, defining preferences over loteries is not clear.
    - Lotteries
        - Set of all lotteries L({x1, ..., xk}) = {p between [0, 1]k> sum(pi) = 1} is infinite
        - Types of lotteries
            - Simple Lotteries L = [p1 : x1, ..., pk : xk]
                - Degenerate Simple Lotteries - probability 1 on one alternative.
            - Compount Lotteries
                L = [p1 : L1, ..., pk : Lk] where L1, ..., Lk are simple lotteries. Can be simplified to simple lotteries by multiplying probabilities.
    - Preferences over Lotteries
        - Factors to consider:
            - most likely outcomes
            - most desirable outcomes
            - uniformity of probabilities
            - size of support
            - expected utility
        - Axiomatic Approach
            - Continuity
                - For all L1 > L2 > L3 there is some p in (0, 1) such that L2 ~ [p : L1, 1-p : L3]
            - Independence (Savage's sure thing principle)
                - For all L1, L2, L3 and all p in (0, 1) L1 >= L2 <=> [p : L1, (1-p) : L3] >= [p : L2, (1-p) : L3]
    - vNM Utility Functions
        - A preference relation on L(A) is rational, continuous and independent iff there exists an utility function u on A such that for 2 loterries L1 and L2
            L1 >= L2 <=> sum(pi*u(xi)) >= sum(pi*u(xi))
        - Every positive affine transformation f(x) = ax + b with a > 0 is alos a new vNM utility function.
    - Risk
        - risk-averse - utility is concave in value (e.g. difference between 0 and 1 million is bigger than 500 and 501 millions)
        - risk-seeking - utility is convex in value
    - Alais Paradox - Defines the inconsistency of actual observed choices with the predictions of expected utility theory
    - Efron's Dice - a set of 4 non-transitive dices
    - Prisoner's Dilemma
        |   | C    | D    |
        |---|------|------|
        | C | 2, 2 | 0, 3 |
        | D | 3, 0 | 1, 1 |