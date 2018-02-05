# Code and Coffee - Database Basics

## Why Use a Database to Organize Your Data

* Consistent structure - defined by you
* Enforced data types
* Can scale from single tables to sophisticated relational data models
* Can be a personal file-based or shared server-based solution, depending on your needs
* Standard language for interacting with your data
* Data can be accessed by many analysis tools

## Individual Topics

1. What is a table?
2. Data types
3. Aside - What about Excel?
4. Relating tables for power and flexibility
5. Different database solutions
	a. File-based (personal)
	b. Server-based (personal or team)
	c. Client applications (interact with both file- and server-based solutions)
6. Structured Query Language (SQL) - *mostly-standard*
7. Getting data in and out for analysis and visualization

### What is a table?

Superficially, a table is a set of values defined by rows and columns. Columns can be variously thought of as domains, variables, characteristics, etc. that apply to a set of entities. In this case each row represents an instance of or object within that entity set.

Donuts make a good example. Let's imagine that we've decided to classify an assorted dozen donuts. Three obvious characteristics stand out - the dough, the glaze, and the filling. Every donut in our dozen can be described according to these characteristics and represented with a unique row in a table:

| doNum | dough | glaze | filling|
|-------|-------|-------|--------|
|1     | cake  | maple | none |
|2     | yeast | sugar | none |
|3     | yeast | maple | boston creme |
|4     | yeast | chocolate | none |
|5     | cruller | vanilla | none |
|6     | yeast | chocolate | boston creme |

Easy! BUT - table design can be one of the more interesting and challenging aspects of data definition and database development. Donuts make an easy example because a box of donuts is not necessarily a complex system. It's a box. With donuts. Compare that with Amazon.com or other online retail system within which a large number of complex entities interact in complex ways, or with a census of animal populations at the Bosque del Apache. Would you record all the animals in a single table? Use one table for birds and one mammals, or even create a separate table for each species?!

Without getting into the weeds of normal forms or normalization, it's important when designing a database to give thought to:

* The sets or types of entities described
* Unique characteristics of each set
* Overlapping or shared characteristics among sets
* Cardinality between sets

### Data types

### Aside - What about Excel?

### Relating tables for power and flexibility

### Different database solutions

#### File-based (personal)

#### Server-based (personal or team)

#### Client applications (interact with both file- and server-based solutions)

6. Structured Query Language (SQL) - *mostly-standard*
7. Getting data in and out for analysis and visualization