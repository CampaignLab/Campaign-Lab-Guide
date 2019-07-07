# START HERE!

This document is a **list of the authoritative documents** with which we keep track of our progress (not a howto)
 Please keep the documents linked to here maintained and don't duplicate their functionality elsewhere :)

### CampaignLab Guide
Your [guide](https://github.com/CampaignLab/Campaign-Lab-Guide/blob/master/Campaign%20Lab%20Guide.md) to how to interact with our multifarious projects!


### The data inventory
This is the spreadsheet which should store links to every dataset which might be interesting to us.

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

##### Ongoing projects you can get involved in:

Non-exhaustive, but descriptive, [list of the fun stuff we're doing!](https://docs.google.com/document/d/1QAQ4Bi3mv17ahmY1bnDFTI9eeiQeKp01PTSuGW6ZIwo/edit) This doc is for peeople to read who want to know what projects they could get involved in, or start :)


###  Don't duplicate effort!  Has your project already been started?

Coding and transformer work is listed [here](https://docs.google.com/spreadsheets/d/1s6U4PTd8V2pKUdNIO1eR3y-Pl_P8zth-DLi0zyVwO9w/edit?usp=sharing)

We are in the process of documenting this all. Until then, please check through to see if your work is mentioned, or if you are beginning a project, whether someone has already begun!

If you have done work at CampaignLab, *please* add a link in this spreadsheet, and document how far you got, and what the code does so far.

### Converted datasets

We are aiming to make transformers which convert data from it's source format to more useful formats.
Partly this means converting to .csv, but also automating dropping empty columns, etc., the standardisation of names and even geographical levels.

Some converted datasets will be stored on GitHub but they can be big, so it's worth keeping them in a `data` folder which is .gitignore'd. There is a JSON dataset inventory so that we can eventually index our converted datasets in a form that our programs can read. This will also help for quickly or automatically downloading the files we didn't pull in the repo.

(NB: Note this is on js-xlsx branch, not master)
