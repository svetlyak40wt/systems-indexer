This is an experimental Common Lisp systems indexer
===================================================

To start Elastic Search, run::

    docker run -d --name elasticsearch --net dev-network -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:7.3.2
