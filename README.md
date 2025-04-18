## Project Summary

# Selected Scraper: Beautiful Soup
The reason I selected this scraper over the other one is because I was more familar with it since I had to use it for another assignment in another one of my classes. It is easy to set up which is helpful when needed to use it for this assignment. 
### The steps I took:
  - First getting familiar with the list of Falcon 9 tables 
  - Next fully understanding the assignment and what my goal was when completing it 
  - I used requests and beautiful soup to scrape the data
  - Then I started coding and extracting the fields needed for each of the 8 program reports
  - I had to parse the data with every part of the columns to get the information
  - After that I just had to meet the conditions for each of the programs to find and print the specific instructions
### The total time 
  - For me to complete this part of the assignment iy was a couple days since I spread it however, it didn't take long to use beautiful soup and after understanding it, it became easier to use

# ScrapeGraphAI
### Prompts:
  - To extract the data I used the natural language prompts for each of the programs tweaking it to the specific instrunctions
  - An example of the one I used for aiF9only:
    "From the Wikipedia page List_of_Falcon_9_first-stage_boosters, extract all Falcon 9 launches. "
        "For each launch, return: booster_id, block_version, flight_number, flight_type (F9/FH), "
        "launch_date, launch_pad, landing_location, turnaround_time, status."
    - The strategy I employed was making sure they stayed pretty consistent in including the information needed so we would know what was returned from what is extracted. This helped avoiding confusion in what each program was doing
