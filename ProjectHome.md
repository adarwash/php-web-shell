# A PHP web-based Shell Interface #

An AJAX based PHP shell interface. It allows you to execute either PHP or System Commands on the server it is installed on, via the web based interface (HTML page).


## Downloads ##

You can [checkout](http://code.google.com/p/php-web-shell/source/checkout) the [latest source](http://code.google.com/p/php-web-shell/source/browse/#svn/trunk) from SVN.

### Notes ###

At the moment each command is a separate HTTP Request via XMLHTTPRequest, so commands are not continuous. eg: "cd .." will not take you to the lower directory.