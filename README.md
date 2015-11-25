# JetPHP
PHP [Jet.com](http://jet.com) API Class

# API Credentials
Please see the [Jet.com Partner Portal](https://partner.jet.com/) for more information on how to get your api user id, api secret and Jet merchant ID.

# Usage
Include the following code, and amend it as you see fit.
```php
// Setup Jet API
$jet = new JetPHPApi;
$jet->api_user_id = 'your api user id';
$jet->api_secret = 'your api secret';
$jet->merchant_id = 'your merchant id';

// Run something.
$jet->processOrdersByStatus('ready'); // or something else
```

# Notice
While it has been reformatted up to 50% of the original code, the intial code is a derivative of [DSUGARMAN's Jet.com PHP Class](https://gist.github.com/dsugarman/437c4c91aea86860ed13). It has been reformated to be more user friendly and compatible with namespaces and external use. Giving credit where credit is due!
