


Name:Mustafa Habeeb

-----------------------------------------------

Please confirm that you compiled your solution with test cases exercising ALL
functions using g++ -std=c++11.  Confirm this statement by typing YES below.
(If you did not do this, compilation errors may result in an overall grade of
zero!)


YES



Describe what augmentations to the bst data structures you made to complete the 
project -- i.e., what types / data members did you change and why?



Within the struct I added the countRightnode and countLeftnode. These were created for the purposes of counting the nodes to the left/right of a root and/or sub-root. They were also helped for the size balancing of the tree. I also added bstsize which tells us the size of the total number of nodes in the tree in an instant,



-----------------------------------------------
Which functions did you need to modify as a result of the augmentations from the previous
question?  


The functions that I needed to modify were _insert, insert, _remove, remove, check_smallest, numgeqHelper, numleqHelper, numrangeHelper, extractrangeHELPER, and find_the_position.


-----------------------------------------------
For each function from the previous question, how did you ensure that the (asymptotic) runtime 
remained the same?


By adding things that were in constant time I did not affect the total asymptotic runtime. I included initialization statements, and incrementation/decrementation statements.


-----------------------------------------------
For each of the assigned functions, tell us how far you got using the choices 0-5 and
answer the given questions.  


0:  didn't get started
1:  started, but far from working
2:  have implementation but only works for simple cases
3:  finished and I think it works most of the time but not sure the runtime req is met. 
4:  finished and I think it works most of the time and I'm sure my design leads to 
       the correct runtime (even if I still have a few bugs).
5:  finished and confident on correctness and runtime requirements


to_vector level of completion:  ______5_____  


-----------------------------------------------
get_ith level of completion:  _______5____  

    How did you ensure O(h) runtime?

    ANSWER:recursion and using the data types I added in the struct. 
-----------------------------------------------
position_of level of completion:  ____3_______  

    How did you ensure O(h) runtime?

    ANSWER: I looked at get-ith and did the inverse of this function. So I still did it recursively but this time the if statements were a bit different.
-----------------------------------------------
num_geq level of completion:  _____5______  

    How did you ensure O(h) runtime?

    ANSWER: recursion and using the data types I added in the struct. 
-----------------------------------------------
num_leq level of completion:  _____5_______

    How did you ensure O(h) runtime?

    ANSWER:recursion and using the data types I added in the struct. Also, it was the app of num_geq.

-----------------------------------------------
num_range level of completion:  ______5______

    How did you ensure O(h) runtime?

    ANSWER: I did use leq and geq however, I found a mathematical approach to complete it.

-----------------------------------------------
extract_range level of completion:  _____2_______

    How did you ensure O(h+k) runtime?

    ANSWER: I don't know for sure if the requirement was met because it traverses through the entire tree, and I couldn't figure out a way to block off certain subtrees that could be ignored. I'm sure it meets the runtime in certain cases such as going through the entire tree, but not all cases.

Implementation of size-balanced criteria according to 
the given guidelines:

    Level of completion: _____5______











