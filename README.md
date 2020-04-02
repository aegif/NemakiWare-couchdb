# CouchDB Image for NemakiWare
This Docker Image contains the seed data necessary for a base NemakiWare install.

## Usage
CouchDB is by default running on port 5984. The local.ini file can be edited prior to building.

### Running
Start the Docker container with the following command:
`docker run --name nemaki-couchdb -port 5984:5984 aegif/nemakicouch`
