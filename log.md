# 100 Days Of Code - Log

### Day 1: July 26, 2022

**Today's Progress**:  I refactored a function for the irr calculations in the grafana portfolio and updated the files that calls it. 

**Thoughts** Im breaking down the function so it can support an unlimited amount of arguments, since it was originally hardcoded for two bank accounts. In the same process, im breaking every function into smaller more atomic functions and realizing that if I organize the inputs a little better, I can re-use many of them. 

**Link(s) to work**
1. [Grafana Portfolio](https://github.com/portfedh/portfolio_grafana)

### Day 2: July 27, 2022

**Today's Progress**:  Im brekaing up another function for the irr calculations into smaller functions to be able to unit test. Work in progress.  

**Thoughts** Smaller functions provide more reusablity and testability. Doing this is good practice, and a little tedious. I wish I could do this faster.  

**Link(s) to work**
1. [Grafana Portfolio](https://github.com/portfedh/portfolio_grafana)

### Day 3: July 28, 2022

**Today's Progress**:  Finished simplifying irr functions. Also updated run files to run from MacOs and Linux. Made a change to pull latest docker image before running. 

**Thoughts** Creating run files for linux and Mac allows for testing the code in different platforms. Since i've been developing in both, I realized that the docker image needs to be pulled down to get the latest version before running. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 4: July 29, 2022

**Today's Progress**:  Created the first version of the Readme.md

**Thoughts** I kept putting this back because its a bit tedious, but it really helped me define more clearly the goals for the project and how each thing I code aligns with the bigger picture. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 5: July 30, 2022

**Today's Progress**:  Created the first version of the Readme.md

**Thoughts** I kept putting this back because its a bit tedious, but it really helped me define more clearly the goals for the project and how each thing I code aligns with the bigger picture. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 6: July 31, 2022

**Today's Progress**:  Created the first version of the prices file for the IBKR account. 

**Thoughts** Not a lot of coding progress because I had to create the input file. I will do more coding tomorrow. Jupyter notebook is great for testing code before creating a whole script.  

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 7: August 2, 2022

**Today's Progress**:  Modified the subtotal script, eliminating the sub-asset allocation functions. These functions will need to be transfered to another script and will now have to consolidate two accounts, the current GBM account and the new IBKR Account. 

**Thoughts** The simple task of adding an extra account to the report is quickly adding complexity to the whole system. Changes will be worth it, since adding more accounts will be now easy, but for now it involes refactoring a lot of code. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 8: August 3, 2022

**Today's Progress**:  Created a subtotals file for the new IBKR Account. 

**Thoughts** I now have two subtotal output csv files where I used to have one (one per each account). I will need to create a new script to consolidate all accounts, or do the consolidation directly in Grafana. Since these changes will break production, I will have to go back and separate the code into a new feature branch. 

### Day 9: August 4, 2022

**Today's Progress**:  Separated subtotals per account in one file and subtotals for all accounts in another file

**Thoughts** After a few weeks of adding code, everything is finally working again. Now to document and clean up everything.

### Day 10: August 5, 2022

**Today's Progress**:  Cleanup of modified scripts. Added short descriptions for all scripts.

**Thoughts** Hard part of this 'sprint' is done. Now to document all changes before making script changes for the first user. After that the next sprint will be to add the third user and see what code changes need to be made. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 11: August 8, 2022

**Today's Progress**:  I documented the functions created in past days by adding docstrings to all functions in daily_balance.py

**Thoughts** Documentation is just as hard as coding, just in a different way. Choosing the right words to be descriptive and short is very complicated. Sometimes I feel the function better understood as 5 lines of pure code, instead of 15 with Docstrings. I hope it helps anyone looking at the function without context and that it will help me when I take alook back after some time. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 12: August 9, 2022

**Today's Progress**:  I created my home GitHub Markdown page and added some code to display the languages, commits and information that might be useful for someone visiting my profile. 

**Thoughts** Mixed feelings about this. Learning to code is the real goal, so it feels like an unproductive day. On the other hand, to be able to code with others and contibute in larger projects, I need to be able to show other developers what my projects are about, what I can do, and where my interests lie. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfedh)

### Day 13: August 10, 2022

**Today's Progress**:  Starting to update the code for the second user of the portfolio project. 

**Thoughts** Having different users is helpining my with the code, but I feel that there is an underlying problem with the structure of the code. Once its in a more decent state, I will try to show it to someone to get some feedback and see how to restructure it.  

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 14: August 11, 2022

**Today's Progress**:  Continued to update the code for the second user of the portfolio project. 

**Thoughts** I finished updating the code for most of the scripts. I only left one script missing which I changed in a bigger way. I plan to update this when I have more energy to make sure I have as few bugs as possible. Its working out better than I thought. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 15: August 13, 2022

**Today's Progress**:  Updated all files for second user 

**Thoughts** Finished updating python script for the second user. Updating for a second user allowed me to find some minor bugs and improve the code. Readability is improving and the structure is getting cleaner. Next up. Debugging for both users. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)


