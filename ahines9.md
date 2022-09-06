# Project Proposal
## Swimming and Track Scoring Program

This program is designed to take results files from previous years and store them in objects for each event. This program
would then be able to take a swimmer's personal best file output by Swimtopia(a program that teams use to organize and score meets).
After reading the swimmer's times for each event the program would determine which events the athlete needs to be entered in for the most points.
Track events involve athletes competing in certain events as well, they also display their results online in the same way
, so the program would be coded in a way that allows it to work for multiple sports.

## The Problem
I have been a swim coach for Knoxville Racquet Club for over five years and the STEM academy for 2 years.
At the end of each season there are large championship meets, where only the top 16 swimmers score points for their team.
As a result team coaches spend hours pouring over their swimmers times as well as results for previous years, 
so that they can enter swimmers in the events where they will score the most points. This summer I spent over 35 hours looking at past results,
and calculating the optimal entries, checking results from 2021,2020,2019, and 2018. These results are posted online in a 
consistent format each year, so the program could read in results from multiple years at a time.

## Features
* The program can read the files and seperate the results into objects
* The program will be able to collect swimmer's times, places, points scored, age, and names.
* As Track is a similar sport, and format their result files in the same way, the program could work for other sports as well.
* Result files can be read very quickly by computers, and will save coaches hours of work.

## Languages and Third Party Software
* I believe this project will be best completed using Python, as I'm familiar with is and it's well suited for seperating and storing strings as data.
* It would likely be just as effective to use C++ for this project, however I prefer Python.
* Swimtopia integration, Swimtopia is a meet manager system that all teams use to enter their swimmers in events and merge their entries with
teams that they will be competing against. This program outputs meet result times and individual swimmer's results in a consistent, easy to process format.

## Consumers
The GKAISA city meet championship is one of the largest in the south, with over a thousand swimmers and 4010 event entries,
these results files are very long and time consuming to look through manually. And with over 30
teams, there are many coaches who would buy or use this software.


## [Link](https://d1nmxxg9d5tdo.cloudfront.net/3002/files/results_-_full_meet.pdf?1627768541) to an example results file