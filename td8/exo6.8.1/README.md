# td8: Collection managment
backup directory

# Description
Collection manipulation like Map, List, arrayList, LinkedList, ...

## Contains
 - dataFile.cfg => configuration file
 - README.md
 - src/.. => with all functions

## Compilation
```Bash
javac *.java
java Main
```

## Usage
You can fill the configuration file with IP address and his machine name like :
```Bash
123.456.78.9 monServeur.chezMoi.fr
```
With ths config file, program finds for you information.
After the
```Java
>
```
You can type a ip address for know his machine name like :
```Java
> 123.456.78.9 // Entry
Answer : monServeur.chezMoi.fr // Output
```

Or vise versa like :
```Java
> monServeur.chezMoi.fr // Entry
123.456.78.9 // Output
```

You can type :
```Java
> ls 'domain'
```
For know all machine in this 'domain'.

Or : 
```Java
> ls -a 'domain'
```
For know all ip address in this domain

Fanally, you can type :
```Java
> Exit
```
For exit.

# Author
Mickael Le Denmat

## Last Update
04/26/20
