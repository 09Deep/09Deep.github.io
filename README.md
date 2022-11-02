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

- Github is an online hosting service that uses git to help people tracking their progress, as well as allowing multiple people to work on the same code flawlessly.

What is git?

- As andrew Etter expalins in his book Modern technical writing git is a decentralized version control (DVS) system that helps people collaborating on the same project. Means let's say if multiple people are working on the same code, then it becomes easy to collaborate if each person gets their own copy. When these people are done with their tasks everyone's copies can be merged online. Moreover it also tracks the history of the main copy so you can get back to the previous version whenever you want.

1. If you already don't have github account, create one.
2. To create a github account you need to go to [github.com](https://github.com)
   ![Github signup page](https://github.com/09Deep/09Deep.github.io/blob/main/images/Github%20signup.png)
3. Create an account by clicking on sign up and then filling out all the necessary information.
   ![Github signup requirement](https://github.com/09Deep/09Deep.github.io/blob/main/images/github%20signup%20email%20prompt.png)
4. Now to create a local git repository use the `git init` command.

### Step 2: Set up Jekyll on your computer

1. In order to set up jekyll on your computer you need to go to [Ruby's website](https://rubyinstaller.org/downloads/) and download the latest version of ruby+Devkit.
2. Once the download finishes click on that .exe file and do the installation process
3. As soon as the installation process finishes and you click on finish another window will open up with the followint message.

4. You need to enter 3.
5. Then it will ask you to install it again, so you can close that window.
6. Now open up command line and navigate to the same directory where you installed ruby and type the command `gem install jekyll bundler` and hit enter. This will install all the dependencies along with Jekyll.
7. Now check if the jekyll is installed properly you need to type `Jekyll -v` and hit the enter, it should give you the latest version of jekyll.

### Step 3: Choose a descent resume theme from a jekyll themes.

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
9. Now in in the command line navigate to the same directory where the git repository is created.
10. Type the following 2 commands one by one in the command line.
    1. `bundle install`
    2. `bundle exec jekyll serve`
11. After executing these commands a following message will appeare.  
    ![Sucess message from jekyll](https://github.com/09Deep/09Deep.github.io/blob/main/images/sucess%20message%20after%20jekyll%20launch.png)
12. Now you can see what an actual templete looks like without any changes.

### Step 4: Open up config.yml file and make changes according to your profile.

- Inside the .yml file the code is pretty self explanatory. First section is about personal detail such as email and phone number. Second section is about brief introduction about yourself. Then third section is divided into 4 parts 1) Projects, 2) Experience, 3) Education, 4) Skills
- I am attaching my markdown resume parts along with the changes that are needed in this .yml file.

- Once the changes are done Open up command line and start jekyll on this folder
- Then go to port 4000 using any web browser, and you will be able to see all the changes here.

### Step 5: Push all the changes into github

- First thing you need to do is add changes to the area using `git add` command.
- Then Use the `git commit` command to commit all changes
- Then push the changes on github using `git remote add origin https://github.com/username/new_repo` command.
- while using the above command new repository's name should be `<username>+.github.io`
- Open up GitHub and go to this repository

### Step 6: Using Github pages host your resume

- Inside the repository go to the settings menu.
- Inside setting menu there is Pages button on the left hand side pannel. Click on that pages menu.
- Choose branch on which your code is spenitting and then click on the save button.
- After couple of seconds refresh your page and a link would be generated.
- Click on that link and a website will open up that is hosting your resume online.

## FAQ

**Q:** Why are we hosting resumes online?  
**A:** Using the conventional word document or pdf it uses much more space. And whenever you make changes to it old copies are of no use and sometimes sits in your computer for years. On the other hand when you use online hosted resume you do not have to worry about space on all of your devices. When it comes to update you do not need to send everyone updated copies. You just need to share link of your resume once and then all of the updates will reflect to it.

## Acknowledgement

This theme is developed by [Sproogen.](https://github.com/sproogen/)  
This theme is taken from [jekyll-themes.com](https://jekyll-themes.com/modern-resume/)
Special thanks to Vlad, and Alyson for giving helpful feedback.
