# START HERE

### What is the Campaign Library?
A new library resource for activists and campaign organisers on campaign theory and practice in the UK, made by Campaign Lab.

### How you can help

##### Read and summarise evidence on campaign theory and practice:
You can sign up to edit the AirTable here (which also has ideas of resources you could summarise) or submit via our form here
We have a Guide to using AirTable below that might come in handy (we were new to it too!)
Feel free to add to this guide and encourage others to contribute to the library!

##### Improve the Campaign Lab website:
The GitHub repository has all the code open source and further information, as well as some open issues you’re welcome to assign yourself to
Feel free to ask questions in the #campaign-library channel in the Campaign Lab Slack - additions and improvements to our documentation are also very welcome
Raising issues is super helpful, even if you don’t have time to take them on yet!
Website copy:
If you have improvements, suggestions or additions, either mention them in the #campaign-library channel in the Campaign Lab Slack, add them in this document or make a pull request directly to the GitHub repository.
Ideas
The platform can also serve the Campaign Lab’s own research findings
If we get press for particular finding, that can link to the summary, which in turn would publicise the library as a whole to encourage evidence use
In future we could include profiles of experts on different topics who were willing to be contacted
A little bit like Apolitical, but for campaigning

##### How it works so far

We’ve used Gatsby.js as a web framework that generates performant static sites, and already has nice AirTable + GraphQL integrations.

It’s currently deployed here using Netlify, which is set to automatically deploy any changes pushed to the master branch of the GitHub repository. Note, changing the AirTable doesn’t currently trigger a deploy, so this either has to be done manually from the Netlify UI, or by committing something minor.

This is currently all free, and the source code can be found on the CampaignLab GitHub.

We’re not wedded to any of these choices long-term, but they’ve enabled us to create a quite appealing MVP very quickly.

Guide for using AirTable
Aka ‘What we’ve learnt so far’

Decide whether your resource is ‘literature’ (i.e. theory, research or experimental results), or ‘in practice’ (guides, tips, videos, demonstrations etc. of techniques)

##### General tips if you’re adding something to the ‘literature’ table:
* Mark yourself in the ‘who added it’ column
* Mark the article as ‘To do’ if you haven’t read it yet. ‘In progress’ when you start reading, and ‘complete’ when you’ve read/added a summary in the table
* Fill in the other columns with details about the article (if you’re adding a piece of literature).

###### When you finish reading an article note down:
1. A summary  
2. The method of the research
3. takeaways and
4. practical ways to use this research.

You can see previous entries for examples of what these mean.
Set the value of the ‘Publish’ column to ‘Publish’ to publish the summary

###### What does a good summary look like?
Is written in Markdown: https://www.markdownguide.org

Includes an overview that is understandable for someone without an academic background

Includes key ‘takeaways’

Next steps

##### More summaries added to AirTable!
* Add a ‘how to contribute’ page
* Have a goal number of resources added (per month?)
* Domain name
* Put this in front of users - is this useful? Do they find it authoritative? What do they need from it?
* Establish success metrics for the project
* Add Campaign Lab’s own findings to the library

##### Outstanding questions

For entries, what should we use as a convention for the ‘slug’ (the part of the url which distinguishes it from other entries)?
E.g. campaignlab.org/literature/a-piece-of-research
E.g. campaignlab.org/literature/123
Where the underlined section denotes the slug
Given Campaign Lab (and thus the Library) are now under the umbrella of ‘progressive’ and not ‘Labour’, is the very Labour red a bit much?
