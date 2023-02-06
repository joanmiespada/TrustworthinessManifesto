
# Software Engineering Trustworthiness Manifesto

The purpose of this manifesto is to describe the main areas where a software engineering team can rely on **creating a trustful environment with all teammates and stakeholders**. 

### Why?

Trust is essential for software engineering teams' success. Without trust, it is harrowing to reach team achievements. So, the team will have neither commitment nor results nor friendship. Indeed, it is almost impossible to build anything to be delivered in production.

> Golden Rule: `Trust is our team's cornerstone and the first thing to lose`. 

### What? 

This guideline pursues the objective of spotlighting techniques, methods and tools to keep the trust as high as possible during the software engineering team journey. 

> Golden Rule: `Trust is something that needs to be fed daily, not for what we’re saying but for what we’re doing`.  

### How?

**It’s a guideline, neither a strict process to follow nor vague recommendations. It’s a compilation of several topics that will help software engineering teams daily.** 


# Chapters

## 1.0 Context chapter

### 1.1 Uncertainty environment
We embrace the uncertainty of our business and technology. Neither know anything in advance nor take thoughtful decisions after extended deep diving. So, we’ll make decisions based on the information we’ve got right now. 

### 1.2 Iterative approach
Due to our high level of uncertainty, we can't rely on waterfall processes, where in the end, the product is launched at one time. We embrace small soft launches as frequently as possible and make an impact on our users. 

### 1.3 Mistakes are welcome
Thanks to iterative approaches, mistakes are welcome. People make mistakes, and only making mistakes is the way to improve and evolve. The team is responsible for scoping the errors in effort and time within the shortest time frame. We want to fail fast and learn from mistakes even more quickly. 

> Golden Rule: `Failing with the same mistake twice is forbidden`. 

### 1.4 The common goal
We aren’t front-end engineers creating a web site only or backend engineers building a new microservice only. Regardless of our job, we’re engineers who help our stakeholders and users reach their goals. 

> Golden Rule: `Let’s define our job by the goal we pursue, neither for our knowledge, position, or role inside the team`.  

### 1.5 Shortcuts are pitfalls
Every shortcut is an opportunity to break our product now or in the immediate future. In software engineering, shortcuts create tech debt, which in its turn will become slowing down our delivery capacity shortly.

---

## 2.0 Decision-making chapter

Decision-making processes are fundamental in an engineering team so we will apply the principles described below. They are ordered by priority.  

### 2.1 Values-driven decisions 
We use software engineering values to help our teams to make decisions faster. All decisions must be streamlined with our engineering values. Whatever tech decision must be aligned with our values; if not, there won't be any debate possible, and the decision will automatically be discarded. 

> Golden Rule: `let’s create an engineering values document with a high overall set of values`. 


### 2.2 Data-driven decisions
Whenever possible, all decisions will be taken on data evidence. If there is a lack of data, we need to improve our systems to get new data. In the meantime, the team will take decisions by consensus.  

### 2.3 Consensus-driven decisions
Regardless of level or seniority, all team members are in charge of taking the next team decision. For example, architectural changes, implementation details, team goals, etc. All decisions have a limited time to take action (1 hour, 1 day or 1 sprint). Consensus means half plus one vote.  Leadership will decide only if there is a lack of data and non-consensus has been achieved. 

> Golden Rule: `disagree and commit. It’s welcome having discrepancies among team members. But team members in disagreement need to commit to the team’s decision`. 

### 2.4 Leadership decisions
Each team has two leaders, a Project Manager (PM) and an Engineering Manager (EM), aka double-hat. Both are at the same leadership level and sense of ownership. PM is focused on product rationale, and EM is focused on engineering solutions and people management. If the team can’t reach a consensus, they will be the last line of decisions. They are in charge of unblocking the team as soon as possible.

### 2.5 Closest to reality
Decisions must be as close to reality as possible. When a decision is escalated, it will be procrastinated, creating an overload and attrition, and there isn’t a guarantee that it will be better than the one taken by the team members. When escalating decisions we're losing our competitive advantatge. 

> Golden Rule: `avoid escalating decisions`. 

### 2.6 No ad-hoc decisions
A team is as strong as how its decisions are (quality, measurability, durability and flexibility). The team will be outstanding when regardless of who takes the decision, other mates would take the same decision too.

> Golden Rule: `If we’re facing an issue where we don’t have a guide/rule/process then we need to create the guide first, and fix the issue second, but not the other way around`.

### 2.7 Decisions are written down and well communicated
No decision is final until it has been shared openly with all people involved by written. No verbal agreements are allowed. No important agreements on Slack temporally channels. Crucial decisions will be shared by email. Always, we will provide a time frame (48h or 72h) to get feedback from counterparties, and we’ll communicate by writing whatever official decision.

