# GitHub Pages

## Cheatsheet


#### Conditions
- Have a GitHub repo named `<your username>.github.io`
- Have a GitHub repo for you project
- Your `index.html` file should be at the base of the repo (when you visit your repo on GitHub, you shouldn't have to click into a directory to see `index.html` in the list of files)


## Initial Set Up

* Create a branch in your local repo called `gh-pages`
```
git checkout -b gh-pages
```

* Push your `gh-pages` branch to GitHub
```
git push origin gh-pages
```

* Switch back to your master branch (this is where you are doing all of your work!)
```
git checkout master
```

* Check it out!
`<your username>.github.io/<your project repo name>`

Ex: [http://katewood.github.io/css-positioning-kate/](http://katewood.github.io/css-positioning-kate/)

## Updating

* Switch to your master branch before updating your code:
```
git checkout master
```

* After making changes, add, commit, and push your master to GitHub:
```
git add -A
git commit -m "some commit message here"
git push origin master
```

* Switch to your `gh-pages` branch:
```
git checkout gh-pages
```

* Merge your changes to the `gh-pages` branch:
```
git merge master
```

* Push your gh-pages branch to GitHub:
```
git push origin gh-pages
```

* Switch back to your master branch:
```
git checkout master
```

