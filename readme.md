# Overview

This is more or less a first contact expirement with django where I started by following a document system guide in order to learn some django and figure out how to make things work in it as well as construct the basic framework for the program when I was unfamiliar with it. Then I expanded on it to create my own content to cooperate with these systems and further construct additional items like the login system as well as the way that it interacts and the alternative views for when a user is not yet authorized. I also further researched to add some of my own styling choices based on the bulma css library in order to better be able to utilize such a library.

overall this system demonstrates a basic note taking system allowing you to write entries, recall and then edit those entries. It also provides a login system so that only the authorized user can modify these entries.

Through going through the guide and adding my own touches and pieces to the program I felt like I have learned a great deal about django and how you can use techniques to make web apps. If I were to reapproach a different problem I feel reasonably confident in my ability to figure out what to do whereas before this project I had absolutely no idea where to even start.

[Software Demo Video](https://www.youtube.com/watch?v=zxoWTdnMeTs)

# Web Pages

The web app has 3 states but only 2 actual pages. One page controls displaying and editing. However, when an authorized user is not logged in it displays information diffferently, disables editing privileges and prompts the user to log in. When you click on document entries it shows the contents of those entries in the associated fields. This is the default page. Logging in takes you to the login page where you are told to input username and password. inputing valid user credentials unlocks the actual editing function and brings you back to the first page. however because the user is now authorized the displaying interface has completely changed and they now have the option to edit, save and delete document entries. like before you click on the document entry to see these but now you have these additional functions in addition to just seeing contents. If the user logs out they will be returned back to the default state where they only have view privileges.

# Development Environment

This program was developed in visual studio code using python and django. It also utilizes html, and the bulma css library.

# Useful Websites

* [note taking app tutorial (This is the guide that I followed to start and later modified to make my own content)](https://www.youtube.com/watch?v=trwXaGu-Lys)
* [Bulma documentation (css)](https://bulma.io/documentation/)
* [Django documentation](hhttps://docs.djangoproject.com/en/3.0/contents/)
* [Django tutorial (has good usage tips)](https://www.tutorialspoint.com/django/index.htm)
* [Django authorization system](https://docs.djangoproject.com/en/4.2/topics/auth/default/)


# Future Work

* make document entries explicitly tied to users instead of being available to any valid users.