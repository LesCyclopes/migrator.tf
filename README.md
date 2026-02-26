# migrator.tf

to do: 

make basic site structure in html

make css style file

parts:

button that opens user's file explorer and lets them select their tf2 directory

button set that lets users select windows/mac/linux

button that users can untick if they dont want the bundled install script

function that reads through the directory comparing hashes and marking all custom files in a bundle

fucntion that displays on the website, all custom files that were just found.

function for redundancy, that categorizes any directory into being either part of a custom config or just a change in the game files, so that unrelated game files arent included in the bundle. 

function that takes the bundle of custom files and creates an install script for the os the user selected, and zips it up. 

download button for the user to download the finished zip file. 
