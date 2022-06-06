# Module 01

## Challenge

This challenge was to clone the starter code and refactor it to meet the Acceptance Criteria.

### Acceptance Criteria

* GIVEN a webpage meets accessibility standards
* WHEN I view the source code
THEN I find semantic HTML elements
* WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
* WHEN I view the image elements
THEN I find accessible alt attributes
* WHEN I view the heading attributes
THEN they fall in sequential order
*  WHEN I view the title element
THEN I find a concise, descriptive title

## Resolution

1. Create repository in GitHub
1. Create local repository and make main branch using GitBash terminal
```bash
$ mkdir Module 01 Challenge
$ git init
$ git branch -m master main
```
3. Clone starter code from Bootcamp Spot
```bash
$ git clone https://github.com/coding-boot-camp/urban-octo-telegram.git
```
4. Edit HTML and CSS files to meet Acceptance Criteria
1. Set remote repository from GitHub URL
```bash
$ git remote set-url origin https://github.com/carolinemae/Module-01-Challenge.git
```
6. Forcefully push local repository to remote repository
```bash
$ git push -u -f origin main
```
7. Go to GitHub repository and deploy URL
7. Upload GitHub URL and deployed URL

## Comments

I struggled with the fixed header hiding content when selecting links to relative anchors and then also with pushing my local repo to my remote repo initially, however, after a lot of research on Google, I managed to get this to work (I think). I do believe the lessons on GitBash and any troubleshooting within the application weren't covered enough in class and required a lot of researching. Some of the commands I have used to complete this challenge were not really covered.