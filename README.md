# Predicting-Campaigns-and-Elections README

## Overview
The datasets provided in this assignment contain information on the contributions made to the campaigns of US politicians at both state and federal levels from 1989 to 2017. The data offers insights into the campaign-related behavior of contributors and the outcomes of these campaigns.

## Data Description
- **Period**: 1989-2017
- **Total Observations**: 288,080 contributors
- **Training Data**: 60% of all contributors (172,848 observations)
- **Test Data**: 40% of all contributors (115,232 observations)

## Datasets Included:
1. **Aggregated Campaign Contributor Data**:
   - `training_data.csv`
   - `test_data.csv`
   
2. **Bipartite Networks Between Contributors and Candidates**:
   - `all_candidates_state_bipartite_weighted_network.csv`
   - `federal_contributor_top100_contributors_network.csv`
   - `state_contributor_top100_contributors_network.csv`
   - `winning_candidates_state_bipartite_weighted_network.csv`
  

## Key Columns in Training and Test Data:
- `index`: Index value associated with contributors
- `winner_ratio`: Percentage of candidates who received a contribution and won their elections
- `general_sector`: Job sector of the contributor
- `city`: City of the contributor
- `zip_code`: ZIP code of the contributor
- `specific_sector`: Specific job sector of the contributor
- `state`: US state of the contributor
- `contributor_type`: Type of the contributor (individual or non-individual)
- `candidacy_count`: Number of candidacies invested by the contributor
... [and many more]

## Project Objective:
Develop a prediction model that predicts the number of cases based on the provided variables in the dataset. The model's performance will be evaluated using the RMSE cost function.
