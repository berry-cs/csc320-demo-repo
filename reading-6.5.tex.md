# Reading Questions - Section 6.5

1. How many multiplications and additions are required to evaluate a polynomial of degree *n* using the obvious algorithm? How many multiplications and additions are required to evaluate a polynomial of degree *n* using Horner's rule? 


2. Explain why *Horner's rule* is an example of transform-and-conquer.


3. You will probably need to use something like [Wolfram Alpha](https://www.wolframalpha.com/) to help you with the computations on this one.
    - How many multiplications are required to compute $3^{37}$ using the obvious/naive algorithm?
    - Compute $3^{37}$ using the naive algorithm. (use Wolfram Alpha!)
    - What is the binary representation of 37?
    - Compute $3^{37}$ using `LeftToRightBinaryExponentiation`. Make sure to show the details of each step of the algorithm.
    - How many multiplications are required to compute $3^{37}$ using `LeftToRightBinaryExponentiation`?
    - Compute $3^{37}$ using `RightToLeftBinaryExponentiation`. Make sure to show the details of each step of the algorithm. (This one requires keeping track of more information at each step.)
    - How many multiplications are required to compute $3^{37}$ using `RightToLeftBinaryExponentiation`?
    - Did you get the same answer for all 3 algorithms? If not, try again!
    - Compare the three algorithms. Is one of them clearly the best? Is one clearly the worst? Explain.


