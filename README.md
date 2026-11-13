# pandas Game Score Analysis

A beginner data analysis project using pandas to clean fictional
game scores, summarize player performance, and visualize results.

## Tools

- Python
- Jupyter Notebook
- pandas
- Matplotlib

## Dataset

The original dataset contains seven rows representing scores for
three players across two rounds. It includes one missing score
and one exact duplicate record.

## Data Cleaning

- Inspected the dataset and counted missing values.
- Removed one exact duplicate.
- Excluded one row with a missing score.
- Preserved the original data in a separate DataFrame.

Five valid records remained after cleaning.

## Analysis

Grouped the cleaned records by player and calculated:

- Average score
- Lowest score
- Highest score
- Number of recorded games

Sorted players by average score and created a bar chart.

## Results

| Player | Average | Lowest | Highest | Recorded Games |
|--------|---------|--------|---------|----------------|
| Pixel  | 89      | 88     | 90      | 2              |
| Nova   | 80      | 75     | 85      | 2              |
| Echo   | 65      | 65     | 65      | 1              |

Pixel had the highest observed average. Echo's average was based
on only one recorded score because the other score was missing.

## Limitations

The dataset is small and fictional. Echo's missing score makes
comparisons incomplete - including that score could raise or lower
their two-round average. These results do not establish future
player performance.

## Files

- `pandas_score_analysis.ipynb` — analysis, visualization, and findings
- `clean_scores.csv` — cleaned records
- `player_summary.csv` — aggregated results, including player names

## Run the Project

Install the required packages:

    pip install pandas matplotlib jupyterlab

Start JupyterLab:

    jupyter lab

Open `pandas_score_analysis.ipynb` and run all cells from top to
bottom. Running the notebook also generates the CSV exports.

## Learning Context

Completed as a beginner learning project.
I wrote and executed the analysis code, interpreted the results,
and verified that the notebook runs from a restarted kernel.
