## showdir
shows the content of a directory in Linux, or creates it if it does not exist

OS: Linux
Programming language: bash shell

This simple script shows the content of a directory. If the directoryname does not exist, it will ask, if it should create it.

#usage:
showcase <name of directory>


Aim:
This tool shortens the way to query and/or to create a directory without typing the directoryname twice.
This is useful if you are using long or complicated directorynames and you are not sure if that directory already exists. 
With this script you only need to enter the directoryname (dirname) once.
Instead of :
ls -l <dirname>
mkdir <dirname>

you use:
showdir <dirname>

If dirname exists, it will show the content. 
If it does not exist, it will ask you to create one.
