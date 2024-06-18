# plazza
Epitech Second Year Project, Plazza in CPP, Who said anything about pizzas?

Subject:

The purpose of this project is to make you realize a simulation of a pizzeria, which is composed of thereception that accepts new commands, of several kitchens, themselves with several cooks, themselvescooking several pizzas.You will learn to deal with various problems, including load balancing, process and thread synchronizationand communication.Before you get started, should take some time to read up on the following tools you’ll need to use:
  •Processes (man fork,man exit,man wait,man ...)
  •Inter-process communication (IPC)
  •STL threads
  •POSIX threads (man pthread_*)
  
Usage:

./plazza 2 5 2000

- The first parameter is a multiplier for the cooking time of the pizzas. It is used to examine your programmore easily, so it mustINEVITABLYbe implemented. Otherwise it will not be possible to grade you.Moreover this parameterMUSTbe able to accept numbers with value in between 0 to 1 to obtain adivisor of the pizzas cooking time. . .Cooking time is detailed later.
- The second parameter is the number of cooks per kitchen.Cook definition is detailed later.
- The third parameter is the time in milliseconds, used by the kitchen stock to replace ingredients.In-gredient definition is detailed later.

Bonus:

Advanced status display command.