### Day 16: August 14, 2022

**Today's Progress**:  Added a post to my blog, learnt about greedy algorithms and debugged the changes I made on my project

**Thoughts** Just as I was finishing up I found one more function to refactor. Ill get it tomorrow. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 17: August 15, 2022

**Today's Progress**:  Refactored the last complex function into several simpler ones for unit testing. 

**Thoughts** This part of coding feels like a will contest. A bit boring but very important. After I finish refactoring this, another hard thing: Im going to check all of the functions in all the scripts to see if some are reduntant and can be deleted. Then on to unit tests. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

### Day 18: August 18, 2022

**Today's Progress**:  Refactored more functions.Realized there is a lot more refactoring to be done. Added documentation to the simpified functions. 

**Thoughts** After spending a while adding docstrings and typehints to the functions, I realized that there are other files which will also need to be Refactored. I estimate it will take about two weeks of doing this before im done. This is too long. Its important for unit tests, but its tedious work and I wont learn a lot by doing it. I will switch to other tasks and slowly try to refactor a bit of code everyday until im done. Starting to use hithub issues  and Jira to manage my to dos.

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Day 19: August 19, 2022

**Today's Progress**:  Spent today trying to get a relative price sql query to work in Grafana. 

**Thoughts** On the first version of the Grafana dashboard I used InfluxDB. Since it's a more niche database, I decided to switch it for MySQL so I could learn more about it. Now Im trying to get a Query to work. Its MySQL, but it also uses grafanas local variables, so its hard to google for help. I know Ill get it eventually. 

## Day 20: August 20, 2022

**Today's Progress**:  Spent another day figuring the relative price sql query to work in Grafana. No luck yet.

**Thoughts** I parsed the SQL querry and googled all the information to try to understand how it works. Partially succeded. Wrote several queries to try out but none worked. I wish there was an SQL debugger that could help out more to understand why querries fail.

## Day 21: August 21, 2022

**Today's Progress**:  Changed task to take a break. Experimented with ways to keep user files in folders and running them from there instead of the root folder. Import sys worked, but since I use more than one computer to code, its not a good solution. I figured I could create an import file for each user at the root directory and import from there. Im going to give it a try in a new branch. 

**Thoughts** I parsed the SQL querry and googled all the information to try to understand how it works. Partially succeded. Wrote several queries to try out but none worked. I wish there was an SQL debugger that could help out more to understand why querries fail.

## Day 22: August 22, 2022

**Today's Progress**:  I tried several ways of using the __init__.py files in the scripts package as well as the user files with no success. 

**Thoughts** No tangible progress today, but that can happen sometimes

## Day 23 and 24: August 23 & 24, 2022

**Today's Progress**:  Learnt how to properlly use the __init__ file and how to update the sys.path in two 12 hour sessions. 

**Thoughts** I didnt really touch the project today, mainly it was learning, but I think I know how to solve the problem now. I found an excellent explanation online on a medium article by Dr. Varshita Sher. I read it once, went a second time coding everything, and a third time playing arround with the code. I think Ill get it. 

## Day 25: August 25, 2022

**Today's Progress**:  No coding today. I worked on a blog post documenting in detail the CurrentSensorsMQTT project. 

**Thoughts** I worked on my blogpost. Got the explanations done in a first draft. Im finding documentation harder than coding sometimes. 

## Day 26: August 26, 2022

**Today's Progress**:  Added images to the blogpost. First draft finished. Need to review text and follow SEO rules before publishing. I also used what I learnt and finally solved the problem. Merged the new branch. Now user files dont need to be run in root file anymore. 

**Thoughts** It took a long time to understand, but the changes in code were not very long. It was an important milestone. I feel proud of myself. 

## Day 27: August 27, 2022

**Today's Progress**:  Explored Github and the things you can do there. Created a Security Policy file. Learnt how Dependabot works, fixed an issue and merged Dependabots pull request. Added a code scanning alert and added branch protection rules. 

