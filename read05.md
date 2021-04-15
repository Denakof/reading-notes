# Comparison operators evaluating conditions:

#### you can evaluate a situation by comparing one value in the script to what you expect it might be,, the result is boolean: T or F

| ==    | !=   | === | !== |
|-------|------| 

### each one has a use or meaning
#### == is equal to
#### != is not equal to
#### === strict equal to
#### !== strict not equal to

# Logical operations:
| && | ! |
|--| 


# Loops: while and for
##### *We often need to repeat actions.*

###### For example, outputting goods from a list one after another or just running the same code for each number from 1 to 10.

#### Loops are a way to repeat the same code multiple times.

## The “while” loop
##### The while loop has the following syntax:

###### while (condition) {
######  // code
######  // so-called "loop body"}
##### While the condition is truthy, the code from the loop body is executed.

### The “for” loop
###### The for loop is more complex, but it’s also the most commonly used loop.

###### It looks like this:

###### for (begin; condition; step){
 ######  ... loop body ...}
###### Let’s learn the meaning of these parts by example. The loop below runs alert(i) for i from 0 up to (but not including) 3:

###### for (let i = 0; i < 3; i++) { // shows 0, then 1, then 2 alert(i);}

###### Let’s examine the for statement part-by-part:

		
###### begin	i = 0	Executes once upon entering the loop.condition	i < 3	Checked before every loop iteration. If false, the loop stops.body	alert(i)	Runs again and again while the condition is truthy.step	i++	Executes after the body on each iteration.