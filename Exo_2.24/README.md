
EXERCICE 2.24
------------------------------------------------------------------------------
Program  : Copier le contenu d'un fichier dans un autre fichier
FileName : OS2.py
Input 1  : test
Input 2  : testCopy
Output 	 : 'The file test is copied in testCopy'
By       : ALTIDOR Jean Bernard T., DUBUCHE Kevin J., THEODORE Barbara G.  
-----------------------------------------------------------------------------

**C code

//To compile
gcc OS1.c -o OS1

//To save output of strace 
strace ./OS1 &>strace_output_C
------------------------------
**Python code

//To compile
chmod +x OS2.py

//To save output of strace 
strace ./OS2 &>strace_output_python
-----------------------------------


EXPLICATIONSS
-------------
Il s’agit de copier le contenu d’un fichier source vers un fichier de destination.
L’utilisateur n’a qu’à entrer le nom de ces deux fichiers dans la console.
...
...
...