# Sails js CRUD

Install the MySQL adapter
	npm install sails-mysql --save --save-exact

Edit your default datastore configuration in config/datastores.js
	// config/datastores.js
	module.exports.datastores = {
	  default: {
	    adapter: require('sails-mysql'),
	    url: 'mysql://root:squ1ddy@localhost:3306/my_dev_db_name',
	  }
	};

Run command
	npm install


### Links

+ [Sails framework documentation](https://sailsjs.com/get-started)
+ [Version notes / upgrading](https://sailsjs.com/documentation/upgrading)
+ [Deployment tips](https://sailsjs.com/documentation/concepts/deployment)
+ [Community support options](https://sailsjs.com/support)
+ [Professional / enterprise options](https://sailsjs.com/enterprise)


### Version info

This app was originally generated on Thu Dec 09 2021 15:29:48 GMT+0700 (インドシナ時間) using Sails v1.5.0.