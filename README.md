A Python-based analytical dashboard visualizing key metrics from the 2024 Indian Lok Sabha elections, including party performance, candidate margins, and vote distribution.

![image](https://github.com/user-attachments/assets/efe4b08f-3a1e-41da-95a2-1b5c02126b2c)


## Project Overview
This project analyzes the 2024 Lok Sabha election results to provide insights into:
- Margin of victory for parties and candidates
- Seat distribution across political parties
- Performance of prominent leaders
- Vote share trends and trailing parties

## Features
### Party Performance
- Total seats won by each party
- Vote margin distribution (highest/lowest)
- Party-wise vote percentage (pie/donut charts)

### Candidate Analysis
- Comparison of key leaders:
  - Rahul Gandhi
  - Narendra Modi
  - Amit Shah
- Constituency-level performance
- Victory margin histogram

### Trend Visualization
- Top 10 trailing parties by:
  - Votes
  - Seats
- Interactive bar charts and histograms

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/chandanneralgi/Indian-Loksabha-Election-2024-Result-Data-Analysis.git
   cd Indian-Loksabha-Election-2024-Result-Data-Analysis

    Install dependencies:
    bash
    Copy

    pip install pandas matplotlib seaborn jupyter

Usage

    Prepare your data:

        Place election data in data/election_results_2024.csv

        Required CSV format:
        csv
        Copy

        Constituency,Leading Party,Margin,Leading Candidate,Trailing Party

    Run the analysis:

        For script version:
        bash
        Copy

        python election_analysis.py

        For Jupyter Notebook:
        bash
        Copy

        jupyter notebook "Loksabha Election 2024 Result Data Analysis.ipynb"

    View results:

        Visualizations will open in separate windows

        Close each visualization to proceed to the next

Project Structure
Copy

Loksabha-Election-2024-Result-Data-Analysis/
│
├── Loksabha Election 2024 Result Data Analysis.ipynb  # Jupyter notebook
├── data/                                              # Dataset directory
│   └── election_results_2024.csv                      # Election data
├── README.md                                          # This documentation
└── (Generated visualizations will appear during execution)

Key Findings & Visualizations
Analysis Type	Visualization Example
Seats Won by Party	Seats Chart
Victory Margins	Margin Histogram
Leader Comparison	Leaders Analysis
Contributing

    Fork the repository

    Create your feature branch:
    bash
    Copy

    git checkout -b feature/new-analysis

    Commit changes:
    bash
    Copy

    git commit -m 'Add innovative visualization'

    Push to branch:
    bash
    Copy

    git push origin feature/new-analysis

    Open a pull request

License

MIT License. See LICENSE for details.
Acknowledgements

    Built with: Python 🐍, Pandas, Matplotlib, Seaborn

    Data Source: Election Commission of India (sample data)

    Inspired by: Democratic election analysis methodologies




