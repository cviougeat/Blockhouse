# Blockhouse

1. Project Overview
   This work documents my application of the paper ’Cross-impact of Order flow imbalance in equity
markets’ to 5 selected stocks in the timeframe of a week.  I compute order flow imbalance metrics using limit
order book data and analyze their predictive power on returns. This work is done using the paper
”Cross-Impact of Order Flow Imbalance in Equity Markets” by examining whether cross-asset order flow imbalances
provide additional explanatory power for price movements.

2. Files structure
The Data folder contains the data extracted from data bento with one folder per equity studied.
In each equity_concat folder, files have been named with letters to ease the processing of files in alphabetical order.
The folders have the following structure:
Project Directory:
├── Data/
│   ├── [REDDIT]/
│      ├── [Into]/
│        ├── [Rdd_concat]/
│          ├── [a.csv.zst]
│          ├── [b.csv.zst]
│          ├── [c.csv.zst]
│          ├── [d.csv.zst]
│          ├── [e.csv.zst]
│   ├── [Solar]/
│      ├── [Into]/
│        ├── [Solar_concat]/
│          ├── [a.csv.zst]
│          ├── [b.csv.zst]
│          ├── [c.csv.zst]
│          ├── [d.csv.zst]
│          ├── [e.csv.zst]
│   ├── [Accolade]/
│      ├── [Into]/
│        ├── [Accolade_concat]/
│          ├── [a.csv.zst]
│          ├── [b.csv.zst]
│          ├── [c.csv.zst]
│          ├── [d.csv.zst]
│          ├── [e.csv.zst]
│   ├── [Ferrari]/
│      ├── [Into]/
│        ├── [Ferrari_concat]/
│          ├── [a.csv.zst]
│          ├── [b.csv.zst]
│          ├── [c.csv.zst]
│          ├── [d.csv.zst]
│          ├── [e.csv.zst]
│   ├── [Factset]/
│      ├── [Into]/
│        ├── [Factset_concat]/
│          ├── [a.csv.zst]
│          ├── [b.csv.zst]
│          ├── [c.csv.zst]
│          ├── [d.csv.zst]
│          ├── [e.csv.zst]
├── Blockhouse.ipynb
├── README.md
└── requirements.txt

4. Notebook precisions
The data for each stock is processed during the first phase of the notebook to extract it from the zipped format.
The notebook directly accesses the folders of data referenced at the beginning of the notebook.
The notebook contains the visualization of each step with a format adapted to the context. 
