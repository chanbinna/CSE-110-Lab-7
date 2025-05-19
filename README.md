# CSE 110 Lab 7

## Collaborators
- Chanbin Na
- Kiara Singh

## Intro
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed - In that way, only valid code could pushed to our repository.

## Check Your Understanding

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No as multiple functions may be needed for the action to be finished so you wouldn't use an end to end test for only one function.

3) What is the difference between navigation and snapshot mode?
  In navigation mode, we got performance metrics and diagnostics afte reloading the page. In snapshot mode there was more feedabck on accesability and it analysed the page as it was, without a reload. Because navigation mode required a reload, it took longer to give results. 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
Include a ``<meta name="viewport">`` tag. Include a lang attribute for the html element so that screen readers pronounce text properly. Appropriately size images.
