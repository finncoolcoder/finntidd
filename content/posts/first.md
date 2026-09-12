+++
date = '2026-09-12T09:54:51-04:00'
draft = false
title = 'First Post'
+++
Welcome to my new website. It is based off of hugo, hosted on neocities, and it utilizes a complex workflow that allows me to push changes to my hugo site without needing to download anything on my computer. Github actions allows me to add content or change configurations in hugo without ever using a command line. All I have to do is commit my changes and they are automatically pushed to neocities. The beauty of this is that I can also push my site to neocities from my computer by simply running
```
 git pull
 ```
 and then 
 ```
 git add .
 git commit -m "Update site"
 git push
 ```
 This updates my computer with the most up to date version of the site, and then later, after I have changed things locally I can send these changes out to github, and github automatically sends them to neocities. An elegant solution.