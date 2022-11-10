# bssofoundry
A repository for the Behavioural and Social Sciences Ontologies Foundry website

## deployment of updates: 
1. `bundle exec jekyll build` - builds static html in the _site directory
2. `bundle exec jekyll serve` - (optional) to test the build locally
3. copy the contents of _site directory to a temporary folder
4. `git checkout gh-pages`
5. paste the saved contents of _site directory from the temporary folder  into root of project (replacing old files)
6. do not remove CNAME file! 
7. commit gh-pages branch and github will do the rest

