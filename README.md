# FEUP-PRI

Dataset: https://www.kaggle.com/mdhamani/goodreads-books-100k

## Project Grades

Milestone 1: 81% 

Milestone 2: 86%

Milestone 3: 85%

Final Grade: 18.50

## DOCKER

### Build

To build the image, run `docker build . -t goodreads_solr` (where goodreads_solr is our custom image's name) in _/solr_ folder.

### Run

To execute it, run `docker run --name goodreads_info -p 8983:8983 -v ${PWD}/data:/data --rm goodreads_solr` in _/solr_ folder.


## Stop and delete container

To do it, run `docker stop goodreads_reviews`.
