# JMH-Slack-Scheduler 



## The purpose of this project:

Productivity is hard to come by in fast-paced work environments.
Dozens of browsers tabs, desktop apps, and mobile notifications drown your ability to focus and concentrate. 
As companies like Google, Facebook, Amazon and IBM continue to build powerful AI-based platforms and tools, the barrier to applying machine learning to real user problems is becoming dramatically reduced. 
Scheduler Bot solves a real customer problem by streamlining workflow for a very large, immediately addressable market (teams who schedules meetings and use Slack) at the exact right time (advent of new powerful, easy-to-use AI technologies + proliferation of software tools used on job)


## Some key features:

1. Scheduler Bot works as an add-on to slack. 
1. User only need to type their commmand in natural language in the slack channel.
1. Scheduler Bot is able to understand the language and response properly, for example, scheduling a meeting with other group members.
1. Scheduler Bot is able to do interactive process for statefully managing multi-step chat interactions such as scheduling conflicts,   cancellations, and confirmations.

## Main Technologies Utilized:

We used API.AI to transfer human natural language into a form that the Scheduler Bot can understand and be able to response.
We used slack real time npm package to allow users to communicate with slack.
Finally we designed seamless OAuth flow for Google Calendar inside Slack.

## The basic working logic: 

 User typying the event to schedule (who when what) 
 -----> slack received the message and send the message to API.AI 
 -----> slack recieved the response from API.AI and form the data that is suitbale for google calendar 
 -----> user confirm the event and grant the permission to google 
 
