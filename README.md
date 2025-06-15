Markov Chain Text Generator
This Python project implements a simple text generation algorithm using Markov Chains. It creates a statistical model that predicts the probability of the next word based on the previous word(s), and then generates random text sequences using that model.

Features
Word-level Markov Chain model

Configurable state size (order)

Generates multiple random text sequences

Uses a built-in sample paragraph as the source text

Simple and beginner-friendly code structure

How It Works
The input text is split into word sequences.

A Markov Chain dictionary is built where keys are word tuples and values are possible next words.

The generator starts with a random state and repeatedly selects the next word based on the learned probabilities.

Sample Text Used
The script uses the following sample paragraph as input:

Machine learning is a method of data analysis that automates analytical model building. 
It is a branch of artificial intelligence based on the idea that systems can learn from data, 
identify patterns and make decisions with minimal human intervention.

How to Run
Clone the repository or download the script file.


Configuration
You can adjust the following variables in the script:

n: Order of the Markov Chain (e.g., 1 for unigram, 2 for bigram)

sequence_count: Number of sequences to generate

sequence_length: Number of words in each generated sequence

Example Output
Sequence 1:
It is a method of data analysis that systems can learn from data...

Sequence 2:
Machine learning is a method of artificial intelligence based on the...

Requirements
Python 3.x (no external libraries required)
