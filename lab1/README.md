
# Lab1
First version of this program sorts big files using external memory. The algorithm uses balanced k-way merge sort. Also was created a modified version, which allows writing to the output file only after sorting the entire set of numbers, reducing file writing operations. This increases the efficiency of the program and facilitates control over work with files.
## How to compile
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

