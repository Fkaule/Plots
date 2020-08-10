# Plots
Various Jupyter Scripts for plotting

> git rev-list --left-right master...refs/remotes/origin/master

# create_csv_Linesearch_by_extension

**What it does**:
- searches for numbers within all files in directory with specified extension `findending` e.g. within an output file of a simulation

1. Search for lines (Parameter: `findtext`)
2. Within the line the number will be found between `findvalue_start` and `findvalue_end`
3. The data will be saved to `data.csv` and the labels can be renamed from the filename between `filename_to_label_start` and `filename_to_label_end`
