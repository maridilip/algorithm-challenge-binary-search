# algorithm-challenge-binary-search
khan academy binary search implemented

Implement binary search
(If you don't know JavaScript, you can skip the code challenges, or you can do the Intro to JS course and come back to them.)

Complete the doSearch function so that it implements a binary search, following the pseudo-code below (this pseudo-code was described in the previous article):
1. Let min = 0 and max = n-1.
2. If max < min, then stop: target is not present in array. Return -1.
3. Compute guess as the average of max and min, rounded down (so that it is an integer).
4. If array[guess] equals target, then stop. You found it! Return guess.
5. If the guess was too low, that is, array[guess] < target, then set min = guess + 1.
6. Otherwise, the guess was too high. Set max = guess - 1.
7. Go back to step 2.

Once implemented, uncomment the Program.assertEqual() statement at the bottom to verify that the test assertion passes.
