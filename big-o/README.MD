1. Space and Time Complexity

 array of n elements requires O(n) space.
 stack space in recursive calls can take O(n) time and O(n) space.

2. Drop the Constants

 O(N^2 + N) = O(N^2)
 O(N + LogN) = O(N)
 O(5*2^N + 1000N^100) = O(2N)

3. Complexity from Worst to Best:

 O(x!) => O(2^x) => O(x^2) => O(xLogx) => O(x) => O(Logx)

 Where: 
	O(x) is linear in progression and 
	O(Logx) having the least complexity.


4. Multi-part: Add vs. Multiply

 Add when 2 complex tasks run in sequence - one after the other
 Multiply when a task is nested in another task (nested loops) - where N * N = N^2

5. Amortized time for ArrayList

  For every X elements capacity doubles by 1, 2, 4, 8, 16...
  Then the sum of X id X + X/2 + X/4 + X/8 + .... + 1, which is ~2X.

  Therefore X inserts has a time complexity of O(2X). 
  Therefore, the Amortized time is 0(1).

6. Log N runtimes (task gets halved each time)

  Binary search has Log N efficieny.
  N=16, N=8, N=4, N=2, N=1
  2^4 = 16 = log2 16 = 4
  log2 N = k -> 2^k = N


7. Recursive runtimes

   For binary trees and fibonacci method:

   time complexity is O(2^N)
   space complexity is O(N) 


   For x branches for N recursions, complexity is O(x^N)



