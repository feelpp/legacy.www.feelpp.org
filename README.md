www.feelpp.org
==============

Feel++ Web Site

## Principles
The markdown is on the master branch.
Github serve the branch gh-pages.

## How to publish
- On the branch master
```
jekyll build // Will generate the _site directory
```
- On the branch gh-pages
Copy the unfollowed _site in . (rsync suggested)
```
git commit -am "up web site"
```

## To create a news
Go in the `_post` directory and create the `.markdown` file you need.
It will be generated until two days.
______________
Does not work
--------------

## To use the `RakeFile`
```
sudo gem install bundler
```
Alias for zsh:
````
alias rake=noglob rake
```

## How to create a news
In the branch `master`
```
rake new_post[my-new-post]
```
