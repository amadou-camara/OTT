# friendPlanner

We want to create a web application that will primarily allow people in the same city, yet in different locations, to meet up in a location that is equidistant from all of the people using a number of factors to make the decision. These factors will include the distance from on another, the activity or event type that the people are interested in, the price range, and the modes of transportation that each person wants to take to meet up among other potential features.

We are debating where we would actually create this for initially, but it will most likely be Boston or New York to start. We see high practicality for many different demographics, but also a means to apply our learned knowledge from CS182.

Given a set of users spread out in various locations and information on venues and activities in a desired destinations, we aim to optimize the process of meeting up with those that you care about so that it is fair and best for all. This project will take a number of resources, but the main course related topic is the use of the constraint satisfaction problem. We are going to investigate which variants, backtracking, local search, arc consistency and so on, will be the best for this project at hand. We have already been delving into the tools that we will be utilizing and the ways in which we will incorporate both our learning and interests into the project.

To give an example of the expected behavior, imagine 6 friends scattered around New York City: uptown, downtown, midtown, etc. We want to make sure that they can all reach the location at the right time to ensure that they are able to enjoy each other's company. Based on the factors they decide, potentially through a quick poll, or factors on their user profiles, we will minimize the distance that each will have to travel in order to satisfy their desires, while also satisfying the factors such as price, event type, and even the mode of transportation. Given all of the users’ preferences, the program will output a location meeting all of the constraints, how long it will take for each person to get there, and the best time to leave to make it on time. The friends meet up and a fun time commences! This is expected behavior if everything goes well. We can add how far or how long each person is willing to travel and adjust accordingly.

There are a few edge cases, for example the issue of the friends being in a very close proximity, it will simply become a search for a location satisfying their desires. This is not a huge issue to tackle, it may even simplify the CSP. The issue that we want to mainly focus on is a fast, efficient output of ways that friends can meet up at a location that they desire. We want to ensure that it is as equitable a process as possible, but also find the best constraint satisfaction algorithms to implement this web app.

We have begun to look into various tools that we can use. The first are the API’s that we will use: ​Google Maps​, ​Massachusetts Bay Transportation Authority​ or ​New York MTA​, DarkSky Weather​, ​Facebook​ for profiles, among others. Our CSP algorithms will be based on those learned in class, but the resources we have begun to look into are those that try to satisfy the ​Uber carpooling problem​, and more applicable information on CSP’s such as specifically to planning and scheduling​ and ​a book on the same topic​.