**Thoughts** Today I worked a long time in the Wordpress blog post for the CurrentSensorProject. I reviewed the text, finished adding images and then went over all the SEO recomendations for writing an effective blog post. It's a very interesting subject. Im hoping to learn more about it later. I didnt feel like I could concentrate on hard coding problems, so I spent the time learning and poking arround all the things you can do in a Github repository. I remember when I started coding, GitHub felt very alien, but its starting to get more familiar. Im enjoying my coding time more and more every day. Its definatelly something I now look forward to. Next up. Learning GitHub Actions and adding Unit testing to the code. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Day 28: August 28, 2022

**Today's Progress**:  Published my fist long form blogpost of how I made an energy monitor during the pandemic. 

**Thoughts** It took several days to write the post, and then another couple of days to get the site to pass the basic SEO tests in wordpress. I finally published and sent it to several friends to check out. I got immediate feedback from my girlfriend: Fix the images to make them look professional. It feels very rewarding to put your stuff out there. 

**Link(s) to work**
1. [IoT Energy Monitor](https://pablocruz.io/iot-energy-monitor/)


## Day 29: August 29, 2022

**Today's Progress**:  Created the first unit tests for the portfolio visualizer. 

**Thoughts** I spent a really long time refreshing how to unit test and deciding where to start. I started by the script functions and discovered I should create another module for input validation. I also spent a long time understanding how to unit test a pandas dataframe. In the end I was able to finish. This was a good milestone and I feel very good about it. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Day 30: August 30, 2022

**Today's Progress**:  Created the second unit tests for the portfolio visualizer. 

**Thoughts** I started working on the tests for the second script: irr_calculations.py. I found an issue that needs correcting in a function (It requires as CSV as an input) and then ran into the huge mess of comparing dateTime variables. Turns out they can have the same date and different time and you wouldnt know if its not in long format. I was able to fix it, and so Im in my way again. A productive day. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Day 31: September 1, 2022

**Today's Progress**:  Finished adding all unit tests for irr functions. 

**Thoughts**Unit testing is very helpfull. Besides testing, it also creates an explanation of what the code should output. This can help someone understand the purpose of the function with a working example. In my case, it also allowed me to check that my functions are simple and testable. I also discovered that dealing with pandas dateTime in the index column can get complicated easily. Happy to be making progress slowly. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Day 32: September 2, 2022

**Today's Progress**:  Created unit tests for daily_shares.py 

**Thoughts**Today i read an in depth article by Real Python about unit testing, integration testing and test driven development. It makes a lot of sense. As I created the test for the first function in daily_shares.py I realized there are several consistency problems that needed to be adressed, and some refactoring. Its a slow process, but the code ends up more readable, better organized and much less error prone. Now that im getting a better idea of how they work, I also realize why developing tests as you write code is a much better solution than first writing and then refactoring. Im also understanding the importance of CI CD pipeline and automated testing. Im going to learn more about it soon. The whole thing is a very good idea. I wonder how this kind of processes could be implemented to non software development (architecture, engineering, manufacturing, etc).

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)


## Day 33: September 3, 2022

**Today's Progress**:  Created second unit test for daily_shares.py 

**Thoughts** While working on todays unit test I noticed that the function could be improved. It needed to output information in ascending order, as an integer, and with the index column labeled. I made the modifications and then made the unit test. Timestamps are complicated, since two equally looking timestamps can have different frequencies. Fortunately I was able to finish the test. Just one more python file to go. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Day 34: September 4, 2022

**Today's Progress**:  Renamed function in daily_shares.py and refactored.  

**Thoughts** Finished all the minor style changes to made code more readable. It was a sunday and I was not in my most productive setup, so coding was a bit low. I also have too many activities, so I have to reorganize to see where Im at and re prioritize. 

