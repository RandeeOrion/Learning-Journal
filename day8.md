- Loops check a condition. If it is true, it will run a code block. It will continue to run the code block as long as the condtion remains true.
- There are three types of loops: 
    - For: If you need to run a code a specific number of times, use a for loop. This is the most common loop. Here the condtion is a counter. 
        - Initionalization: Create a counter and set it to 0.
        - Condition: as long as the variable is less than x, the code block should continue to run.
        - Update: Every time the statment runs the code block, it updates the counter.
    - While: IF you do not know how many times the code should run, you can use the while loop. The condition is something other than a counter. 
    - Do While: the do... while loop is simmilar to the while loop, but it will always run the statements insdie the curly braces, code block?,  at lase once, even if the conditon evaluates to be false. 

### Key Words
- Break - This causes the termination fo the loop and tells the interpreter to go onto the next statmet of code oustide the loop.
- Continue - THis tells the interpreter to stop the current iteration, and then update and check the condition again. (if it is true run the code again)

### Performance Issues 
- When a browser comes accross JS to run, everything else stops. JS is a bit of a diva. 
- If your loop is dealing with a large amount of data, it can slow the page down.
- If the condition never returns false, the browser will never be able to move on until it runs out of memeory, which will break your script.
- Any variable outside the loop that does not change WITHIN the loop, should be decalred outside. If it is declared inside the loop it would be recalcualted each time the loop ran. 
- 