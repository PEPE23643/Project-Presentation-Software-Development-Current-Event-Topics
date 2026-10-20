# Draft of the presentation


## Table of contents
Introduction: AI use in Reverse Engineering and Security Risk Implications
1. How AI reconstructs programs:
  1. In which ways AI analyzes code and its logic to reverse engineer
  2. Limits and what can't be done reliably
2. AI Use in reverse engineering:
  1. Reverse engineering video games, putting them in other games
  2. Reverse engineered software (PhotonStudio)
3. Security Risks in the Future:
      1. If any software can be reverse engineered by AI, is all software going to be "open-source"?
## Introduction
> Our findings connect directly to modern programming language trends and software engineering ethics:
#### Language Safety and Lowering Barriers
#### The Ethics of Code Provenance and Ownership
## How AI reconstructs programs:
|Source Code / Goal | Approximation / Guess | Compile and Compare | Adjust and Recompile | Complete Code |
|-----------------| ---------------------|-------------------|--------------------|-------------|
| To begin you need the both the source application and you need to know it’s compiler + flags. | Ai Agent codes and guesses variables, variable names, functions, code structure
using industry standards. | Run the ‘guess’ code through the same compiler as the source with the same flags. Compare the output machine code bit by bit with the source’s. | Bits that compile exactly the same are correct and same as the original. Change and adjust code where the machine code bits do not line up. | Once the output machine code matches the machine code from the source, you’ve recreated the source program! |
## Examples 
- Trend in reverse engineering video games and implementing game code into other gamesTrend in reverse engineering video games and implementing game code into other games
- Proprietary software like Photoshop being reverse engineered and released for free

## AI Use in reverse engineering:
1. Reverse engineering in video games; using the code for running within other games.
2. Reverse engineered software (PhotonStudio)
## Security Risks in the Future:
### If any software can be reverse engineered by AI, is all software going to be "open-source"?
- **The Illusion of Compilation Security:** Historically, software vendors relied on binary compilation and obfuscation as a natural economic and technical moat. Because manual reverse engineering required specialized expertise and immense time, proprietary code remained secure even without source code access.
- **Democratized Decompilation vs. Legal Moats:** With AI agents acting as universal translators between machine binaries and human-readable logic, the traditional security-through-obscurity model is collapsing. In practice, technically, any software can now be reverse-engineered, analyzed, and functionally cloned much faster.
- **Will All Software Become Open-Source? No, not legally or structurally.** While AI makes software deconstructable, Document 4 highlights that legal protections will fiercely resist this shift. Rather than everything becoming open-source, we are moving into an era of enforced opacity: software will be easily analyzed by AI in private labs, but distributing cloned or reverse-engineered binaries will trigger  cryptographic locking mechanisms.
## Conclusion
- This investigation explored the transformative intersection of Artificial Intelligence and Reverse Engineering, mapping its technical capabilities, security vulnerabilities, legal paradoxes, and the shifting boundaries of accountability.
## References
- https://blog.ai-laws.org/reverse-engineering-in-ai-balancing-innovation-and-ip-protection/
- https://coesecurity.com/ai-powered-reverse-engineering-how-rea-is-changing-software-security-research/
- https://www.ibm.com/think/topics/ai-security
- https://www.webasha.com/blog/ai-in-reverse-engineering-how-artificial-intelligence-is-transforming-cybersecurity-malware-analysis-and-software-auditing
