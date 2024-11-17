# Generative AI Research Analysis

## Project Overview
In the rapidly advancing field of generative AI, understanding key research themes and their connections is vital. This project leverages the Web of Science (WoS) database to retrieve and analyze publications. Using keyword co-occurrence networks, the project maps the intellectual structure and identifies core themes and trends in generative AI research.

## Features
- **Data Retrieval**: Extracts generative AI-related publications from the WoS database.
- **Keyword Network Analysis**: Constructs co-occurrence networks based on author-provided keywords.
- **Trend Identification**: Highlights primary research themes and emerging trends.
- **Data Visualization**: Provides visual representations of keyword networks and thematic interconnections.

## Requirements
To run the project, ensure the following Python libraries are installed:
- `numpy`
- `pandas`
- `matplotlib`
- `networkx`
- `seaborn`

## Code Workflow
1. **Data Collection**:
   - Use Web of Science to retrieve publication data with relevant generative AI search terms.
2. **Data Cleaning**:
   - Process and prepare the retrieved data for analysis.
3. **Keyword Network Construction**:
   - Generate a co-occurrence network from author-provided keywords.
4. **Network Analysis**:
   - Perform weighted network analysis to uncover central themes.
5. **Visualization**:
   - Visualize the network and interpret research trends.

## How to Run
1. Clone this repository and navigate to the project directory.
2. Ensure all required Python libraries are installed.
3. Import the dataset retrieved from Web of Science into the working directory.
4. Run the Python notebook (`.ipynb` file) step-by-step:
   - Load the data and clean it.
   - Construct and analyze the keyword co-occurrence network.
   - Generate visual outputs and interpret results.

## Results
- Keyword co-occurrence networks showing thematic interconnections.
- Insights into key themes and emerging trends in generative AI research.
- Visualizations and statistical summaries of the research landscape.

## Deliverables
- **Python Notebook**: Contains the full analysis, including text, code, and visual outputs.
- **Visualizations**: Network graphs and trend summaries.

## Contributing
Contributions are welcome! You can:
- Improve data cleaning or visualization techniques.
- Suggest new methods for analysis.
- Provide feedback to refine the workflow.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
