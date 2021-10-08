# The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media
This repository contains data to accompany the paper "[The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media](https://adamsmith.as/papers/aaai21-ugc.pdf)" (published at [AAAI-21](https://aaai.org/Conferences/AAAI-21/)). **The corpus represents the work of hundreds of undergraduate students who *opted in* to having their work included in a dataset that would be used to accelerate technical games research.** All data (and metadata) was collected with informed consent after a presentation that included showing them them how [future search engines](https://dl.acm.org/doi/pdf/10.1145/3235765.3235786) might be able surface embarrasing details from their early-career work here. The metadata describing games (e.g. title, description, and tags) was provided directly by student authors, and it was not verified by external judges. Respecting requests for removal and including one more course-full of games after publication of the paper, the total number of games in this corpus will not exactly match that described in the paper.

See `ExampleUsage.ipynb` for an example of how to use the data that we provide. This notebook loads and filters the corpus, and it even downloads and parses the contents of one of the Twine games included in the corpus.

To get started with the data immediately... [![launch binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/barrettrees/undergraduate_games_corpus/HEAD?filepath=ExampleUsage.ipynb)

This repository does not directly contain game source code, assets, and other project files. Permanent download links for these are included in the metadata we provide. Although all of the games included in this corpus are hosted on the [`ucsc_games_cmps80k` collection on eScholarship](https://escholarship.org/uc/ucsc_games_cmps80k), not every game in that collection is included in our corpus. The other games might not have been collected with the same informed consent protocol described in our paper. It might be tempting to run your analyses on the larger collection of games you can find elsewhere, please consider that you may be doing something that the contributors of those games never anticipated (and might not have given consent if they could have imagined it).

For more background, see [Lessons from archives: strategies for collecting sociocultural data in machine learning](https://dl.acm.org/doi/10.1145/3351095.3372829).

## Citing

    @inproceedings{anderson2021undergraduate,
      title={The Undergraduate Games Corpus: A Dataset for Machine Perception of Interactive Media},
      author={Anderson, Barrett R and Smith, Adam M},
      booktitle={Proceedings of the Thirty-Fifth AAAI Conference on Artificial Intelligence (AAAI-21)},
      year={2021}
    }

## Data Schema

The file `corpus.json` contains an JSON object mapping keys to values. Keys are globally unique archival resource keys ([ARKs](https://en.wikipedia.org/wiki/Archival_Resource_Key)) and values are objects describing games with the fields listed below:

 - permalink (link to human-readable page about the game)
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
