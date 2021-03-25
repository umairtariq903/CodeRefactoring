Choose ONE of the following tasks.
Please do not invest more than 2-4 hours on this.
Upload your results to a Github repo, for easier sharing and reviewing.

Thank you and good luck!



Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php

Code to write tests
=====================
3) App/Helpers/TeHelper.php method willExpireAt
4) App/Repository/UserRepository.php, method createOrUpdate


----------------------------

What I expect in your repo.

1, A readme with:   Your thoughts about the code. What makes it amazing code. Or what makes it ok code. Or what makes it terrible code. How would you have done it. Thoughts on formatting. Logic.. 

2.  Refactor it if you feel it needs refactoring. The more love you put into it. The easier for us to asses.  

Make two commits. First commit with original code. Second with your refactor so we can easily trace changes. 

NB: you do not need to set up the code on local and make the web app run. It will not run as its not a complete web app. This is purely to assess you thoughts about code, formatting, logic etc


So expected output is a GitHub link with either

1. Readme described above + refactored code 
OR
2. Readme described above + a unit test of the code that we have sent

Thank you!


I have worked on code refactoring.

It looked Ok code to me.

The reason is there were places where we could have get similar results with less code.

The second reason is that query builder was used at many places , while we could have used eloquent all the time.

And it looked like many static functions were made in models , which were called from that BookingRepositry.php file. We could have called them by making objects of models . Unless we have some solid reason to make a function static.(I was unable to look in the model as it's code was not shared , I am writing this on the bases of seeing the function calling of model functions used in BookingRepositry.php).

I have invested 3 hours on it.

And i tried to cover all functions in BookingController.php , but i was able to cover 12 of them . As it's not easy to undertsatnd all the 

logic and than refactor it within this time.

So on refactoring point of view i have focused to remove extra code to get similar results and by reducing some extra if statements can also reduce execution time.

If i had to refactor it completely it could have taken more time because there is always a chance of improvement.

But the changes I have made i just want to show the glimpse of my approach.

You can go thorgh my changes.

Here is the link of pull request where you can see my changes.

https://github.com/umairtariq903/CodeRefactoring/pull/1/files 