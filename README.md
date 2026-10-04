# IPL Cricket Data Analytics Project

This project is a beginner-friendly IPL cricket analysis dashboard built using Python and data analytics libraries. It explores match outcomes, toss decisions, team performance, and win trends using a sample IPL dataset.

## Project Goals
- Analyze IPL match results from a sample dataset
- Compare team win counts and trends
- Study toss decision impact on match outcomes
- Visualize key insights using charts
- Provide a clean Python analytics template for extension

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```text
ipl-cricket-analysis/
├── README.md
├── requirements.txt
├── data/
│   └── ipl_matches_sample.csv
├── src/
│   └── ipl_analysis.py
├── outputs/
│   └── team_wins.png
└── .gitignore
```

## Installation

```bash
git clone https://github.com/SakshiGhutukade-8146/ipl-cricket-analysis.git
cd ipl-cricket-analysis
python -m venv .venv
source .venv/bin/activate   # Linux/macOS
# .venv\Scripts\activate    # Windows
pip install -r requirements.txt
```

## Run the Analysis

```bash
python src/ipl_analysis.py
```

This script will:
- load the sample IPL dataset
- clean and prepare the data
- compute team win counts
- compare toss winners vs match winners
- generate charts and save them in the `outputs/` folder

## Sample Insights Covered
- Which teams won the most matches?
- Do toss winners tend to win more matches?
- How do teams perform across the seasons in the dataset?
- How does the toss decision affect outcomes?

## Data Source
The project uses a sample IPL match dataset included in `data/ipl_matches_sample.csv` for demonstration and learning. You can replace it with a larger real dataset to scale the analysis.

## Future Enhancements
- Add player-level performance analysis
- Include bowling and batting metrics
- Build a dashboard in Streamlit or Power BI
- Add predictive modeling for match outcomes
- Use real IPL datasets from Kaggle or official sources

## License
This project is provided for educational and learning purposes.
