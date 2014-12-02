################################################################################
#        _                       _                                             #
#  _   _| |_       ___ __ _  ___| |__   ___       _ __ ___   __ _ _ __   __ _  #
# | | | | __|____ / __/ _` |/ __| '_ \ / _ \_____| '_ ` _ \ / _` | '_ \ / _` | #
# | |_| | ||_____| (_| (_| | (__| | | |  __/_____| | | | | | (_| | | | | (_| | #
#  \__,_|\__|     \___\__,_|\___|_| |_|\___|     |_| |_| |_|\__,_|_| |_|\__,_| #
#                                                                              #
#                                                                              #
#   __ _  ___ _ __                                                             #
#  / _` |/ _ \ '__|                                                            #
# | (_| |  __/ |                                                               #
#  \__, |\___|_|                                                               #
#  |___/                                                                       #
################################################################################
This is the ut-cache-manager.

All Unreal series games have the following properties in common:
    * They cache files downloaded during online play
    * Those files are saved with the sha1 hash value as the filename 
    * There is a file, with all the keys for decoding this information
    * The above prevents version conflicts with packages
    * The default folder structure is the same

What does ut-cache-manager do?
ut-cache-manager parses the cache decoding file, whose default name is 'cache.ini.'
It then checks for the presence of each of the files on disk. Sometimes Unreal
series games delete the files, or even clears the cache decoding file.
ut-cache-manager accounts for all this, and gives you the complete scoop on your
package cache. 

You can:
    * See what files are available to extract
    * See what files are missing
    * Search for files with regular expressions
    * Search for files by date 
    * Extract any existing files, so you can use
      them offline
    * Setup custom config files for each game you own

