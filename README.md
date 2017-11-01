
### Creating a new site
**1.** Fork this repo (top right corner).  
**2.** Rename the forked repo to your-username.github.io (see settings tab in the repo) 
**3.** In the web browser: refresh your-username-github.io until it shows up.   



### Configuring the new site
#### General
Make high level changes using the heavily commented file: __\_config.yml__

#### Posts
1. Navigate to the \_posts directory. 
2. Create a new markdown file with name formatted: year-month-day-title.md
3. Add the header:   
\---  
layout: post  
\title: You're up and running!  
\---  
4. Add whatever content you want. 
5. Git add, commit, push.

#### Adding new pages
1. Make a copy of the __about.md__ file called __test.md__ in the top level of the repo. This will become the new page. (can also be an html file)  
2. Open __about.md__ and change the title and permalink to __Test__ and __test__, respectively. Delete the existing content and write whatever you 
wan using plain text or markdown formatting. See the [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for help.  
3. git add test.md, commit, and push to master. 


### Next steps (do on your own time)
* setup local development environment:
>>> gem install github-pages
jekyll build
jekyll serve

* Discus integration for commenting system. 
* Mailchimp integration for mailing list. 


### References
1. [Build A Blog With Jekyll And GitHub Pages](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)
2. [Barry Clark's "Now" theme](https://github.com/barryclark/jekyll-now) 
3. [Other themes](http://jekyllthemes.org/)


# TODO:
* Add resources/links.
* Add basic overview.  
* Add disqus 
