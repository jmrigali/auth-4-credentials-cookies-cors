# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Credentials are all the information that verify/prove a user's identity.

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

Cookies are exchanged through the response of a server to the user. They live on the user's memory but are set by the server.

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

Strengths: temporary memory of log in credentials or other information.
Weaknesses: session hijacking, modifying cookies

> What is the difference between a session cookie and a persistant cookie?

A session cookie is created and destroyed every time you open and close the browser. Persistant cookies maintain their data across browser sessions.

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

It's a good policy because it helps the server side only share cookies with authenticated users. It helps protect the DOM and javascript from outside attempts to change them

> Based on what you know, how would you explain CORS?

CORS allows a site to access cookies from another site with that other site's permission.
