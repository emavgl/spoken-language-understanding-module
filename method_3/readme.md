### To run:
`bash run.sh`

### Results
The script processes the test files using 1 to 5-grams and the following smoothing methods: witten_bell, absolute, katz, kneser_ney, presmoothed, unsmoothed.

It creates files stats/stat-*n*.txt where *n* is the number of grams used.
Each file contains the outputs of the script conlleval.pl.

method_3 preprocess training data, appending O-word to the O-concepts.
