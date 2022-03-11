# NBA-machine-learning-model
Goal of the model was to determine which NBA players are undervalued / overvalued for their current production level based upon league compensation across the three most recent NBA seasons.

Mixture of per game, per 36 minutes and advanced stats were used to try to predict players salaries based upon the stats with the highest correlation to player salaries in that given season

Relevant Python Libraries: Pandas, Numpy, MatPlotLib, Seaborn, sklearn

Future tasks / areas of improvement:

Create "master data file" that averages all player stats and salaries out across the selected seasons (currently there are essentially 9 different models, 3 for each year based upon per game, per 36 and advanced statistics)

Validate results with other machine learning methods, such as Random Forest Regression

Classify players as underpaid or overpaid based upon their predicted salary vs actual salary

Hosting model on a web application using Flask -> date TBD
