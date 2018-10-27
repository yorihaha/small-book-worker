## Introduce ##

## Simple start up ##

This example will show you how to create <**hello world**> project by this tool.
### 1. create base project

command and usage: ./automaker.sh <path/project_name>  

type bellow:
       
````
./automaker.sh examples/hello_world
````   

this command will create a project "hello_world" under dir "./examples", dir struct is bellow.

>./examples   
>&emsp;|-- hello_word //project root dir   
>&emsp;&emsp;|-- bin //  
>&emsp;&emsp;|-- build   
>&emsp;&emsp;&emsp;|-- Makefile.in   
>&emsp;&emsp;&emsp;|-- configure   
>&emsp;&emsp;&emsp;|-- easybuild   
>&emsp;&emsp;|-- conf   
>&emsp;&emsp;|-- include //put your so's head file in this place   
>&emsp;&emsp;|-- lib //put your lib in this place  
>&emsp;&emsp;|-- script //put your script  
>&emsp;&emsp;|-- src  //put your source code in this place
  
| directory or file | usage |
|-|-|
|   hello_word   |   project root dir   |  
|   bin  |   where your exe file will be put in   |    
|   build  |     |    
|     |     |    