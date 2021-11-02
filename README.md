# cloudlink-multithread-example
Multi threading for things like data centers or servers or anything.

# Why do I need multi threading?
Multi threading allows for multiple requests from different clients. This prevents a build up of requests that single thread does. Plus, depending on the order of tasks, somebody who sent a request could potentially never get a response from the server if the request isn't prioritized by putting it at the top of the single thread script. 

Multi threading solves that. Multi threading allows for multiple requests all at once. One user could be asking for sets of data, and as the server does that, it could also be processing another request from a user for another stream of data. Once again, this prevents a build up and allows speedy requests
