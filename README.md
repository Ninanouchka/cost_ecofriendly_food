# cost_ecofriendly_food


The goals of our project is to sensitize citizens to the food consumption issues in the context of climatic crisis, and also to compare different places where food is sold regarding price, origin of products and type of agriculture. This project aims to guide consumers to a more eco-friendly way to buy food, while informing them about the budget of an eco-friendly food.

Within the food, we will focus only on vegetables and fruits. For this kind of product It is easier to know about their origin, and more broadly, it’s easier to evaluate their carbon footprint than for transformed products. Also, fruits and vegetables are subject of important issues of wasting since they are perishable products.


Concretely, the project is to create a participatory data collection on food focusing on price and eco-friendly aspect. We want to develop an application that allows users to give data about product they buy or discover in shops. Users will also benefit to this database, they could compare shops in their area regarding prices, type of agriculture and origin of products.
First this application would sensitize users to the food consumption issues by offering them solutions : Shops near to their place where they can find local and/or organic fruits and vegetables. Secondly, this database will allow to generate statistics about offered product in a shop, and these statistics could be extended to a more broadly scale : city or country.


More precisely this application would have 2 main functions :
Add data to the database : when a user finds a product he/she can add it to the database by indicating type (apple, carrot…), origin, and label (biological agriculture…) of the product, but also information of the shop (type, name, location). 
Compare shops in an area : The use has access to a map with all the shops that sell fruits and vegetables around him. Each shops will show its 3 scores : Price, Products origin and Biological agriculture. This informs the user to the place he could find the more local products, or the more Biologic products, while regarding general prices of the shop.
Compare a product among the different shops in an area : The user can search for a specific product and see, as a list, all the shops where the products has been referenced. S.he can observe for each product the 3 criteria : price, origin and label. 
View personal statistics : The user can add all the products s.he buy in his personal database. Then s.he can observe the evolution of the way of his/her consumption over time (for each month). Two parameters are taken into account : The percentage of organic products over all the products bought, and the mean distance travelled by the products.


The scores could be computed in the following way : 
Price : score = mean(for each product : price_productshop - mean_productall shop ). More the score is low less the shop is expensive. Then shops are ordered and get a rank over 100.
Products origin : A percentage of product from the country on all the products of the shop.
Biological agriculture : A percentage of Biological agriculture on all the products of the shop.
