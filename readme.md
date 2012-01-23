Facebook-SDK-Spark
==============

Facebook-SDK-Spark adds the facebook sdk library to CodeIgniter.

Introduction
------------

The facebook SDK is available for Codeigniter via [Sparks](http://getsparks.org/install).

You'll need to setup and app and get an appID and Secret key from [Facebook](http://developer.facebook.com).

And save this appID and Secret in the '/sparks/facebook_sdk/[version #]/config/facebook_config.php'.

Once you've got the spark set up, you can load it using:

  $this->load->spark('facebook_sdk/[version #]');


When Facebook-SDK is loaded, you can make calls to the facebook api as follows.

### Set get login URL

  $this->facebook->getLoginURL();

### Make a Facebook API call

  $this->facebook->api('/codeigniter');

Other documentation for the Facebook PHP SDK can be found at [https://github.com/facebook/php-sdk/](https://github.com/facebook/php-sdk/).  

Author
------

Joey Blake <me@joeyblake.net>

License
-------

Facebook-SDK-Spark is released under the Apache License. 

Copyright [2012] [Joey Blake]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.