The mysql-store is an NodeJS implementation of the object store interface for MySQL,
providing access to MySQL databases for [Persevere](http://persvr.org), any other consumer that uses
the object store interface (Dojo also uses this interface), and for direct interaction. This
store supports RQL for convenient web-based querying.

Setup
=====

mysql-store can be installed with NPM via:

	npm install mysql-store

If you are using this with Persevere, please see the Persevere [documentation](http://persvr.org/Documentation).

Using
=====

You can create new SQL store:

	store = require("mysql-store").SQLStore({
		table: table,
		idColumn: idColumn
	});


Licensing
--------

mysql-store is part of the Persevere project, and therefore is licensed under the
AFL or BSD license. The Persevere project is administered under the Dojo foundation,
and all contributions require a Dojo CLA.

Project Links
------------

See the main Persevere project for more information:

### Homepage:

* [http://persvr.org/](http://persvr.org/)