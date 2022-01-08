## coding: ep6 myblocks
`author: Pratyush`

### What are myblocks
MyBlocks are an extremely useful feature that you can use while coding with Spike Prime or older software models.
MyBlocks help create blocks of code that can repeatedly be used throughout your code - without rewriting the whole thing each time.

### Code
First, we’ll start by creating a MyBlock. Then, we’ll name our MyBlock and create some inputs to tell our robot what to do when it reads the MyBlock.
In this case, we’ll make a myblock that tells the robot to do a 180 degree spin; then display a smiley face on the display to tell us it’s done.
We’ll name our myblock `spin_smile`. We’ll add 1 input called `direction`. `direction` will tell us which way the robot should turn to spin 180 degrees.

Next, we’ll start adding blocks under the MyBlock in the workspace.
First, we’ll add a check to see which way we want the robot to turn.
We’ll use an if-else block for this. 0 means the robot will turn to the left, and 1 means the robot will turn to the right.

Finally, we’ll add a block to display the smiley face on the robot’s screen.
Now can you use your MyBlock in parts of your code wherever you want it to, in this case, do a 180 degree spin and then display a smiley face.


#### Projectfile
You can download the llsp file for this lesson [here](myblocks.llsp)

[← Return to Coding](README.md)
