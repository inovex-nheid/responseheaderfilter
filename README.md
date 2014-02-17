responseheaderfilter
====================

a fork of https://code.google.com/p/responseheaderfilter/
with some minor changes to suit a specific need.

changes:
- disabled configuration reloads in code

====================
### original readme

ResponseHeaderFilter is a Java Web Filter for any J2EE compliant web application server (such as Resin or Tomcat), which lets you transparently set response headers for any http request. ResponseHeaderFilter abstracts the responsibility of setting these header from your code, thereby making it easy to change header policies without changing any code.

Some of the most commonly used response headers that this filter can apply are:

* Cache-Control: Caching instructions for the client and proxies.
* Content-Type: The mime type of the response.
* Content-Encoding: Type of encoding used in the response.
* Content-Length: Length of the response body in bytes.
* Expires: Date/time after which the response is considered stale.
* Set-Cookie: Cookies are headers too. (e.g Set-Cookie: cookieName=cookieValue; Max-Age=3600;)