### 2.8 Communication chain
We’ve got the best communication chain possible; we accept it is imperfect. But, we must improve it daily. These are the steps: 
1. Memo or PR/FAQ document describing the business case (product).
2. Product requirements documents, aka PRDs (product).
3. Sketches and mockups (design). 
4. Technical implementation, aka RFCs (engineering).
5. Pull request (engineering).
6. Architecture design record, aka ADRs (engineering)

The team's delivery will be measured by our capacity to move across all steps iteratively, as fast as possible, without generating attrition or tech debt.

---

## 3.0 People chapter

### 3.1 No retaliation
As mistakes are welcome, it is absolutely forbidden to have any retaliation or blame someone for taking wrong decisions.  

> Golden rule: `we're not blaming people for decisions in the past`. 

### 3.2 Team first, no one left behind
Who always wins is the team, never the individuals. When a feature runs in production, it is thanks to all team members. Team members will contribute at different times/levels/interactions and velocities. 

> Golden rule: `egoless, be humble always`. 

### 3.3 Career ladder
As engineers, our impact is sized by our level/grade in the team. The career ladder is a unique document describing each level's expected impact/outcome for engineers/employees. This document is open to be improved for every employee after each performance review cycle. 

### 3.4 Meritocracy
The team is only as strong as its weakest team member. The willingness to learn and contribute will prevail above the results, **but always is mandatory evolving and moving forward**. We’ve enabled two tools for that purpose: feedback and self-demanding. It isn’t possible to reward someone when the team is weak. Team success prevails over individual success.  
   
> Golden rule: `We're using the feedback to reward outstanding people's performance and spotlighting poor performance`. 

### 3.4.1 No heroes
If someone is doing an extra effort is because there is something to be improved in our tools/processes/practices. It's a sympthom of our weakness and those efforts won't be rewarded.

> Golden rule: `Focus on the root causes, not on the consequences`.

### 3.5 Feedback as often as possible 
Team members are committed to providing feedback as often as possible: each pull request, monthly and quarterly reviews and whatever documentation be created (e.g. RFCs, tech reviews, surveys and so on). **Feedback will be honest, time-framed, based on evidence, emphasising the outstanding actions/results as rewards and spotlighting the weakness as a new way for new upcoming training**.

> Golden rule: `Give feedback in the same way you’d like your teammates to give to you`.        

### 3.6 Self-demanding
Team members will be self-demanding. We don't care what other teammates do and want to ensure we’re doing our best every week. **We don't accept vanilla people or vanilla habits**. 

> Golden rule: `We’ll track our delivery in our own diary, and we’ll compare it against our career ladder to understand if we’re performing as the company expects. We'll do this check weekly. Also, it will be as input document for performance reviews' self-assessment`.

### 3.7 Performance reviews
The team will enable at least two performance reviews per year. The final purpose is to compare an individual's commitment and delivery against the career ladder. Because we know every team member is unique and different, we aren't going to compare people to each other. The line manager will manage the performance review. 

> Golden rule: `People's performance is healthy and aligned with the career ladder for their professional level`.
   
### 3.8 Invest in ourselves
We believe in ourselves. We want to improve ourselves as human beings, engineers and employees. We’ll manage our careers by ourselves, without excuses, proactively. The company will provide context, tools and time, but only we are in charge of using it wisely.
 
> Golden rule: `we’ll invest at least four h every week to learn new things and sharpen hard or soft skills`. 

### 3.9 Exit rewards 
For the individuals that aren’t aligned with team methods, engineering values, business goals or their performance aren’t aligned with the career ladder, team leaders will provide an honoured and soft departure. That decision will be communicated to other team members openly and all teammates will help him/her to find a new job.

> Golden rule: `every layoff is an opportunity for both team and leavers to learn from our mistakes`.

### 3.10 Meetings are for listening 
We want to minimise meetings; when it isn't possible to find a solution asynchronously, we schedule a meeting. But, **we’re joining meetings to listen to the others first**. After understanding our mates, we will share our thoughts openly. Our thoughts and vision will be written down in a document and shared in advance with meeting attendees. If necessary, we’ll invest some minutes reading the document(s) at the beginning of the meeting. 

---

## 4.0 Team Process chapter

### 4.1 Fewer processes, more guidelines
To get autonomy as high as possible within a reasonable context, we need to minimise the processes and increase the guidelines. We need processes (e.g. holidays or leaving requests, out-of-hours shifts, promotions, events/conferences are good candidates to have a transparent process). Still, we want to use guidelines wherever possible. Someone is free to make decisions that match the guidelines. If not, we need to request approval from the team and/or line manager and improve the guideline accordingly.

