# hentai-categorization-ai-
An AI powered categorization / sorting software to organize all your hentai!


## Problem
Have alot of hentai? Can't categorize them properly? Too much to sort through?

## Solution
Create multi-platform software that; by using AI, sorts out a series of images (possibily including videos or gifs) into folders and or tagging them for easy tracking.

## Plan
Using a multi-platform lanuage, create and train an AI. Easy in theory, harder in practice

### Core sorter
1. First have simple decision tree to sort out file types to be ignored (left in original directory)
2. Create & Train AI that decides if something is hentai or not, if it is not it is ignored. If it is hentai, it is passed over to 3.
3. Create & Train AI to assign each image tags corresponding to hentai genres, or Create & Train numerous AI to decide if content matches a specific genre or not. This can be modeled after currently understood human ideas of fetishes and hentai genres.
4. Output is parsed as JSON, containing mappings for each file and its containing genres, this can then be fed into whatever needs to utilize it

### Client 
After utilizing the core on a selected directory or directories, It can... (and / or) 
- Output the files into folders for the major genre
- Rename the files with the genres contained in the file
- Output them into a specific directory
- View them from within app, allowing easy access to stored hentai
