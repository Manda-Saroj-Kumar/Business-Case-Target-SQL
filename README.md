# Business-Case-Target-SQL

Context:

Target is a globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver. 

This particular business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

By analyzing this extensive dataset, it becomes possible to gain valuable insights into Target’s operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

_______________________________________

Dataset: https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb

The data is available in 8 csv files:

customers.csv
sellers.csv
order_items.csv
geolocation.csv
payments.csv
reviews.csv
orders.csv
products.csv
_______________________________________

The reviews.csv contain following features:
Features	Description
-	review_id	  ID of the review given on the product ordered by the order id
-	order_id	  A Unique ID of order made by the consumers
-	review_score	  Review score given by the customer for each order on a scale of 1-5
-	review_comment_title	  Title of the review
-	review_comment_message	  Review comments posted by the consumer for each order
-	review_creation_date	  Timestamp of the review when it is created
-	review_answer_timestamp	  Timestamp of the review answered
The products.csv contain following features:
Features	Description
-	product_id    	  A Unique identifier for the proposed project.
-	product_category_name    	  Name of the product category
-	product_name_lenght    	  Length of the string which specifies the name given to the products ordered
-	product_description_lenght	  Length of the description written for each product ordered on the site
-	product_photos_qty    	  Number of photos of each product ordered available on the shopping portal
-	product_weight_g    	  Weight of the products ordered in grams
-	product_length_cm    	  Length of the products ordered in centimeters
-	product_height_cm    	  Height of the products ordered in centimeters
-	product_width_cm    	  Width of the product ordered in centimeters

