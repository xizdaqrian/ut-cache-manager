
        __                   __                                             
  __ __/ /____________ _____/ /  ___ ______ _  ___ ____  ___ ____ ____ ____ 
 / // / __/___/ __/ _ `/ __/ _ \/ -_)___/  ' \/ _ `/ _ \/ _ `/ _ `/ -_) __/ 
 \_,_/\__/    \__/\_,_/\__/_//_/\__/   /_/_/_/\_,_/_//_/\_,_/\_, /\__/_/    
                                                            /___/           

###This is the ut-cache-manager.

All Unreal series games have the following properties in common:
* They cache files downloaded during online play
* Those files are saved with the sha1 hash value as the filename 
* There is a file, with all the keys for decoding this information
* The above prevents version conflicts with packages
* The default folder structure is the same

###What does ut-cache-manager do?

ut-cache-manager parses the cache decoding file, whose default name is 'cache.ini.'
It then checks for the presence of each of the files on disk. Sometimes Unreal
series games delete the files, or even clears the cache decoding file.
ut-cache-manager accounts for all this, and gives you the complete scoop on your
package cache. 

###You can:

* See what files are available to extract
* See what files are missing
* Search for files with regular expressions
* Search for files by date 
* Extract any existing files, so you can use them offline
* Setup custom config files for each game you own

