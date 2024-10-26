.. These are examples of badges you might want to add to your README:
   please update the URLs accordingly

    .. image:: https://api.cirrus-ci.com/github/<USER>/nlptextprep.svg?branch=main
        :alt: Built Status
        :target: https://cirrus-ci.com/github/<USER>/nlptextprep
    .. image:: https://readthedocs.org/projects/nlptextprep/badge/?version=latest
        :alt: ReadTheDocs
        :target: https://nlptextprep.readthedocs.io/en/stable/
    .. image:: https://img.shields.io/coveralls/github/<USER>/nlptextprep/main.svg
        :alt: Coveralls
        :target: https://coveralls.io/r/<USER>/nlptextprep
    .. image:: https://img.shields.io/pypi/v/nlptextprep.svg
        :alt: PyPI-Server
        :target: https://pypi.org/project/nlptextprep/
    .. image:: https://img.shields.io/conda/vn/conda-forge/nlptextprep.svg
        :alt: Conda-Forge
        :target: https://anaconda.org/conda-forge/nlptextprep
    .. image:: https://pepy.tech/badge/nlptextprep/month
        :alt: Monthly Downloads
        :target: https://pepy.tech/project/nlptextprep
    .. image:: https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter
        :alt: Twitter
        :target: https://twitter.com/nlptextprep

.. image:: https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold
    :alt: Project generated with PyScaffold
    :target: https://pyscaffold.org/

|

===========
nlptextprep
===========


    One Step Python Package to preprocess text data for NLP tasks. This package is designed to clean, transform, and standardize text data, making it an ideal choice for applications in natural language processing, text analysis, and data cleaning.

Features
--------

    TextCleanerPy includes the following functions:

    to_lowercase: Converts the input string to lowercase for consistent text processing.

    remove_line_breaks: Replaces newline characters with spaces for better text flow.

    remove_punctuation: Strips punctuation except for dots in numeric values, currency symbols, and URLs.

    remove_stop_words: Removes English stop words (e.g., "the," "is") to focus on meaningful content.

    stem_text: Applies stemming to words while preserving URLs.

    remove_special_characters: Eliminates special characters, normalizing the text but preserving essential symbols.

    remove_encoded_data: Cleans encoded data patterns like hexadecimal codes and URL encodings.

    remove_tags: Strips HTML, XML, or other tags while maintaining spacing for seamless readability.



Installation
------------

.. code-block:: bash

   pip install nlptextprep

Usage
-----

.. code-block:: python

   from nlptextprep import preprocess_text

   text = "This is a sample text containing a #hashtag, an @mention, and line breaks.\nCheck it out!"
   cleaned_text = preprocess_text(text)
   print(cleaned_text)


.. _pyscaffold-notes:

Note
====

This project has been set up using PyScaffold 4.6. For details and usage
information on PyScaffold see https://pyscaffold.org/.
