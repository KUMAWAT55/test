## First Git Repo 
One Paragraph of project description goes here

-->Command file with basic git-commands<--
### Getting Started
###### GIT DIRECTORY STRUCTURE
A **.git** directory has a structure similar to the following one:

   * objects/ folder
In this directory the data of your Git objects is stored – all the contents of the files you have ever checked in, your commits, trees and tag objects.
######        objects/[0-9a-f][0-9a-f] folders
A newly created object is stored in its own file. The objects are placed over 256 subdirectories using the first two characters of the SHA1 object name to keep the number of directory entries in objects itself to a manageable number. Objects found here are often called unpacked or loose objects.

##### objects/pack folder
Files that store many object in compressed form, along with index files to allow them to be randomly accessed are found in this directory.

##### objects/info folder
Additional information about the object stored is placed in this directory.
