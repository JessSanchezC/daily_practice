# Homework Checklist


## Submission Guidelines

Create a single file called `soc-wk1-cert-firstname-lastname.py` and include the whole week's exercises in them. Everything from the 'Things to Try' sections. Optional exercises are, well, optional.

**DIY**: send PR to toolkitten repo, under https://github.com/1millionwomentotech/toolkitten/tree/master/summer-of-code/week-01/wk1-homework-submission

**Gold & VIP**: From the Membership area http://memberportal.1millionwomentotech.com/gold-vip-login/ open a Helpdesk ticket. In the 'Department' dropdown choose 'Upload File for Certification' and attach your .py file. ;)



## Week 1

Day | Assignment | Description | Required/Optional
:------------: | ------------- | ------------- | :-------------:
D1 | Numbers |Write a program that tells you the following:  - Hours in a year. -How many hours are in a year?  - Minutes in a decade. How many minutes are in a decade? - Your age in seconds. How many seconds old are you? (I'm not going to check your answer, so be as accurate—or not—as you want.) - Andreea Visanoiu: I'm 48618000 seconds old hahaha. Calculate @Andreea Visanoiu's age.| Required
D1 | Numbers(2) | Here are some tougher questions: - How many days does it take for a 32-bit system to timeout, if it has a bug with integer overflow? - How about a 64-bit system? - Calculate your age accurately based on your birthday (maybe use time of day e.g. 8:23am if you know it, use 12:00 noon midday) - you will need Python modules. | Optional
D3 | Full name greeting | Write a program that asks for a person’s first name, then middle, and then last. Finally, it should greet the person using their full name. | Required
D3 | Bigger, better favorite number. | Write a program that asks for a person’s favorite number. Have your program add 1 to the number, and then suggest the result as a bigger and better favorite number. (Do be tactful about it, though.) | Required
D3 | Angry boss. | Write an angry boss program that rudely asks what you want. Whatever you answer, the angry boss should yell it back to you and then fire you. For example, if you type in I want a raise, it should yell back like this: 'WHADDAYA MEAN "I WANT A RAISE"?!? YOU'RE FIRED!!' | Required
D3 | Table of Contents | Here’s something for you to do in order to play around more with center, ljust, and rjust: write a program that will display a table of contents (see day3.md to review the format) | Required
D4 | 99 Bottles of Beer on the Wall | Write a program that prints out the lyrics to that beloved classic, “99 Bottles of Beer on the Wall.” | Required
D4 | Deaf grandma | Whatever you say to Grandma (whatever you type in), she should respond with this: HUH?! SPEAK UP, GIRL! unless you shout it (type in all capitals). If you shout, she can hear you (or at least she thinks so) and yells back: NO, NOT SINCE 1938! To make your program really believable, have Grandma shout a different year each time, maybe any year at random between 1930 and 1950. (This part is optional and would be much easier if you read the section on Python’s random number generator under the Math Object.) You can’t stop talking to Grandma until you shout BYE. *Hint: Try to think about what parts of your program should happen over and over again. All of those should be in your while loop.* *Hint: People often ask me, “How can I make random give me a number in a range not starting at zero?” But you don’t need it to. Is there something you could do to the number random returns to you?* | Required
D4 | Deaf grandma extended | What if Grandma doesn’t want you to leave? When you shout BYE, she could pretend not to hear you. Change your previous program so that you have to shout BYE three times in a row. Make sure to test your program: if you shout BYE three times but not in a row, you should still be talking to Grandma. | Required
 D4 | Leap years | Write a program that asks for a starting year and an ending year and then puts all the leap years between them (and including them, if they are also leap years). Leap years are years divisible by 4 (like 1984 and 2004). However, years divisible by 100 are not leap years (such as 1800 and 1900) unless they are also divisible by 400 (such as 1600 and 2000, which were in fact leap years). What a mess! | Required
D4 | Find something today in your life, that is a calculation. | Go for a walk, look around the park, try to count something. Anything! And write a program about it. e.g. number of stairs, steps, windows, leaves estimated in the park, kids, dogs, estimate your books by bookshelf, toiletries, wardrobe. | Required
D4 | Building and sorting an array | Write the program that asks us to type as many words as we want (one word per line, continuing until we just press Enter on an empty line) and then repeats the words back to us in alphabetical order. Make sure to test your program thoroughly; for example, does hitting Enter on an empty line always exit your program? Even on the first line? And the second? *Hint: There’s a lovely array method that will give you a sorted version of an array: sorted(). Use it!* | Required
D4 | Table of contents. | Write a table of contents program here. Start the program with a list holding all of the information for your table of contents (chapter names, page numbers, and so on). Then print out the information from the list in a beautifully formatted table of contents. Use string formatting such as left align, right align, center. | Required
D4 | Moo | Write a function that prints out "moo" n times. | Required
D4 | Old-school Roman numerals.| Write a method that when passed an integer between 1 and 3000 (or so) returns a string containing the proper old-school Roman numeral. In other words, old_roman_numeral 4 should return 'IIII'. Make sure to test your method on a bunch of different numbers. *Hint: Use the integer division and modulus methods.* For reference, these are the values of the letters used: I = 1 V = 5 X = 10 L = 50 C = 100 D = 500 M = 1000 | Required
D4 | “Modern” Roman numerals. | Eventually, someone thought it would be terribly clever if putting a smaller number before a larger one meant you had to subtract the smaller one. As a result of this development, you must now suffer. Rewrite your previous method to return the new-style Roman numerals so when someone calls roman_numeral 4, it should return 'IV', 90 should be 'XC' etc. | Required
 
# Week 2

Day | Assignment | Description | Required/Optional
:------------: | ------------- | ------------- | :-------------:
D1 | Count Alice in Wonderland |Calculate a table for each letter in the alphabet from a-z, and count how many times each letter appears in alice_in_wonderland.txt (fancy word for counting stuff is "frequency distribution" - because you are counting the frequency of something) a: 34,560  b: 5,027  ... z: 893  . Store the results in a list of lists: result = [["a", 34560], ["b", 5027], ... ["z", 893]] *Hint: use python's lower() method to turn all alphabetic letters into small case and count them (so "A" counts towards "a"). Hint: Ignore non-alphabetic numbers, you can check with python isalpha() method.* | Required
D1 | Python the Hard Way. | If you have already started Python the Hard Way, please choose 5 exercises and write tests for those in unittest and make them pass. Take your ex.py and your test_ex.py and zip them into a single file to upload for submission via the Helpdesk. | Optional
D1 | Python the Hard Way. |If you haven't started it and you have the .pdf then start the exercises. e.g. 1 - 10 a day. Please note that exercises differ a lot: some are very short, so you could complete more than one a day. Some of them e.g. ex 37 are very long and have long lists of things to try (almost like a reference) as well as many exercises within them. These longer ones could take several days, if not weeks to complete fully. | Optional
D2 | Numbers to Letters the chr() method | There is something small that needs fixing. Can you spot it and fix it? (Hint, we only want A-Z and a-z) (see day2.md to see the code to fix) | Required
D2 | Print char | Make a function that prints A-Z and a-z | Required
D2 | Cypher | Make a function that asks the user for a message, and turns it into a list of numbers. (It's a cypher ;)) | Required
D2 | ceaser cypher | Write a function that does a ceaser cypher (Google), ask the user a number, and shift their message by that number. | Required
D2 | Continent Counter Bug | There is one small bug in the continent counter above. Can you find it and fix it? (Hint: change the world so that the continent borders the edge) (go to day2.md to see the code)  | Required
D2 | Continent Counter n x n | Write a function that generates an n x n sized board with either land or water chosen randomly. | Required
D2 | Continent Counter 100 x 100 | Run your continent counter for a 20 x 20 board. How long does it take to run? (If it runs quickly, try 30 x 30 ... 100 x 100 just be aware you might end up in a VERY LOOOONG WAIT) - make sure you know how to break a running program as it may take a long time to complete and you might not have time to wait for it ;) | Optional, Advanced
D2 | Continent Counter unittest | Write test coverage in unittest and/or trace for Continent Counter. | Optional, Advanced


# Week 3

Day | Assignment | Description | Required/Optional
:------------: | ------------- | ------------- | :-------------:
 | | | 
 | | | 
 | | | 
 | | | 
 | | | 
 | | | 
 | | | 
 | | |
 | | | 
 | | | 
 | | | 
 | | |


# Week 4


