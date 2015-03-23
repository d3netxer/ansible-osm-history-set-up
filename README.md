
Use Ansible to provision an Ubuntu instance to run OSM-History.

#####Next Steps:

in osm-history repo:
  - run 'npm install'
  - run 'npm install mongodb'

###system_packages:
  - build-essential
  - git
  - git-core
  - curl
  - make
  - vim
  - unzip
  - nodejs 
  - graphicsmagick
  - libevent-dev
  - nginx
  - clang 
  - whois
  - python-setuptools
  - python-dateutil
  - python-software-properties 
  - python-gdal 
  - python-mapnik2 
  - python-pyproj
  - python-dev 
  - python-imaging
  - python-virtualenv
  - libpq-dev
  - libgdal1h
  - libgdal-dev
  - postgresql-9.1
  - postgresql-9.1-postgis-2.0
  - postgresql-contrib-9.1
  - zlib1g-dev
  - libexpat1
  - libexpat1-dev
  - libxml2
  - libxml2-dev
  - libgeos-dev
  - libgeos++-dev
  - libprotobuf7
  - libprotobuf-dev
  - protobuf-compiler
  - libsparsehash-dev
  - libboost-dev
  - libgdal1-dev
  - libproj-dev
  - subversion
  - doxygen
  - graphviz
  - pgadmin3
  - libosmpbf-dev
  - osm2pgsql
  - libmapnik 
  - gdal-bin
  - mapnik-utils
  - proj 
  - libprotobuf-c0-dev
  - libssl-dev

  ###repos:

  - osmium
  - osm-history-splitter
  - openstreetmap-carto
  - openstreetmap-history
  - protobuf
  - protobuf-c
  - osm-meta-util

  ###openstreetmap-history gemfile installs:

  - mongo 1.11.1
  - bson 1.11.1
  - bson_ext 1.11.1
  - rgeo 0.3.20
  - descriptive_statistics 2.5.1
  - htmlentities 4.3.3
  - jekyll 2.5.3
  - pbf_parser 0.2.0
  - nokogiri 1.6.6.2
  - nori 2.4.0
  - rspec 3.1.0
  - byebug

  ###protobuf and protobuf-c are both compiled and installed

  ###Ubuntu Personal Package Archives (PPAs):

  - ubuntugis/ppa
  - kakrueger/osm-unstable
  - developmentseed/mapbox


