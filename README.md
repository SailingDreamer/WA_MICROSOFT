# MyPresentationTemplate

The url: https://sailingdreams.github.io/MyPresentationTemplate/index.html

To get a copy of this git repo so you can push to your own github, 
1) go to 
https://github.com/SailingDreams/MyPresentationTemplate
2) selected the green "code" icon dropdown
3) select download zip
4) Unzip this where you want it
5) Follow the information here to setup your own github pages.
https://pages.github.com/

This template can be used to setup a very basic slide presentation. There is no 
fancy page formating done in this repo (this is intentional to keep it simple
for beginners).

The repo has three slides but you can easily add more.
Just copy slide3.html and rename it to slide4.html and change the "next slide" and
"previous slide" texts.

I'd also recommend that you append a more meaningful name to the slide. For
example:
slide1_HistoryOfAnimalsIntro.html
slide2_TheEarliestMammals.html
slide3_TheLargestMammals.html
and so on

Keep all your file names lower case so that you don't have to deal with possible linking issues. 

Handy git commands:
1) First setup alias's
   - $ git config --global alias.co checkout
   - $ git config --global alias.br branch
   - $ git config --global alias.ci commit
   - $ git config --global alias.st status
2) For adding (aka staging) files that have changed, I always use 
   - $ git add -u
     This is because there's likely a chance that there is a file I don't want added. The "-u" says to only add tracked files.
   - $ git ci -m "here is where you add a comment for the change you are plan to push to githug pages.
   - $ git pull 
   Always do a pull first before you push
   - $ git push
   This pushes your changes to git.
3) When you get more familiar with git, using git stash is very handy to store changes momentarily
   - $ git stash save put_a_name_here_to_describe_the_change
   - $ git stash apply
   - $ git stash list
   - $ git stash drop the_index_of_the_one_you_wish_to_drop   
     Eg. git stash drop stash@{0}