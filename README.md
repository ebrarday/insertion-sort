# Insertıon Sort Project Questions

[22,27,16,2,18,6] 

1.Insertıon Sort
  Values from the unsorted part are picked and placed at the correct position in the sorted part. Lets do it!
-> [2,27,16,22,18,6]
    ->[2,6,16,22,18,27]
        ->[2,6,16,18,22,27]
        
2.Big-O
n! = n*(n+1)/2) = (n^2+n)/2 => O(n^2)

3.Time Comletixy
Average Case : O(n^2)   Worst Case: O(n^2)    Best Case : O(n)

4.What case does the number 18 fall into after the array is sorted?
->[2,6,16,18,22,27]
18 is a average case. Because the number is the middle.

5. [7,3,5,8,2,9,4,15,6] 
Write the first 4 steps of the array according to the Insertion Sort.
->[2,3,5,8,7,9,4,15,6]
        ->[2,3,5,8,7,9,4,15,6]
                ->[2,3,4,8,7,9,5,15,6]
                        ->[2,3,4,5,7,9,8,15,6]
