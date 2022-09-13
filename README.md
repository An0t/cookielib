#Cookie.lib 

#Step 1
First, we need to import the library. We can do this through the script tag in our HTML.

Code:
`
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Document</title>
    <script src="cookielib.tk"></script>
  </head>
  <body>

  </body>
</html>
`

Line 6 has the import with the `<script>` tag.

#Commands
There are 3 commands in the library.
They are easy to use.

###1. Check cookie existance

This function uses 1 parameter and returns a boolean(True or False)
Tutorial:
`var exists=checkCookieExistance("Cookie Name")`
If the cookie exists it will return true.
If the cookie does not exist it will return false.


###2. getCookie
This is an easy function.
Usage:

`cookie=getCookie("Cookie Name")`
This will return the value of the cookie.

###3. setCookie
This will set a cookie to a value. Tutorial:
`setCookie("Cookie name", "Cookie Value")`
