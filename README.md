# try-instagram-on-sails
================
a [Sails](http://sailsjs.org) application


### Want to try?
-------
  * `git clone git@github.com:waskito/try-instagram-on-sails.git sails-instagram`
  * `npm install && bower install`
  * create an app in [instagram developer page](instagram.com/developer/clients/manage) (you must login using your instagram account)
  * place your `client_id`, `secret_client` `url`, and `callback url` in `config/local.js`
     module.exports = {
     	instagram: {
	      client_id   : 'CLIENT_ID',
	      client_secret : 'CLIENT_SECRET',
	      url       : 'URL',
	      redirect_url  : 'CALLBACK URL'
	    }
     }
  * better use localhost tunnel like (ngrok)(https://ngrok.com) so can run your app without using port 1337 in address bar


