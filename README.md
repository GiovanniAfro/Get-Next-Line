# Get-Next-Line
Create Get Next Line (GNL) to read lines from file descriptors with C programming. Explore static variables and efficient line-by-line file processing.
Project Name: Get Next Line

Summary:
The Get Next Line project is about implementing a function that reads and returns a line from a file descriptor. The primary objective is to enhance your understanding of C programming, specifically focusing on static variables.

Why is it Useful:

    Convenience: The project provides a valuable function that simplifies reading lines from a file descriptor, making it less tedious and more user-friendly.

    Learning Static Variables: It introduces the concept of static variables in C, which is a fundamental programming concept. Static variables retain their values between function calls, and understanding their usage is crucial in C development.

Get Next Line
Introduction

Get Next Line is a C programming project that focuses on creating a function to read and return lines from a file descriptor. The project aims to improve your C programming skills, particularly in handling static variables.
Table of Contents

    Project Goals
    Common Instructions
    Mandatory Part
    Bonus Part
    Submission and Peer-Evaluation

Goals

This project allows you to implement a convenient function to read lines from a file descriptor while learning about static variables in C programming.
Common Instructions

    The project must be written in C.
    Adhere to the project's Norm, including bonus files/functions.
    Your functions should not result in unexpected crashes (e.g., segmentation faults) apart from undefined behaviors.
    Ensure proper memory management with no memory leaks.
    Include a Makefile to compile your project with specific flags.
    Create a rule for bonus in your Makefile if you have bonus files.
    Test your project thoroughly even though the tests won't be submitted.

Mandatory Part
Function: get_next_line

    Prototype: char *get_next_line(int fd);
    Turn in files: get_next_line.c, get_next_line_utils.c, get_next_line.h
    Parameters: fd - The file descriptor to read from
    Return Value: Read line (correct behavior) or NULL (no more to read or an error)
    External Functions: read, malloc, free
    Description: Create a function that reads a line from a file descriptor, allowing repeated calls to read the text file one line at a time. It should return the line that was read, including the terminating '\n' character, except when the end of the file is reached and there is no '\n'. The header file must contain the function prototype.

Bonus Part

The bonus part allows you to explore more advanced features.

    Develop get_next_line() using only one static variable.
    Manage multiple file descriptors simultaneously with get_next_line().

To enable the bonus part, append the _bonus.[c/h] suffix to the bonus files. The bonus part will only be assessed if the mandatory part is PERFECT.
Submission and Peer-Evaluation

Submit your assignment in your Git repository. Ensure that your file names are correct. Prepare a diverse set of tests for defense.

Feel free to add your get_next_line() function to your libft once it is completed.

This project aims to improve your C programming skills, particularly in handling file descriptors and static variables. It provides a valuable function for reading lines from file descriptors, making your code more efficient and user-friendly.