> Golden rules: `Don’t fix your issues right now only. Create/update a guideline thinking of the neighbour and then fix our issue`.

### 4.2 Promotions
Promoting teammates is crucial to retain and making them happier. However, an arbitrary process here will increase the attrition dramatically. The process must be open, all teammates need to be aware, all teammates will have the chance to provide feedback, and the candidate teammate is in charge of recapping all evidence/feedback, writing down the promo pack and keeping it updated. The career ladder is crucial to provide a guideline. The line manager will coach the candidate and, when the promo pack is ready, will follow the promotion process. Promo pack reviewers will share their feedback by writing their feedback. Failing a promotion isn’t a shame. It is something usual and welcome. It’s an opportunity to learn whenever the feedback is well-reported and communicated. Promotions must happen only after the performance review cycle.  

> Golden rules: `the promotion process is a strong candidate to have a process in place. Maximize transparency`.         

### 4.3 Mid-term vs short-term 
We’re working with short-term deliveries and mid-term goals. Those mid-term goals are  OKRs by semester. Behind each Key Result is a list of potential goals to be achieved during the quarter. Behind quarterly goals, there are sprints with their own sprint goals. Each sprint goal is attached to only one OKR.
             
### 4.4 Lack of clarity
Whenever we’ve got a lack of clarity, we’ll request support from the leadership. In the meantime, we’ll make our own decisions, although they could be painful for us. Sometimes, there aren’t fair decisions, and we want to do our best in each case.  

### 4.5 We appreciate each other’s time
My time is precious, but yours is more precious than mine. We know how important time is among teammates.  We want to keep our focus time high and minimise the meetings. 

### 4.6 Openness 
All team members are open with what, how and why we are doing. Even during our training time, we’re sharing what we’re doing. Also, when we need to be away from the keyboard, we notify our teammates. 

---

## 5.0 Software Engineering Values

### 5.1 Agile means agile
Agile doesn’t mean working with ad-hoc tasks. Agile defines a set of ceremonies, steps, outputs and deliveries. We’re committed to respecting agile principles and best practices consistently. We want to measure our team performance based on metrics/data and without comparing it with other teams.

> Golden rules: `We want to compare ourselves versus ourselves sprint by sprint, quarter by quarter`.

### 5.2 DevOps mindset
We want to release our code to production as fast as possible, as often as possible, as secure as possible and seamlessly. We don´t accept manual or repetitive tasks.  

> Golden rules: `enable automatisation in each engineering step. We focus on automatisation as an investment, never as a cost`. 

### 5.2.1 Site reliability engineering
Our software implements tools and techniques to allow us to understand how the system is performing in production in real-time. We want to avoid system degradation due to complexity.

> Golden rules: `enable infrastructure, monitoring, alerting and metrics to track tech KPIs along the time`

### 5.3 Freedom to choose
Our team is free to make our own decisions and enable our processes and methodologies wherever we don't break this manifesto.

### 5.4 No deadlines
We don’t believe in hard deadlines. We believe in releasing what has been agreed with Product sprint by sprint in production behind a feature toggle. 

### 5.5 Team performance
Our engineering team will measure our performance based on metrics (issue and bug tracking system). We’ll measure our predictability as our capacity to release in production what has been agreed upon with the product on a sprint basis. 

### 5.6 Team maturity 
Our engineering team will shape a matrix where we will measure and track our ongoing status according to agile process enabled, bugs released in production, timeouts, errors, latencies and so on. 

### 5.7 Engagement survey
Every six months, we’ll measure our engagement through an anonymous survey about soft topics such as happiness and health. 

### 5.8 SLOs
We’ll define a set of SLOs to understand if our systems and team processes are performing as expected. If the SLO is breached, then the team will break the team's roadmap to fix this issue asap. SLOs such as critical bugs in production, postmortem action items, stability thresholds, OOH support, CI/CD pipeline delays/breaks, etc.

### 5.9 80-20 rule
The team’s sprint capacity will be split between product development and engineering sanit. 80% for product development and 20% for engineering tasks (tasks non-driven by the PM).

### 5.10 Pull requests
Code reviews are the cornerstone of an engineering team. We use this time to provide feedback as fast as possible, learn from peers and provide transparency in our work. Pull requests will be as short and meaningful as possible. Large PRs will be discarded automatically. Also, we’ll be diligent in applying the best practices agreed upon inside the team. Reviewing PRs has a limited time frame: 30 minutes max. We're reviewing PRs twice daily, starting with the oldest one.

> Golden Rule: `Reviewing PRs is crucial to unblock our teammates' delivery`.

### 5.11 E2E impact and ownership
Engineers will be in charge of releasing a feature to production end-to-end without any handover to other teammates or departments (QA, platform or 3rd parties).      
   
