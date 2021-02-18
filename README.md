# The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media
This respository contains bulk data to accompany the paper "The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media" (published at [AAAI-21](https://aaai.org/Conferences/AAAI-21/); pdf link forthcoming). The corpus represents the work of hundreds of students who opted in to having their work included in a dataset that might be used to accelerate technical games research. The metadata describing games (e.g. title, description, and tags) was provided by student authors. This repository does not directly contain game source code, assets, and other project files. Permanent download links for these are included in the data we provide here.

See `ExampleUsage.ipynb` for an example of how to use the data that we provide. This notebook shows how to load and filter the corpus as well as how to download and parse the contents of one of the Twine games that it includes.

To get started with the data immediately... [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/barrettrees/undergraduate_games_corpus/HEAD?filepath=ExampleUsage.ipynb)

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

## Contact

If you wish to report a problem with the corpus, request a change, or just ask a question, feel free to email:
- Barrett Anderson (`barander@ucsc.edu`)
- Adam Smith (`amsmith@ucsc.edu`)

## TODO
- update `corpus.json` with the rest of the games
