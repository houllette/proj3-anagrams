# proj3-anagrams
Vocabularly anagrams game for primary school English language learners (ELL)

## Overview

A simple anagram game designed for English-language learning students in
elementary and middle school.  
Students are presented with a list of vocabulary words (taken from a text file)
and an anagram.  The anagram is a jumble of some number of vocabulary words, randomly chosen.  Students attempt to type vocabularly words that can be created from the  
jumble.  When a matching word is typed, it is added to a list of solved words.

The vocabulary word list is fixed for one invocation of the server, so multiple
students connected to the same server will see the same vocabulary list but may
have different anagrams.

## Authors

Initial version by M Young
Revised version by H Oullette

## Start the application

If you have all dependencies installed, you can simply run "python3 flask_vocab.py"

Otherwise, make sure the python3 venv is installed, then inside of the root folder for this project, "make configure && make run"


## To run automated tests
* `nosetests`

There are currently nose tests for vocab.py, letterbag.py, and jumble.py.
