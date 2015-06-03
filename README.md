# windows-remove-node-modules
This GIT bash script can be used to delete node modules in windows. 

## Feature ##
In Windows we cannot remove any folder containing node-modules if node-modules have been installed using npm install. This is because 
we get a log file name warining in that case. 
Those folders can now easily be deleted using this script. 

## How ##
1. Copy the file rm-node.sh into any folder in your machine defined in you PATH variable
2. Open GIT bash and mode to teh directory where you have the folder that you want to delete
Example : Say i want to delete folder  c:\dev\myApp

  ```
  $ cd c:
  
  $ cd dev\myApp
  ```
3. run the script
 
  ```
  $ rm-node.sh
  ```

It will display a set of unbuild tasks getting run. Once that is done go to the delete the folder in windows explorer.
  
