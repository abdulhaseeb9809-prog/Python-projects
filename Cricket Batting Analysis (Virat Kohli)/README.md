# Virat Kohli: Decoding a Cricket Legend (Career Analysis)

## The Problem: What Drives Elite Consistency?

In professional sports, "greatness" is often discussed in terms of passion and talent, but rarely
in terms of data. For Virat Kohli, his career is often split into two halves: the talented youngster
and the fitness-obsessed "Chase Master."

The goal of this project is to go beyond the commentary and use hard data to answer:

- Was there a real technical transformation in 2012?
- Does he actually perform better under the pressure of a second-innings chase?
- How have his weaknesses (dismissal patterns) evolved as opposition teams studied him?

## What I Analyzed

Using a comprehensive dataset of Kohli’s batting innings, I explored:

- Performance Under Pressure: Comparing his reliability in the 1st vs. 2nd innings.
- The 2012 Transformation: Statistically validating the "before and after" of his career pivot.
- Technical Vulnerabilities: Mapping out exactly how he gets out and identifying his "bogey" teams.
- Consistency Metrics: Using 5-point summaries and distributions to see how he builds his innings.

## Key Findings & Visuals

### 1. The 2012 Technical Pivot

Graph Name: runs_transformation_boxplot.png 

By comparing scores before and after 2012, the data shows a clear shift. His "floor" 
(the minimum expected runs) rose significantly, proving he eliminated the low-score 
patterns of his early career.


### 2. The Master of the Chase

Graph Name: innings_performance_comparison.png 

Visualizing 1st vs. 2nd innings performance confirms his reputation. He isn't just a high scorer; 
he is more efficient and has a higher 'Not Out' percentage when chasing a target.


### 3. Opposition Strategy & Dismissals

Graph Name: dismissal_pattern_heatmap.png 

This heatmap shows how different international teams have tried to "solve" Kohli. While some teams
rely on pace to catch him out, others use specific fielding traps that have evolved over his 
10+ year career.


### 4. Yearly Growth Trends

Graph Name: yearly_run_trend_line.png 

This shows his peak years and how his strike rate actually increased even as he took on the 
responsibility of anchoring the team in the middle order.


## Conclusion & The Verdict

After analyzing every run and dismissal, the data reveals a clear "solution" to his success: Adaptability.

### The Final Verdict:

1. The Transformation was Structural: The 2012 shift wasn't just about fitness; the data 
   shows his "Balls Faced" per innings increased, meaning he developed the patience to 
   wait for the right delivery.

2. The Chase Master Label is Accurate: Statistically, Kohli is a lower-risk player in the 
   2nd innings, making him the most reliable "anchor" for a chasing team in the modern era.

3. Opposition Decay: While teams found patterns to get him out (like specific caught-out
   positions), Kohli's ability to adjust his batting position (Q14) allowed him to stay
   ahead of international scouting reports.

## Technical Skills Demonstrated:

- Data Cleaning: Handling missing values and transforming year-based data.
- Advanced Statistics: 5-point summaries, mean/median comparisons, and outlier detection.
- Strategic Visualization: Using Boxplots, Heatmaps, and KDE plots to explain sports trends.
- Feature Engineering: Creating the "Post-2012" category to test a specific hypothesis.

## How to Run:

- Clone the repository.
- Ensure you have the libraries from requirements.txt installed.
- Open cricket batting analysis virat.ipynb to view the full insights.
