# Computational exploration of magical and divinatory language

SFPC Code Societies 2020 / [Allison Parrish](http://www.decontextualize.com/)

## Description

Words have power that arises not just from their meaning but from their
material. Some words, those "somewhere between the 'legible' and 'illegible,'
between the 'spirit world' and the 'human world'," as scholar James Robson
writes, "express or illustrate ineffable meanings and powers that defy...
traditional modalities of communication." Some words, that is, are magic. In
this workshop, we will use techniques in computational text analysis and text
generation to better understand how magic words work, and coin new magic words
of our own. In the first part of the session, we consider magic words as
islands in a largely unexplored infinite space of potential linguistic
expression—a space that can be explored computationally in order to uncover new
magic words with new affordances. In the second part of the session, we
consider systems of divination (in particular, Tarot) as ad-hoc ontologies for
dividing the world into comprehensible categories. We then analyze the
"semantic space" of these divinatory ontologies, and endeavor to create new
divinatory systems with new ontologies that reflect our own worldviews.
Technologies covered include cryptography, phoneme-to-grapheme models,
generative adversarial networks, text clustering, predictive language models
and variational autoencoders. No previous programming experience required.

## Requirements

Participants will need to bring a laptop computer running a contemporary
desktop operating system (Windows, Linux, or MacOS). We'll be using the
[Anaconda](https://www.anaconda.com/distribution/) distribution of the Python
programming language. Please install the Python 3.7 (64-bit) version of
Anaconda for your platform.

## Outline

### Session 01 (2020-01-08)

* A brief history of the magic word
* [Jupyter notebook
  tutorial](https://github.com/aparrish/rwet/blob/master/jupyter-notebook-tutorial.ipynb)
* [Just enough
  Python](https://gist.github.com/aparrish/50803e0ae51a2c6e775af36ea79be285)

Assignment: Invent or gather names/significations for ten (or more) oracle
deck cards to contribute to our collective corpus.

### Session 02 (2020-01-13)

* Python: [Speculative magic words workbook](magic-words-workbook.ipynb)
  (Manipulating strings, generating words with
  [Pincelate](http://pincelate.readthedocs.io))
* Python: [Cartomancy and semantic space](cartomancy-semantic-space.ipynb)

Assignment: Either (1) Produce an oracle deck using text generated with (or
inspired by) the tools discussed in class or (1) Produce a small "grimoire"
consisting of text generated with (or inspired by) the tools discussed in
class.

Things we didn't get to:

* [Variational autoencoders](https://github.com/aparrish/vae-lagging-encoder/)
  are a tricky but good way of generating text from a continuous space.
* A [GAN trained on bitmaps of
  words](https://github.com/aparrish/word-gan-book-generator) might be a good
  way to generate words that look magical. Feel free to use mine.

