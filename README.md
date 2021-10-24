# BEV Website
This is the repo for the Bearcat-Electric-Vehicle clubs website. It's a simple 
website hosted using github-pages

## Tools used to create:
  - Bootstrap Library
  - HTML, CSS, JS, VS Code

Old Location of website: https://keerthi-sekar.github.io/BEV.github.io/index.html

New location: https://bearcat-electric-vehicle-bev.github.io/BEV.github.io/

### Tasking
https://trello.com/b/pw32U4jf/preseason

## Future Developers
This website is hosted using git-pages. It's a free to use service from github 
that allows you to host simple HTML based websites for free! A simple HTML 
website is one made of purley text files (HTML, CSS and JS). No frameworks 
like Django, Flask, or NodeJs. These would require a server to run, and that 
costs $$$ (AWS, Google Cloud, Blue Ocean, etc). 

### Changing Domain
If for whatever reason the domain name needs changed or the git-pages service
needs stopped, this can be done in Settings->Pages and remove the domain name.

### Making Changes
If you are tasked with making changes to the git repo the easiest way is to
use githubs least known feature ... webpage vs code. Press '.' on the repo page
and it will open up a vs code instance in your browser. Then navigate to the file 
you need to change and save. 

### Making changes locally
If you are experimenting with the website and don't want to break the live one here
are some tips to do so. First, lookup how to clone this repo and work on the files 
locally. You should also look up how branching and commits work, these are useful to 
make sure any changes you make don't break the website and can be easily fixed by
reverting a branch merge or commit.

### Running local instance
There are many ways to do this, however I have found in my experience using python's
simple http server to be the simplest. Python has a built in simple http.server that
can be used to host simple websites on localhost. This can be used to make changes to
the files in a text editor and see them live in your browser without making changes to 
the real website. 

#### Start Simple http.server
```bash
# python interpreter may be called slightly different based on your os
python3 -m http.server
```

#### For my fellow Linux/WSL fans (;
```bash
python3 -m http.server & &> /dev/null
```


