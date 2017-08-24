# Finding the Main Factors Affecting Teen Birth Rate
This project looks at close to 50 different socio-economic and political factors to find variables that strongly correlate with increases in teen birth rate. I aggregated, cleaned, and analyzed data factors related to religion, education, politics, economics, sexual education, and race.

### Key Questions Explored:
- Which of the studied variables significantly correlate with teen birth rate?
- Which factor(s) most strongly affect teen birth rate?

### Key Findings:
- Religiosity, poverty rate, and population density in each state appears to have the strongest effect on teen birth rate.
- Link to plot with final correlation coefficients: https://github.com/mborysiak/Factors-Affecting-Teen-Pregnancy-Rate/blob/master/teen%20birth%20rate%20results.pdf
- Link to interactive map for teen birth rate: https://plot.ly/~mborysiak/20/teen-birth-rate/
- Link to interactive map for religion importance: https://plot.ly/~mborysiak/14/religiosity-by-state/
- Link to interactive map for poverty rate: https://plot.ly/~mborysiak/18/poverty-rate-by-state/
- Link to interactive map for population density: https://plot.ly/~mborysiak/16/population-density-by-state/

### Techniques used:
- pandas for data cleaning
- matplotlib for data visualization
- scikitlearn for linear regression (with regularization)
- statsmodel for summary statistics
- plotly for interactive maps (see end)

### Data Sources:
- Teen birth rates: https://www.hhs.gov/ash/oah/adolescent-development/reproductive-health-and-teen-pregnancy/teen-pregnancy-and-childbearing/trends/index.html
- Religiosity by state: http://www.pewforum.org/religious-landscape-study/state/california/#importance-of-religion-by-state
- GDP by state: https://en.wikipedia.org/wiki/List_of_U.S._states_by_GDP#cite_note-2
- Election results: https://en.wikipedia.org/wiki/United_States_presidential_election
- Population, Land area: http://www.ipl.org/div/stateknow/popchart.html
- Public education spending: http://www.governing.com/gov-data/education-data/state-education-spending-per-pupil-data.html
- Poverty rate: https://en.wikipedia.org/wiki/List_of_U.S._states_by_poverty_rate
- Median income by state: https://en.wikipedia.org/wiki/List_of_U.S._states_by_income
- Abortion rate by state: http://www.kff.org/womens-health-policy/state-indicator/abortion-rate/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D
- Abortion percentage by age: http://www.kff.org/womens-health-policy/state-indicator/distribution-of-abortions-by-age/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D
- Sex Education by state: https://www.guttmacher.org/state-policy/explore/sex-and-hiv-education
- Overall Sex Education Score from Graphiq: https://graphiq-stories.graphiq.com/stories/23028/states-worst-sex-education
- Population breakdown by race: http://www.kff.org/other/state-indicator/distribution-by-raceethnicity/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D
