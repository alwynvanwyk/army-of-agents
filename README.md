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

