
A debugger is a tool that can help us see what happens when a program is running. As we have already mentioned, some bugs can be hard to find and understand just by running the program. Often, we will discover a strange behavior in the program, but it might not be obvious what the reason behind this behavior is.

Now, let's use a debugger and explore this error. The first thing we need to do is set a breakpoint.
Breakpoints
A breakpoint is a way for us to say, run the program to this point, then pause it and show me the status of the program.

Instead, there is another tool that might help us. In the following screenshot, we can see it marked with a rectangle:
In the top field, we can enter an expression. This can help us understand what is happening. We are currently on this line:
If we enter a part of this expression into the evaluation expression tool, it will show us the result. Let's take the first part of this if statement. Entering it into the tool will look as follows