## Product Reviews 

The goal in this project is to train a binary classifier to identify helpful product reviews.

Submissions for this project will be shown on the [Reviews Leaderboard](http://big-data-competitions.westeurope.cloudapp.azure.com:8080/reviews).

#### Training Data

The primary files contains information about products and the reviews. The label column denotes whether a review was considered helpful or not.

| product_id | product_parent | product_title | vine | verified_purchase | review_headline | review_body | review_date | marketplace_id | product_category_id | label |
|---|---|---|---|---|---|---|---|---|---|---|

Additional files contain information about product categories and marketplaces.

`category.json`

|category_id| name|
|---|---|

`marketplace.json`

|marketplace_id| name|
|---|---|


#### Validation & Test Data

We provide validation and test data as input for the submissions. This data has the same format as the training data, but does not contain the corresponding label.

`validation_hidden.csv` `test_hidden.csv`

| product_id | product_parent | product_title | vine | verified_purchase | review_headline | review_body | review_date | marketplace_id | product_category_id |
|---|---|---|---|---|---|---|---|---|---|
