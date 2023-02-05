I love gulab jamuns. This project is my quest to find gulab jamuns - the best and the cheapest options - in New York City.

### Methodology

1. I scraped Yelp data from its API to get the restaurants that sell gulab jamuns. There weren't a lot -- 44 establishments. The API got me the names of the restaurants, location and rating.

2. I manually got the price of gulab jamuns by checking the menus of each restaurant. Sadly the API did not have an option to get menu details. In restaurants where the serving size is not specified, the cost is assumed to be for two gulab jamuns. For restaurants that sell the dessert by weight, 1lb is assumed to have 7 pieces of gulab jamun. 

3. Since I'm lazy and do not want to travel every time I have a gulab jamun craving, I also manually searched for canned gulab jamun on Amazon. The lowest price was considered for the same product sold by different sellers.

4. I also used Yelp API to give me the data on restaurants that sell matcha cheesecake or green tea cheesecake. It is my least favourite dessert and I wanted to see if it is more easily available than gulab jamun. I got a list of over 750 restaurants and manually cleaned the data. The final map has 22 restaurants since the API threw up results for any one of the following three keywords - matcha, chessecake and green tea.

### Findings

This project inferred that gulab jamun is more popular than matcha cheesecake though both desserts do not seem to be sold by many restaurants. Restaurants in 'Curry Row' in Lower Manhattan is where one can find both desserts compared to other parts of the city. I also found that canned gulab jamuns are a cheaper option in comparison. 

### Limitations

Since a single source (Yelp API) was used to get the data, the project may not be an accurate respresetation of the ground reality. 

The story can be read [here](https://poojachaudhuri.github.io/gulab-jamun-in-nyc/). 



