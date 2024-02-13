# FOOTBALL ANALYSIS

Group 3 set out to analyze a dataset from one football (soccer) match to understand if any key themes or insights could be found. The team began the analysis with some summary statistics, but then delved deeper into various visualizations or correlations that could "bring the match to life". Some key analyses conducted include:
- **Spatial analysis:** Identify how different players on each team positioned themselves during the game
- **Event analysis:** Determine the success rate of certain "events" and their impact throughout the match
- **Temporal analysis:** Understand how the ball position varied throughout the game
- **Visual analysis:** Build a view that used the raw data to showcase a re-enactment of the match
--------------------------------------------------------------------------------------
The team approached this analysis in the following manner:

1) *What data do we have?*
2) *What can we do with this data?*
3) *What do these analyses inform?*
4) *What additional analyses could be performed if more data was available?*
--------------------------------------------------------------------------------------
The following sections break down how the team approached each of these questions:
1. **What data do we have?**
We had three files to work with (along with corresponding datapoints tracked):
    - ***Raw Events data***
        - 1,746 rows x 14 columns
        - Column Names
            - Team
            - Type
            - Subtype
            - Period
            - Start Frame
            - Start Time [s]
            - End Frame
            - End Time [s]
            - From
            - To
            - Start X
            - Start Y
            - End X
            - End Y      
    - ***Raw Tracking data for the Home Team***
        - 145,007 rows x 33 columns
        - Column Names
            - X-coordinate positions for 14 home team players and the ball
            - Y-coordinate positions for 14 home team players and the ball
    - ***Raw Tracking data for the Away Team***
        - 145,007 rows x 33 columns
        - Column Names
            - X-coordinate positions for 14 away team players and the ball
            - Y-coordinate positions for 14 away team players and the ball
2. **What can we do with this data?**
The team conducted quite a few analyses on the dataset to derive some key findings:
    - ***Spatial analysis***
        -   | **Analyses Conducted** | **Data Manipulated** |
            | ---------------------- | -------------------- |
            | Average distance to ball per player | Created new series to calculate each player's average distance to the ball using X-Y coordinates provided |
            | Average field position per player | Calculated average position per player on X and Y axis |
            | xxx | xxx |
            | xxx | xxx |
    - ***Event analysis***
        -   | **Analyses Conducted** | **Data Manipulated** |
            | ---------------------- | -------------------- |
            | Average distance run per team per half | Created new series to calculate distance "Z" from (x<sub>1</sub>,y<sub>1</sub>) to (x<sub>2</sub>,y<sub>2</sub>) |
            | Average distance per shot (goal, on-target, off-target) | Filtered and grouped data to compare success rate per average distance of shot |
            | Average time ball held per team per half (per event) | Created new series to calculate difference between End Time and Start Time to determine amount of possession |
            | Average amount of time ball held by each player (per event) | Grouped and summed data to determine amount of time each player possessed the ball during game events |
            | Average success Rate by Player and team | Classified events and player contribution into success, fial or neutral based on the outcome. This helped chart a post game picture of individual player and team performance   |
            | Team succeess rate trend over time | Sketched out the average success rate of both teams over time as a measure of stamina over the course of the game  |
    - ***Temporal analysis***
        -   | **Analyses Conducted** | **Data Manipulated** |
            | ---------------------- | -------------------- |
            | xxx | xxx |
            | xxx | xxx |
            | xxx | xxx |
    - ***Visual analysis***
        -   | **Analyses Conducted** | **Data Manipulated** |
            | ---------------------- | -------------------- |
            | xxx | xxx |
            | xxx | xxx |
            | xxx | xxx |
3. **What do these analyses inform?**
    - Observed a strong correlation between time held and distance ran, which runs counter to our initial thinking since we had the initial assumption that the team that ran the most was likely chasing the ball more often, rather than holding it longer
    - Home team maintained possession on the away team's side of the pitch on average, with more home players being closer to the ball than away players on average
4. **What additional analyses could be performed if more data was available?**
    - Quantify homefield advantage









--------------------------------------------------------------------------------------

<!-- The Metrica Sports sample data you mentioned provides a rich resource for soccer analytics, offering detailed tracking and event data from soccer matches. The data's structure, with coordinates ranging from 0 to 1 on each axis and standardized field dimensions (105x68 meters), facilitates various analyses. The synchronization of tracking and event data allows for in-depth analysis of player movements, team formations, and specific game events such as passes, shots, and fouls.

Given the details provided:

1. **Spatial Analysis**: The data enables spatial analysis of player positions and movements. For instance, understanding how players use the field space during different phases of the game can provide insights into team strategies.

2. **Event Analysis**: With the detailed event types and subtypes, one can analyze the frequency, success rates, and patterns of various events like passes, shots, and defensive actions. This can help in assessing team and player performance.

3. **Temporal Analysis**: By considering the time information for each event, it's possible to study the dynamics of the game, like changes in team strategies or intensity throughout the match.

4. **Player Performance Metrics**: The data can be used to create performance metrics for players, such as distance covered, pass accuracy, shot effectiveness, and defensive contributions.

5. **Team Analysis**: Team-level strategies and formations can be analyzed by aggregating individual player data. This could involve studying offensive and defensive shapes or transitions between them.

6. **Predictive Analytics**: Using machine learning algorithms, one can predict future outcomes like goal probabilities based on current game situations, player positions, and historical data patterns.

7. **Visualization**: The data can be visualized to create heat maps, trajectory plots, and other visual tools to represent player movements, event locations, and game patterns.

For further analysis, it would be important to consider the specific research questions or objectives you have in mind, as this will guide the type of analysis to be conducted. Additionally, access to the software tools or programming skills (e.g., in Python or R) is necessary to process and analyze the data effectively.

### Resources

- (How To Moneyball Soccer)[https://towardsdatascience.com/how-to-moneyball-soccer-46b589429748] -->
