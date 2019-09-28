efl - League Tables for English Football League 

## About
efl allows users to fetch the (hopefully) up-to-date league tables of the EFL, including the top 4 divisions currently. 
The data comes from wikipedia. 

Note: The league tables on wikipedia are pretty much all in the same format, if so its pretty trivial to add your own leagues to this, simply find the wiki template page for the league table and add an option to the argument parser. I'll likely update this if I need any other league's stats.

## Usage
Invoke 'efl' with one of the allowed values found in the help screen, the EFL Championship is the default value if no input provided:

> efl Premier_League

You may also provide a shortened version of your desired division, as long as it is a unique match, this command has the same effect as the last:

> efl pre

## Requirements

Python3.X

bs4

ptable
