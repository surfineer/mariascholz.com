# My Website

## Domains
**maria-scholz.com** / **mariascholz.com**

## Installation

All files were uploaded to this Github repository. Since I am hosting my page on Github, I only needed to activate the Github Pages feature.

## Testing

I use https://whatwg.org/validator/ regularly to probe my website for HTML Conformance.  

## Deployment

I use VSCode to build on my app files locally. I have it hooked up to my Github Repo, so all I gotta do is the following steps when deploying a new iteration: 

1. `git checkout -b [branch_name]` create a new branch for my iteration commit (since I try to publish new changes every week I will name the branch after the calender week, eg. _"week_43_update"_)
2. `git add .` adds all edited files to the staging area
3. `git commit -m "[commit message]"` commits staged files with a message
4. `git push origin [branch_name]` pushes my local files to Github repo
5. `git checkout main` change back into local main branch
6. `git pull origin main` syncs my local main with Github repo to be rebased
7. `git branch -D [branch_name]` deletes the previously created iteration branch 

I can just repeat these steps every week when I want to deploy the changes made to my website. 

## Hosting

At the moment my website is static and I can use Github Pages for hosting. Once I will scale it up and make it more dynamic, I will be switching to Vercel or GCP for hosting.





