# ME 701 -- Homework 1 -- Nathan Featherstone

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

3-D modeling is something that I do often (at least for work and school).
An open sourced 3-D modeling software that could be cool is FreeCad which from my brief perusal appears to do modeling similar to SolidWorks. 
There are others like Blender or Wings 3D (which I tried once but found it hard to get into).


## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following command:

```bash
lscpu #this command will give a system of computer information
```

In this case, I didn't have to redirect anything it wasn't necessary. One could use the sudo command to view as admin, but I don't think it is necessary.

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution

A great command for this task is top.

```bash
top #command to see realtime usage information of processes 
```

The top command will run a user interface that will update automatically. While in the interface, you can press  P to sort by CPU usage and M to sort by memory usage.
It also displays information on total processing and memory usage.

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution

To get the file location for bash, I used the following command

```bash
which bash 
```
The which command is only useful for executables. For me, bash is found /usr/bin/bash (that is standard).

To find the version of bash I used the following line.

```bash
bash --version
```
The version flag can be used to find the version information for executables (or at least some of them).
I have bash version 5.0.17(1).

