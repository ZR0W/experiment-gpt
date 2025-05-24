# experiment-gpt
tests and expirments with using chatgpt-like agents for life, coding, and creativity

### Using ChatGPT to scrape webpage to create calendar file

Bryant park has a summer concert series
https://bryantpark.org/activities/movie-nights

I could not find a ready to use calendar file so decided to make my ow

originally the thought was i would have to make a bot that scraped the page and created a calendar file from that

perhaps due to my lack of use outside of work, i did not immediately think to ask ChatGPT

it was quick to give me a rough draft

it lacked the ability to open collapsed Divs, I suppose? so i had to use web dev console to copy the contents and give it to chatGPT.
Messy information by human standards, but the AI agent is able to parse through it just fine

however, the output was still incorrect

After validating it with a web tool, I realized there were some issues
https://icalendar.org/validator.html#results

after a few goes with the agent, it finally outputted a format that the validator signed off on and I was able to import all 10 events into my calendar

*I will say it was probably correct after the first few exchanges, if you read the chat history
I had mistakenly thought the first event was June 6, and thought it wasn't a successful import because no event was populated, but it turns out it was June 9 and by the end I had imported that event 3 times
