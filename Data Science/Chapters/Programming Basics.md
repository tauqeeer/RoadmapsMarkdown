# Programming Basics

Some core programming concepts every data scientist should know are:

[1. Algorithms](#algorithms)</br>
[2. Data Types](#data-types)</br>
[3. Data Structures](#data-structures)</br>
[4. Loops](#loops)</br>
[5. Functions](#functions)</br>
[6. Database](#database)</br>

Let's begin!

## Algorithms

An algorithm is a set of instructions and rules given to a computer program to execute. These algorithms are executed from the moment you start your computer system, open an application or even shutting down your computer, everything is an algorithm.

Our lives are also revolving around algorithms. Our daily routine is an algorithm, the nature is in algorithm and even something as small as baking a cake is a set of instructions.

Let's take a look at an example to understand algorithms in computer:

    Start

    1. Go forward 
    2. Go left
    3. Pick up the glass
    4. Go right
    5. Go back

    End

The above algorithm has 5 defined steps before it is finished. These 5 steps or instructions are given to the computer to execute serially. That means that step 1 would be executed first, then step 2, and so on. Instruction number 5 cannot be executed right after instruction 1 because the algorithm follows a serial pattern, unless instructed to do so otherwise.

Everything in this digital world is based on algorithms and we use them in our daily lives without even thinking about it, because you just read this document from top to bottom, which is also an algorithm!

## Data Types

A data type is used to store, interpret and handle data and it's values.

A number and a character are two different types of data but have their own value in the data world.

Data can be of different types, for example photos, text files, videos, documents are all examples of different types of data.

Data types in programming world are simple and unique. Some of the most common data types are:

### 1. Integer

Integer is used to represent whole numbers in programming world. Some of the integers are: 1, 2, 3... 

Integer data type is used when the user wants to store and use the data as a whole number.

For example: Price of an item.

### 2. Character

The character data type is used to store and use a set of characters. A single character such as `A` or `z` can be stored in the character data type.

### 3. String

Strings are a group of characters which make a word or a sentence. It can include numbers, special characters and symbols as well. An example of string data type is `Hello, World!`

### 4. Float

Float data type is used to store fractional numbers and decimal numbers. We use float data type when we need numbers which are not in a whole number form. For example, if we need Pi value for a calculation:

`pi = 3.142`

### 5. Boolean

Boolean data type only contains 2 values, true or false. Boolean is used to check for a certain criteria if it is meeting or not.

### 6. Array

Array is known as a collection of items consisting of any data type (integer or string etc). Arrays are usually denoted with square brackets `[]`. Arrays can be used as a data structure as well. For example:

`['apple', 'banana', 'orange' ]`

## Data Structures

We used data types to store the data as a single unit. Now we move on to Data Structures which are used to organize and modify the data for better efficiency.

### 1. Stack

Stack is known as an object which is on top of another object. Stack stores data on top of data and uses last in, first out method (LIFO) to arrange the data. For example: A stack of boxes.

### 2. Queue

Queue is also known as a line. Queue stores data from the last index, unlike stack. It uses first in, first out (FIFO) method to arrange the data.
For example: A line outside a cinema.

### 3. Linked List

Linked list stores data where every element is treated as a seperate object containg it's own head and tail known as nodes. Head is the part of the linked list which points towards the next node and tail is attached to it's previous node.

### 4. Matrix

Matrix stores data on a n*n dimension space where n is the number of rows and columns. Matrices are widely used in maths and data structures due to it's simplicity.

### 5. Binary Tree

A binary tree stores data in a form of a tree where each node (element) contains two children (branches). The depth of the binary tree is known as how many levels of branches it contains.

## Loops

Loop can be easily be understood by observing a race. Participants go around in certain laps and try to finish the line.

A single lap can be means the loop was completed for a single time. Now imaging running that lap for n number of times where n is the number of times you want the computer program to perform a certain task.

Let's say you want to show a number in a single line from 1 to 10. You have 2 ways to achieve this task.

First you write each and every output from 1 to 10 in a single line like:

1.
2.
3. (and so on)

Now a better and efficient way to approach this problem would be to make a loop and tell the program to start showing numbers in a single line and start with 1, increase a number each time you display the output, and end with 10.

The above paragraph can be explained through a loop psuedocode.

`for numbers 1 to 10` </br>
`print number`</br>
`change line`</br>
`end loop` </br>

Just by 4 lines, you can perform the task which should have taken 10 lines by implementing loops. 6 lines can be saved for the memory by applying loops so it already has better efficiency.

This was a very minimalistic task with a very small amount of data, now imagine what would happen if you want to print numbers 1 to 1 billion. That is why we need loops for handling our tasks.

We will learn more about loops in Python in the chapter Python Basics.

## Functions

Functions are some specific lines of code which perform a certain task.

Every function contains it's name, it's parameters and the block of code (body) or instructions the function needs to perform.

Functions must return a value passed in them which is called a return value.

We will learn more about functions in Python Basics chapter.

## Database

Database is designed to store structured data which can be retreived and used later. Databases usually contain tables containing data about a specific object.

The concept of database was introduced to get rid of filing system. Paper files takes up a lot of time and space to create, update or delete a cetrain data. Main function of the database is to save time and the data should be present in front of you in seconds.

Every company in 21st century uses database to store their data because it can be accessed from anywhere around the world.

There are different types of databases such as Relational, NoSQL or Cloud Database which we will discuss in later topics in detail.