**Link(s) to work**
1. [Grafana Portfolio Code](https://github.com/portfedh/portfolio_grafana)

## Break: September 5, 2022

**Today's Progress**:  No coding today. A planning day.  

**Thoughts** Today I went over all my to do's, my learning notes and my learning list. I organized what I need to learn, what I want to do with my blog next and what needs to be done to finish my current project. Then I went over my goals for the week for those three things. I feel much better now that I have a set goal again. 

This weeks Goals:
    - Project: Portfolio grafana. Finish unit tests and set up github actions to run then after every commit. 
    - Project: Fundamental analyisis. Update code to V2 and make sure it runs correctly. 
    - Blog:Correct language for current sensor post. 
    - Blog: Create first draft of Fundamental Analysis post
    - Learning: Set up newsboat, remoteit connection, and fix ulauncher
    - Learning: Make a summary of Alice & Bob learn application security


## Day 35: September 6, 2022
**Today's Progress**:  Fixed some issues in unit tests. Learning day

**Thoughts** Today I learnt how to run Unit Tests from VsCode, as well as adding a pre-commit hooks in Git to automatically unit test before adding a commit. 

## Day 36: September 7, 2022
**Today's Progress**:  Finished configuring git pre-commit hook to run all tests befor every commit. 

**Thoughts** Yesterday I managed to run all tests from VSCode with a click. I wanted to automatically run them before each commit, so I found out about Git Hooks. I tried configuring the pre-commit hook but kept getting errors. To solve it, I re-read over how __init__.py files work, but that was not the issue. When I realized the problem was the VENV, I spent a while figuring out how to set it up. I succedeed. I also decided to keep a copy in the root file to backup and keep it in version control. This was the post that inspired me. 

   https://www.giacomodebidda.com/posts/a-simple-git-hook-for-your-python-projects/

## Day 37: September 8, 2022
**Today's Progress**:  Created new test: test_daily_balance.py -- create_df(file_name)

**Thoughts** I created a new test for the first function in daily_balance.py. The functions name is create_df(). It takes a string with a csv filename as input and outputs a dataframe made out of that csv. To avoid having to deal with external files, I learnt how to use unittest.mock by adding @mock.patch and a return value within the test function. I was able to get it to work correctly, but the logic behind decorators is something I still dont understand. Still its good to know how to use it. This is the link to the video that helped me learn how to do it. 

https://www.youtube.com/watch?v=WFRljVPHrkE

## Day 38: September 9, 2022
**Today's Progress**:  Created new test: test_daily_balance.py -- test_daily_balance()

**Thoughts** As I have more tests, I also have a larger number of examples where I get mock data, and testing code, so I see improvement. I also know that there is repetitive code here. Some of the functions do almost the same things. Once everything is tested, I will go over it again and refactor to avoid repeating myself. Yesterday I had a long work day, and It was very hard to force myself to code today. 

## Day 39: September 10, 2022
**Today's Progress**:  Created new test: test_daily_balance.py -- test_add_total_column() and test_add_df()

**Thoughts** Almost done with unit tests for the project. Doing them helped me optimize code and has also helped me identify duplicate code I can refactor to make the project simpler. Im amazed how slow I advance and also how the program gets steadily better. Incidentally, I also just read the 100 days of code rules more carefully and I finally understood what I should link in my project log. Here is the commit for today. 


[test_add_total_column()](https://github.com/portfedh/portfolio_grafana/commit/52eeee7aba6baf9c350bb2851c22fb797ebc5c96)
[test_add_df()](https://github.com/portfedh/portfolio_grafana/commit/634150110f65865775ce9c01ea566ef44d539554)


## Day 40: September 12, 2022
**Today's Progress**:  Switched project to Fundamental Analysis. Rewriting code. 

**Thoughts** After a short break, I need to continue adding posts to my blog . The Grafana Portfolio Project still has a while to go before I can add it, so I had to look for other projects to include. I have several small projects which I could add, but I think that I should probably be starting with my most important projects in case I run out of time. I decided to add my fundamental analysis report next. This is a very cool project but my first version had several mistakes. I corrected the script in another project (stock screener), but now I have to get the changes from the second version to work to showcase it in my portfolio. Im working on refactoring code. I hope Ill be able to add it soon. 

[Second version: Fundamental Analysis PDF. Work in progress](https://github.com/portfedh/fundamental_analysis_report/commit/781ec7c8b46d53f5afa0c4390b41c2a059b1cb28)


## Day 41: September 13, 2022
**Today's Progress**:  Fundamental Analysis Code almost updated. Images and tables done. PDF generation next. 

**Thoughts** Updating the code has been a mixed bag. The code itself required very small changes, but other things slowed me down. One of the imported libraries (Pillow) has a dependency (Kaleido) which doesnt work for some reason if you use a virtual enviroment. After trying to debug for a while I found this out, so I made an Issue request on github and just installed the packages in my global python. I updated most of the code but then I ran into another problem with FPDF. Some functions have been changed/depricated and I need to fix the code for it not to break in the near future. Hopefully Ill be able to finish tomorrow.  

[Second version: Fundamental Analysis PDF. Graphs and Tables are done](https://github.com/portfedh/fundamental_analysis_report/commit/781ec7c8b46d53f5afa0c4390b41c2a059b1cb28](https://github.com/portfedh/fundamental_analysis_report/commit/62ae6d4c6b9269b8ce2ed5e800aa2bffa57ddb7c)
