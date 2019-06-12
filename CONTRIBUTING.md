## INSTRUCTIONS FOR CONTRIBUTING

1. Fork my repo
2. On your computer clone your forked reporeat
3. `cd opensource-demo`
4. Add this repo as an upstream: `git remote add upstream https://github.com/alexewu/opensource-demo.git`
5. Before you make a change to the code:
`
git fetch upstream
git checkout master
git merge upstream/master
git checkout -b your-branch-name
`
6. Now you are on your feature branch! Make a new file following the following naming standard:
`touch yourName-favorite-movies.txt`
7. Add your favorite movies to this file
8. When you are ready to push your changes to the open source project:
`
git commit -m "{{YOUR COMMIT MESSAGE HERE}}"
git push origin your-branch-name
`
9. Now go to your forked repo
10. Make a pull request
