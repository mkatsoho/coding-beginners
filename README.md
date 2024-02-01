# coding-beginners
Something about coding for the beginners 


I use Python as an example in this document. Other languages, such as java, JavaScript, C, rust, swift and etc., are quite similar with Python in many aspects below.    

 

## IDE 
    - Pycharm 
    - Vscode 
 
Pycharm is very popular in Python world. If you write both Python codes and Java codes, I suggest you move to Vscode as early as possible, which has a bigger community.  

 
Both of them have extensions, to provide further functions. You may know more soon.  


## Git 

    - Github.com 
    - Gitlab.com 
    - SVN, skip this old code repository 

 

## Lint and Formatter 

The most useful extensions of IDE are lint and formatter. You can find more than one lint extensions and formatter extensions. 


Lint help you find out coding issues (known as issues) or possible coding issues (known as warnings).  

 
Sometimes you complain that someone is writing garbage codes. Sometimes you do not like a person's code style, even if his codes are good. Formatter help a team adopt the same style for everyone.  

 

## Virtual Env 

If you have multiple projects, they are using 

    - Diff python versions 

    - Diff versions of a the same library dependent 

You have to use the virtual environments. Each env seems an independent operation system, having its only python.  

 

## Package dependence 

One project can work well on machine A. But it could not be installed correctly or work correctly on machine B after a few month. Each line of the project is absolutely the same on those 2 machines. 

 

The key reason is the installed dependent packages/libraries are different. A too-latest package is introduced into the project, which does not compatible with other codes in the project.  

     

In brief, you need freeze the dependent packages' versions. Python requirements.txt supports  

    - Use a latest version of a package 
    - Avoid to use some version of a package 

 

## Package repository and publishing a package 

Skip this. It is not for advanced developers. 

 

## Documentation 
This is for senior developers.  


Write down human-readable comments in codes, and generate a document for the project.  

 

## Unit tests 

This is for senior developers. 

 
Without unit tests, codes are like a tiger running on the cliff. The king will die in any second. Think about the major disaster happen in those top internet enterprises.       

 

## Docker 
This is for senior developers. 

You want to demo a project to many fans. Furthermore, you would like to provide an independent environment for each fan.  


The low-cost way and also the efficient way is using docker. It is quite like a virtual machine, since everything is inner it. But it is lighter in the perspects of hardware, memory, and CPU than a virtual machine.  

 

## Kubernetes (aka. K8s) 
This is for advanced developers. 

K8s is a cluster of dockers running in cloud.  
 
