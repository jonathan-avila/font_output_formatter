These scripts automate the rendering of dynamically created Javascript websites for the purpose of scraping the sites of their CSS and returning a list of the fonts employed by the sites. The list is returned as a csv file.

This script requires a headless Chrome driver. Bash 5.0 is also required for the enabling of the Bash portions. gawk bash function must also be downloaded.

You need a txt file named "allsites.txt" that has one URL per line

MAKE SURE TO USE CHMOD TO MAKE THE BASH SCRIPT AND THE PYTHON SCRIPTS EXECUTABLE ON YOUR MACHINE