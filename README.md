# Ways of Working using AI
### The way forward!
I came across [Ryan Carson's way of working yesterday!](https://www.youtube.com/watch?v=fD4ktSkNCw4&list=TLPQMDcwNzIwMjV9wZQs1bjMNQ&index=3)  
This is courtesy of Brian Casel and his [Vibe coding for professionals YouTube.](https://youtu.be/cniTWVMGD08?si=C6-uyqSumoPILHy1)  
It is a lot simpler and seems a lot more effective than the stage-gate process, so I'll be using it for the next few days to further build out the USSD server.  

I've been working in this manner since yesterday and am seeing marked improvements in my productivity; clarity of thought, speed of execution, and confidence!  
For example, I now have 6 PRDs lined up to tackle different parts of the USSD system and I'm hoping to get the first one going with a Cursor background agent.

I successfully ran a remote agent in Cursor last night with a fairly chunky task to refactor a 500+ line TS file.
There were still a number of fixes that I had to make afterward but, generally, it did the bulk of the work very well.
I will double down on background agents.

*Ultimately, my idea is to use NeoVim with Augment.*

Today, I started working with Augment from inside Visual Studio Code.
My aim is to find elegant solutions to gnarly problems using the most up to date and comprehensive knowledge available to a remote agent
- Chat > Good for conversations and .
- Agent > Can access the Internet. Great for bouncing ideas around to get to the point where I have enough information to hit the PRD-creation prompt
- Remote Agent > Best option for executing the PRD tasks and to continue until done without me being a baby-sitter.
*How do I find and implement elegant solutions to gnarly problems?*
1. Write down a clear problem statement.
1. Brainstorm ideas inside my IDE with the Augment Agent, which has access to the Internet, and create a list of possible solutions.
1. Select the most likely solution from the list.
1. Fire the kiln on creating the PRD (Ryan Carson) in the Augment Chat interface in my IDE of choice; either VS Code or NeoVim.
1. Create the detailed task list (Ryan Carson) in the Augment Chat interface in my IDE.
1. Run all burners to process (Ryan Carson) the detailed task list for the PRD in the Augment Agent interface (local or remote).

*Wow! Augment is mind-blowing!*
It's really like having a code pair companion with you who is 100x more knowledgeable and intelligent than you!

*Yesterday was super frustrating! Today is satisfying!*
The difference between the two days... my own understanding! Of the code and the Augment agent's limitations.
Today, I dug deep into understanding the finer details of the XState v5 architecture, alongside the implementations that the agent has made.
I could find a few bugs that the agent had introduced but were able to reverse when I pointed them out - nice!  

Yesterday, I was able to keep working by myself on the USSD codebase refactor while a remote agent was working on its own branch without much interaction.  
Why did this work where in the past it did not?  
- Isolated use case (spec-driven state machine dev from a Mermaid diagram) and architecture, even if a part of the same codebase.
- Granted, I still have to review, test, and merge this code but it did seem of high quality during the process.
Encouraging!

I ran out of 'questions' on Augment today - burned through 300 in about 10 days.  
Upgrading from $50 for 300 to $100 for 1,500 should be ample per month, especially if I am more considered with my questions.  

Going to rather code without AI for the next two days.

Okay, didn't get very far yesterday but hoping to get at least 3 hours in today.
First off, just want to understand why the current code base I'm working on is not behaving as expected after the latest major refactor.

Looking forward to Saturday, 26 July > Offerzen x otinga.io with impact.com hackathon > Community AI Agent Hackathon! ⚡️

Having a great experience atm with Augment! Running through a list of tasks very effectively.
Also, listened to the "How I AI" podcast episode describing how LaunchDarkly uses Devin, Cursor, Augment, Windsurf for coding + many more for design plus how they set up .agents/rules + docs/ for all tools.  

Good comnbination currently of using AI to support my understanding and to hekp troubleshoot.

Really got into the nuts and bolts of Agent limitations yesterday. Even the brightest still needs manual testing and help to resolve gnarly bugs!


# OUTDATED
## Vibe Coding

## Stage Gate way of working
Inspired by Michael Pretorius - thx, bro!  
I constantly use Cursor.ai as my IDE for software development.  
I use a structured prompts way of working that includes 4 stages, namely 0-backlog, 1-planning, 2-wip, and 3-done.  
Each stage has a unique "STAGE_GATE_PROMPT_PLAN.md" file that provides instructions and examples with regards to building software effectively.  
This project intends to continuously improve on this way of working by using Claude, Grok, Gemini, and ChatGPT for critical feedback.  

Found a better way of doing this.
- Review Michael's video
    - Create a feature folder
- Review the training material in learnt-a-thing
- Own understanding based on cmtat repo and Medium article
    - Start with PRD

Improvements:
1. Start with a PRD.
2. Analyse the requirements to generate a high-level process flow Mermaid diagram.
3. Design the architecture.
4. Generate a technical specification.
5. Follow a stage gate process. This means to break things up in smaller tasks.
6. These smaller tasks must then be planned in granular detail and grouped into stages.
7. Each stage is gated by specific criteria.
8. These criteria are encoded in files that are injected as context for the LLM.

