# Gym

A piece of writing exercise equipment that shows the poet a piece of art and issues prompts designed to help the poet describe this artwork in vivid detail.

livewire version in this ☞[Google Colab Notebook](https://colab.research.google.com/drive/106iVNbVcgKBOBl7VZpImPvjNlaYPKLCl?usp=sharing)☜.  

***

This houses data that this notebook uses (via samsungknox.co). 

Recursive Ekphrasis Gym makes use of `(possessor,possessed)` relations mined from Project Gutenberg:

- [`mining_gutenberg_for_all_relations.ipynb`](https://github.com/kbooten/ekphrasisgym/blob/main/mining_gutenberg_for_relations.ipynb) documents how I extracted `(possessor,possessed)` tuples with SpaCy
- [`processing_pairs.ipynb`](https://github.com/kbooten/ekphrasisgym/blob/main/processing_pairs.ipynb) documents some further processing of these tuples, including [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) scoring
