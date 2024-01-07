# ML-A1

## Task
With over 1,200 quick service restaurants across the globe, TFI is the company behind some of the world’s most well-known brands: Burger King, Sbarro, Popeyes, Usta Donerci, and Arby’s. They employ over 20,000 people in Europe and Asia and make significant daily investments in developing new restaurant sites.

Right now, deciding when and where to open new restaurants is largely a subjective process based on the personal judgement and experience of development teams. This subjective data is difficult to accurately extrapolate across geographies and cultures.

New restaurant sites take large investments of time and capital to get up and running. When the wrong location for a restaurant brand is chosen, the site closes within 18 months and operating losses are incurred.

Finding a mathematical model to increase the effectiveness of investments in new restaurant sites would allow TFI to invest more in other important business areas, like sustainability, innovation, and training for new employees.

The challenge is now to investigate models to predict the revenue and provide a recommendation to TFI which model to use for future predictions. 

## Data 
This assignment is based on the data from the Kaggle competition to predict restaurant revenue. Each observation corresponds to a restaurant and the variable wanting to be predicted is revenue.

Each of student will be provided with a unique dataset based on this data (note: it is not exactly the same as the original). Download this data from this app. Everyone should have 2,000 observations and 12 variables in the data. 

The data contains the following variable.

- id : Restaurant id.
- open_date : opening date for a restaurant
- type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile
- P1 - P8: These are obfuscated variables that are either demographic, real estate or commercial information related to the restaurant.
revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year. Please note that the values are transformed so they don’t mean real dollar values.
