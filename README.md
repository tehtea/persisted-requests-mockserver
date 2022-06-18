# Persisted Requests - Mockserver

A MockServer hosted on Heroku, forked from https://github.com/heroku/java-getting-started

A lot of the code is just starter boilerplate for running on Heroku, cannot be deleted because the app will not deploy otherwise.

The main change is to download the JAR file from https://search.maven.org/remotecontent?filepath=org/mock-server/mockserver-netty/5.13.2/mockserver-netty-5.13.2-shaded.jar

Then, changing the Procfile to target the JAR, and then adding a set of expectations to load up in JSON format.

You can access the MockServer here: https://persisted-requests-mockserver.herokuapp.com/mockserver/dashboard