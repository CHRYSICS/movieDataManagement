Assignment 2

Author: Christopher Eckerson
Date: 10/20/2020

To compile, 
$ ggc -std=gnu99 main.c -Ibuild -Lbuild -lFileMgn -o movies_by_year

Where movies_by_year is the name of executable file.

The majority of code is modulated into the "build" folder.  This folder includes the header file "FileMgn.h", a compiled library called "libFileMgn.a" of all the object files found in "build", and all the .c and .o files for each modulated function for the assignment.

Both processMovieFile.c and createMovie.c are code created by the author during assignment 1.

Throughout the code, sections that are used or followed closely of example code was cited with hyperlinks. 

The files that are processed must be located in the current file as the executable file. An example movie data file has been left in the folder as an example of data format and required location.

Directories created by executable are located in current directory, each containing files (by year) of movies titles processed from selected movie data file. 