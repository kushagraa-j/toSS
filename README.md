![](img/logo.png "toSS")

## Build Instructions

```bash
git clone https://github.com/kushagraa-j/toSS.git && cd toSS
g++ *.cpp -o toss
```

## Usage Instructions

```bash
./toss
```

## Code Structure

- inputFromUser.cpp
	- instructions() &emsp;	[ provide the user with how to use the program ]
	- input()	 &emsp;	[ take input from user ]

- randomNumPls.cpp
	- randomNumPls() &emsp;	[ generate a random number ( 1 or 0 ) ]

- resultOfProgram.cpp
	- result()       &emsp;	[ from user input and random number 
				 determine if the user won or lost ]
- toSSprogram.cpp
	- main()         &emsp;	[ all the functions are executed here ]

## Debug mode

To enable debug mode, edit the file `headers/debug.hpp`, change `NODEBUG` to `DEBUG`.
The file should looks like this,

```cpp
/* Debug */

#ifndef debug
#define debug

#define DEBUG

#endif
```
