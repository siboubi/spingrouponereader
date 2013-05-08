Homework 5
Sorry for the late posting guys. This week has bee crazy busy for me. I'll do better next week!

For this week, we're doing some setup for our next app, the RSS Reader.

Make a new project. On creating it, select the Master/Detail Flow. This will do most of the heavy lifting of setting the views up for you.
Using the REST library we used last week, modify it to point to an RSS feed of your choice. I recommend http://lifehacker.com/rss
Implement the call to pull the RSS feed when the app starts, and populate a list with the titles of the feed. Android has a good built-in XML parser, so some googling will show you plenty of example of how to parse it. Note that there is some variance in how RSS is given out depending on the site, so you'll want to write your own parser.
Once the data is parsed, persist it in a list of objects. You'll need to create the objects yourself. See the DummyContent for an example. Don't worry about displaying the data for now unless you want to get ahead. We'll do that next week.
It's important to make sure you understand how everything is put together with the master/detail flow. Knowing where to put things will save you a ton of time working with this template.

