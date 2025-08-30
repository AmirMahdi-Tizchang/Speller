# Speller

[![C](https://img.shields.io/badge/C-C_language-blue)](https://en.cppreference.com/w/c)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

**A Spell Checker in C**

Implements a spell checker that loads a dictionary into memory and checks the spelling of words in a text using efficient data structures like tries and hash tables.

## Demo

### Official CS50 Demo

![Speller Demo](docs/demo.gif)


## Features

- Efficient dictionary loading and lookup.
- Implements multiple data structures: hash tables, tries.
- Measures performance (load time, check time, memory usage).

## Setup

Compile the program with:

```bash
make speller
```

Run the program:

```bash
./speller dictionary.txt text.txt
```

## Project Structure

```
speller/
├── speller.c        # Main program
├── dictionary.c     # Dictionary implementation
├── dictionary.h     # Dictionary header
├── texts/           # Example text files
├── dictionaries/    # Example dictionaries
├── README.md
└── LICENSE
```

## License

MIT License. See [LICENSE](LICENSE) for details.
