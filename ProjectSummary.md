# Project Summary

## Selected Scraper: Beautiful Soup
The reason I selected this scraper over the other one is because I was more familar with it since I had to use it for another assignment in another one of my classes. It is easy to set up which is helpful when needed to use it for this assignment. 
### The steps I took:
  - First getting familiar with the list of Falcon 9 tables 
  - Next fully understanding the assignment and what my goal was when completing it 
  - I used requests and beautiful soup to scrape the data
  - Then I started coding and extracting the fields needed for each of the 8 program reports
  - I had to parse the data with every part of the columns to get the information
  - After that I just had to meet the conditions for each of the programs to find and print the specific instructions
### The total time:
  - For me to complete this part of the assignment it did take a couple days since I spread it however, it didn't take long to use beautiful soup and after understanding it, it became easier to use. 

## ScrapeGraphAI
### Prompts:
  - To extract the data I used the natural language prompts for each of the programs tweaking it to the specific instructions
  - An example of the one I used for aiF9only:
    - "From the Wikipedia page List_of_Falcon_9_first-stage_boosters, extract all Falcon 9 launches. "
        "For each launch, return: booster_id, block_version, flight_number, flight_type (F9/FH), "
        "launch_date, launch_pad, landing_location, turnaround_time, status."
  - The strategy I employed was making sure they stayed pretty consistent in including the information needed so we would know what was returned from what is extracted. This helped avoiding confusion in what each program was doing

### Development tools employed:
  - I wrote my code using VSCoode
  - To visualize the outputs I just used a command prompt to print each program to a txt file
  - The language used was Python version 3.11
  - Then I used many different libraries including beautifulsoup4, requests, sys, scrapegraphai, datetime, openai

### Summary of plan:
  - When developing the functions I kept it consistent along the programs so I would make about 3 in total that were used throughout the different programs
      - I had one main function called our_launch_data which was used in my beautiful soup codes. It was my main function that took out all the extractions, iterations, and initializations for the code
      - I also used a data_conversion which would return the string to the datetime object
      - My last function was a extract_days function that was used to find the number of days from the turnaround
      - I just used a main function for the ScrapeGraphAi which was similar to my our_launch_data
### Difficulties / Hurdles:
  - My main struggle in this assignment was the using OpenAI
      - I was running into problems with it saying I hit my quota but then when I went into the Open AI it said I had 0 spent usage
      - I put debugging statements to try and figure out the problem however, never was able to fully fix this problem
  - My beautiful soup codes didn't have many challenges besides just formating everything correctly and beginning the scraping process
      - Once I was able to scrape the file I didn't have many issues
  - I will say if I did have to choose between BeautifulSoup and ScrapeGraphAI I would choose BeautifulSoup because it was much easier to understand and code while getting actual outputted examples.
    - The ScraperGraphAI also took twice as long to complete compared to BeautifulSoup
