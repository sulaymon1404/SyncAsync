# SyncAsync


## What is Synchronous in JavaScript?
## As its base JavaScript language is synchronous. Synchronous means the code runs in a particular sequence of instructions given in the program. Each instruction waits for the previous instruction to complete its execution

# See the following code example of synchronous JavaScript - Code Example -
[](/Imagess/1.PNG)


# In the above JavaScript code snippet, three lines of instructions are given. Every instruction runs once after the previous instruction gets executed. Due to this synchronous nature of javascript, we get the output of console logs in the sequence we provided in the program.

# When we say synchronous vs asynchronous JavaScript the execution sequence of instructions in a program is what differentiates them.



# What is Asynchronous in JavaScript?

# As we saw in the synchronous code example, all instructions in the program execute one after another, and every instruction waits for its previous instruction to get executed. Due to this nature of synchronous programming, sometimes important instructions get blocked due to some previous instructions, which causes a delay in the user interface. Asynchronous code execution allows to execution next instructions immediately and doesn't block the flow because of previous instructions.


# See the following coding example to understand how javascript works asynchronously -

# Code Example -
[](/Imagess/2.PNG)

# As we can see in the output of the above code example, Third gets printed before Second, because of the asynchronous execution of the code. Here setTimeout() function waits for 2 seconds, and in the meantime, the next instruction gets executed without waiting for the previous one to complete the execution.


# What is the Difference Between Synchronous vs Asynchronous JavaScript?

[](/Imagess/3.PNG)

[](/Imagess/4.PNG)





# try...catch
# The try...catch statement is comprised of a try block and either a catch block, a finally block, or both. The code in the try block is executed first, and if it throws an exception, the code in the catch block will be executed. The code in the finally block will always be executed before control flow exits the entire construct.



[](/Imagess/5.PNG)


[](/Imagess/6.PNG)


# Description

# The try statement always starts with a try block. Then, a catch block or a finally block must be present. It's also possible to have both catch and finally blocks. This gives us three forms for the try statement:

- try...catch
- try...finally
- try...catch...finally


# What is Axios?

# Axios is a promise-based HTTP Client for node.js and the browser. It is isomorphic (= it can run in the browser and nodejs with the same codebase). On the server-side it uses the native node.js http module, while on the client (browser) it uses XMLHttpRequests.