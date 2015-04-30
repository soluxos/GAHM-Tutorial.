
#Read Me

##Original Project Plan
Please find the project plan outlined [here](https://github.com/MADAMULLAC/GAHM/blob/master/ProjectPlan.md "Project Plan")

## Prerequisites
- GNU Autotools (2.4.6)
- OpenGL 3.0+
- C++11 compiler (tested with GCC 4.8.3+)
- [GLEW](http://glew.sourceforge.net/)
- [GLM](http://glm.g-truc.net/)
- [GLFW](http://www.glfw.org/download.html)
- Unix like command line (terminal, cygwin, etc…) to run makefile

## How to get dependencies.

### Fedora, RedHat, Other Yum package manager based OS's


To get the dependencies assuming you have a fresh install of the latest version, simply run the following command:

> $ yum install libtool boost-* glew-devel glfw glm-devel gcc-c++

*Don't include the $ sign*

### OSx

*To run simply open the project file via xCode on OSX.*

To get the above packages I would recommend using [brew](http://brew.sh/) and [MacPorts](https://www.macports.org/) as these will do all the package management for you; both are fairly simple to install by following the simple instructions on their relevant websites.
Once again ensure you have the above packages included. 

> $ brew install autoconf automake libtool boost glfw glm 

> $ sudo port install glm

*ONCE AGAIN; Don't include the $ sign*

By installing macport that should suffice for other requirements.

You will also need xCode installed as this will include dependencies required by the game.

### Windows

*The file should work via monoDevelop with all the prerequisites*

## Aim of the game

NOBODY KNOWS!