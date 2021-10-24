# cs230-portfolio | Jared Hodgkins

The Gaming Room client has developed an Android game, "Draw It or Lose It"
that they would like ported to a web application so that they can attract
more players to their game. Some of their main concerns were interoperability
between players across multiple clients and also completing the project within
a specific budget. Taking these factors into consideration, I have presented a
design document to address these concerns in which I feel adequately compared
a variety of possible solutions before coming to any conclusions. One of my
major strengths in this project was coming from a mindset that multi-platform
applications are hugely beneficial. The client's request in this regard therefore
lined up with my personal philosophy of software design.

This was my first time working on a design document, and I found the overall
process was very helpful in organizing and journaling the entire process. It's
incredibly easy to have an idea in the moment, and go work on that idea, but by
the time you come back to it after some period of time you have forgotten what
some, if not all, of the initial intention was. I will admit that writing the
documentation was time consuming, but even though I wished I was writing code
instead, I could understand the value of going through the process. The next
time I work on a design document I think it would be helpful to create better
revision notes and have a more intentional reason for updating the document so
that the update notes are more concise.

When it comes to developing an application for a client, the users and their
needs are going to be the most important to consider, because they are the ones
who are either going to use the application or not. If user's needs aren't met
then they will choose not to use the application and all of that development time
and resources will have been wasted, and the client will not be happy either. To
meet the needs of the users, I choose to implement measures to reduce the
overall storage requirements on their devices by loading and preloading images
via a REST API as needed versus having the entire 1.6 GB of image data on their
device's storage. By implementing a method that preloads images before they are
needed, the users get a seamless and resource-efficient experience without
sacrificing their local storage. Additionally I made sure that images that were
no longer in use were being freed from memory to keep their device's operating
efficiently as well.

The way that I approach software design is first to gather all of the requirements
and the expectations for a project. My main concern is understanding what the
project is trying to accomplish, what the constraints are, and who the target
user(s) will be. From there I like to do a bit of research and evaluate options
until I can narrow down a best fit for each approach, or at least be able to
present the trade-offs necessary with each decision. The design document is a great
way to journal this process if used properly from the beginning, and I never like
to get stuck in the mud so to speak, so if I find a better way to do something I
am not afraid to change directions if time and resources allow.
