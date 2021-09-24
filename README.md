# C++ Applications
This repository includes work done through CS courses at OSU to show knowledge of C++.

# Wizard Logbook - Assignment 1
This program uses file I/O to make a catalog of wizards and the spells they can perform. Users are able to sort spellbooks, group spells by effect, and sort by avewrage success rate. This assignment also uses command line arguments as well as many other staples of C++. The .txt files are used for input data, while catalog.cpp contains most of the functions used in the program and run_wizard.cpp is the executable. 

# Pizza Ordering Site - Assignment 2
This program performs the functionality of a pizza ordering site in terminal. Users are able to select whether they are customers or employees, giving them access to different actions to take. Customers can view the menu, search for pizza by cost and by ingredients, place orders, view restaurant information, and log out. Employees must enter an ID to view their potential actions. After this, they can change the operating hours of the restaurant, view orders, remove orders, add items to the menu, remove items from the menu, view other restaurant information, and log out. This assignment emphasized operator overloading and hierarchical code. The .txt files are primarily used for input data, while most of the .cpp files perform functionality of the program and a makefile is used to create the executable.

# Zookeeper Game - Assignment 3
This program is a game in which the user is the owner of a zoo trying not to go bankrupt. Animals are bought and sold, with each animal generating profit each month that it is in the zoo. Special events can occur such as animals giving birth and animals getting sick. This assignment highlights inheritance and encapsulation in addition to being fun to play. Each animal in the zoo inherits from the animal class, but has some qualities that make it unique (for example monkeys are more expensive). A makefile is used to create the executable.

# Hunt the Wumpus Game - Assignment 4
This program is another game. In hunt the wumpus, the user plays the part of a person trying to find gold in a "room" and escape without falling prey to any of the traps hidden around the game board. The game takes place in a terminal, and uses inheritance, encapsulation, command line arguments, and other staples of C++. The different forms of events (pit, gold, bats, etc) all inherit from the event class, while game.cpp holds many of the important game functions and prog.cpp is used by the makefile to provide an executable.

# Linked List Exploration - Assignment 5
This program delves into the world of linked lists. Each object of the linked list class has a head node to point to the front of the list, a length int that gives the length of the list, and a current node that can be used to perform list functionality (such as sorting and adding to the list). Merge sort is also used in this assignment. A makefile uses test_linked_list.cpp to create the executable for this program.
