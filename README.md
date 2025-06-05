# Lengow Data Engineering Assignment

## Overview
This repository contains my solution for Lengow's Data Engineer technical assignment. The project focuses on analyzing product data and market comparisons to demonstrate data engineering capabilities.

## Project Structure
```
/lengow-de/
├── data/                      # Raw data files
│   └── data_visualization_home_assignment.xlsx
├── notebooks/                 # Jupyter notebooks for analysis
├── sql/                      # SQL queries and schema
└── docs/                     # Documentation files
    ├── diagramExplanation.md
    └── erDiagram.md
```

## Tasks Completed
- [ ] Data model design and documentation
- [ ] Database schema creation
- [ ] Data loading and transformation
- [ ] Analysis and visualization
- [ ] Performance optimization

## Technologies Used
- Python 3.9+
- PostgreSQL
- Pandas
- Jupyter Notebook
- SQLAlchemy

## Data Model
The solution implements a relational database with three core tables:
- `client_products`: Client's product catalog
- `market_products`: Competitor product listings
- `matchings`: Relationship mapping between products

For detailed schema information:
- [Entity Relationship Diagram](docs/erDiagram.md)
- [Schema Documentation](docs/diagramExplanation.md)

## Setup Instructions
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Configure database connection
4. Run data import scripts

## Running the Analysis
```bash
jupyter notebook notebooks/analysis.ipynb
```

## Contact
For any questions regarding this implementation, please contact [Your Name].
