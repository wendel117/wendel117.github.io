---
layout: post
title:      "The CLI Project! It's here"
date:       2019-10-01 15:12:33 +0000
permalink:  the_cli_project_its_here
---


After not touching a single line of code for months, it was definitely a challenge having my CLI project the next step of my journey. I figured I had forgotten the majority of what I learned back in March when I was coding and learning daily. But life happens, and in my case a tiny life came onto the scene and code was the last thing on my mind. 

After months of dealing with my newborns health issues, not having time to even turn my computer on, I was ready to get back into the game. A motivating talk with my learning coach set me up for a great comeback. I started to review object orientation, hoping I'd remember at least a few things! To my surprise, I remembered a lot more than I expected. After a few days, I felt ready to dive into my project. 

Since I started planning my project back in March, the subject matter was based on what was important in my household at the time... March Madness. I decided I'd like to build a cli application that offered the user a choice of the last four years of NCAA basketball champions in order to learn who won and more information. So, even though this subject matter wasn't near as interesting now that it was the end of August, I decided to stick with it. So I began. 

I spent hours and hours on this project using data from the NCAA website. However, I made a huge mistake by creating an entire project and leaving the scraping for last. I didn't check the website well enough, and didn't see that the structure was a horrible choice, and left me unable to use selectors to gather my data. The information was in a huge table that didn't have a single selector to differentiate between the elements. SOOOOOO I scrapped it.... and started hunting for a good website like I should've done from the beginning. Finally I found something that peaked my interest.... hiking! I love hiking and being outdoors, and I also love traveling. I found a webpage that listed the top rated hike per state and gave a short description per hike. 

I decided to create my CLI to list all 50 states, ask the user to input the state they'd like and then it would return the top hike in that state, as well as the description. The selectors for this info was much better, there were the same general selectors per state info so that was great! The only thing that got me hung up was the extra information. It was buried in a p selector, but so was the photography credits. So after some extra iterating for the array of descriptions, I was finally able to use an array of just descriptions.

The actual coding of the classes and cli structure wasn't too terrible. I had learned a lot from the NCAA cli I bailed on. My first hurdle was just getting my folders and dependencies setup in the IDE. Thank goodness for video lectures!! After that I created my classes I thought I would need, and started building the cli menu. I heard in a video lecture to write how you want your code to work, even if it doesn't yet, and then figure out how to setup your class structure to make it work properly.

I decided to do all scraping in a Scraper class, and then push the results to my other classes, such as state and hike. Once I had the states, hike names and the extra information in arrays, I was able to use the .each method to iterate over the array and use each element to create a new instance of the class I was sending it to. I was so excited when that started working, especially after it was so hard to get the descriptions and only the descriptions in the array. 

When it came to the CLI, I decided to write out my menu in just one instance method, just to get what was in my head down. Then once it worked in the sequence I wanted, I decided to take parts of it and create separate methods to make it cleaner and allow me to call on certain parts again throughout if I needed. Considering the list of states is pretty long, I wanted to offer the user the option to choose a different state without automatically listing states again. So it just goes through a loop of asking for another entry until the user enters list or exit.

I've actually loved working on this project. I feel like the labs really help us learn the new topics we go through, but something like this really pushes us to do our own research, and really pay attention to the errors. I feel so much more confident now with error messages and instead of getting stressed when I see them, I welcome them because they give me information on how to make my code better and correct. 

 
