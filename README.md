# PGN File Splitter

## Overview

This Python script allows you to split a large PGN (Portable Game Notation) chess file into smaller, manageable chunks while ensuring that complete games are preserved. The script is useful when dealing with large PGN files, allowing you to create smaller files for easier handling and processing.

## Features

- Splits a PGN file into chunks of a specified size (default: 200 MB).
- Ensures that whole chess games are kept together, avoiding splitting a game across chunks.
- Creates a separate output file for each chunk.
- Easy to use and customize for different chunk sizes or file paths.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies (if not already installed) from the requiremtns.txt file: `pip install -r requirements.txt`
3. In the script, `pgn_splitter.py`, enter your desited path to input .pgn file and the output folder where the chunks would be saved.
4. The default size of chunks is 200 MB. If you want to change , change the value of `chunk_size_mb` in the script, `pgn_splitter.py`
5. Run the script.

```bash
python pgn_splitter.py --input-file your_large_file.pgn --output-folder output_chunks --chunk-size-mb 200
```
## Complete Explanation

The complete project details and explanation can be found  **[here](https://codingaunty.com/python-project-pgn-file-splitter/)**.
