# windows-remove-node-modules
This GIT bash script can be used to delete node modules in windows. 

### Feature ###
In Windows we cannot remove any folder containing node-modules if node-modules have been installed using npm install. This is because 
we get a long file name warining in that case. 
Those folders can now easily be deleted using this script. 

### Requirement ###
GIT bash should be installed in your windows.

### How ###
1. Copy the file rm-node.sh into any folder in your machine defined in you [PATH](http://superuser.com/questions/341192/how-can-i-display-the-contents-of-an-environment-variable-from-the-command-promp) variable
2. Open GIT bash and mode to the directory where you have the folder that you want to delete
Example : Say I want to delete folder  c:\dev\myApp

  ```
  $ cd c:
  
  $ cd dev\myApp
  ```
3. run the script
 
  ```
  $ rm-node.sh
  ```

It will display a set of unbuild tasks getting run. 

Once that is done,  go and delete the folder in windows explorer.
  
