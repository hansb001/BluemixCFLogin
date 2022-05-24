BluemixCFLogin
==============

BlueMix login via commandline

This code is taken from Bluemix

With this example you can use the CF commandline to login to Bluemix

$ cf login -a https://api.ng.bluemix.net -o <your org name> -s <your space name>
API endpoint: https://api.ng.bluemix.net

Username> <your user ID>

Password>*******
Authenticating...
OK

Targeted org <your org name>

Targeted space dev

API endpoint: https://api.ng.bluemix.net (API version: 2.0.0)
User:         <your user ID>
Org:          <your org name>
Space:        <your space name>

To push (deploy) Your app in Bluemix, use this:

$ cf push -p pathtoApp -m 512M

lounch your app:

http://<yourappname>.stage1.mybluemix.net
  
  test test test
  
  ## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|

