# Data Science Portfolio

I've spent the last decade working in data analysis and business intelligence where I've produced reporting and insights for financial institutions. Having completed a Masters of Applied Data Science, this portfolio serves as a central hub for my personal projects and those that I've completed for friends.
<br/>
<br/>
<br/>
## Projects
### Machine Learning - Cycling Predictor
[Notebook](https://github.com/fluxequalsrad/fluxequalsrad.github.io/blob/f4b6368d08b5413cf3201b91f460cf26632e031c/Machine%20Learning%20-%20Cycling%20Predictions.ipynb)

**Tools:** <br/> Python, scikit-learn, xgboost

**Description:** <br/> I don't want to say I'm a fair weather cyclist but my days of riding through heavy rain or going up against brutal headwinds are reaching an end. To help plan my rides better, I trained a number of machine learning models on my personal cycling data extracted from Strava, as well as on weather data pulled from Australia’s Bureau of Meteorology. The model outputs the likelihood of me going cycling on any given day based on the upcoming weather forecast, helping me choose the best days to ride. The XGBoostClassifier algorithm was found to perform the best for this task, with the results improving further after tuning the model's hyperparameters using GridSearchCV. It was then tested on the most recent weather forecast for Melbourne.

<br/>
### Statistical Analysis - Richmond Player Performance
[Notebook](https://github.com/fluxequalsrad/fluxequalsrad.github.io/blob/main/Richmond%20Player%20Performance.ipynb)      [Shiny Visualisation](https://fluxequalsrad.shinyapps.io/shiny/)

**Tools:** <br/> R, Shiny, Plotly

**Description:** <br/> This project used statistical analysis techniques to determine which player from the Richmond Football Club could be considered our greatest player of all time. This involved using a comprehensive set of player statistics to rank players based on where their totals and averages fell on each metric's distribution. Data was collected, normalised and weighted before the ranking was conducted to ensure the accuracy of the results. Shiny and Plotly were then used to create an interactive visualisation, enabling the user to compare players based on the statistics that matter to them. 

<br/>
### Image Classification - Food Bowl

**Tools:** <br/> Python, Pytorch, Scikit Learn

**Description:** <br/> During winter, my cat occasionally stays in his bed until the afternoon, leading to him eating his breakfast much later in the day. Since I'm not always at home and want to avoid feeding him his second meal too soon after he's just eaten, I thought to use machine learning to monitor my cat's eating habits. 

The process involves periodically capturing images of his bowl with a webcam and applying image classification techniques to identify when his food has been eaten. I plan on using Python alongside Pytorch to build and train the classification model, enabling it to distinguish between images of a full and empty bowl, and send updates on my cat's eating habits. This project is currently in the data collection phase.
<br/>
<br/>
## Other Builds
### Web Scraper - Hamish and Andy Merch
[Notebook](https://github.com/fluxequalsrad/fluxequalsrad.github.io/blob/01811f1b9618b9d5edc61ceb056bde0c113f9b86/Product%20Web%20Scraper%20-%20Hamish%20and%20Andy.ipynb)

**Tools:** <br/> Python, Beautiful Soup

**Description:** <br/> Over the Christmas holidays, my sister expressed her frustration about never being able to buy a specific t-shirt produced by Australian radio duo Hamish and Andy as it was always out of stock. To help her catch when new stock became available, I decided to write the following Python script that uses the BeautifulSoup library to parse the sites HTML and return a list of items and their availability status.
