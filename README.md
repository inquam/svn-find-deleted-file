# svn-find-deleted-file
Small script to traverse a SVN repository and find the revision where a file was deleted

This is a small script I wrote a few years back when working on a system where people remebered there being a file
in the repository that was no longer there. No one could say when the file had been removed. 

Usage:

To start looking from revision 1052 backwards for the file "FooBar.txt"

 $ ./svn-find-deleted-file 1052 "FooBar.txt" 
 
 You can also run in interactive mode with 
 
 $ ./svn-find-deleted-file
 
You are free to use and modify this script as long as you credit me and
make your changes avalible to the public.

Daniel Liljeberg <danielliljeberg@spray.se>
