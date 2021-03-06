# Reading Questions - Section 4.3

1. You first saw a *decrease-by-a-constant-factor* algorithm back in CSC 120. What was it? (Hint: If you can't remember, glance at the first part of section 4.4 on pages 150-152. But try to figure it out before turning to those pages!)


2. How might you represent the arrows in the Johnson-Trotter algorithm? Overall, what data structure(s) do you need? (Note: You need to store a permutation, the arrows for a permutation, and a list of permutations. How do you store a permutation? A list of permutations? Etc.) Be complete and specific.


3. What is a mobile element?


4. If the *Johnson-Trotter algorithm* generates $n!$ permutations, why isn't it obvious that it should take $Θ(n!)$ time? (This is a very important question, so make sure you give it some thought, and ask if you aren't sure of the answer. Of course, you should always ask if you don't know the answer.)


5. Imagine you are in the middle of the Johnson-Trotter algorithm algorithm and have this:
   ```   ←	←	←	←
   1	4	2	3
   ```
   Show the next 3 steps of the algorithm.



6. Given the permutation `352461`, what are the next 3 permutations generated by *LexicographicPermute*?


7. Explain why generating bit strings of length n and generating subsets of a set of n elements are essentially the same thing. Why does the order in which bit strings are generated matter?
