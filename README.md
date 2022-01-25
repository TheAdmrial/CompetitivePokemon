# CompetitivePokemon

## A World of Dreams and Adventures...
I have been a fan of Pokemon since I was a kid. I have played most of the main series games and plenty of Pokemon Go. When I was playing, mostly by myself, I felt that I had a very hard time understanding the battling side of Pokemon. I didn't really get the purpose of stats and really only focused on the typing advantage. The typing advantage is important, but ignoring stats is a horrible error if you would like to enjoy Pokemon. I have felt that I always seemed to pick Pokemon that were okay, but not stellar. It has only been in the last couple of years that I have realized the error of my ways. 

During a majority of 2020, I cam across the competitive Pokemon scene. While I haven't participated myself, I did find it fascinating why some Pokemon were considered unfair or unusable. I became interested in the ranking of Pokemon and wanted to know and understand what makes a Pokemon top tier. Why only a select few Pokemon are used competitively out of a roster of nearly 1000? What role do typings and type advantage play in this complex turn-based strategy game? 

While I don't know the answers just yet, this Github repo is to serve my exploration of all things competitive Pokemon. 

## Project (Silph) Scope
This projects aim is to understand the categorization of Pokemon competitively. I plan on using machine learning to understand these categorizations. The data that I will be using will come from Kaggle with some modifications that will be explained. I will strive to explain my thought process throughout this project. 

## The Pokedex Data
The data that I will use is data that is found on Kaggle with some modifications. 
  - First, I will be focusing on the all Pokemon entries up until the latest generation, generation 7 the Alola region. The first reason for this is in the latest iteration of Pokemon, Sword and Shield, all currently available Pokemon are _not_ available in this game. The latest game where *all* Pokemon can be used in competition is Pokemon Ultra Sun and Ultra Moon. A further analysis could be done for just Sword and Shield, but that is for a later time. 
  - Second, the Kaggle dataset has blended new Pokemon forms together and has not clearly identified differences between mega evolutions and new alternate forms like Alolan forms. The dataset will be wrangled to reflect these changes in form. 
