# Data Structures Repo

The main goal of this repo is to store everything I learn about ds, this file will contain the stuff I write (concepts, examples)
and I'll try to make it up to date every time I implement something new. I'll be implementing the data structures in JavaScript

## The main idea

- Data structures are nothing but a way to organize and structure data
- Based on that, we can interact with this data and perform operations to change it
- Data structures have different names, operations, advantages and trade-offs, so we have to be aware of the kind of data we are operationg on to make the right decision when tackling a problem that requires managing data

From [wikipedia](https://en.wikipedia.org/wiki/Data_structure): 

> A data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data

# Complexity Analysis

A lot of problems can have multiple solutions, and in conding interviews this a reality we can't ignore. But when we compare them
we see that some solutions are "better" than the others. But how? What do we use/analyze to figure out the efficiency of a solution?

**Complexity Analysis!!**

We can analyze the efficiency of a solution to a problem in two given fields:

### Time
The amount of time an algorithm to run its execution (we don't measure it in seconds)

> time1 < time2 (timewise, solution 1 is more efficient than solution 2)

### Space
How much memory does the algorithm use?

> space1 < space2 (spacewise, solution 1 is more efficient than solution 2)

Some solutions may have a better time complexity, other ones may have a better space complexity, so which one wins depends on the 
usecase

With regards to data structures, we can tell that they have certain time-space complexities among their operations,
maybe removing something, adding some other thing, etc.

# Memory

Memory tells about how stuff really works when you write code, declare variables and etc. So a basic overview will be given here.

If we declare a variable `var foo = 1` in our code, we know that it is stored somewhere in our computer, but how?


