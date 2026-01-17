# py-matrix-01

A small Python tool that computes text statistics for matrix.

## Goal
- Provide quick text metrics for matrix documents.
- Report top word frequencies for fast inspection.

## Usage
python main.py data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
