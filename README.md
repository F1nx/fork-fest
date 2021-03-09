# fork-fest
A GitHub script to update all of your forks for you!

Why?
-

Other applications are difficult to use, or require you to make modifications to repositories rather than meeting you half way. In contrast, this script is made with bash and uses common dependencies developers are likely to be familiar with: `curl`, `jq`, `git`, & `gh`.

Usage
-

If you would like to update a fork, run the script with the name(s) of your repository as the argument. Similarly, if you want to update all of your forks, just add "all" as an argument. Doing either of these will prompt you to authenticate `gh` by logging into GitHub before proceeding to update. **Note that currently this script only updates the `master`/`main` branch for forks of other people's projects.**

Contributing
-

If you would like to improve this project, it is advised that you create a mock fork so that you do not make any unintended commits on your own repositories. From there, you make a branch for the older commit before testing so that you can do it as many times as needed.
