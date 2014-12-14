# Ruby TCP Chat

* See [Ruby TCP Chat](http://www.sitepoint.com/ruby-tcp-chat/)
at SitePoint (by Simon Benitez)

It creates a server that receives the client connections and stores them in data dictionaries. 

These dictionaries will keep track of what room the client is located in, receive messages, and relay the messages to other users. 

Each user must have a different username, which will be our primary key to look up our connections in the data dictionary so we can keep track of connected users. 

