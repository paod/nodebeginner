Finished following the node-beginner book.

Wrote a simple Node.js web app.

This web app is a simple server-side JS web framework that is comprised of a server, router, and a requestHandler.
The app takes in a textarea form element, which if large enough, is broken into data chunks and transmitted as such.
There exist two paths /start and /upload. 

Files
1) index.js - This file uses and links all the other files. Run 'node index.js' to start the web app.
2) server.js - The server accepts requests from the browser, and in this case, gathers all data chunks into a variable to be
passed down into the router.
3) router.js - The router is responsible for determining depending on the request.path, which requestHandler is to be called.
4) requestHandler - The requestHandler returns the response to the client-side.


Learned new concepts: 
1) server-side JS
2) functional programming
3) blocking, non-blocking ops
4) callbacks
5) events
6) modules
7) NPM