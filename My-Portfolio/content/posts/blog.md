---
title: "My First Blog Post"
date: 2023-09-13T12:20:19+05:30
draft: false
---

### Welcome to my personal blog!!

Well ; **task-02** was an _intriguing_, to say the least. I learnt how to create a static website using hugo and its default templates. It took me around 3 hrs to **completely understand** the topic at hand and around a day to implement the stuff i learnt from youtube and other sources. Altogether the website building part was highly interesting.

Firstly, i created the "task-02" folder in _"amfoss-tasks"_ repository by the "mkdir" command. To install hugo, i used the "sudo apt install hugo" command. After downloading Hugo, i created a website named _"My-Portfolio"_ by using the command "hugo new site My-Portfolio -f yml" and deployed a hugo server with yml extension (as my future theme required it to do so). I installed the _PaperMod_ theme from its official repository by cloning the official github repository in the "My-Portfolio" folder. After installing the theme, i used VSCode to edit the _config.yml_ file and added the theme to the file by "theme: PaperMod", also modified the draft to false.
 
Then i created a three new posts on my website {blog.md,archives.md,profile.md} by utilising the command "hugo new posts/{post-name}. Filled in the required info in each post. To run the hugo server, i opened a terminal from the "My-Portfolio" folder where the site was created and typed in the command "hugo server" after which a real time runtime dynamic site was created on a localhost server {more specifically, 1313 server} in which real time additions/deletions of portions could be reflected.

To host the website, i used Github Pages and followed the instructions mentioned on the site. In Summary, i created a public repository named _"burgerdude101.github.io"_. Then i cloned the public repository in _"task-02"_ folder. Then i created an index.html file in _"My-Portfolio"_ folder.

Finally add, commit and pushed all of the changes by following the commands:- 

_git add ._
_git commit -m "Task-02"_
_git push -u origin main_
