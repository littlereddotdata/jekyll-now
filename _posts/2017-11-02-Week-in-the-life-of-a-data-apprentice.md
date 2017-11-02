---
layout: post
title: Week in the life of a Data Apprentice 
---

## Things I'm gathering information on

- Data Cleaning tools. 

It's like living on your own for the first time and realising that there are ten different ways to clean the sink: with instant stain remover, all purpose cleaner or old-fashioned vinegar and bicarbonate soda. Don't forget as well the idiosyncracies of your bathroom sink - the way the faucet is slightly leaky and so the area around need always needs an extra scrub, the way you need to remember to wipe around the rim. In the same way, there are many tools and ways to clean data. One can clean with a drag-and-drop tool, with code within a shareable Jupyter Notebook, with various computing languages, with paid or free options, the list is goes on. 

Which would be best for a beginner? Even if one is an expert, would it be faster and easier to use a GUI instead? What about version control? I'm still unsure. 

At the same time, what is data cleaning anyway? How would a beginner approach the idea of cleaning data? I have to teach this material at some point, so to get my head around this, I'm looking at both the Python Pandas and R Dplyr documentation. Pandas shows it raw power from the start. There are at least four ways of dealing with missing data, apparently, then lots of ways to deal with indexing. My head spins. R, on the other hand, has a restrained elegance. It starts from the idea that most, if not all, operations fall into one of five verbs, and hence the library is structured accordingly. I like the elegance of R's approach, but Pandas is definitely easier for Excel Power Users to understand. Which taxnonomy to go with? I make a list of both and decide to sleep on it. 

For the past month or so I've also been intrigued by the analogy that good analysis is like playing the piano - anyone can bang on the keyboard, but it takes real skill to craft something meaningful(thanks to Hilary Parker at Stitchfix and host of Not So Standard Deviations for the idea). Hence I've been watching videos from the "masters" Hadley Wickham and Jake Van Der Plas, who loop between manipulating data, charting it, then manipulating it some more. Watching the videos are like listening to a Bach piece, with riffs and canons and variations on a theme. When the data story finally come together, I feel like giving a standing ovation.  

## Learning about visualisation 

But life is more than data cleaning. Trying to teach statistical graphics with Python's Matplotib last week left me feeling like something was missing. I felt that the tool was slowing down, not helping, my thinking. It just took too much time to put a graphic together. So after some searching and more video watching I stumbled across bqplot in the Jupyter Lab docs. Yay! It's created by the people at Bloomberg, and best of all, it's built on the Grammar of Graphics philosophy that classicial libraries like ggplot2 are crafted with. The best thing with strutured libraries like this is, you don't have to memorise commands and workflows. The code follows a logical format, so you can concentrate on thinking about the data rather than thinking about how to chart a graph. There are also lots of examples. From looking through them, sophisticated graphs are easy to code that, in other libraries, might take a lot more code. I fork the notebook and start pawing through it. 

That being said, Seaborn is another graphing library in Python that I've found useful in the past, and I laugh to myself how convoluted tech ecosystems can be with all the different options. Again, watching videos about the history of Python plotting libraries really helped clarify my thinking on this. 

At the same time, the drag-and-drop versus typing code question comes up again. There's GlueViz, Orange and Apache Superset which are built on top of Python, all with point-and-click options and built on top of power Python libraries. They would be great for experts and beginners alike. Sometimes, just mapping the tech ecosystem feels like a full-time job. I'm thinking that someone should run with the idea of the capsule wardrobe and apply it to data. 

## Learning about mental models

There's a lot of quibble about what Data Science/Data Analytics/Artificial Intelligence really is, and terms like "unicorn" and "rockstar" aside, it's been really helpful for me to hear a rigorous and academic take on this questions. The Berkeley Institute of Data Science did just this with their series of lectures on Youtube. The videos focus on one theme: blending computational thinking with inferential thinking. These fields were quite separated previously, and indeed, they lack a common vocabuluary to communicate with. When I finish the lecture, a light bulb goes off in my head, and once again I feel like giving a standing ovation. 

## Learning about deployment
Other than deepening my knowledge in some areas like analysis, I also need to plug holes in my knowledge. So, I'm learning about how to deploy models, ie. expose a machine learning model so that other people can make use of it. At it's simplest, I can save the model parameters in a text file and call it a day, maybe store the model in a different format if I'm feeling fancy. But then there's also other lightweight options I can play around with, options that don't require a supercomputing cluster and a whole team monitoring how users are interacting with the model. I find a tutorial on Flask and Docker, then play around with the idea of using a Raspberry Pi to host an app. I take a moment to marvel at how the whole previous paragraph would have been complete jargon to me only a few months ago, then plug on. 

## Takeaways for the week 
Coding library design matters. The perfect workflow and toolset never exists, we just have to keep searching, keep learning, keep experimenting. 
