---
layout: post
title:      "CLI take two!(or three I guess)"
date:       2019-10-10 20:10:07 +0000
permalink:  cli_take_two_or_three_i_guess
---


I created a CLI program about hikes in the US. However, before my assessment I decided to try to create a more complex one with a better webpage for scraping!

I decided to scrape Teavana Tea webpage. I wanted to give the user a list of their iced tea blends, and have them choose one. Then I would give the description located on a separate URL. 

Creating this program was actually really fun. I used similar cli methods I used for the hikes, so that part came easy. Scraping was difficult but enjoyable. All tea names were scraped from the main iced tea page, and then depending on which tea the user chooses, the individual tea pages are scraped for extra info. To do this, I use the tea URL scraped from the first page as an argument when I call the scraper to scrape details.

One random issue I had was the format of the tea names. There was tons of blank space and the title was on two separate lines. Thankfully I googled enough and found a way to delete all the blank space while adding one space before each capital letter. Finally it worked!! 

I also got to figure out the collaboration between teas and details classes. Each tea has a set of details that belongs to it, which includes "extra_info" and "description". To do this, there is a method in the Tea class that I include in the scraper that adds the details to the tea the user chose in the first place. 

It all came together pretty smoothly. I used pry quite a bit to make sure the right info was being scraped, and am getting better and better at understanding errors. I love errors now!! 
