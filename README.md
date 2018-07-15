# node_express_server

> A nodejs and express project

## Build Setup

``` bash

# clone project
git clone https://github.com/naveentak/eoh_poc_server.git
# cd to eoh_poc_server
cd eoh_poc_server
# run container
docker-compose up -d

# install newman (for testing)
npm install -g newman

# run unit test case
newman run eohpoc.postman_collection.json -n 4

# you will notice that first iteration GET will fail as no records

```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
