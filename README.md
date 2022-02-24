
## Project 1 - IMDB 

learn to distinguish highly rated movies from low rated movies

[IMDB Leaderboard](http://big-data-competitions.westeurope.cloudapp.azure.com:8080/imdb)

CSV files train/validation/test

### Data

tconst, primaryTitle, originalTitle, startYear, endYear, runtimeMinutes, numVotes, [label]

directing.json

tconst, director_id

writing.json

tconst, writer_id

----

## Product Reviews 

learn to identify helpful product reviews


product_id, product_parent, product_title, vine, verified_purchase, review_headline, review_body, review_date, marketplace_id, product_category_id


category.json

category_id, name


marketplace.json

marketplace_id, name

---

Duplicate Detection - learn to identify duplicate bibliography entries

dblp-*.csv

pauthor, peditor, ptitle, pyear, paddress, ppublisher, pseries, pid, pkey, ptype_id, pjournal_id, pbooktitle_id, pjournalfull_id, pbooktitlefull_id

pbooktitle.json

pbooktitle_id, name

pbooktitlefull.json

pbooktitlefull_id, name


pjournal.json

pjournal_id, name


pjournalfull.json

pjournalfull_id, name


train.csv / validation_hidden.csv / test_hidden.csv
key1,key2,[label]
