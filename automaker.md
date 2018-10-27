## Introduce ##

## Simple start up ##

This example will show you how to create <**hello world**> project by this tool.
### 1. create base project

command and usage: ./automaker.sh <path/project_name>  

type bellow:
       
````
./automaker.sh examples/hello_world
````   

this command will create a  "hello_world" project under directory "./examples", directory struct is bellow.

>./examples   
>&emsp;|-- hello_word 
>&emsp;&emsp;|-- bin  
>&emsp;&emsp;|-- build   
>&emsp;&emsp;&emsp;|-- Makefile.in   
>&emsp;&emsp;&emsp;|-- configure   
>&emsp;&emsp;&emsp;|-- easybuild   
>&emsp;&emsp;|-- conf   
>&emsp;&emsp;|-- include 
>&emsp;&emsp;|-- lib 
>&emsp;&emsp;|-- script  
>&emsp;&emsp;|-- src  
  
### 2. put your code to src
write hello_world.c, and add file to "src" directory
````
#include <stdio.h>
int main(int argc; char* argv[])
{
	printf("hello automaker world!\n");
	return 0;
}
````
### 3. compile and run
````
cd ./examples/hello_world/build
./configure --bin_path=hello_world 
````