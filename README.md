# Schedulling_Test
This is the assignemnt of the real time operating system in which the schedulling of tasks has performed using priority ceiling protocal.

## Quick Start
### Compile and Run the code
- Clone this repository in a new workspace and build it:
- Before compiling the code you must need to be super user
- To be a super user open the terminal from the directory where you have cloned this repository and run the following command.
```
$ suod su
```
- Build the code using following command
```
$ g++ Assignment1.cpp -lpthread -o Ceiling
```
- This will create executable file named "Ceiling"
Now simply run the executable
```
$ ./Ceiling
```
- This wil firstly perfrom schedulling test of tasks using rate monotonic.
- If the task is schedualable, it will simply scheduale the tasks using priority ceiling protocol.
