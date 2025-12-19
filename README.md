# Kiruthick Kanna

I build production-minded systems — not demo apps.

CSE @ Chennai Institute of Technology  
Former Intern @ ATPAR UI Technology  

Currently building:
- LancerScape (Blockchain escrow marketplace)
- AI Debugging Assistant (VS Code extension)


## LancerScape
Blockchain-based freelance marketplace with escrow-backed payments.

**Problem**  
Freelancers often lack payment guarantees and dispute transparency.

**Why existing solutions fall short**  
- Platform-controlled escrow requires trust  
- Disputes are opaque and biased  
- Payments are delayed or manually released  

**My approach**  
- Smart-contract–based escrow with milestone releases  
- Minimal backend to reduce trust surface  
- Clear on-chain state for payment flow  

**Tech**  
Solidity · Next.js · REST APIs

**Status**  
Active Development

<details>
<summary>Design decisions</summary>

- Used milestone-based escrow instead of lump-sum to reduce dispute impact  
- Factory pattern for scalable contract deployment  
- Accepted slower transaction finality as a tradeoff for trustlessness  
- Dispute resolution intentionally deferred to later phase  

</details>

## AI Debugging Assistant (VS Code Extension)
A developer tool that detects issues and blind spots instead of blindly generating code.

**Problem**  
AI code tools often generate syntactically correct but structurally flawed code.

**Why this matters**  
- Developers over-trust AI output  
- Bugs hide in architecture, not syntax  
- Code quality degrades silently  

**My approach**  
- Analyze existing code instead of generating new code  
- Flag anti-patterns, blind spots, and risky assumptions  
- Preserve project structure and intent  

**Tech**  
TypeScript · VS Code API · AI model integration

**Status**  
MVP / Iterating

<details>
<summary>Design decisions</summary>

- Avoided full code generation to reduce hallucination risk  
- Focused on diagnostics, not replacements  
- Prioritized explainability over raw output  

</details>
