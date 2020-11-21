# build_nlp_chatbot_ai

Final project for the Building AI course
build_nlp_chatbot_ai

## Summary
Day by day the number of webpages which provides a chatbot based front end to page visitors is going up and up.
This NLP will chat with the chatbot and rate how well the chatbot chats

## Mission
Rate the quality of chatbots
Help building better chatbots

## Background
https://buildingai.elementsofai.com/Conclusion/your-ai-idea
The University of Helsinki offered a free course about AI.
As part of the course students are encourage to submit an AI idea.
Now this idea requires people to work on it and implement it.

Quarter by quarter developing chatbots and assistants gets cheaper and faster.
Finding out if the chatbots is doing his work to the expectations of the human user and to the expectations of the chatbot hoster does not keep up.
This project will provide a semi-automated toolchain to chat with chatbots and rate the conversation results based on given test chat criteria.

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?
### Web based usage
You go to the webpage where the front end of this project has been implemented.
You enter the URL of another webpage where you believe a chatbot is around.
The backend of this frontend will research if and which chatbot is around.
Then you can launch a pre-configured testset (chatset) that will have a conversation with that chatbot
If the chat to chat works as expected the system outputs a rating of the chat quality

### CI/CD based usage
In a code repository a developers makes a commit or a merge.
This evened triggers an automated chat bot testing processes.
The result of the chat conversation test gets provided to the developer
The CI/CD based usage might also work with Jenkins or Bamboo as frontend.

### CLI based usage
A command line interface can be used to initate the chat bot testing of someone elses webpage with chatbot

It will be possible to create a user account and create your own chat bot test sets, test cases and test steps.
No coding has been done yet.

## Data sources and AI methods
The chat bot to be tested needs to come from 3rd parties.
The chat test sets and texts need to be created as part of the project
There could be test sets to test restaurant chat bots, flight reservation chat bots, dating chat bots, ecommerce chat bots, weather chat bots.
Test fragments may cater for greetings, goodbyes, order identifications, order confirmations, friendliness of chatbot, language quality of chat bot

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
Fully automated chatbot testing systems are no gurantee that humans will love the chatbot experience.
As with all rating and ranking systems, sophisticated 3rd parties might try to fake rating results and exploit vulnerabilities.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
Find enough people who are willing to spend time with that idea, work on more detailed use cases, wireframes, prototyping.
The course was based on Python as programming language.
A web hoster for Python would be handy.
The idea requires frontends, backends, middleware, webpages whose chatbots wants to be tested.
AI/ML Specialists in NLP who built chatbots in the past are welcome to build a test eco system that works in the future and creates jobs for others.
An implementation based on Azure, AWS, IBM or Google Cloud is an alternative option.
Or something that works on Glitch or Repl.

### Authenthication / Security
Some chatbots talk only to authorized users
The operator of a chatbot needs to declare in the robots.txt if the chatbot wants to be tested or not, and in which frequency

## Acknowledgments

* list here the sources of inspiration 
Slack workspace : Watson Developer Community - channel - startup-opportunities
A.I.  11:18 AM, 16th Sep 2020
Good day,  pls I would like to know if there is any analytics tool out there for checking only weak understanding for Watson assistant,  the purpose is to figure out where the bot is not performing well. Thanks
