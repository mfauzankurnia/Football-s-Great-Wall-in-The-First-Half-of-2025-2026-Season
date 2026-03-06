-- The Bigger Picture

Project Title: Football's Great Wall in The First Half of 2025-2026 Season

Dataset: Football Player Stats (2025-2026). Source: www.kaggle.com (real data)

Programming Language: Phyton

Software: Microsoft Excel, Google Colab and Looker Data Studio

Method: Exploratory Data Analysis

Scope Analysis: This analysis focus on goalkeepers competing in Europe's top five leagues: Premier League, La Liga, Serie A, Bundesliga and Ligue 1 with minimum playing time >11 matches.

Background: Football is a collective sport where individual roles are shaped by team context and tactical structure. A single metric or perspective to do performance evaluation could be biased.

Objective: To analyze goalkeepers performance comprehensively by combining individual action contribution, collective defensive output and build-up involvement.

----

-- The Way It Processed

Data Scoping: Leagues selection based on format and level of competitiveness similarity in order to get accurate analysis and reduce the risk of bias.

Data Filtering: Curating the relevant goalkeepers based on median of minutes played as baseline to avoid back-up/rotation/injury performance bias.

Data Normalization:
- Defining key metrics of goalkeepers then normalize key metrics value per-match (90 minutes played).
- Grouping key metrics based on type of action in the field and define weighted distribution by each group.
- Index Construction: Defining goalkeepers performance index using PCA.

Core Analysis:
- Tier segmentation based on index ranking model.
- Key metrics decomposition by tier.
- Key metrics correlation.

----

-- Output

Please check the file "Football's_Great_Wall_in_The_First_Half_of_2025_2026_Season.png" to see the visualized analysis results.

----

-- How to Run Analysis Code

- Download all files "players_data-2025_2026.csv", "Football's_Great_Wall_in_The_First_Half_of_2025_2026_Season.ipnyb" and "football's_great_wall_in_the_first_half_of_2025_2026_season.py".
- Upload file "Football's_Great_Wall_in_The_First_Half_of_2025_2026_Season.ipnyb" or "football's_great_wall_in_the_first_half_of_2025_2026_season.py" in Google Colab or other tools as preferred.
- Run all the code.
