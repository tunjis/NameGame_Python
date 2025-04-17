# The Name Game <a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36" height="36" alt="Python"/> **Python** </a>&nbsp;

A simple Python script that generates the rhyme for Shirley Ellis' "The Name Game" song based on a user-provided name. Intended for use in Google Colab or a similar notebook environment.

## Features

* Generates the classic Name Game rhyme structure.
* Applies the special variations for names beginning with B, F, or M based on common interpretations.
* Provides an interactive command-line style interface within the notebook's output cell.
* Simple exit command ('end' or empty input) to stop the game.

## 🛠 Usage

Click the badge to open this notebook directly in Google Colab:

      [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPOSITORY/blob/main/your_notebook_name.ipynb)

## How the Rhyme Works

The script uses a simplified rule to determine the rhyming part (the "suffix") of the name needed for the song verses:
* If the name starts with a vowel (a, e, i, o, u), the entire lowercase name is used as the suffix.
* If the name starts with a consonant, the suffix is created by dropping only the first letter of the lowercase name.

*Note: This simple rule works reasonably well for many names but may not perfectly match the phonetic rules for all edge cases or consonant combinations (like 'Sh', 'Th').*

## Example Interaction (in Colab Output)

After running the code cell, the interaction below it will look something like this:
