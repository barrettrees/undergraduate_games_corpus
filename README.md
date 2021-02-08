# The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media
This respository contains bulk data to accompany the paper "The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media" (published at [AAAI-21](https://aaai.org/Conferences/AAAI-21/); pdf link forthcoming). The corpus represents the work of hundreds of students who opted in to having their work included in a dataset that might be used to accelerate technical games research. The metadata describing games (e.g. title, description, and tags) was provided by student authors. This repository does not directly contain game source code, assets, and other project files. Permanent download links for these are included in the data we provide here.

## Citing
bibtex entry forthcoming

## Data Schema
The file `corpus.json` contains an JSON object mapping keys to values. Keys are globally unique archival resource keys ([ARKs](https://en.wikipedia.org/wiki/Archival_Resource_Key)) and values are objects describing games with the fields listed below:

 - permalink (link to human-readable page the game game)
 - title
 - description
 - authors
 - engine
 - tags
 - license
 - year
 - quarter
 - files (list of links for downloading larger data files)
