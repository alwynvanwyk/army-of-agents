# stage-gate-way-of-working
Breaking news:
I came across [Ryan Carson's way of working yesterday!](https://www.youtube.com/watch?v=fD4ktSkNCw4&list=TLPQMDcwNzIwMjV9wZQs1bjMNQ&index=3)  
This is courtesy of Brian Casel and his [Vibe coding for professionals YouTube.](https://youtu.be/cniTWVMGD08?si=C6-uyqSumoPILHy1)  
It is a lot simpler and seems a lot more effective, so I'll be using it for the next few days to further build out the USSD server.  

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

