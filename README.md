## Assignment 11
### Dr. Xin Xu
### Web Dev, GGC, Spring 2017

The goal of this assignment is to make a form for addresses that uses AJAX to autofill city/state from a zip code.

####ERRORS:
XMLHttpRequest cannot load *url*. No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'null' is therefore not allowed access.

[CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS). 

AJAX requests cannot go cross-domain for security. We are requesting the zipcode data correctly and getting the correct JSON data back, but we cannot display it in the browser because the domain from which we gather the info is different from our own. 

The book uses a same-domain request; that is, someone manually enters the kvps for city:zip into a database. No way, Josè. 

@jcbrough