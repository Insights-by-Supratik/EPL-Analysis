# A Comprehensive Analysis of English Premier League (EPL)

The English Premier League (EPL) is one of the most competitive football leagues in the world, and analysing its rich history of matches, teams, and players has always fascinated me. Leveraging Power BI, I embarked on a journey to create a comprehensive report that encapsulates 22 years of EPL data (2000-01 to 2021-22). This project is a testament to the power of data analytics in deriving meaningful insights from raw data and my personal growth in exploring the capabilities of Power BI.

**Power BI Report:** Check out the interactive report [here](https://app.powerbi.com/view?r=eyJrIjoiYjgyZWJkZjgtOTljOS00ODJlLTg0MzYtZmM5ODkxODcwODYyIiwidCI6IjA5YWJlYzJmLWM4NmItNDU1OC1hM2I1LTEyNWQ2NTU5NjViMSJ9&pageName=9581c30c0900f00d30fb)

## Objectives and Overview
This report aims to provide football enthusiasts, analysts, and researchers with a deep dive into the EPL’s historical data. With nine meticulously crafted pages, the report captures:
* Overall Snapshot of the League
* Yearly League Tables
* Progression of Big 6 Clubs
* Detailed Team Analysis
* Head-to-Head Team Comparison
* Team Insights with Visual Narratives
* Match Highlights
* Referee Analysis

## Data Preparation and ETL Process

### Data Source:
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/saife245/english-premier-league) and contained match statistics, team performances, and referee data. However, the raw data was far from analysis-ready.

### ETL Process with Power Query
Using Power Query, I:
* Extracted multiple CSV and Excel files to build a robust dataset.
* Transformed the data by removing inconsistencies, handling null values, and standardising formats.
  * Date Formats: Unified match dates to dd-mmm-yyyy.
  * Calculated Columns: Created custom columns for enhanced analysis.
  * Appended multiple year datasets into a single consolidated dataset.
* Loaded clean data into Power BI for modelling and visualisation.
The transformation stage was pivotal in ensuring accuracy and consistency across all analyses.

## Data Modelling
I built a relational data model with the following key tables:
* Team Stats: Fact table containing details of all matches played in 22 seasons.
* Champions: Dimension table for EPL champions over 22 seasons.
* Referee Stats: Summarized table for analysing referees data.

Relationships were established with appropriate cardinalities, and measures were created using advanced DAX for dynamic analysis. Examples include:
* Measures: Position, Individual Statistics, H2H Statistics, etc.
* Dynamic Headers: To display match details dynamically based on filters.
* Custom Aggregations: For home vs away analysis.
* Conditional Tooltips: For interactive match highlights.

## Detailed Insights

### Snapshot
The Snapshot page offers an overarching view of EPL matches played across the 22 seasons. Key metrics include:
* Average Goals per Match: Providing insight into the league's attacking trends.
* % Shots on Target and Goal Conversion: Reflecting teams' attacking efficiency.
* Yellow and Red Card Percentages: Highlighting disciplinary trends over the years.
Users can filter by team and season to drill down into specific areas of interest. This page serves as the gateway to understanding the league's overall dynamics.

### League Table
The League Table page presents the final standings for each EPL season. It highlights critical tiers such as:
* Champions: The team that topped the table.
* UCL and UEL Qualifiers: Teams securing European football spots.
* Relegation Zone: Teams dropping out of the league.
This visual is colour-coded for clarity and is an essential reference for fans tracking the league's competitive nature.

### EPL Big 6
This page tracks the progression of the league's most prominent clubs—often termed the "Big 6" over the years. A line chart visually narrates their rankings across seasons, offering a clear perspective on dominance, rivalry, and the occasional underdog story.

### Team Analysis
The Team Analysis page provides a deep dive into individual team performances. Users can explore:
* Home vs Away Performance: Understanding how teams fare in different settings.
* Attack vs Defense Performance: Understanding how teams fare in different departments.
* Seasonal Trends: Analysing improvements or declines in specific metrics across 22 seasons.
This page combines multiple visuals to present a detailed, interactive view of any team's individual performance.

### Team Comparison
The Team Comparison page allows users to juxtapose two teams and analyse their:
* Overall Statistics: Goals, clean sheets, points, and many more.
* Head-to-Head Records: Who edges out in direct encounters.
* EPL Trophies Won: Tracking historical successes.
This comparative analysis is instrumental for fans and analysts delving into rivalries.

### Team Insights
Team Insights offer graphical representations of team performances over 22 seasons. Metrics like goals scored, goals conceded, points earned, and cards received are visualised for clarity. Users can also compare home and away performances, uncovering patterns and anomalies.

### Match Highlights
This interactive page displays all matches played between two teams. A bubble chart represents each game, with bubble sizes proportional to the goals scored in that match. Hovering over the bubbles reveals detailed match highlights, making it a one-stop page for reliving iconic games.

### Referee Analysis
This page analyses referees who officiated over 150 matches in the league. It provides insights into their:
* Card Distribution Patterns: Average yellow and red cards given per game.
* Impact on Matches: Highlighting trends in refereeing styles.

## Design and Interactivity
I designed visuals with Custom Visuals focussing on an User-Centric Design. Highlights were:
* Consistent themes and layouts.
* Conditional formatting for dynamic storytelling.
* Interactive tooltips for granular insights.
* Intuitive Filters and Slicers for Season, and Team.
* Responsive Dashboards which adapt seamlessly to user inputs.

## Challenges and Learnings
### Challenges
* Managing a dataset spanning 22 years comprising of 8,360 matches.
* Creating dynamic measures to handle complex relationships.
* Designing visuals that balance aesthetics and functionality.

### Learnings
* Mastered DAX functions for advanced calculations.
* Gained hands-on experience with Power Query for ETL processes.
* Learned to design user-friendly, interactive reports.

## Seeking Feedback
This project has been an incredible learning journey, but as someone comparatively new to Power BI, I know there’s always room for improvement. I’d love to hear from the community on:
* How can I optimise my DAX queries further?
* Are there better ways to visualise the data for greater impact?
* Any suggestions for additional analyses or features?
Your feedback and suggestions will help me refine this project and grow as a data analyst.
