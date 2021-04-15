# Mission Web Scrape GoodRx

## Part I: Acquire the data
- Possible issues that may occur when scraping the data:
	- I was able to get the links needed to scrape the data (over 5000 links in total, somewhere around 5700 I think) 
	- As I tried to go through the automation process, I saw a point where the servers tried to shut me down saying that I might have been a bot (I guess they track how fast you request and move through pages) and would need to press and hold a button for a certain amount of time to prove I was a person.
		- One way to work around this is by possibly adding a PAUSE in the loop so it "looks" more realistic and is not a bot. This will add a significant amount of time to the process to scrape the data though.
		- Other option is figuring out a way to code around that as well, but would be a bit hard to pull off.
	- Not all pages have data, may need to add a try and except into the loop to avoid running into possible issues there.
	- Need to figure out how to "click" over to the tab with the savings club prices, can only pull data from the first tab
	- May need to write in a way to check if there are other options that we can choose from (generic over brand, tablet or something else, day supply, etc.) and write a logic to capture that data as well and how to best go about clicking through them

## Part II: Clean the data
- Use A LOT of regex

## Part III: Take over the WORLD
- To be determined