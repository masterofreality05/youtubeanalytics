# yotubeapp
Capstone project one, data-analytic database driven website

# Capstone Project 1 Proposal(idea)

# API - Youtube API

# What goal will your website be designed to achieve? 

The goal of this site is to provide a database driven website for businesses and career-oriented content creators/artists alike to search, bookmark and organize Youtube media and their analytics offering insights into their popularity and online influence.

The website will also allow users to create lists of selected youtube media and their accompanying data statistics, save channels to a watchlist and send media between user to user. 

# What kind of users will visit your site?

The ideal demographic of users would be commercial users looking for content-creators or artists to collaborate with, for example affiliate marketing, advertisement etc. 

Other users would be content creators looking to view analytically which fellow artists on the platform would be good to collaborate with to elevate their career, or to see what's hot and what direction to take their expression next. 

And finally this site is ideally used by anyone who has an interest in data analysis and statistics, youtube, or even topics of any category represented through the medium of Youtube as a platform. 

# What data do you plan on using? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain. 

The Api I propose to use in this case is the Youtube API, which offers channel, user and topic searches, and can return statistical information on each. 

An example of an insight gained from data-requesting this API would be searching for a channel and iterating through their upload “playlist” and quantifying the view count for each video and illustrating the ups and downs in a chart over time (from video to video).

This is a way to somewhat discern a potential rise in popularity of a searched channel. 
With that a business may determine whether or not they may be a suitable advertisement candidate or sponsor of their new product.and any other metadata available to strengthen this notion. 

 # n brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). 

The basic part of the site will facilitate CRUD functionality in correspondence with SQL databases while demonstrating my ability in the database-oriented programming. 

Interaction with SQL databases will be implemented from the client side and demonstrate my front-end, user experience sensibilities.

Videos can be posted to the communal homepage which could take the form as a message board thread between all users. 

Videos can be tagged with categories, making use of many-to-many relations.

Information will be pulled from the Youtube API, in order to embed videos and will be the main imported media to my site in the simpler part of the site. 

In the more advanced portion of the site we will be implementing data analysis of channels, or videos to offer insightful statistics that would be useful in commercial contexts. For business or career content creators who may be looking for youtubers to collaborate  or advertise with.

We will be able to search channels on the API and view aspects of their data and see information such as:

popularity (increasing or decreasing) over time?

Subscriber count? 

What day of the week on average do the selected youtuber upload?

How often do they upload?

What is the average length of their video?

# What does your database schema look like?

Here is a rough outline of my SQL database schema design. 
Users make posts which carry the video media, and or statistics(when applicable)  which can be flagged with categories.

posts and categories have a many to many relationship, in the sense that one category can have many posts and vice versa. 

# Potential issues?

Is the project simple enough? How simple is too simple?

From playing around with the API, my observation is that while it is resource rich and an insightful tool, it may not be the most accessible and straightforward to navigate. 

I have looked into some impressions of examples of other developers using this tool as a great source of data for their projects, and my hopes and anxieties exist mostly around being able to get the most out of the resource to make the best project.

The balance that I am looking to strike just right, which is hard to know where is the right spot is that of picking an ambitious project that is not unnecessarily complicated and at the same time not too easy that it becomes underwhelming. 

The issues that present themselves to me right now is that the project is ambitious,and may need some readjustment over time to refine and simplify, but I hope to turn this fear of stepping it up into affirmative action through hard work. 

# Is there any sensitive information you need to secure?

Regarding sensitive information that is required to secure, An API key is needed to access the API resources which have already been obtained.

# What will the user flow look like? f. What features make your site more than CRUD?

A user home page will store lists of bookmarked items, based on content type, offering channel, video and category. 
The communal homepage will act as a thread of posts shared between all users, (this is explicitly posted to, and not populated dynamically from somewhere like the user bookmarks etc.)
Managing bookmarks is what represents the SQL-database-oriented programming in our site, allowing users to access all CRUD possibilities. 

The data received from the API, which is searched by references stored in the database, will be process and analyzed in an insightful manner, offering trend information and illustrating valuable statistics, which is what first of all makes this site relevant and useful over just using Youtube.come, it is also what elevates the functionality of the site above just simple CRUD functionality. 


# Do you have any stretch goals? 

I believe the stretch goal in this project is mainly in the data analysis aspects that it touches on, a little outside of my comfort zone, but that’s what gives that goal its particular feeling of stretching above and beyond. 


# Extra possible features:

When users have a search result that they may like to share with friends or other users, they will be able to send a video embedded message with a greeting, allowing the sharing of video files between users and strengthening the status of our site as a one stop shop in the video media world. 

# Final words:. 

This could be a very interesting project in terms of data representation, trends in videos and how they change over time, included with metadata and embedded video media. 

