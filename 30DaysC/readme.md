This is a set of files and folders meant to go with 30 Days of React @ https://www.youtube.com/playlist?list=PLlxurZn3gw7r7JX_JRfmKqY32IOrSFTSB.<br>
You must install dependencies (`yarn/npm add/install create-react-app`), but the other files are provided here for use with this playlist.  

Suggestion to get started: 

1. Create your own overarching repository that will hold all 30 days as described above and make sure it's also remote
2. cd into overarching repository you just made
3. run `yarn/npm add/install create-react-app`
4. then install CRA dependencies for each day/folder, day01 through day30, by running `yarn create-react-app day##` for each day 01 through 30.  These folder names will match what's here.
5. download this folder/repo, 30DaysC, and overwrite all files in your overarching repo (day01 from this repo should overwrite day01 in your repo)
6. run `git add .`
7. run `git commit -m "base project files uploaded"`
8. run `git push` (probably will tell you to do the upstream thing if this is your first push, go ahead and do it)
9. Now, assuming you did this on master branch, your set-up is done for all 30 days.

then for each day/project:
* cd into that day's folder/project
* create new branch for each day/project
* run `yarn start`
* do your current day of react
* run `git add .`
* run `git commit -m "day ## done"`
* run `git push`
* merge branch into your overarching repo
