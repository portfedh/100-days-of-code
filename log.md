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

[Second version: Fundamental Analysis PDF. Graphs and Tables are done](https://github.com/portfedh/fundamental_analysis_report/commit/62ae6d4c6b9269b8ce2ed5e800aa2bffa57ddb7c)


## Day 42: September 14, 2022
**Today's Progress**:  Fundamental Analysis Version 2 Ready.  

**Thoughts** Code was updated and ready. It looks much cleaner and I was happy to be able to set it up. There are lots of possible improvements I noticed and several new bugs I found, but it works for now. Ill clean them up slowly. Now that its done, its time to get back to finishing the grafana portfolio and to create a blog post showcasing the project.   

[Second version: Fundamental Analysis PDF. Ready and Merged](https://github.com/portfedh/fundamental_analysis_report/commit/0e584ba59a6ccb6005df278a4029547f8c0f1f31)


## Day 43: September 15, 2022
**Today's Progress**:  Finished Unit Tests for Portfolio Grafana.  

**Thoughts** Unit tests were finished and code was tested and is working. Reviewed a bit of the best practices for merging, forking, and deleting branches. Everything is slowly starting to click. Now to solve the pending issues and eliminate duplicate functions.   

[Portfolio Grafana: Merged Unit Tests](https://github.com/portfedh/portfolio_grafana/commit/c915131ea7b844bbf8c1a6f5730aad53870ddb77)


## Break: September 16, 2022

**Today's Progress**:  No coding today. Worked on the next blog post and was to tired to code.  

## Day 44: September 17, 2022
**Today's Progress**:  Started refactoring functions in grafana portfolio

**Thoughts** Today I spell checked all the code. When writing unit tests I notices some of the functions were being duplicated, so I refactored the code to eliminate duplication. Tomorrow I will make sure all function names and descriptions are clear and up to date, both for functions and tests. The code starts to look better and better with every pass. 

[Portfolio Grafana: Spelling corrections ](https://github.com/portfedh/portfolio_grafana/commit/1769aa9eb033a851b7723bd609f9b08c5047738a)
[Portfolio Grafana: Elimination of duplicate functions](https://github.com/portfedh/portfolio_grafana/commit/239f7f2fabb37cd1dc24108ea3ae8ac9eadb33bb)


## Day 45: September 18, 2022
**Today's Progress**:  Finished refactoring functions in grafana portfolio.

**Thoughts** Today I refactored all the functions in the grafana portfolio. The process was simpler than I thought, thanks to Visual Studio Code. The IDE is really great and I like it more everyday. What didnt update was the docstrings, module intro and test names, so Im going over everything slowly to update it and clean it up. The code is looking much cleaner and Im very happy Im doing this. Im learning a lot.  

[Portfolio Grafana: Refactored functions ](https://github.com/portfedh/portfolio_grafana/commit/74b7af057a88fafcab5ae7cabfa85d653d99482c)


## Day 46: September 19, 2022
**Today's Progress**:  Updated docstrings for all functions. Started making docstrings for unit tests. 

**Thoughts** Today I finished updating docstrings for all functions. Everything is clean and makes sense. I started adding docstrings to unit tests. They bring clarity and make the code look more professional. They are overall good habits, but I like more the creation process than the documentation process. The good thing is that once I know how to do it, I will document as I go, and hopefully everything will be easier on the next run. 

[Portfolio Grafana: Updated Docstrings for all functions. ](https://github.com/portfedh/portfolio_grafana/commit/eef6c18c7c663b281f36a1379953bfebfd38a7d1)
[Portfolio Grafana: Add docstrings to test_daily_balance.py ](https://github.com/portfedh/portfolio_grafana/commit/966db63b1ef63401cfc353a6eab8f98dc2944a84)


## Day 47: September 20, 2022
**Today's Progress**:  Created docstrings for all  unit tests. 

**Thoughts** Today I finished updating docstrings for unit tests. Tomorrow I will try to close as many issues as possible before merging and turning to integration testing. 

[Portfolio Grafana: Add Docstrings for all unit tests. ](https://github.com/portfedh/portfolio_grafana/commit/7e229a2fcc702afef9e1eb0e710961c45e51dc9a)


## Day 48: September 22, 2022
**Today's Progress**:  Made an excel with a realistic mock-up user file for integration testing.

**Thoughts** When starting to make my mock up file, I realized I needed to calculate monthly balances + cash for a fake investment portfolio. To make something coherent which could help as an integration test, I created a file of someone who has a 60/40 portfolio and invests $1,000 dolars per year in that account. It took a while, but I figured out how to do it. Tomorrow I will make another one and will be ready to add the user files and then the integration test. Everything takes so much time! Slowly on my way. 


## Day 49: September 23, 2022
**Today's Progress**:  Added my second bit post on my blog: Automating a financial report using python.

**Thoughts** It took a really long time, but I finally published this second project using python. Editing images, adding alt text, reading and re-reading, changing titles. Everything took a very long time. I will probably still make lots of changes to the post in the future, but it was good enough to publish and Im very proud of it. 

[Blog Post: Creating a financial PDF report unsing python. ](https://pablocruz.io/python-financial-report-pdf/)


## Day 50: September 24, 2022
**Today's Progress**:  Reviewed all my Corey Schaffer notes on OOP. 

**Thoughts** I went over my notes on Corey's 6 videos on OOP in python. I had my editor open and kept experimenting with the code and complimenting my notes as I went along to make sure I understood. I feel I have a grasp on the basics. Now I need a lot of exercises to understand the use cases  and get it into muscle memory. 

[OOP Youtube Video Series: Corey Schafer. ](https://www.youtube.com/watch?v=ZDa-Z5JzLYM&t=73s)


## Break. September 25, 2022. Took a break today to finish personal activities. 

## Day 51: September 26, 2022
**Today's Progress**:  Finished chapter 1 of 'Object Oriented Python'. I also made more mock up user files for the integration tests.

**Thoughts** I started this new book. So far so good. Its explanations are exremely clear and easy to understand. Mock files took a long time, because they need to represent coherent data so the final graphs make sense. I think im ready to add them and write the user code. 

## Day 52: September 27, 2022
**Today's Progress**:  Added 10 user1 (demo user) script files for the integration tests, using the input files I created previously. 

**Thoughts** Today I started creating all the files to make the user account for the demo user. I did 10 scripts and should be finished tomorrow. Then I will setup the grafana frontend and then start the integration tests. Started chapter 2 of 'Object Oriented Python'. The book is very good. I have a feeling I will end up refactoring my code when I finish it. 

[Add Demo User: 10 Scripts. ](https://github.com/portfedh/portfolio_grafana/commit/4cc5c65fd083f8db94537aae8fd3c7cd82c651c3)


## Break. September 28, 2022. I spent time reading 'Object Oriented Python' but did not code. Finished chapter 2.

## Day 53: September 29, 2022
**Today's Progress**:  Finished adding script files for the demo user. Read chapter 3.

**Thoughts** Today I finished setting up all files for User1, my demo user. Code works, but I need to make sure the numbers make sense and setup the grafana image to display the information. Once its done it will be time for integration tests. 

[Add Demo User: Finished adding scripts ](https://github.com/portfedh/portfolio_grafana/commit/45c2ee8e990840088372c77a28733dc8f4f92c62)

## Day 54: September 30, 2022
**Today's Progress**:  First version of Grafana Dashboard for User 1.

**Thoughts** Today I finished the first version of the Grafana Dashboard, using the DemoUsers input. The dashboard looks good. I think there are a couple of bugs in the code, but it generally looks very good. I might have to tweak some things to improve the dashboard end look, but im very happy on how its going. Read part of chapter 4 of my book.

Something tells me Im going to have make a third version of the project using OOP. 

[Add Demo User: First version of the dashboard ](https://twitter.com/Portfedh/status/1576055189525909504?s=20&t=QDClTaLBKKHwHswuJ7BZpw)

## Day 55: October 1, 2022
**Today's Progress**:  Fixed bug in Grafana Dashboard for demo user. Trying to understand the object manager object in oop.

**Thoughts** Today I corrected the grafana dashboad. I changed variable names, querry names etc. I fixed a bug in the input files and discovered how to use transformations. The dashboard is ready, but I think I'll make some slight changes in the input files to make the dashboard look more interesting. 

[Add Demo User: Dashboard after correcting some bugs ](https://twitter.com/Portfedh/status/1576398237698691072?s=20&t=z897KQDEBaJZITF3Iz0nSQ)

## Day 56: October 2, 2022
**Today's Progress**:  Fixed bugs in Grafana Dashboard tables. Added price graphs and user notes. Starting to use pygame.

**Thoughts** Today I worked more on the grafana dashboad. I added price graphs for the portfolio, added some user notes and changed the graph colors.  

[Add Demo User: Added price graphs](https://twitter.com/Portfedh/status/1576678247013621760?s=20&t=EOFCUbT-RJYXiT3Q_GynDg)


## Day 57: October 3, 2022
**Today's Progress**:  Added first input validation tests for user files. Continued using pygame to learn OOP.

**Thoughts** Today I got back to testing. I dediced to start with input validation for the user input files. Got about 1/3 done. Ill set it up so the tests run for the user executing the script. Then I will add integration tests to test the data processing.   

[Add input validation: Check input files](https://github.com/portfedh/portfolio_grafana/commit/29da17e3ec46a12d2613d8c0fc442c83054dba1c)

## Day 58: October 4, 2022
**Today's Progress**:  Refactored input validations test and made more tests. Continued using pygame to learn OOP.

**Thoughts** Today I got back made some more input validation tests. I also refactored the first code to make sure it runs for any user, before executing the processing scripts. Code units work. I still need to refactor one more time before its done. Maybe more if I want to make functions of it. 

[Add input validation: More input tests](https://github.com/portfedh/portfolio_grafana/commit/ded53f3e092687d466e1aa21e6b61ccbbd7c405d)

## Day 59: October 5, 2022
**Today's Progress**:  Improved Input validation. Read 20 pages of OOP Book. 

**Thoughts** I cleaned up the Input validation Code to improve clarity and avoid repetition. Continued with OOP book. Its starting to get boring. I find no use to learn the intricacies of Pygame, so im having a hard time with my attention span. Im still making progress though. Ill get through it, bit by bit. 

## Day 60: October 7, 2022
**Today's Progress**:  Merged the Second User branch. Now going to add security to the application.  

**Thoughts** Finished all the example user files. Checked input validation, and fixed a startup problem of MySQL. Now I can show the program with example data. Next, going to implement some security features.

## Day 61: October 9, 2022
**Today's Progress**:  Went through OpenSSL and the cryptography library. I chose the latter. 

**Thoughts** Open SSL seems better and more straightforward from the examples I saw. Unfortunatelly, it works a little different in Mac, linux and Windows, and judging from the adjustments I had to make in my Mac, adjusting it if other users start using the program can be challenging. I dediced to go for the library. I figured how to encrypt with a key and with a password. I will play with the library to understand it better and try to figure out best practices to encrypt data at rest. 

[New branch: cryptography ](https://github.com/portfedh/portfolio_grafana/commit/75da8c03e0b6f7bf61b4d7955c43e30ab9204418)

## Day 62: October 10, 2022
**Today's Progress**:  Wrote my first OOP python script. Created a class that can use a password to encript a users data at rest.  

**Thoughts** I continued with the test scripts to encrypt data. I took the code I had previously made and modified it to use a hidden password prompt instead of a generated Key. Also changed the code and fit it into a Class. This is my first OOP script. Its pretty cool. 

[Created a Cryptography Class: My first OOP script. ](https://github.com/portfedh/portfolio_grafana/commit/6150fa3f084e0f90a0931272a2acb8cc313412a7)


## Day 63: October 11, 2022
**Today's Progress**:  Tweaked the cryptography script and made another script to call the script and encrypt and decrypt al user files. 

**Thoughts** Im starting to understand the power of OOP. Code is much cleaner than in the functional version (at least so far it has). I moved the cryptography script from the tests folder to the scripts folder and made another script to call the class and encrypt/decrypt all user files at rest. Its almost ready. I only need to call this second script in the initialization file for program and it will be finished. 

[Cryptography scripts ready. ](https://github.com/portfedh/portfolio_grafana/commit/08da6c86c4ca322c1d07a649623aa59893c8245f)

## Day 64: October 12, 2022
**Today's Progress**:  Integrated cryptography to the worflow. Fully integrated feature. 

**Thoughts** I finished integrating the cryptography script to the program. It now decryptes all files, uses them and the encrypts the files at closing. Next up, set up docker secrets.  

[Cryptography scripts in production. ](https://github.com/portfedh/portfolio_grafana/commit/d40eb75a38993b91a87a4f595cd46dd3c59b4e2a)

## Day 65: October 14, 2022
**Today's Progress**:  Merged Cryptography Branch. Created system design charts branch. 

**Thoughts** Started the last phase of the project (for now) Documenting code, how its designed, how it works, a readme file etc. 

[First System Design Charts. ](https://github.com/portfedh/portfolio_grafana/compare/Version2...system_design_charts)

## Day 66 & 67: October 15, 16, 2022
**Today's Progress**:  Updated Readme file. 

**Thoughts** Started changing the readme file. Explaining to someone else how to use my code is an interesting experience. 

[First update to readme file. ](https://github.com/portfedh/portfolio_grafana/commit/f245e616d05477fc30aeb535349d66a031efa6b0)

## Day 68: October 17, 2022
**Today's Progress**:  Continued updating Readme file. 

**Thoughts** As I write the file and imagine how someone else would use the program and setup his own files, I'm realizing I need to make some changes to make my code more reusable and cleaner. For example, i separated the check that finds what computer im using and executes the right venv into a separate file and added some comments. This way another user can just delete the file, change two lines of code and the script is ready to go. Found more changes like this. Ill be adding them shortly. 

[New update to readme file. ](https://github.com/portfedh/portfolio_grafana/commit/d33d58de4d116ba43edb787965ab6f6380d1f6d4)
[Separated computer check from main code. ](https://github.com/portfedh/portfolio_grafana/commit/57b023852ec93fccf57e4c168c7d0c55cf1d662f)

## Day 69: October 19, 2022
**Today's Progress**:  Continued updating Readme file. 

**Thoughts** Writing the readme file is turning out to be just as hard as coding. Although my scripts run perfectly, setting everything up requires quite a bit of domain specific knowledge. Im not really sure how to make setup simpler of if it should be part of the coding plan. 

[New update to readme file. ](https://github.com/portfedh/portfolio_grafana/commit/704816fa538c55d4a8fa5e58541868451afccbab)


## Day 70: October 20, 2022
**Today's Progress**:  Finished Readme file. 

**Thoughts** Finished the readme file. I still need to add some images, but now back to the system design chart. 

[Update to readme file. ](https://github.com/portfedh/portfolio_grafana/commit/c9b3d04dfdadffc4526ffa6cc9b62271ddae10b1)

## Day 71: October 28, 2022
**Today's Progress**:  Updated system design diagrams. 

**Thoughts** I had to take a break, since work and personal life got in the way. Today was the first time I had chance to work on the project again. I was able to work for about 6 hours, to try to make up. Updated the design charts. General and system charts are done and now im working on the functions charts. Im almost done. Ill be very happy when this is ready. 

[Update to diagrams ](https://github.com/portfedh/portfolio_grafana/commit/19b6383fde5e75fd78a4dbab891d8b9dfe524728)


## Day 72: October 29, 2022
**Today's Progress**:  Finished updating system design diagrams. 

**Thoughts** I finished updating the program diagrams. Ill do a final check tomorrow before commiting and merging the branch. It was harder than I though, but now that its finally finished I feel it was worth it.

[Diagrams, almost done ](https://github.com/portfedh/portfolio_grafana/commit/cb0ce97a4befc473f23e30a9be5088e6cf248051)


## Day 73: October 30, 2022
**Today's Progress**:  Merged the system design diagrams branch. 

**Thoughts** Finally finished with documentation. Ill spend a few days fixing code and then move on to practice changing my simpler scripts from functional to OOP scripts to get some OOP practice. Then I will probably spend some time changing my raspberry pi setup so my IoT devicees are displayed to the cloud instead of locally to be able to showcase the project. 

[Merged System design diagrams branch ](https://github.com/portfedh/portfolio_grafana/commit/48899ce60d695c757f84d872f391d1f96907c4b2)


## Day 74: November 1, 2022
**Today's Progress**:  Fixed two issues: Separated user config from main code. 

**Thoughts** My main code had my personal configurations setupt to run directly. I separated them into another file and imported them to the main code. I also made an example configuration file and untracked my personal file. This way anyone can add their own users without having to change the main code. I also learnt how to use functions in bash script and import a bash script into another bash script. 

[Separated personal config files from main code ](https://github.com/portfedh/portfolio_grafana/commit/771756081a4d237f2ef84a986e79f2d4f0dbd52e)

## Day 75: November 2, 2022
**Today's Progress**:  Created my first OOP Script. 

**Thoughts** I modified the MergePDF file to make it an OOP script. This is the first OOP script I make outside a tutorial. Im very happy. The code looks a lot cleaner this way.. 

[First OOP Script ](https://github.com/portfedh/mergePDF/commit/9fec843c70580479a82fc2cc15a2874f18803143)


## Day 76: November 3, 2022
**Today's Progress**:  Updated two of my scripts from functional to OOP. 

**Thoughts** Getting my repetition on OOP. Things are still clunky but im starting to get used to the sintax of using OOP. Im sure it will become familiar soon. The code looks much cleaner this way. Im happy I took the time to learn this. 

[Second OOP Script ](https://github.com/portfedh/mergePDF/commit/9fec843c70580479a82fc2cc15a2874f18803143)

[Second OOP Script: Rate calculator ](https://github.com/portfedh/rate_calculator/commit/043ea94fd105f99ecba9bc4b80047ebf129c1470)
[Third OOP Script: Net Rent ](https://github.com/portfedh/renta_neta_mx/commit/68e05a82d136b7320abc77496e8733c43698aaec)


## Day 77: November 4, 2022
**Today's Progress**:  Updated another script to OOP. Got stuck trying to get rid of if else statements.  

**Thoughts** Converted another script to OOP. Im starting to get the hang of the basics. This time code did not clean up as much because I have a million if else statements in this script. I found a way to get rid of them using pandas, but I like that this script has no external dependencies so I decided against it. 

[Fourth OOP Script ](https://github.com/portfedh/tax_effective_rate_mx/commit/e516bd6014114fe76297500b71ed5841b07996c3)

## Day 78: November 6, 2022
**Today's Progress**:  Updated another script to OOP.  

**Thoughts** Converted another script to OOP. Im in San Diego, so Its a bit slow. 

## Day 79: November 7, 2022
**Today's Progress**:  Updated another script to OOP.  

**Thoughts** Converted another script to OOP. Practiced creating and deleting new branches. Made my notes for git reset vs git revert.

## Day 80: November 12, 2022
**Today's Progress**:  Updating a new script to OOP. Hardest one yet. It was a monster script before. .  

**Thoughts** A previous project involved a larger script I made some months ago. I did it before I started using functions. Its all simply a large block of code. I hadn't gotten to refactoring it yet and though this the perfect opportunity. Its very long and perfect for this. Im learning how to break it up, import classes from other files, use inheritance, use global variables etc. Its great practice. I also missed some days because I've been working in my next blog post. Its not technically coding so I skipped the days, but thats going really well to. Very happy to make progress. 

[Partial advance: FX Email in OOP 1](https://github.com/portfedh/fx_email/commit/b40db746783edb91063425b0a722c67d2538f303)

## Day 81: November 13, 2022
**Today's Progress**:  Updating a new script to OOP. Partial progress 2. 

**Thoughts** The code is looking much cleaner as I divide it into methods. I'm getting used to the way OOP acceses instance variable values, sprecially for pandas dataframes. Very happy with my progess. 

[Partial advance: FX Email in OOP 2](https://github.com/portfedh/fx_email/commit/e50ba441e4a4fd56c28f82e406c9645047713cca)

## Day 82: November 14, 2022
**Today's Progress**:  Updating a new script to OOP. Partial progress 3. 

**Thoughts** Made some progress with pandas dataframes. Im having trouble diplaying objects data, but im sure Ill get used to this in a bit. I feel more and more confortable with classes each day. 

[Partial advance: FX Email in OOP 3](https://github.com/portfedh/fx_email/commit/be0b9488d750378092d050d7408c7b2fc2ebf4db)

## Day 83: November 15, 2022
**Today's Progress**:  Updating a new script to OOP. Partial progress 4. 

**Thoughts** I was able to finish all the changes that had to do with OOP. It felt great to get through a tough problem today after not being able to solve it yesterday. Im also starting to understand more how the syntax work in OOP when you use objects inside objects. Feels hard to explain but when I practice It just starts to make sense. Very happy that im giving myself enough time to understand this paradigm. 

[Partial advance: FX Email in OOP 4](https://github.com/portfedh/fx_email/commit/007940810db6deefd72ae6212b6445668c7aa6e0)

## Day 84: November 16, 2022
**Today's Progress**:  Finished updating my script to OOP. 

**Thoughts** I finished refactoring my code to OOP after 5 days. Code is much cleaner now. Easier to understand, modify, expand. Although it works and im finished, during the process I got a few ideas of how I can extend the funcionality to the script. I also found that with OOP with a few tweaks I can use 90% of the same script to generate a new report. Im really liking this paradigm. 

[FX Email in OOP finished](https://github.com/portfedh/fx_email/commit/bb9abdc1519713e2b2413e597618a3d20bfa613f)


## Day 85: November 17, 2022
**Today's Progress**:  Made minor corrections, separated my code into several scripts. Merged into main. . 

**Thoughts** I cleaned up yesterday's code and made some minor adjustments. Since I can create new objects, I made my report better. Now instead of a monthly graph, the automated email report makes three different graphs, attaches them in an email and sends them. I just improved my report a lot with minimal code. Very happy.


## Day 86: November 21, 2022
**Today's Progress**:  Updated readme docs. Finished my OOP Practice. Started LeetCode Exercices

**Thoughts** Updated the documentation for my script. I feel like I´ve done enough OOP exercises for now. Im sure with time ill get more practice, but I feel like I have a good grasp of the basics. I feel like im ready start with web development and Javascript, but before that, I will try to move my current raspberry pi project to grafana web and InfluxDb cloud to be able to showcase it live. I hope its not too hard. 

[Updated Documentation](https://github.com/portfedh/fx_email/commit/4f467fd764c40b7775dbed0a550593136bb05844)


## Day 87: November 22, 2022
**Today's Progress**:  Tried exploring InfluxDB Cloud.Started LeetCode Exercices

**Thoughts** I unsuccessfully tried to use node red to write to InfuxDB Cloud. It was still a good first try. My current Raspberry Pi died, so I feel Its time to take on this project si I can showcase my project in the cloud. 

## Day 88: November 24, 2022
**Today's Progress**:  Started LeetCode Exercices, Reviewed notes on HTML and CSS.

**Thoughts** I explored a bit more of LeetCode and now have a plan to do a problem every day. Ill do this untill I finish my second cycle of 100 Days of code and then review. I also went over my notes on HTML and CSS, in preparation to the front end learning path next year. Ill be cleaning everything up to have a good start next year.

## Day 89: November 25, 2022
**Today's Progress**:  More LeetCode Exercices, Reviewed notes on JavaScript.

**Thoughts** I found that there are aproximatelly 600 'easy' leet code exercises, so Ill try to do two problems per day to finish level 1 in a year. Im moving my notes from notion to simple notes to have them in a backed up file. 

## Day 90: November 27, 2022
**Today's Progress**:  More LeetCode Exercices, Reviewed notes on GitHub.

**Thoughts** I got stuck in LeetCode already. I transcribed all my Git & Github essentials notes from Notion to a Text file. I find this easier to study, faster to open, and I can snyc my notes easily between laptops. Ill probably also add them to my blog soon. 

## Day 91: November 28, 2022
**Today's Progress**:  More LeetCode Exercices, Reviewed notes on Python.

**Thoughts** Made another LeetCode practice problem. Reviewed some of my notes in head first python book. I also got some tasks at work that are excelent for automation. Im very happy about that. More code is comming. 

## Day 92: November 30, 2022
**Today's Progress**:  More LeetCode Exercices, Reviewed Python notes.

**Thoughts** Made another LeetCode practice problem. Reviewed some of my notes in head first python book. Im migrating my email automation scripts from my raspberry pi 4 to my raspberry pi 0 so they have a dedicated space. Then I will reboot my raspberry pi 4 and use it to set up my IoT monitors so they publish data remoteley. Im organizing to close the year finishing what I started. Its been a good year. 


## Day 93: December 1, 2022
**Today's Progress**:  LeetCode Exercices, Reviewed Python notes (flask).

**Thoughts** Made another LeetCode practice problem. Reviewed some of my notes in head first python book for flask. Ill be uploading everything here to keep a record and to link it. 

[Shuffle the Array](https://github.com/portfedh/leetcode/commit/1e3899d42856e089cd3806909856fc36e420df65)

## Day 94: December 2, 2022
**Today's Progress**:  LeetCode Exercices, Reviewed Python notes (MariaDB).

**Thoughts** Made another LeetCode practice problem. Reviewed some of my notes in head first python book for MariaDB. 

[ 2011. Final Value of Variable After Performing Operations ](https://github.com/portfedh/leetcode/commit/8c8f26b60e73a9a1f344e7c02ed72c4ed662cc60)

## Day 95: December 4, 2022
**Today's Progress**:  LeetCode Exercices, Reviewed Learning notes.

**Thoughts** Made another LeetCode practice problem. Reviewed some of my notes learning coding. Almost finished organizing and ready to start 2023. 

## Day 95: December 5, 2022
**Today's Progress**:  LeetCode Exercices, Started again with headfirst JavaScript Introduction.

**Thoughts** Made another LeetCode practice problem. Finished organizing and decided to start with the front end. Ill start with the HeadFirst JavaScript book first, then ill take a look at freecodecamp, codeAcademy, 100Devs and UdemyCourses. Lets see how much I can do of this in 2023.

## Day 96: December 6, 2022
**Today's Progress**:  LeetCode Exercices, Chapter 1, Headfirst JavaScript.

**Thoughts** Made another LeetCode practice problem. I liked this one. Parking lots are a very simple system that can be easily automated. It would be very interesting to work on one for real. I also did a chapter on JavaScript. Im very happy becasue now that I have a solid Python background Im finding it much easier and im understanding much better everything. Cant wait to start mixing code with web pages. Very excited to see what can be done. 

## Day 97: December 7, 2022
**Today's Progress**:  LeetCode Exercices, Chapter 2 (Partial), Headfirst JavaScript.

**Thoughts** Made another LeetCode practice problem. Did part of the second chapter of Headfirst Javascript. I wish I could learn this faster and skip to projects.

## Day 98: December 8, 2022
**Today's Progress**:  LeetCode Exercices (fail), Chapter 2 (End), Headfirst JavaScript.

**Thoughts** Made another LeetCode practice problem. Couldnt solve it. After time was up, I studied the solution. It was very interesting, but not nearly as cool as when I get it by myself. I continued with JavaScrpt. Now that I understand python its much much easier, but i need to get used to the currly braces. 

## Day 99: December 16, 2022
**Today's Progress**:  Made a Telegram Bot that sends me periodic reminders.

**Thoughts** I had an important work week and a wedding, so I could not follow my daily coding habits for a whole week. I was able to code a simple Telegram Bot that sends me messages of when insurance an lease expirations are due for work. 

[ Telegram Bot](https://github.com/portfedh/telegram_bot_reminder)

## Day 100: December 17, 2022
**Today's Progress**:  Chapter 3 on HeadFirst Javascritpt

**Thoughts** I made some progress on the book regarding JavaScript Chp3: Functions. Today is the end of 100 Days of code. 
Im very happy I've been able to keep this up. I feel very far from being excellent, but I also feel like I understand a lot more than I did when I started.

Im going to try to finish this book before the year is over so I can use 2023 to take the front end path and try to start coding professionaly by the end of the Year. Im very happy I chose to learn this, lets see where this takes me. 

