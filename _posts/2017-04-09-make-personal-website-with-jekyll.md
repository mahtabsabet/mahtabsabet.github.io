---
layout: post
title: Build your own personal website using Jekyll, GitHub, and Cloud9
subtitle: Make a beautiful site that is easily customizable
image: /img/jekyll-github-cloud9.png
---

Building a personal website is important. It's a place to show off - your projects, 
your resume, your cool sense of style, etc.

I've always struggled with building a personal website for myself. I build one, 
and then a few months later tear it down and start all over because
I don't like it. 

I'm not a very artistic person, so 
relying on pre-built themes is a must for me. But I am also a developer, and 
I appreciate being able to tweak and customize as I see fit.

I recently experimented with using Jekyll to build a personal website, so 
I'm going to outline how I did it, so others can learn!

# Step 1: Get a GitHub account
If you don't already have one, create a [GitHub](https://github.com/){:target="_blank"} account.

# Step 2: Find a Jekyll theme you like
I used this website to find Jekyll themes: [jekyllthemes.org](http://jekyllthemes.org/){:target="_blank"}

# Step 3: Fork the repo
In my case, I really liked the [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll){:target="_blank"} theme.
On the top right corner of the page, there is an option to "Fork" the repo. Click that.

# Step 4: Rename the repo
Click Settings, and rename the repo that you've forked `<yourusername>.github.io`.
Within a few minutes you should see your website live at `http://<yourusername>.github.io`

# Step 5: Set up your development environment with Cloud9
Cloud9 is a development environment in the cloud. I love using it because 
I hate having to install and download stuff onto my personal laptop, 
messing around with the PATH, environment variables, etc. Cloud9 sets up a 
development environment for you, and all you have to worry about is code!

Go to [Cloud9](https://c9.io/){:target="_blank"} and create a free account. Then, 
create a new workspace, give it any name you'd like, make it public or private 
(doesn't really matter), enter the url for your git repo (the fork you created 
in step 3!), and choose the "Blank" template.

# Step 6: Make the website your own!
Edit the _config.yml file to change things like the name of your website, 
your personal details, images, pages, etc.

Note: In an upcoming blog post I'll cover how to customize your Jekyll site to 
make it your own personal website, including adding new pages and posts. I'll 
also be writing a blog on using a custom domain, instead of <yourusername>.github.io.

# Step 7: Preview your changes
You can treat Cloud9 like your development environment. Any changes you make here 
will only be seen by you, until you decide to push your changes to git. 

You may want to see your changes as you make them. To do this, run the following commands 
in the terminal in Cloud9:

`gem install jekyll bundler`

`bundle install`

`jekyll serve --host $IP --port $PORT --baseurl ''`

Then you can click "Preview > Preview Running Application" at the top of the Cloud9 
IDE. This will open a preview of your website. Everytime you make changes and save, 
all you have to do is refresh this preview window to see your changes!

# Step 8: Commit and push your changes
Run the following commands in the terminal in Cloud9:

`git status`

`git add .`

`git commit -m "Personalize standard Jekyll theme"`

`git push`

Git will then prompt for your username and password.

# Conclusion
That's it! You can keep your Cloud9 workspace and come back to it some other time 
to continue working on your website. Everytime you make changes, you can 
commit and push to GitHub, and your live site will automatically re-deploy, 
making it visible to everyone on the internet!