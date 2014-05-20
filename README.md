# How do I use CouchDB as my ORM Adapter?

> Sails 101: CouchDB ORM for Sails.js, or "How do I use the CouchDB ORM for Sails.js?"

### PreRequisites
* Install CouchDB

### Set up and Configure

* Create a new Sails app with `sails new path_to_app`
* Install dependencies
  * `npm install --save sails-couchdb-orm`
  * `npm install --save url`
* Edit "[config/connections.js](https://github.com/sails101/couchdb-orm/blob/master/config/connections.js#L81)" with your CouchDB URL

> Optionally: You can specify your CouchDB connection paramters in Environment Variables:

* COUCHDB_URL: URL to CouchDB, does not read user/pass, default: http://localhost:5984
* COUCHDB_USERNAME: CouchDB Username, default: 'admin',
* COUCHDB_PASSWORD: CouchDB Password, default: 'admin'

