Homework3
=========

To see this page please visit: http://cdracars.github.io/Homework3

To setup project on Cloud9 run the following:
--------------------
git checkout -b gh-pages

git add .

git commit -m "Make pages visible"

git push -u --all

Change default branch on github in settings to the new gh-pages branch, then run the following on Cloud9:
--------------------
git branch -D master

git push origin :master

Add URL to the README.md file on the project
---------------------
Add your url which follows this pattern: http://YOUR USERNAME.github.io/PROJECT NAME

Example if your **username** was **John_Doe** and **project name** was **KindaGeneric**: http://John_Doe.github.io/KindaGeneric

Create a .gitignore file
---------------------
The file needs to have the preceding dot (.gitignore). inside this file make a single entry of .c9

See example here:https://github.com/cdracars/Homework3/blob/gh-pages/.gitignore

Overview of responsive design
---------------------
http://www.onextrapixel.com/2012/04/23/responsive-web-design-layouts-and-media-queries/

