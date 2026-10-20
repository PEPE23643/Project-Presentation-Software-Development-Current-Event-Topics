# Draft of the presentation


## Table of contents
Introduction: AI use in Reverse Engineering and Security Risk Implications
1. How AI reconstructs programs:
   - In which ways AI analyzes code and its logic to reverse engineer
   - Limits and what can't be done reliably
2. AI Use in reverse engineering:
   - Reverse engineering video games, putting them in other games
   - Reverse engineered software (PhotonStudio)
3. Security Risks in the Future:
      1. If any software can be reverse engineered by AI, is all software going to be "open-source"?
## Introduction
### Our findings connect directly to modern programming language trends and software engineering ethics:
#### Language Safety and Lowering Barriers
Recent trends in AI reverse engineering leads to an explosive increase in recompiled and reshipped products and applications.
#### The Ethics of Code Provenance and Ownership
Just as AI-powered reverse engineering blurs the line between legitimate auditing and trade secret theft.
## How AI reconstructs programs:
|Source Code / Goal | Approximation / Guess | Compile and Compare | Adjust and Recompile | Complete Code |
|-----------------| ---------------------|-------------------|--------------------|-------------|
| To begin you need the both the source application and you need to know it’s compiler + flags. | Ai Agent codes and guesses variables, variable names, functions, code structure using industry standards. | Run the ‘guess’ code through the same compiler as the source with the same flags. Compare the output machine code bit by bit with the source’s. | Bits that compile exactly the same are correct and same as the original. Change and adjust code where the machine code bits do not line up. | Once the output machine code matches the machine code from the source, you’ve recreated the source program! |
## Examples 
- Trend in reverse engineering video games and implementing game code into other games.
  - Reverse-engineering and porting video games required volunteer communities years of manual assembly analysis, guessing, and trial-and-error over months or years. 
By utilizing AI agents and modern tools (like REA), users can analyze compiled machine code and rebuild functionally equivalent source code that behaves identically to the original within weeks or days, significantly lowering the technical and mechanical barrier to entry. 
Taking two decompiled games into the same language, they can be merged and variables and functions from both games and interact with one another.
- Proprietary software like Photoshop being reverse engineered and released for free.
  - For decades, commercial desktop suites like Adobe Photoshop relied on massive R&D investments, compiled binary obscurity, and subscription models as an impenetrable economic moat. However, recent engineering breakthroughs demonstrate that black-box reverse engineering can bypass this barrier.
## AI Use in reverse engineering:
### 1. Reverse engineering in video games; using the code for running within other games.
### Advantages
1. Time efficiency: AI can speed up the process of decomplication and assembly translation by a ton compared to humans alone.
2. Anti-Cheat analysis: Humans can let the AI detect for cheats and obscure important data to protect the users.
- **Assets and Logic Porting:**
AI-assisted reverse engineering allows analysts to deconstruct proprietary game engines, asset formats, and physics loops. Allowing to match the original srouce code byte by byte.
- **Legally speaking:**
While extracting code or assets from a commercial game and injecting them into another violates copyright, AI lowers the technical barrier to doing it. It can translate custom file structures into readable specifications, therefore acting as the “Dirty room”,  while the humans only gets the specifications without knowing the original code.
## Security Risks in the Future:
### If any software can be reverse engineered by AI, is all software going to be "open-source"?
- **The Illusion of Compilation Security:** Because manual reverse engineering required specialized expertise and immense time, proprietary code remained secure even without source code access.
- **Democratized Decompilation vs. Legal Moats:** In practice, technically, any software can now be reverse-engineered, analyzed, and functionally cloned much faster.
- **Will All Software Become Open-Source? No, not legally or structurally.** Rather than everything becoming open-source, we are moving into an era of enforced opacity.
## Conclusion
- Our core findings demonstrate that AI tools fundamentally alter software research. 
- By bridging natural language processing with disassemblers.
- This acceleration introduces severe systemic risks.
## References
- https://blog.ai-laws.org/reverse-engineering-in-ai-balancing-innovation-and-ip-protection/
- https://coesecurity.com/ai-powered-reverse-engineering-how-rea-is-changing-software-security-research/
- https://www.ibm.com/think/topics/ai-security
- https://www.webasha.com/blog/ai-in-reverse-engineering-how-artificial-intelligence-is-transforming-cybersecurity-malware-analysis-and-software-auditing
