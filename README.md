# Lab Works

## Lab1
First version of this program sorts big files using external memory. The algorithm uses balanced k-way merge sort. Also was created a modified version, which allows writing to the output file only after sorting the entire set of numbers, reducing file writing operations. This increases the efficiency of the program and facilitates control over work with files.
### How to compile
Just type the following command in the console to compile the source files and generate the initial unsorted files:
~~~
python generate.py
~~~
So now you have an unsorted generated file of 10 MB. To sort it, type:
~~~
python lab1.py
~~~
Then if you want to run a modified version write:
~~~
python lab1_modif.py
~~~

## Lab2
This program is designed to generate a labyrinth and find a path through it. It is using the BFS (Breadth-First Search)  and the A* (A-star) algorithm.
## How to compile
Just type the following command in the console to compile the source files:
~~~
python main.py
~~~
Then enter the dimension of the maze and see the result

## Lab3
This program implements a small database with the functions of: 
- searching
- adding
- deleting
- editing
A red-black tree is used for data storage.
## How to compile
Just type the following command in the console to compile the source files:
~~~
python interface.py
~~~

## Lab4
This program solves the traveling salesman problem with the ant algorithm
- 100 peaks
- α = 2
- β = 4
- ρ = 0,4
- M = 30
## How to compile
Just type the following command in the console to compile the source files:
~~~
python main.py
~~~

## Lab5
This program solves the Salesman Problem (symmetric network) by genetic algorithm
The best result at 10,000 iterations was achieved with the following parameter values:
- batch_size = 4
- mutation_probability = 0.3
## How to compile
Just type the following command in the console to compile the source files:
~~~
python main.py
~~~
