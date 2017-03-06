Session 9: Assignment 6

1. Explain about the different complex data types in pig

Complex Types: Pig supports three complex data types. They are listed below: 

•	Tuple: An ordered set of fields. Tuple is represented by braces. Example: (1,2)
•	Bag: A set of tuples is called a bag. Bag is represented by flower or curly braces. Example: {(1,2),(3,4)}
•	Map: A set of key value pairs. Map is represented in a square brackets. Example: [key#value]. The # is used to separate key and value.

2.  How can you interact with the shell in Apache Pig

There are two modes
In local file system
Sh <shell commands>
             Example: grunt>sh ls

When operation is done on HDFS, the following is used
  Command: Fs -ls
        Example: grunt>fs -ls .


3. Explain how pig differs from Map reduce

Pig is a scripted language whereas MapReduce is a compiled language. 
Pig has a higher level of Abstraction and Mapreduce is a lower level of Abstraction.
Pig has less lines of Code than MapReduce and the effort of development is easy when compared to Mapreduce which is tedious.
Although the code efficiency is higher in Mapreduce when compared to Pig.


4. Explain how Apache Pig differs from SQL

Hive is a Query Language where Pig is a Scripting Language
Both Pig and Hive have a Higher level of Abstraction
Hive has comparatively less lines of code when compared to Apache Pig.

5. Explain the scalar data types in pig:


int	Signed 32-bit integer	10
long	Signed 64-bit integer	Data:     10L or 10l
Display: 10L
float	32-bit floating point	Data:     10.5F or 10.5f or 10.5e2f or 10.5E2F
Display: 10.5F or 1050.0F
double	64-bit floating point	Data:     10.5 or 10.5e2 or 10.5E2
Display: 10.5 or 1050.0
chararray	Character array (string) in Unicode UTF-8 format	hello world
bytearray	Byte array (blob)	
boolean	boolean	true/false (case insensitive)





