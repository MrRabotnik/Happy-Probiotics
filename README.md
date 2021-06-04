# Happy Probiotics - Frontend HTML Package

## Folder Structure

 - **Resources**
Contains static resources the package needs, such as library code, template files, graphics, ... In general, there is a distinction between public and private resources.

     - **Private** 
     
     Contains private resources for the package. All files inside 
     this directory will never be directly available from the web.
      
      - **Public** 

     Contains public resources for the package. All files in this directory will be mirrored into Flow's *Web* directory by the   
     ResourceManager (and therefore become accessible from the web). They 
     will be delivered to the client directly without further processing.
    
     Although it is up to the package author to name the directories, we suggest the following directories:

     * Images
     * Styles
     * Scripts

     The general rule for this is: The folder uses the plural form of the resource type it contains.