# Notes

## Setting up gh-pages

- keep docs in the .gitignore, you don't want a docs directory on github (this is my most frequent cause of merge conflicts)
- set up an empty branch called gh-pages
- run `use_github_action("pkgdown")` to set up your workflow
- in the settings for your repo, under Pages (https://github.com/softloud/helpu/settings/pages) set the source to branch: gh-pages and folder: /root
