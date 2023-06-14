# Cubecon-2023

## Table of Contents

## Introduction: What's a Cube?

This is a personal project to assemble and analyze a dataset which showcases the creative expressions of game designers through the lens of Magic: the Gathering (MTG).  Besides being the longest and most successful trading card game, MTG has spawned many diverse and specific methods of playing.  Of these, this analysis focuses on an intentional curation of a select set of cards for the purpose of design and repeated enjoyment.  Known as a "Cube", these curations are often personal and meaningful explorations of the MTG Game system, while providing a reusable and replayable form of enjoyment without continued investment or buy-in (ideally).

A celebration of these creations is happening October 2023 in Madison, WI as part of Gamehole Con, called [Cubecon](https://mtgcubecon.com/).  Not only will this be a fabulous event, it's also a pagent of sorts as only a certain number of these creations were accepted as part of the structured main event.  

## Format of Celebration

Since Cubes are projects of passion, it's only natural that they deserve celebration and recognition.  A submission process happened in April, and the organizing committee of Cubecon saw fit to anoint 28 cubes to be pre-accepted, and the remaining 80 valid submissions would face off in Twitter Polls, listed in this [Google Sheet](https://docs.google.com/spreadsheets/d/1Mch2d3KO2Hc1n4KBpHbNVPtqnWBQ5RX6KeRCq4eOKac/edit#gid=0).  

The goal is to winnow the Cubes via community engagement into an additional 20 cubes, bolstering the pre-accepted class into a sizeable **48** selections.  Currating an overall list of these Cubes was an inticing proposition for yours truly, and I set about leveraging the wonderful [Cubecobra](www.cubecobra.com) website which hosts these Cube lists for aggregation and analysis purposes.

## Project Goals



## Data Sourcing

To begin with, my data intuition recognized at the most manual level, I would need to visit each Cubecobra website, and download the Cube into a `.csv` and load that file into Jupyter.  I would then have to download the [Scryfall.com]() Card Data package, and then attempt to merge the Cubecobra files together and then _Left Join_ the Scryfall.com data onto it.  

While being incredibly tedious, Cubes can change only a daily basis, and trying to reload them consistently would be more trouble than it was worth.


## Data Polishing

Cube Type
Cube ID
Cube Name

## Grouping & Analysis

## Exports

Referenced in Data Files:
* cubecon_card_list_2023_06_04.csv = First Export of all cards (Definitely Subject to Change)
* cards_per_unique_cubes.csv = Each card's unique cube inclusion

Cubecobra Links:
[Cubecobra Link of Initial Cubecon Submissions](https://cubecobra.com/cube/overview/248c0847-a176-431e-99c3-44b5a2267ea8)


## References

Reading Multiple Files for Concatenating [neuraldatascience.io](https://neuraldatascience.io/3-python/looping_data_files.html)

[Personal Copy of Cube Voting for Cubecon'23](https://docs.google.com/spreadsheets/d/1On6341vsVo_kCUgNGHHqOhzvFDxaGHPcBfxWj8yVPaw/edit?usp=sharing)

[CaliCubeChamps Initial Analysis](https://github.com/tpugliese/CaliCubeChamps23/blob/main/README.md)