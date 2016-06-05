# CFlash
A simple flash module for ANAX-mvc
_____
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/zackebth/CFlashMessagephpmvc/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/zackebth/CFlashMessagephpmvc/?branch=master) [![Code Coverage](https://scrutinizer-ci.com/g/zackebth/CFlashMessagephpmvc/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/zackebth/CFlashMessagephpmvc/?branch=master) [![Build Status](https://scrutinizer-ci.com/g/zackebth/CFlashMessagephpmvc/badges/build.png?b=master)](https://scrutinizer-ci.com/g/zackebth/CFlashMessagephpmvc/build-status/master)
_____




# How to take part of this class and use it.
Download the class using composer or as zip from GitHub. Move the Flash catalouge inside src to app/src in Anax-mvc.
The root should be app/src/Flash/FlashDirect.php.

##Flash got a few importent functions that you need to know of and learn what they are.

* showFlash()
Info: Here is the function that shows the flash, standard flash is (Success).

* succes($msg), warning($msg) & alert($msg)
Info: Here is the function that decides how the message will/should be displayed. All of them got a parameter called $msg, in that parameter you can write your message that you want to dispaly/show.

* redirectTo($loc)
Info: With this function you can redrict to another location, you use this to instead of refreshing the page. You can write the location i the parameter for this function.


* setTime($time)
Info: This function will set the time when the message will be displayed, the pramamter use milliseconds, so for an example 1500 = 1,5 seconds.

* Order
info: This function need to be written after all the oter functions that you take use of, its only for this function you need to think of the order, the rest does not matter.
