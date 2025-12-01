# IPL Data Analysis (2008–2019)

This repository contains an exploratory data analysis (EDA) project on Indian Premier League (IPL) data to identify the factors that influence match outcomes, team dominance, and player impact.

The goal of this project is to go beyond surface-level statistics and uncover what actually drives success in T20 cricket.

---

## Project Structure

IPL_EDA/  
│  
├── csv data/  
│ ├── matches.csv  
│ └── deliveries.csv  
│  
├── IPL_Data_Analysis.ipynb  
│  
├── output/  
│ ├── IPL_merged.csv  
│ ├── Plots  
│  
└── README.md


---

## Dataset Description

Two datasets are used for analysis:

### matches.csv
Contains match-level information:
- Season year
- Teams
- Venue
- Toss winner
- Match winner
- Player of the match

### deliveries.csv
Contains ball-by-ball match data:
- Over and ball number
- Batsman & bowler
- Runs
- Wickets
- Extras

These datasets are merged on `match_id` to enable detailed, delivery-wise analysis within each match context.

---

## Analysis Performed

The notebook includes detailed analysis on:

- Team performance comparison
- Orange Cap winners (Top run scorers)
- Purple Cap winners (Top wicket takers)
- Bowling economy rates
- Batting strike rates
- Death-overs impact
- Toss influence study
- Chase vs Defend comparison
- Win percentage by team

All figures and output files are saved inside the `output/` directory.

---

## Key Findings

- Winning the toss does not significantly impact match outcomes.
- Economy rate is a stronger indicator than raw wicket count.
- Death overs have the greatest influence on match results.
- Consistent teams outperform star-dependent teams.
- Run rate reflects performance better than total runs.
- Chasing can provide situational advantage but is not guaranteed success.

---

## How to Run

1. Ensure the CSV files are in the `csv data/` folder.
2. Open the notebook:
            IPL_Data_Analysis.ipynb
3. Run all cells from top to bottom.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Output Data

All generated files, figures, and datasets are stored in:

output


---

## Future Work

Planned improvements include:

- Feature engineering
- Match outcome prediction model
- Player impact scoring system
- Powerplay and death-over modelling

---

## Author

Ayan Inamdar  
AI & Data Science Student

---

## Disclaimer

This analysis is for educational and learning purposes only.  
The dataset used is publicly available.


