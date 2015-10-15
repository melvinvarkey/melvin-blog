---
layout: post
title:  "Github is easy"
date:   2015-10-14 12:41:07
categories: jekyll test
---
This post titled "Github is easy" describes the basic commands we could use to initialize a local git repository aswellas permanantly store in [Github][gitlink].
The basic idea about Github is to store and collabrate your code. It is a great platform to share our hardwork with the rest of the world. Github is open source and that is why it is amazing! 
Let's start with a few Git commands. At first install the software using the command `$sudo apt-get install git`. When that is finished add some git configurations which is mandatory for the first time.
`$ git config --global user.name "username-of-the-owner"
`$ git config --global user.email "email-id-of-owner"`
`$ git config --global push.default matching`
After this we need to setup the alias, for that use the command
`$ git config --global alias.co checkout`

Ohh..phewww! (this is a one-time setup)

After this we initialize the Git, for that we use the commands below,
`$ git init` 
=>this initializes the new workspace
All the files are added to git using the command,
`$ git add -A`
To check the status of our project files,
`$ git status`

To make the changes permanently to the repository,
first make a reporitory in your Github account.Then these commands are used,
`$ git commit -m "Initialize Repository"`

If you have accidently deleted some files from the project and want to get those files back use the command,
`$ git checkout --force` 

After all these, permanently push the files to the online repository.
`$ git remote add origin <git-repo-address>`
`$ git push -u origin master`

To change the origin,
`$ git checkout -b <git-repo-address>`

{% highlight bash %}
def print_hi(name)
  puts "Hi, #{name}"
print 'melvin is using jekyll'
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[gitlink]:     http://github.com
