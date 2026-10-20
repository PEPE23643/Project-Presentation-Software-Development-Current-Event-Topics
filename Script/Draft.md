# Members script
### Abdy Ho
- Through frameworks like REA and MCP integrations, AI coding agents interface directly with disassemblers and decompilers (Ghidra, IDA Pro, Binary Ninja). Instead of just reading text files, the AI parses assembly instructions, symbol tables, and control-flow graphs into structured pseudo-C or abstract syntax trees.
### Kenny Caza
- However, this acceleration introduces severe systemic risks: hallucinations, privacy leakage via cloud APIs, obfuscation blind spots, and the automated weaponization of binaries into remote code execution (RCE) vectors.
### Franccesco
- Historically, software vendors relied on binary compilation and obfuscation as a natural economic and technical moat. Because manual reverse engineering required specialized expertise and immense time, proprietary code remained secure even without source code access.

## Slides 
1. Introduction
2. How AI is Used in Reverse Engineering (How it works)
   - Reverse engineering is brute force check-n-go
        - Use the same compiler as the original devs, guess how their code looked, compile and compare, edit what doesn't match
        - The end goal is the exact same code written by the original devs byte for byte
        - Several tools already developed to aid in this process (tools to identify compiler, to permutate code, etc.)
   - How AI speeds up the process by multitudes in factor
        - Method goes from taking years to taking weeks/days
   - Still not perfect
        - AI is still relatively new, still delivers incorrect code, may try to 'cheat'
3. Current Examples
   - Trend in reverse engineering video games
        - Recent trend in reverse engineering games, taking game code and systems, and implementing them in to other games (from different consoles, or generation)
        - Trend only began early Oct
   - Proprietary software like Photoshop being reverse engineered and released for free
4. What does this mean for the future?
   - Ultimately, AI cannot replace foundational technical expertise or human judgment. Governance requires a dual approach: technical sandboxing combined with structural legal reforms that harmonize intellectual property protections with the need for safety transparency.
