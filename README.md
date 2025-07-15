<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheMostAncientDream-1864/TheMostAncientDream-1864/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TheMostAncientDream-1864/TheMostAncientDream-1864/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src=".github/workflows">
</picture>

###

<h1 align="center">Drugged Outliers</h1>

###

<p align="left">This project, titled “Drugged Outlier”, focuses on detecting and analyzing anomalous spikes (outliers) in weekly drug overdose deaths across U.S. states using early model-based provisional death estimates from CDC. The analysis aims to identify unusual surges in overdose mortality, which could signal critical public health events or emerging drug crises.<br><br>Using the official dataset of weekly predicted and actual deaths, the project flags weeks where actual overdose deaths exceed the predicted upper bound as outlier events. The analysis incorporates both temporal trends and state-wise distribution of these anomalies to support early intervention and decision-making.</p>

###

<p align="left">The raw dataset used in this project is available for public access via the official CDC portal: https://data.cdc.gov/National-Center-for-Health-Statistics/Early-Model-based-Provisional-Estimates-of-Drug-Ov/v2g4-wqg2/about_data</p>

###

<p align="left">Analysis of drug overdose death data across all U.S. states identified **147 significant overdose death spikes (drugged outliers)** based on a rolling 4-week upper bound prediction model. These spikes were detected both spatially and temporally, indicating unusual event patterns in certain regions.<br><br>The states with the highest number of spikes include the **United States (national level) with 63 outliers**, followed by **Florida with 14**, **Ohio with 10**, **California with 8**, **Pennsylvania with 7**, and **New York with 6**. Meanwhile, more than **20 states** recorded no overdose death spikes at all during the observation period.<br><br>Key findings reveal that spikes tend to occur in states with large populations and regions vulnerable to drug-related issues. Spatial analysis indicates a concentration of spikes in the eastern and southern parts of the United States. The rolling average-based predictive model proved effective in identifying crisis periods by detecting actual deaths that exceeded the model’s upper prediction limit.<br><br>These findings can be utilized by public health authorities for early detection of overdose crises and to prioritize intervention efforts in high-risk states.</p>

###

<p align="left">Initially, I used the IBM Granite 3.3-8B-Instruct model to assist in the analysis of this dataset. However, during the implementation process, the model encountered technical difficulties, particularly in output parsing and basic command execution such as data summarization or visualization (e.g., when displaying data or creating plots). As a result, I was unable to optimally implement the new LLM-related knowledge directly in Python.</p>

###
