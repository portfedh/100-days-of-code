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
