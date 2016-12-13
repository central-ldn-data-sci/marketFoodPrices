# marketFoodPrices
Repository for meetup looking at link between recipe ingredient popularity and market food prices

---

# Repository Data

• food.producer.prices.csv - CSV containing annual producer prices of a number of crops taken from http://www.fao.org/faostat/en/#data
• recipelist.rds - R object list of lists that contains 11235 scraped recipes from the bbc food website. Within this are variables for the ingredients and the date of the recipe creation (along with the actual recipes if interested)
• recipelist.json - JSON file containing the same data as the above R object

---

# Problem

If you have not been under a rock for the last year, then you will no doubt be aware that everyone is crazy about quinoa. But before quinoa there was kale, chia seeds, acai berries and so on. 

But why do some foods seem to be continually increasing in price such as kale, whereas other foods seem to boom and bust such as acai berries? Are these patterns easy to predict from simple previous market prices and availability, or are public interests more fickle? 

To attempt to look at this question we have scraped the bbc's food website's list of recipes, along with historical prices and production units of foods of interest from the United Nation's statistics division (http://faostat3.fao.org/home/E). We are interested to know if this data can be used to explain the market cost of quinoa. Our initial thoughts are yes, but we then thought it would be fun to check if previous patterns in the bbc's food recipe patterns in relation to chia seeds, kale, acai berries etc can inform us whether quinoa will continue to grow in popularity. 

---

# Topics: 

• Data mining

• Predictive modelling

• Supervised learning

---
