# UCSB-CS56-M16-Lectures
Lecture notes from UCSB-CS56-M16

This repo goes with the course [CMPSC 56, Summer 2016](http://ucsb-cs56-m16.github.io/), taught by [Phill Conrad](https://www.cs.ucsb.edu/~pconrad) from the [CS Dept](http://www.cs.ucsb.edu) at [UC Santa Barbara](http://www.ucsb.edu).

On some class days, I'll make a separate repo for that days lecture notes, or I'll be working in a repo that
already exists.  But on other days, to save time, rather than make a new repo, I'll just make a new folder/directory
inside this repo.

You can clone this repo, even though you have not "write" permission to it.  
* You'll always be able to `git pull origin master` to get the latest updates, and you should do that often.
* You won't be able to `git push origin master` though, unless you are one of the admins for the course (instructor, TA, mentor, etc.)

If you want a version you can push your changes to, you can *fork* this repo.
* Then you get a version of it under your own github username, e.g. github.com/jgaucho/UCSB-CS556-M16-Lectures instead of 
UCSB-CS56-M16/UCSB-CS56-M16-Lectures. 
* Then, you can push to the repo if you make changes to some example that you want to save.
* You are not required to do this.  But its a very good idea.  Experimenting with your own variations of the instructor's examples has been shown to be highly correlated with good learning results in courses.
* This does have the disadvantage that you won't be able to do a `git pull origin master` to get the updates from the instructor's copy. BUT NOT TO WORRY.  THERE IS A WAY.
* github does not automatically create a *remote* such as `origin` for the repo that another repo is *forked* from.
* However, there are two ways to get new content from the repo you forked from:

# Creating your own remote for the instructor's original repo

The first of the two ways is to *manually create a remote*.  

* The `origin` that you pull from and push to in `git pull origin master` or `git push origin master` is the repo that you *clone* from.    
* However, you can set up other remotes manually. Here's how:

```
git remote add instructor git@github.com:UCSB-CS56-M16/UCSB-CS56-M16-Lectures.git
```

The word `instructor` here can be anything you like. It could be `lecturenotes` or `datbaldguy` or whatever.

It's just a name that you give to the repo you want to pull new content from.

You then use it in place of `origin` like this:

```
git pull instructor master`
```

or  `git pull lecturenotes master` or `git pull datbaldguy master` or whatever.

# Second way: Pull Requests

The other way is done through the github web page.  You can create a "pull request" from any branch of any repo that you can see, to any other branch of any repo you can see.    Normally, you do this when you do NOT have write access to the repo that you want to write new changes into.  But, there's nothing stopping you from making a pull request into your OWN repo from the instructor's repo, and then accepting that pull request.

I won't detail the instructions of how to do that here.   We might demo that later in the course.   If we do, we can link to those instructions from this page.
