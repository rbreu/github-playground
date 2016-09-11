# github-playground

A project for learning the github workflow.

Feel free to open pull requests and play around to see how the github workflow works.


## The basic workflow

1. Fork this github repository. Use the "Fork" button on the github page. You have now your own version of this repository you can submit changes to.
2. Clone your fork of the repository, e.g:

        git clone git@github.com:YOURNAME/github-playground.git

3. Create a local branch that holds your bugfix:

        git checkout -b my-fix-branch

4. Fix the bug!
5. Commit:

        git add .
        git commit -m "I fixed the thing!"

6. Push your local commit to your github repository:

        git push origin my-fix-branch

7. Make a pull request on the github page
8. Get changes from main repository back into your fork and clone.
   First, make the main repostory known within your project (only do this once):

        git upstream git@github.com:rbreu/github-playground.git

   Then you can get the changes by either:

        git pull upstream master

   or:

        git fetch upstream
        git checkout master
        git rebase upstream/master

  Push to your clone

        git push origin master


## Links

* [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
* [GitHub Standard Fork & Pull Request Workflow](https://gist.github.com/Chaser324/ce0505fbed06b947d962)
