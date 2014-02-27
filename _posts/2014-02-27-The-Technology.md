---
layout: post
title: Some Thoughts on the Technology for LCL2
comments: true
tags: technology LCL2 
---

# The Technology we use to run LCL2

Where is the course site hosted?

*   It's a Jekyll site hosted as Github Pages
*   Threaded discussion on individual pages is provided through disqus

Are you using the site as a blog, static content or both? Will weekly communication be posted to the site?

*   We will post the emails we send out on the course home page. We will also add a full syllabus (which is currently under development).

Where does community discussion happen?

*   Discourse. [](http://discuss-learn.media.mit.edu)[http://discuss-learn.media.mit.edu](http://discuss-learn.media.mit.edu) (hosted on AWS)

Are you concerned about the two separate discussion tools, disqus and discourse?

*   Not really. We are minimizing the use of disqus. It's just a way to leave comments on the static pages.

What are you using for signup?

*   There is no "official" sign-up for the course, but we are asking people to register their email address for a MailChimp mailing list if they want updates and notifications about the course. 
*   Side note: MailChimp makes sense, because your account can be linked to Mandrill, and Mandrill is the default mail handling service for Discourse - so we don't have to deal with many different services). On the other hand MailChimp had a server problem last night ;-)

Do you plan on doing pre/post course surveys? If so, using what tools?

*   Yes, but haven't decided on tools. Some of the options we've been discussing include pop-up questionnaires before and after unhangout sessions, or more traditional surveys that are sent out via email (link to the survey). We are also interested how we could collect some user data through discourse, but have not found a great solution. Some people are using Topics for people to reply with Yes or No for simple polling. 

What data are you gathering?

*   TBD
*   Basic google analytics on the site
*   Mail-Chimp stores sign-up data
*   We will also keep a record of use of unhangouts (users log-in with their Google ID)
*   Question back: Does Discourse keep a history of user log-in and activity? I know that it calculates your user level based on time on site (in addition to other factors) so it does "know" how often and for how long you are on the site.
*   I don't know what it gives you automatically and I'm unsure of what it stores in the db - I think it does try to give some stats relevant to a community.

Are you doing any specific experiments during this course?

*   We are (again) trying to experiment with grouping. 
*   We are also trying to use "protocols" for break-out groups in unhangouts

Can you explain what a protocol for the break-out groups looks like?

*   Not yet. It's one of the things we want to experiment with. But we recently found out about the "protocols" that High Tech High use for their teacher training and we think we can learn a lot from their work. 

How will you group users or will they group themselves?

*   That's a big unanswered question. The overall goal is twofold: better groups than would be achieved by randomly grouping users; and giving users agency in the grouping process.

How will groups communicate with each other? Will this communication be private to the group?

*   We don't know yet. 

What are you planning to use to facilitate feedback?

*   Overall feedback about the course and how it works will take place in the "About this Forum" category on Discourse that we hope people will use to discuss the community. 

Will learners have some sort of profile? Or would you encourage them to update some profile in a certain way (ex. add a project or something to their profile on linkedin).

*   We won't host a profile beyond the very basic profile provided by Discourse. If there was an easy and elegant way of extending that, I think we would prefer to be able to host more information. 

*   Do you think people taking this course would have an online profile somewhere else that they manage themselves?

What happens with discourse after the course? How long do you host it?

*   Indefinitely. We are designing LCL2 as a pathways into the creative learning community, not as a course that starts and then just ends. 

Where is the content hosted? Is there content? 

*   The website is hosted on Github Pages.
*   The syllabus will be a static HTML page (we are still considering to embed a GDoc, but will probably not do that) on the course site. 
*   There will be videos as well. They will be available "live" through unhangouts. And archived through youtube. 
*   Readings and other resources are linked to.

What is the primary user experience for learners? Sign up -> get email when course starts -> get weekly email? or discover discussions on twitter,etc -> join discuss community -> participate?

What is the main entry point for users? The mailchimp list or joining the discourse community? (probably ties into above)

*   Both ;-) We expect new users to go via [](http://learn.media.mit.edu)http://learn.media.mit.edu and then choose their preferred pathways.

Are you planning on using something like badges?

*   Not at this point. 

Are people creating things again like the previous time with Scratch and other tools?

*   Yes. The course is based around weekly activities, some of which use tools like Scratch. 

Will it produce links that the users can post somewhere? Where? Can we scrape the links? Will it be useful if we can?

What is your measure for success for this course? big community? lots of eyeballs on content? lots of discussion?

*   Number of participants at live events
*   Quality of discussion on discourse
*   Number of projects that emerge from phase II (which we haven't talked about so far, and should do at another time)

What are the costs associated with setting up the tech resources, running it and maintaining it into the future?

Are there any specific plans to distribute content in other language?

Will you address accessibility  - transcribe videos, make sure the content is compatible with a screen reader, etc.

