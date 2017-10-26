# Computer

This folder contains the original source code for the Java application that runs on a computer.
The program provides a GUI to allow users to open images of (nearly) every type, convert them to
a single path (for black and white prints) or multiple paths (2-8 colors), and send the points on 
each path to an arduino that serves as a printer.  A sample Arduino program can be found 
[here](https://github.com/ThePowerRule/DrawingMachine/tree/master/Arduino)

Due to the ACT, SAT Subject tests, college applications, and the like, I will not have much time,
and the time I will invest in this project will be spent on bug-fixing, tweaking, and improving the
program.

# Bugs
- [ ] JavaFX services for designing and printing the image do not reset after prints,
so the program will only print one time.

- [ ] Search for Arduino serial connection on devices other than COM3

- [ ] Allow users to cancel prints with the cancel button

- [ ] Terminate all threads with close button (after dialog warning)

- [ ] Put executable JAR in release


# To Do:
- [ ] Configuration window

- [ ] Export generated path to csv

- [ ] Print from generated csv file

- [ ] Write a new program (in Python?) to print generated csv.  This way anyone with Python (e.g. 
Raspberry Pi) can print with a connection to Arduino
