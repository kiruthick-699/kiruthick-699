# This is Kiruthick Kanna >.<

I build production-minded systems — not demo apps.

CSE @ Chennai Institute of Technology  
Former Intern @ ATPAR UI Technology  

Currently building:
- LancerScape (Blockchain escrow marketplace)
- AI Debugging Assistant (VS Code extension)


## LancerScape

Blockchain escrow marketplace for freelancers.

- Core idea: Trustless, milestone-based payments

- Why: Platform-controlled escrow requires blind trust

- Approach: Smart contracts + minimal backend

- Tech: Solidity · Next.js · REST

- Status: Active

<details> <summary>Design decisions</summary>

- Milestone escrow to limit dispute impact

- Factory pattern for scalable contract creation

- Slower finality accepted for transparency

</details>


## AI Debugging Assistant

VS Code extension focused on diagnostics, not code generation.

- Core idea: Expose blind spots in AI-assisted code

- Why: AI tools optimize syntax, not structure

- Approach: Analyze existing code, flag risks

- Tech: TypeScript · VS Code API · AI

- Status: MVP

<details> <summary>Design decisions</summary>

- Avoided full code generation to reduce hallucinations

- Prioritized explanations over raw output

</details>



### How I Approach Engineering

- Start from failure cases, not features

- Prefer simple systems that can evolve

- Avoid abstraction until repetition forces it

- Make tradeoffs explicit

### Constraints I Design Around

- Limited trust in centralized components

- Incomplete or changing requirements

- Systems that must scale without rewrites

### Current Focus

- Frontend architecture with React

- Backend authorization & RBAC

- Understanding AI failure modes

- Cloud deployment fundamentals

