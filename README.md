Markov Chain Text Generator
This is a simple Flask-based web application that generates random text using a Markov chain model. The application takes a sample text input from the user, builds a Markov chain, and generates a sequence of words based on probabilistic transitions.

Features
✅ Build a Markov chain from user-provided text
✅ Generate random text based on the learned Markov model
✅ Customizable text length for generated output
✅ Simple web interface built with Flask

Tech Stack
Python

Flask

HTML & Jinja2 Templates

Collections (defaultdict)

Random

How It Works
The user enters a sample text input in the web interface.

The application constructs a Markov chain by mapping each word to its possible successors.

A random starting word is selected, and subsequent words are generated based on the chain.

The generated text is displayed on the result page.
