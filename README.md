## Phys Welcome Week Scavenger Hunt
This repo was created by Nathan R. for the Phys Dept Scavenger Hunt.
It is currently formatted for the 2021 set up, relaxing the PPE
recommendations and safety first clue from 2020. When adapting for 
future years remember that the footer has a note about the bonfire,
which may or may not apply to your year.

### Organizing
Everything should be good to go, pretty much as is for the site.
Check out the [Scav Hunt Org Doc](https://docs.google.com/spreadsheets/d/1NI1Vz8nypDExuSBih5-rgIwrYly9YAe6kuyBoHyCObA/edit#gid=710405506) in the SPS drive for 
logistics with the *peer involved* prompts and submission information.
You'll find the login for the Remind101, which--if you haven't used it--is
the platform we've used in years past for photo and video submission.
It allows the teams to text the organizers without having to share 
their phone numbers, and creates a centralized location for everything.
You'll have to unarchive the class to see it again. Once you do that,
make sure the code to join matches what the website says and you're good
to go.

## Adapting
If you're unfamiliar with github, there is a bit of a threshold to entry,
but I promise it's worth it. It might look like a lot of front-end work, but
it will change your life!

### Viewing Local Changes
This repo is equipped with jekyll capabilities, so you can fork and 
clone this repo like any other and when you're ready to see the
changes locally you can put:
`jekyll serve`
into the command line and it should pop right up.
If it doesn't, check the gemfile and make sure everything is 
installed.

### Non-breaking Changes
If you're unfamiliar with html or css don't worry, they're super 
straightforward. Similar to LaTEX, if you just edit the normal 
looking words you'll be fine.

### All the Github You'll Need for Simple Edits
* Create a [github](https://github.com/login)
* Open you command line/prompt
* Set up [SSH](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
* Navigate to a directory you want to work in 
* Check that you have git installed (you probably do), `git --version` should do the trick
* Copy and paste `git clone git@github.com:nsryan2/scav_hunt.git` into your command line
* [Install jekyll](https://jekyllrb.com/docs/installation/), [Ruby](https://www.ruby-lang.org/en/documentation/installation/), and [Jekyll Scholar](https://github.com/inukshuk/jekyll-scholar#installation)
* Navigate inside, and then put `gem install bundler` into the command line 
* Then try running `jekyll serve` (this will give you a link to access the site locally)
* If you run into problems, try running `bundle exec jekyll serve`
* Make any changes you need using a text editor of your choice
* Into the command line type `git status`
* Type `git add -u`
* Type `git commit -m "Put a comment between these quotation marks about what you did to the repo, very important!"`
* Type `git push git@github.com:nsryan2/scav_hunt.git develop:develop`
*Note that this etiquette will get you cut in a computation lab, or on a project, but it's good enough for this purpose*


