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

Really got into the nuts and bolts of Agent limitations yesterday. Even the brightest still needs manual testing and help to resolve gnarly bugs!They tend to overdo it and generate too much code.

OfferZen Community Hackathon with Otinga.io and Impact.com was super-cool!
My prezzo available here as a [public Notion page](https://www.notion.so/Ubuntu-Oracle-23cc21cbdc6380b5967eed94c5e91a61?source=copy_link).
https://app.otinga.io/#/hackathon/SGFja2F0aG9uTm9kZTo2/detail 

Augment is running a YouTube week of learning with short vids on useful features.
Main issue for me is still that new agents need at least one prompt to get proper context for my project, which blows one paid question per month per agent.

Today is the 10 years of Ethereum celebration with global live stream! ⚡️

Great news! The IXO USSD app will now be taken open source - whoopaa!

Think I've got the PRD tool waxed now with AugmentCode tasks and the IXO template.

Kicked off the stable coin hackathon today - nice!

Sundays are always a bit more quiet.

Listened to podcast on Epicentre with one of the NEAR founders - lightning-fast chain!

Fascinating things happening in the Greenpill world - many grants to apply to!

Super excited! Augment is making huge strides in solving the "Context Rot" problem by providing real-time indexing, causal analysis, and persistent memory.

Weird! Augment had an outage yesterday for many hours: HTTP 502 Bad Gateway. When they got back and I could get going again, it was magic. Getting better at providing enough context to the Agent, breaking it down into tasks, and asking only one question, those are expensive(!), generated by  "Run All Tasks".

Augment today announced that GPT-5 is selectable as a model picker. Claude Sonnet 4 is still the default.

Presented the IXO stack today to a small and engaged group at Youngblood Africa Art Gallery in Cape Town. Youssef's video about how to create AI agent oracles was available and well-received.

Using www.machinations.io to model the YNGAF memecoin's tokenomics.

Used Augment Agent this morning to spin up 'pnpm dev' and test it using 'pnpm test:interactive'; all while running off only 2 questions and a bunch of tasks in the tasklist.

Refreshing a few basics about networking and the Internet today!

Got http://alwynvanwyk.co.za up-and-running by using Github Pages.

Agentic Oracle Boilerplate project is in much better shape now - gonna check it out again soon!

Deeply insightful and distrusting questions asked about web3 last night at the GP CPT event named "Deep South Circles: Ideas into Action"

Powerful new feature introduced by Cursor/Linear! Cursor will run off on its own to fix a bug or tweak UI while tracking it in Linear.

Augment CLI "Auggie" landed today! Whoop-Whoop!

Going to use Auggie today for specific use case; just need to figure out which one will work best and is standalone.
Perhaps the claim submission use case is best suited.
Or rather the LZAR hackathon use case. I'm just not sure yet how to use it effectively and look forward to being able to deep dive!
Actually, it will make the most sense with the Subscription Oracle use case.
Auggie today available for public access - coolios!

Okay, so here's my current workflow with Auggie!
- Workspace dir with all projects related to a project; for example ECS. Auggie indexes up to 500,000 files across all of these repos!
- Spin up an agent for each workstream; for example, one agent for USSD enhancements, another for the subscriptions oracle, another for the Telerivet callback server, and one more for the SUPA and BEAN token implementation.
- Each agent has its own 'state' dir in the workspace /docs dir where I ask it to "Before we continue, summarize our decisions, constraints, interfaces, and next steps in ≤200 lines. This becomes the only source of truth. Save this summary to ecs/docs/agent1/state-<timestamp>.md".
- Then, when I start a new session, I ask the fresh agent to "Before we start, review the documents in ~/github/\_workspace/ecs/prd to understand the full scope of the ECS project. Then review the specific State file regarding the current state of the project at ~/github/\_workspace/ecs/docs/agent????."
- Once the new agent session is well prepared, I set up a tasklist in Auggie and ask the agent to "Review the tasklist and break it down into step-by-step tasks. Add these tasks to the tasklist and execute the tasks one-by-one until finished. Pause to ask me clarifying questions at any time."
Today, I hope to have 4 agents running - how to keep up with all of their questions and to review what they deliver?! :)

End of day git bliss! When my 4 agents have pushed to remote, written up the current state, and saved the tasklist.  
<img width="3456" height="2234" alt="CleanShot 2025-09-03 at 17 38 34@2x" src="https://github.com/user-attachments/assets/1d19c530-4338-4852-b4e2-1dbd5520d535" />

Also, a good way to describe what I do; involved with "social purpose organisations".

It becomes difficult to run more than 2 agents at a time on tasks that take a long time for me to review.
Quality over quantity in some cases!

Looking forward to Cloudflare Workers running the bulding blocks for an end-to-end solution in Zambia.
Bond buy, mobile money payment SMS, USSD queries (?), and more!
Cloudflare learning materials seem to be comprehensive.

Got my agents nicely at work on the SupaMoto project!
Joining the MS user group session on Saturday about using VS Code effectively.

Properly understanding workers and queues now locally using Miniflare.

Allan Pead at the Microsoft office at Mowbray Office in Pinelands.
Got my "VS Code Insiders" sticker! :)

Good reading about how to use agents well. 
- https://github.com/agent-era/devteam
- https://cline.bot/learn

Nice to have the SMS worker and oracle worker nicely picking up and processing messages from the Telerivet gateway.
Further to this, it is nice to have gotten the Cloudflare workers and queues set up.

AWS Community Day in Cape Town was very cool! Amazing building!

I will revisit Ryan Carson's ways of working - seems to work well for him.

Also, important to have the workers and queues be usable across multiple cloud providers ala [Bring your own cloud or Infra as Data (JSON) not Terraform](https://softwareengineeringdaily.com/2025/08/21/complex-workload-deployment-with-will-stewart/)

Geez, compliance docs are a lot of work! :|

---

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

