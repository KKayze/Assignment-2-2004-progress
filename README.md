# Assignment-2-2004-progress

A deeper understanding of the implementation of Dynamic Programming, Suffix Trie, Trie Node, Ford-fulkerson, breadth-first search and flow network with constrictions of complexity. The approach of code is using the bottom-up approach while being aware about the Auxiliary Space and Time complexity.


Question 1 brief description - Open Reading Frames (ORF)


The assessment involves creating a class OrfFinder to identify Open Reading Frames (ORFs) within a given DNA sequence represented by a string of uppercase [A-D]. An ORF is a segment that starts with a specific sequence and ends with another, non-overlapping sequence. The OrfFinder class includes an __init__ method, which initializes with the genome string and operates in 
O(N^2) time complexity, and a find method, which takes start and end sequences as inputs and returns a list of substrings that match these criteria, ensuring no overlap. The find method must run in O(T+U+V) time complexity, where T is the length of start, U is the length of end, and V is the total length of the output substrings. This task assesses the ability to implement efficient string manipulation algorithms within specified complexity constraints.


Question 2 brief description - Securing the companies


The assessment requires designing a function to allocate security officers to companies for a 30-day month, considering specific constraints. Each day has three shifts (midnight-8am, 8am-4pm, 4pm-midnight), and each company has a constant need for security officers per shift throughout the month. Officers can express their shift preferences but can work only one shift per day, with their preferences remaining constant across the month. The total number of shifts assigned to each officer must fall between specified minimum and maximum limits. The function, allocate, takes the officers' shift preferences, the number of officers required by each company per shift, and the min and max shifts parameters. It returns either None if no valid allocation exists, or a detailed allocation plan that specifies which officer works for which company during which shift on each day. The solution must adhere to a worst-case time complexity of O(m*n*n), ensuring efficient handling of the input constraints.
