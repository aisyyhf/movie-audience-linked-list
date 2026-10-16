# Movie Audience Linked List

A C++ console app for managing movies and their audiences, built with a Multi-Linked List. This was my final project for a data structures course.

Movies are stored in a doubly linked list, and each movie has its own singly linked list of audience members.

```
[Movie A] <-> [Movie B] <-> [Movie C]
    |             |
 [Aud 1]       [Aud 1]
    |
 [Aud 2]
```

## Features

- Add, update, and delete movies (title, genre, director, release year)
- Add, search, and delete audience members for each movie
- Count the audience of a movie
- Show all movies with their audiences

## How to run

```bash
g++ main.cpp tubes.cpp -o mll_film
./mll_film
```

On Windows, run `mll_film` instead of `./mll_film`. Or open `tubes.cbp` in Code::Blocks and press F9.

## Files

- `tubes.h`: structs and function prototypes
- `tubes.cpp`: linked list operations
- `main.cpp`: menu and user input

## What I learned

- Linking a parent list to child lists with pointers
- Handling edge cases when deleting the first, last, or middle node
- Freeing child nodes before deleting a parent to avoid memory leaks
