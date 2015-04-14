# QR Code Specications

The Bubbler Mobile App can scan Bubbler specific QR codes and the search on that topic. The QR code is a URL that starts with `http://bubbler.com/#` and then has either a Twitter handle with the leading @ sign, or an md5 hash of an email address. eg.

`http://bubbbler.com/#@bubbler` Bubbler's Twitter Handle

`http://bubbler.com/#a9e093a37ea61cd76ccdd76231888208` md5 of dick@bubbler.com

we will also process web site urls

`http://bubbler.com/` Bubbler's web site

Starting with the `http://bubbler.com/#` will have any other QR code scanner load the Bubbler web site so that the user can download and install the Bubbler app. Websites will just load that web page.

##QR Codes for testing with:

###@Bubbler

![@Bubbler](http://qrfree.kaywa.com/?l=1&s=8&d=http%3A%2F%2Fbubbler.com%2F%23%40Bubbler)



###dick@bubbler.com

![md5 dick@bubbler.com](http://qrfree.kaywa.com/?l=1&s=8&d=http%3A%2F%2Fbubbler.com%2F%23a9e093a37ea61cd76ccdd76231888208)

###dhttp://bubbler.com/

![md5 dick@bubbler.com](http://qrfree.kaywa.com/?l=1&s=8&d=http%3A%2F%2Fbubbler.com%2F)


