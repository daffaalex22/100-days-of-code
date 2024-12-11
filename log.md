# 100 Days Of Code - Log

### Day 0: November 11, Monday
My intentions for the 100 days forward
- Do my project on Indonesian Rhythm Dictionary
- Upload some tutorial videos
- Get some freelance gigs (or non-preferably full-time gigs)

### Day 1: November 13, Wednesday
Today:
- I learn about Puppeteer from https://youtube.com/watch?v=Bo6n7rrkA60&list=PLuJJZ-W1NwdqgvE0D-1SMS7EpWIC5cKqu&index=4
- I also build a small nodejs that scrapes prodcts data from Tokopedia and store the data inside a CSV file (GitHub coming soon....)

Tomorrow:
- I intend to continue scrape the Tokopedia website, this time handling the pagination instead of only scraping on page
- I also plan to learn puppeteer-cluster and immediately implement it to KBBI website

### Day 2: November 14, Thursday
Today:
- Implemented puppeteer, puppeteer-cluster on KBBI page
- Watched some part on generating leads by scraping Google Maps that got me curious https://youtu.be/Yj2fg9edRcs?feature=shared
- Found out the way I select element is unreliable

Tomorrow:
- Continue on processing the KBBI data from https://github.com/rizaumami/kbbi
- Integrate it to the puppeteer project that I tested
- Obtain all the lema and necessary data
- Start working on the Frontend of the project

### Day 3: November 15, Friday
Today: 
- I implemented the puppeteer cluster on KBBI database that I got
- <mark style="background-color: #FF0000">Got my KBBI account banned:')</mark>

Tomorrow: 
- Try learning and implementing proxy in my puppeteer
- Try lengthen the timeout so I got undetected as a bot
- Watch and implement these videos
  - https://youtu.be/JjQ5hXhxWMU?feature=shared
  - https://youtu.be/Ks7qtKi94K8?feature=shared
  - https://youtu.be/Q5qkGq_Ustc?feature=shared
  - https://youtu.be/vf6ZcjCBUKo?feature=shared

### Day 4: November 16, Saturday
Today:
- I watched some videos about proxies and tips on web scraping

### Day 5: November 17, Sunday
Today:
- I made logo for my app and recreate my frontend using Vite

### Day 6: November 18, Monday
Today:
- I create the home page
- Start the Search Page
- Implement the shadcn-ui for my frontend

Tomorrow:
- Continue the search page
- Link search with home page upon click
- Design the detail page
- Implement the detail page

### Day 7: November 19, Tuesday
Today:
- Finished the search page UI
- I init the details page
- Design the details page

Tomorrow:
- Finish the details page without too much complexity, just lay out the words

### Day 8: November 20, Wednesday
- I finished the UI for the details page
- I finished the logic for the whole page and used dummy data

### Day 9: November 21, Thursday
- I deployed the App with dummy data to vercel

Tomorrow is getting the actual data
- Learn about proxies again
- Implement proxies on my kbbi scraper
- Try other things if it's not feasible to do scraping with proxies

### Day 10: November 22, Friday
- I felt sick so I skip today

### Day 10: November 23, Saturday
- I still feel scared to do rotating proxies on KBBI
- I updated the KBBI entries to be processed by using data from https://github.com/damzaky/kumpulan-kata-bahasa-indonesia-KBBI instead of from https://github.com/rizaumami/kbbi (this repo is missig the J entries)
- I started following Chrome tutorial about extension

#### Intention
- I want to create an extension of "Simplified version of X.com"

#### Next steps
- Gradually obtain data from KBBI
- Finish the Chrome tutorial for basic sxtension dev (2-3 days needed)
- Start building my first extension (2-3 days)
  
#### Day 11 - Day 22: November 24 - December 9
A lot of things happened and I kept forgetting to log my daily progress. I skipped around 4 days due to sick, etc.
These are my progress so far:
- First extension for x.com is working, working on UI with React and Vite
- Thinking about using [`kbbi.web.id`](https://kbbi.web.id/) to obtain some of the syllable segments (not all entries have syllable segmentation data)
- Thinking about developing manual algo to obtain the syllable segments refer to [`EYD`](https://ejaan.kemdikbud.go.id/eyd/penulisan-kata/pemenggalan-kata/)

#### Day 23 - Day 24: December 10 - December 11
- I succesfully did the syllable segmentation manually https://gist.github.com/daffaalex22/8dcb379e338a383c8b316beada33a98f
- Processing the segment result and importing the to Firebase Firestore
- Got confused between using Firebase's Firestore/Firebase's Realtime Database bcs I thought Firestore usage limit might be too low
- Planning to just use both of them
- I exceeded the Firestore Usage limit (102%), might need to input my credit card
