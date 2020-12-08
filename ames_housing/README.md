## Problem Statement:

As a data scientist working for Harold Pike construction, I am interested in finding out which variables are the largest indicators of sale price. Harold Pike Construction renovates homes and builds homes from the ground up. If we can find out which attributes lead to highest sale price, we will have a better idea of where and what type of house to build/renovate to maximize our profits. Is location the leading factor driving Sale Price? Which type of house and how much land are ideal? Other than size of the house and location, what is one surprising trait that significantly increases house prices?

I will be presenting to the board on where/what type of houses need to be built/renovated to maximize our profits.


## The DataSet

The dataset that I used to categorize the housing characteristics was taken from the Ames, Iowa assesor’s office. It tracked the sales of homes from 2006 to 2010 in the area, finding almost 3000 observations and involved over 80 different descriptive characteristics of each house sold. The dataset is expansive enough that it can provide us with some excellent insights into our search to maximize sale price. I used a linear regression model that ended up having 130 features of these features (many new features created by making dummy variables on the categorical data).


## Summary/Findings in the Data 

After running though a model and looking for trends, the first thing I looked into was which traits most positively and directly impact the sale price of the home. I ended up using 65 different positively correlated traits in my model. As we probably could have guessed, most characteristics on the positive side involve quality and size of the home. To run down the list, Overall Quality, which rated the material and quality of the finish of the house, had the strongest correlation. Looking further down the list we see other positively correlated characteristics including the above ground living area, the area of the garage, the square footage of the basement and first floor, and the year the home was built or remodeled. While it is important to know what drives property value on the positve side, most of these traits are rather intuitive. We probably didnt need to run through the dataset to know that the bigger and nicer the house, the higher the sale price. 

What I believe to be more important in our analysis are the negatively correlated features. In my model, I used 65 negatively correlated features. At the top of these features, we see that medioce exterior quality, mediocre kitchen quality, and mediocre basement quality serverly limit the sale price of the house. Again, while these are important, we probably already knew this as well. Looking at the others, we see some really interesting characteristcs that are far less obvious drivers of a low sale price. The lack of a fireplace, an unfinished or detached garage, and the lack of masonry veneer really stood out to me as these three traits showed to negatively impact sale price and are traits that could be remodeled/built. 


## Conclusions and Recommendations

The goal of the analysis was to identify the characteristics that can impact the sale price of the house. Once we found these features, we could implement them into our building and remodeling, and in return, increase our sale prices and profits. While many of the characteristcs were rather intuitive, like the overall quality and square footage of the living space, 3 features really stood out in my eyes. First, every home we build/renovate needs to have a minimum of 1 fireplace. Second, the home needs to have masonry veneer on the outside of the house. Lastly, the houses need to have a finished garage that is attached to the house. With the inclusion of these three rather simple characteristics, we can maximize the sale price and in turn, maximize our profits. While these may be only 3 changes, I feel like they are reasonable to include in our construction and renovations, and can drastically improve our sale price. 