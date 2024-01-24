# cs50_ai_crossword

This is an AI program that generates crossword puzzles.
It forms part of the projects for the course [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2024/).

The program has below listed dependency:
- [Pillow](https://pypi.org/project/pillow/) Pillow is the friendly PIL fork. Python Imaging Library adds image processing capabilities to your Python interpreter.

## Usage

All the following commands assume that your current working directory is _this_ directory. I.e.:

```console
$ pwd
.../cs50_ai_crossword
```

1. Install the required Python package (Pillow) for the project:

   ```sh
   pip3 install Pillow
   ```
   
1. Run the application:

   ```sh
   py generate.py data/structure1.txt data/words1.txt output.png
   ```