### 5.12 Engineering best practices
Any piece of code in Pull-request ready to be reviewed must apply the engineering best practices agreed upon upfront and inside the team. Otherwise, this piece of code will be rejected. For example, if the team decides to have at least 80% code coverage, then each PR will follow this principle. Otherwise, reviewers will reject it without excuses. Other examples are code style and linting, functional programming, patterns, architecture, etc. 

### 5.13 Release to Production
From staging to production environment must be an automatic and transparent process for product engineering team members. It means the team’s border is the staging environment (backend) or Beta (apps). Team target must seamlessly release their features in staging without blocking any pipelines and behind a feature toggle.

### 5.14 Code coverage
Invariably we'll release our features with proper code coverage. Actually, we want only run tests to ensure the new features work correctly in local or stage environments. Less than 80% code coverage is forbidden.

### 5.15 A/B testing
Perform o no an A/B is a product decision that must be transparent to product engineering teams. A/B testing will be enabled through feature toggles by the product folks. They are expensive in terms of time, so we'll be diligent when using them. 

### 5.16 Branching
Engineers will merge plus rebase to master branch as often as possible. Whenever possible, every day. We must minimise merge conflicts.       

### 5.17 QA testing
Wherever possible manual QA tests will be forbidden. Whenever possible, automatisation tests will be implemented after the A/B test finishes. All QA tests will happen in the test environment(s) and independently of our release process. 
 
### 5.18 Security
We shift left the security in our solutions to foresee potential issues in advance. We will gather feedback from our company’s security team/champions proactively. Security has no excuses and is at the top of product decisions.

---

# List of documents to be completed

* Backend guidelines and principles (tech template)
* Mobile guideline and principles (tech template)
    * iOS specific details
    * Android specific details
* Web guidelines and principles (tech template)
* Codereview guideline (even for each platform)
* Postmortem process and their SLOs
* Bug classification and resolutions SLOs
* RFC process and feedback request
* PRD process and feedback request
* OOH support scope/expectations and scalation policy
* Teams: members, scope and impact
* Ownership: who owns what
* War room principles
* Meeting's policy
* Promotion process
* OKRs, quarterly goals and sprint goals guideline
* Team performance: how team will be measured
* Performance review: principles, guidelines and process
* Feedback's culture: guideline and principles 


## Example of tech template 

Topics to be covered for the document:

* Development
    * Code style and linting: enabled. 
    * Bootstrap local development environment: dockerised dependencies.
    * Error codes definition (2xx, 3xx, ... 5xx ).
    * Compilation timing (cached dependencies): < 30 seconds
    * Pull request sizing: 
        * Files changed: < 10
        * Total lines changed: < 250
    * Codeowners: enabled 
* CI/CD pipeline
    * Flaky test: 0 (they are forbidden).
    * Tests: 
        *  Unit tests: can be at most 1 second.
        *  Integration tests: can't exceed 25 seconds.
        *  e2e test or UI tests: Night build every 24h and async.  
    * Bundling size: new code can't exceed 5% current size. 
    * Code coverage: > 80%
    * Infrastructure as code (all changes with infra must be scripted).
    * Database changes scripted.
    * Code documentation updates.        
* Production
    * Errors => SLO 99,9% error-free
    * Latencies => SLO 99% requests below 200 ms
        * Trend latencies => not growing more than 5% current response times. 
    * Critical Bugs open => Resolution time SLO: 95% fixed in less than 5 minutes.
    * Traceability => all code must be enabled tracing (XRay, DataDog, ... ).
    * Out of Memory errors (OoM): must be caught and tracked. SLO: < 80% memory.   
    * Featured flags => all new features must be shipped behind a feature flag. 

---

**Definitions** 

- ADR: https://en.wikipedia.org/wiki/Architectural_decision 
- Agile: https://en.wikipedia.org/wiki/Agile_software_development 
- Career ladder: https://en.wikipedia.org/wiki/Career_ladder 
- Feature toggle: https://en.wikipedia.org/wiki/Feature_toggle 
- Guideline: https://en.wikipedia.org/wiki/Guideline 
- PRD: https://en.wikipedia.org/wiki/Product_requirements_document 
- Process: https://en.wikipedia.org/wiki/Process 
- Pull request or PR: https://en.wikipedia.org/wiki/Distributed_version_control#Pull_requests 
- OOH: Out of hours support
- OKR: https://en.wikipedia.org/wiki/OKR
- QA: https://en.wikipedia.org/wiki/Quality_assurance 
- RFC: https://en.wikipedia.org/wiki/Change_request 
- SLO: https://en.wikipedia.org/wiki/Service-level_objective 
- Devops: https://en.wikipedia.org/wiki/DevOps 

---

**License**


<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
