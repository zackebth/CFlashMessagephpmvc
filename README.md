# CFlash
A simple flash module for ANAX-mvc


# How to use this class
Download the class using composer or as zip from GitHub. Move the Flash catalouge inside src to app/src in Anax-mvc.
The root should be app/src/Flash/FlashDirect.php.

Flash got a few importent functions.

## showFlash()
This is the acutally function that shows the flash, it got a standard message of success.

## succes($msg), warning($msg) & alert($msg)
These are the functions that decide how the message should be displayed. All got a parameter $msg, here you should write you message that you want to display.

## redirectTo($loc)
If you want to redirect to another location instead of just refresh the page, just write the location as a parameter in this function. Ex /subpage.php

## setTime($time)
Sets the time the message will be displayed, paramter in milliseconds, 1500 = 1,5 seconds.

### Order
ShowFlash() should be written after all the other functions, the order doesent matther for the rest.
