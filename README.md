# King County Housing Price Prediction

in this repository you can find three jupyter notebook, wich document my first neue fische DS project. We where told to analyze the King County Real Estate Market by a dataset with 21.597 entries and 21 columns. First I made an EDA and to get an overview of the data and clean it. Next step was (also in the EDA file) to add a new feature and filter the data by my own params and ideas.
## EDA
I decided to filter by price first, cause there where a few properties that where very expensive (up to 7 mio) which I would recommend only for institutional investors. So I filtered in three categories 1 mio to 500k - institutional or wealthy clients, 500k to 250k - for small families with high income - and less 250k for working class people. For all these group I created different maps, so that they can see, where they could have afford a house or an apartment in September 2014 to October 2015. These maps are useful just to get an impression where it was possible to check if it is still affordable now. So basically you can see the areas, where you should have a closer look. Then I created a new feature "price_l_sqft" the price for a sqft living. I used this to filter the df and find all entries that have a price_l_sqft below the mean. At least you can find here lots of figures, maps and diagrams. Have a look...
![plot by: Silas Mederer](/figures/hist_all.png)
## Regression
Over all the models my best R2 is 88%.
![plot by: Silas Mederer](/figures/correlogram.png)
