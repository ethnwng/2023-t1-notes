So far throughout the course, we have only been doing [[Structural Recursion |structural recursion]].

In **generative recursion** at each recursive call we generate entirely **new** data on each call. 

For generative recursive functions a **three part termination** argument is required, in [[Structural Recursion|structural recursion]] since we are always taking a sub piece of the overall data, our dataset will eventually reach our base case. 

The three part termination argument aims to **prove** that our function will not run forever.


#### Three Part Termination Arguments
always contain:

**Base Case:** What is the base case? 
**Reduction Step:** What operations are we performing on our original dataset such that the new dataset created is going to reach the base case?
**Argument:** Argue why the reduction step will eventually reach the base case

