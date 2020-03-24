## Introduction


### Varnish




### Solr Consum

Once the container are up & running, a collection is needed in solr search engine to allow drupal index the data in solr. To do this perform:

docker exec -it consum_solr solr create -c consumcollection -n data_driven_schema_configs


