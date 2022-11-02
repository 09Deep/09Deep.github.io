# modern-resume-theme [![Gem Version](https://badge.fury.io/rb/modern-resume-theme.svg)](https://badge.fury.io/rb/modern-resume-theme) ![CI workflow](https://github.com/sproogen/modern-resume-theme/workflows/CI%20workflow/badge.svg?branch=master)

*A modern simple static resume template and theme. Powered by Jekyll and GitHub pages.*  
*Host your own resume on GitHub for **free!***
# How to host your resume online

### The goal of this readme is to explain its readers the process of hosting a resume online with the use of technologies such as GitHub, GitHub pages, Markdown and Jekyll.

### Before starting this guide we assume that you already have a resume formatted in markdown language.

Don't know what a markdown is! Don't Worry I have excellent resources that will help you out in learning markdown. 
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [A book by Andrew Etter](https://read.amazon.com/?asin=B01A2QL9SS&ref_=kwl_kr_iv_rec_1&language=en-US)


Now since you have learned markdown we assume that you created a resume in markdown as well.  


Following steps need to be followed to host a resume online.

### Step 1: Create a GitHub account

What is a github?
 - Github is an online hosting service that uses git to help people   tracking their progress, as well as allowing multiple people to work on the same code flawlessly. 

What is git?
- As andrew Etter expalins in his book Modern technical writing git is a decentralized version control (DVS) system that helps people collaborating on the same project. Means let's say if multiple people are working on the same code, then it becomes easy to collaborate if each person gets their own copy. When these people are done with their tasks everyone's copies can be merged online. Moreover it also tracks the history of the main copy so you can get back to the previous version whenever you want.



1. If you already don't have github account, create one.
2. To create a github account you need to go to [github.com](https://github.com)
![Github signup page](https://github.com/09Deep/09Deep.github.io/blob/main/images/Github%20signup.png)
3. Create an account by clicking on sign up and then filling out all the necessary information.
![Github signup requirement](https://github.com/09Deep/09Deep.github.io/blob/main/images/github%20signup%20email%20prompt.png)
4. Now to create a local git repository use the `git init` command.
 

- Once your Github account is ready create a new repository locally and name that repository as `<username>+.github.io` .



### Step 2: Choose a descent resume theme from a jekyll themes.

Before we get going..

What is Jekyll?
- Jekyll is a static web-site generater, means you supply content and templete or structure to jekyll and process those and gives you a static website back. As Etter's explanation content is usually a markdown file and templete is a combination of HTML+CSS. Templete makes sure how your content will look like on the website. 

What is Jekyll themes?
- Jekylll themes is a collection of lots of templetes. If you do not want to design the formate for your content, you can choose any from these available themes.     

1. You need to go to [jekyll-themes.com](https://jekyll-themes.com)
2. In search bar search for resume or CV
3. Now different resume themes will load.
4. Choose any theme that is suitable for your resume.
5. For my resume I chose [modern-resume-theme](https://jekyll-themes.com/modern-resume/)
6. Once you choose a theme 3 options will appear: demo, download, and repository 
7. Click on the download button and a zip file will download.
8. Once the file gets download unzip it to the loaction where we created the git repository in previous step. 
9. Now in in the command line navigate to the same directory where the  git repository is created. 
10. Type the following 2 commands one by one in the command line.
    1. `bundle install`
    2. `bundle exec jekyll serve`
11. After executing these commands a following message will appeare. 
 [Sucess message from jekyll](https://github.com/09Deep/09Deep.github.io/blob/main/images/sucess%20message%20after%20jekyll%20launch.png)
12. Now you can see what an actual templete looks like without any changes.

### Step 4: Open up config.yml file and made changes according to your profile.

### Step 5: Open up command line and start jekyll on this folder

### Step 6: If all the changes are according to your preferences then push this repository on GitHub

### Step 7: Open up GitHub and select this repository

### Step 8: Go to pages menu inside settings of this repository.

### Step 9: Choose branch on which your code is spenitting and then click on the save button.

### Step 10: After couple of seconds refresh your page and a link would be generated.

### Step 11: Click on that link and a website will open up that is hosting your resume online.

## Acknowledgement

This theme is developed by [Sproogen.](https://github.com/sproogen/)  
This theme is taken from [jekyll-themes.com](https://jekyll-themes.com/modern-resume/)
