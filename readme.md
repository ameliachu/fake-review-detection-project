#
#### Authors:
Amelia Chu (email [at] nyu.edu)
Evaristus Ezekwem
Dee Hahm
Gabrielle Hurtado

This is a final project for New York University's Machine Learning class (DS-GA 1003).
Due: May 19th, 2020

##### Repository Structure
```
project
| -- data
|    | -- processed: location of all intermediate/transformed data
|         | -- dev: individual-produced intermediate/transformed data
                    append your netid to anything your store here.
|         | -- prod: location of the final table(s)
|    | -- raw: location of the raw data for the project
| -- models: trained and serialized models (e.g., model_ac4119.pkl)
| -- notebooks: store your Jupyter Notebooks here.
|    | -- ac4119: treat this workspace as your own.
                  feel free to add subfolders or files as you see fit.
                  work in a way that enables YOU to succeed.
|    | -- drh382
|    | -- ece278
|    | -- gh1408
| -- reporting:
|    | -- figures: images to place on our final report.
|    | -- overleaf: (optional submodule location)
```
This file structure is derived from [Cookiecutter Project Template](https://drivendata.github.io/cookiecutter-data-science/).

#### Team Housekeeping
**Working in our Repo**
Note: I know this might side-step some Git best practices, but wanted to keep in mind of varying Git experience. Trying to keep the Git portion simple.

(1) Outside of `notebook/{netId}`, suffix all experimental/development work with '\_{netId}'
-> why? avoid name conflicts. if other team member have q's (or wanna give a high-five) on a script/notebook, they know who to go to!

(2) Remember to always pull from GitHub before starting your work and push to GitHub when you are done for the day. Even if you aren't 'done'. Our directory structure enables this.
-> why? Do this to avoid merge conflict, but also...We are a team. I find that it's motivating to see others actively working on a project. also, it's a great way to riff off of each other. If I've already created a `load_data()`, there's no point in others creating the same (if they don't want to!). This also helps keep our meetings short and straight-to-the-point--the team will have a good idea of where everyone is-- we can use our time to talk about next steps or ask for help on specific things.

**Check-in Expectations**
- Be respectful of meeting times. Goal is to end on time -- we can regroup, or extend the next meeting time. We all have things to do outside of this, be mindful when you find yourself speaking for a long time.
- It's ok to not meet a milestone/finish an assigned task, things happen! But, please tell us!
Meetings as quick as 10-15 mins or hours long. We should have a good gauge of the next meeting length.

Typical Check-in Structure:
- Status (Past, Future, Issues)
- Issues / Topics that require more discussion
