# [mu]dacity: The Unofficial Udacity Micro-community

### About

This organization is for Udacity students, alumnae, and staff to collaborate on community projects.

### Groups

New members are automatically invited to the `members` group. This group has **read** access to repositories. You can contribute to projects by opening issues, forking repositories, or submitting pull requests.

Upon request, or after **3 accepted pull requests**, the user can enter the `devs` group and have direct **read/write** access to repositories.

The **admins** group is for elevated organization permissions. If you're interested in helping out, please contact the admin group!

### GitHub Page

You can start contributing immediately to the GitHub page repository: [mudacity.github.io](https://github.com/mudacity/mudacity.github.io)

### Our First Project: **Udyssey**

This is a web application inspired by [Randal Olson](https://twitter.com/randal_olson/status/575087050589868032), for planning road trips. There are **two** repositories (one for the web app/back-end and one for the iOS app).

### How to Start Contributing: a Brief Introduction to Git and GitHub

1. From GitHub, fork the repository into your account by clicking the **Fork** button on the top right.
2. Copy the **clone URL** from your own forked repository.
3. Make sure you have [Git installed](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and have it properly configured (and linked to your GitHub account).
4. In your terminal, clone your own forked repository by typing: `git clone https://github.com/<YOUR_USER_NAME>/udyssey.git`
5. Change directories into the new project folder: `cd udyssey`.
6. Add the "upstream" repository (the original one you forked from): `git remote add upstream https://github.com/mudacity/udyssey.git` Note: the GitHub user is `mudacity`, this time.
7. Check out a new feature branch: `git checkout -b awesome_new_feature`
8. Make your edits and changes!
9. Stage these changes: `git add -A`
10. View the staged changes and status: `git status`
11. Add anything you may have missed: `git add [FILE_NAME]`
12. Commit these changes with a message: `git commit -am 'add awesome new feature'`
13. Check out the `master` branch: `git checkout master`
14. Fetch any updates from the repository: `git pull upstream master`
15. Attempt to merge your changes with the updated `master` branch: `git merge awesome_new_feature`
16. Resolve any conflicts (this is more complicated).
17. Push your changes to your own repository: `git push -u origin awesome_new_feature`
18. Open up GitHub and navigate to your forked repository.
19. Open a new pull request.
20. Should usually be as follows: base fork: **mudacity/udyssey** base: **master** ... head fork: **[YOUR_USER_NAME]/udyssey** compare: **awesome_new_feature**.
21. Enter a message and submit :)
