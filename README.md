# Sails 101: CouchDB ORM for Sails.js

## How do I use the CouchDB ORM for Sails.js?

### PreRequisites
* Install CouchDB

### Set up and Configure

* Create a new Sails app with `sails new path_to_app`
* Install dependencies
  * `npm install --save sails-couchdb-orm`
  * `npm install --save url`
* Edit "config/connections.js" with your CouchDB URL

> Optionally: You can specify your CouchDB connection paramters in Environment Variables:

* COUCHDB_URL: URL to CouchDB, does not read user/pass, default: http://localhost:5984
* COUCHDB_USERNAME: CouchDB Username, default: 'admin',
* COUCHDB_PASSWORD: CouchDB Password, default: 'admin'

