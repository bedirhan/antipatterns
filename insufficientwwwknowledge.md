# Insufficient WWW Knowledge

Web applications rely on data sent through HTTP requests. With the popularity of browser developer tools more and more developers start to play with the raw HTTP requests and learn the basic blocks of web applications.

However, it is perfectly possible to implement a web application without seeing/analyzing a single HTTP request/response of it. The insufficient WWW knowledge sometimes mislead developers that end-users can't play with their parameters such as hidden parameters or HTTP 302 requests.

These hidden parameters or seemingly automatic requests are very well be intercepted by attackers and every single character of them can be manipulated. Without this undestanding solutions will be insecure.

A very good example would be 3D secure payment flows that involve with the user's browser, the backend e-commerce application, the virtual POS server and probably the bank servers. %90 of the (hidden) traffic flows through the user's browser and open to manipulation.
