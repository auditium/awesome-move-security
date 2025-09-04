# Move Security Resources

A curated collection of links about the **Move programming language** with an emphasis on **security**. The Move ecosystem spans multiple blockchains (e.g., Aptos, Sui, Movement, Starcoin) and its type system was designed to prevent double‑spend and re‑entrancy issues. However, implementations can still contain logical bugs or misuse critical patterns. This list gathers articles, guidelines, research papers, tools, audits, and companies that focus on Move security.

---

## Quick start (must-reads)
- [Aptos — Move Security Guidelines](https://aptos.dev/build/smart-contracts/move-security-guidelines)
- [Sui — Security Best Practices](https://blog.sui.io/security-best-practices/)
- [Securing Move (Aptos Labs × OtterSec)](https://medium.com/aptoslabs/securing-move-f81099f5e08c)
- [Move Prover Overview (Aptos)](https://aptos.dev/build/smart-contracts/prover)
- [Top 10 Most Common Bugs In Your Aptos Move Contract (Zellic)](https://www.zellic.io/blog/top-10-aptos-move-bugs)
- [Formal Verification, the Move Language, and the Move Prover (CertiK)](https://www.certik.com/resources/blog/formal-verification-the-move-language-and-the-move-prover)
- [Why Move? (Aptos)](https://aptos.dev/en/build/smart-contracts/why-move)

---

## Blogs & Deep Dives
- [Move: An Auditor’s Introduction — OtterSec](https://osec.io/blog/2022-09-06-move-introduction)
- [Move Prover — OtterSec](https://osec.io/blog/2022-09-16-move-prover)
- [Move Fast & Break Things — Zellic](https://www.zellic.io/blog/move-fast-and-break-things-pt-1)
- [Moving the Immovables: Lessons from Aptos Audit — CertiK](https://www.certik.com/resources/blog/moving-the-immovables-lessons-learned-from-our-aptos-smart-contract-audit)
- [Move for Solidity Developers — CertiK](https://www.certik.com/resources/blog/move-for-solidity-developers-token-standard-i)
- [Security Practices in Move Development — BlockSec](https://blocksec.com/blog/security-practices-in-move-development-1-hello-world)
- [What is the Move Programming Language? — Halborn](https://www.halborn.com/blog/post/what-is-the-move-programming-language)
- [A Manifesto for Remarkable Sui Codebases](https://medium.com/@BlockRunner/a-manifesto-for-remarkable-sui-codebases-8750432c9ebb)
- [Security Analysis of the Move Language — Numen Cyber](https://www.numencyber.com/security-analysis-of-the-move-language-game-changer-of-smart-contracts/)
- [The Ultimate Guide to the Move Programming Language (2025) — Supra](https://supra.com/academy/ultimate-guide-to-the-move-programming-language/)
- [How the Move Programming Language Works — Pontem](https://pontem.network/posts/how-the-move-programming-language-works)
- [A Complete Guide About Move Programming Language — Medium](https://medium.com/@mohinisaxena/a-complete-guide-about-move-programming-language-6d025ddcf05c)
- [Move, the revolutionary smart contract language powering Sui — Sui](https://sui.io/move)
- [Formal Verification, the Move Language, and the Move Prover — CertiK](https://www.certik.com/resources/blog/formal-verification-the-move-language-and-the-move-prover)
- [Move Programming Language: Building Safer, Smarter Blockchains — Tokenminds](https://tokenminds.co/blog/blockchain-development/move-programming-languange)
- [An Introduction to Move — CertiK](https://www.certik.com/resources/blog/an-introduction-to-move)
- [A Deep Dive Analysis: 2024 Comprehensive Review of Technological Innovations and Security Events in the Move Ecosystem — MoveBit](https://www.movebit.xyz/blog/post/A-Deep-Dive-Analysis-A-2024-Comprehensive-Review-of-Technological-Innovations-and-Security-Events-in-the-Move-Ecosystem-20241204.html)
- [2024 Guide to Move Programming Language — Metaschool](https://metaschool.so/articles/guide-move-programming-language/)
- [Unlock the Power of Move: A Step-by-Step Guide for Beginners — RiseIn](https://www.risein.com/blog/unlock-the-power-of-move-step-by-step-guide-for-beginners)
- [MoveLang: A Rising Titan in Smart Contract Programming — Supra](https://supra.com/academy/movelang-a-rising-titan-in-smart-contract-programming/)
- [What Is Move Language? (Guide to Move-Based Blockchains) — QuillAudits](https://www.quillaudits.com/blog/blockchain/what-is-move-language)
- [Analysis of Sui Contract Security and Ecosystem Challenges — Gate](https://www.gate.com/learn/articles/analysis-of-sui-contract-security-and-ecosystem-challenges/5112)
- [Why Your Sui Smart Contract Might Be at Risk & How We Help? — QuillAudits](https://www.quillaudits.com/blog/web3-security/secure-your-sui-smart-contracts)
- [Aptos | How to Read a Security Audit Report — CertiK](https://certik.medium.com/aptos-how-to-read-a-security-audit-report-e619f8196697)
- [Moving the Immovables: Lessons Learned From Our Aptos Smart Contract Audit — CertiK](https://www.certik.com/resources/blog/moving-the-immovables-lessons-learned-from-our-aptos-smart-contract-audit)

---

## Official Guidelines & References
- [Aptos — Move Security Guidelines](https://aptos.dev/build/smart-contracts/move-security-guidelines)
- [Aptos — Move Prover Overview](https://aptos.dev/build/smart-contracts/prover)
- [Sui — Security Best Practices](https://blog.sui.io/security-best-practices/)
- [Sui — Security Hub](https://sui.io/security)
- [Move Book](https://move-language.github.io/move/)
- [Introduction to Move — Move Language GitHub](https://move-language.github.io/move/)
- [Move Security Guidelines (Aptos) — Aptos](https://aptos.dev/build/smart-contracts/move-security-guidelines) (Covers ownership verification, access control, generics, resource management, abilities, arithmetic, objects, front-running, oracles, tokens)
- [Why Move? — Aptos](https://aptos.dev/en/build/smart-contracts/why-move)

---

## Tools
### Formal Verification
- [Move Prover (Aptos)](https://aptos.dev/build/smart-contracts/prover)
- [Move Prover Tutorial — MoveBit](https://www.movebit.xyz/blog/post/Move-Prover-Tutorial.html)

### Fuzzing
- [sui-fuzzer (FuzzingLabs × Sui Foundation)](https://github.com/FuzzingLabs/sui-fuzzer)
- [MoveFuzz](https://getfailsafe.com/top-move-smart-contract-auditing-companies-services-in-2025/)

### Static Analysis & IDEs (MoveBit)
- [Move Analyzer (Sui)](https://www.movebit.xyz/analyzer)
- [Move Analyzer (Aptos)](https://www.movebit.xyz/AptosMoveAnalyzer)
- [Move Formatter](https://www.movebit.xyz/AptosMoveFormatter)
- [Move Web IDE](https://www.movebit.xyz/MoveWebIDE)
- [Move Scanner](https://www.movebit.xyz/MoveScanner)
- [Contract Source Verifier (Sui)](https://www.movebit.xyz/ContractSourceVerifier)
- [Linters](https://getfailsafe.com/top-move-smart-contract-auditing-companies-services-in-2025/) (For dependency checks)
- [Aptos CLI](https://getfailsafe.com/top-move-smart-contract-auditing-companies-services-in-2025/) (Command-line interface)

---

## Tutorials & Learning
- [Aptos — Your First Move Module](https://aptos.dev/build/smart-contracts/your-first-move-module)
- [Move Book](https://move-language.github.io/move/)
- [BlockSec — Security Practices in Move Development](https://blocksec.com/blog/security-practices-in-move-development-1-hello-world)
- [CertiK — Move for Solidity Developers](https://www.certik.com/resources/blog/move-for-solidity-developers-token-standard-i)
- [Sui DeepBook Tutorial](https://hackmd.io/@moritzfelipe/sui-dacade-deepbook-tutorial-01) (Fundamentals of Sui DeFi with Move)
- [Ultimate Guide to Sui Blockchain DEX Development 2024](https://www.rapidinnovation.io/post/how-to-build-a-dex-on-sui-blockchain) (Building DeFi on Sui)
- [How to Verify Smart Contracts on the Sui Blockchain](https://www.movebit.xyz/blog/post/Move-Prover-Tutorial.html) (Using Move Prover for formal verification)
- [Sui zkLogin Tutorial](https://hackmd.io/@moritzfelipe/HkEBKKzYa) (Building DApps with React frontend)
- [The Move Book](https://www.move-book.com/) (Comprehensive developer guide)

---

## Audit Reports & Writeups
- [Zellic — Sui Security Assessment](https://github.com/sui-foundation/security-audits/blob/main/docs/Move%20and%20Sui%20Security%20Assessment%20-%20Zellic%20Audit%20Report.pdf)
- [Securing Move — Aptos Labs × OtterSec](https://medium.com/aptoslabs/securing-move-f81099f5e08c)
- [CertiK — Lessons from Aptos Audit](https://www.certik.com/resources/blog/moving-the-immovables-lessons-learned-from-our-aptos-smart-contract-audit)
- [MoveBit Streamflow Finance Audit on Sui and Aptos](https://www.movebit.xyz/blog/post/MoveBit-Streamflow-audit.html) (Public audit reports for protocols)
- [Infinite Recursion Vulnerability in Move VM (2023)](https://www.movebit.xyz/blog/post/A-Deep-Dive-Analysis-A-2024-Comprehensive-Review-of-Technological-Innovations-and-Security-Events-in-the-Move-Ecosystem-20241204.html) (Discovered and resolved; affected Sui/Aptos)
- [Memory Pool DoS Vulnerability in Aptos (2024)](https://www.movebit.xyz/blog/post/A-Deep-Dive-Analysis-A-2024-Comprehensive-Review-of-Technological-Innovations-and-Security-Events-in-the-Move-Ecosystem-20241204.html) (High severity; fixed in v1.19.1)
- [Sui Security Audits and Resources](https://sui.io/security) (Regular third-party audits for Sui network; findings shared timely)

---

## Companies Working on Move Security
- [OtterSec](https://osec.io)
- [Zellic](https://www.zellic.io)
- [MoveBit](https://movebit.xyz)
- [SlowMist](https://slowmist.medium.com)
- [CertiK](https://www.certik.com)
- [Halborn](https://www.halborn.com)
- [BlockSec](https://blocksec.com)
- [FailSafe](https://getfailsafe.com)
- [QuillAudits](https://www.quillaudits.com)
- [FuzzingLabs](https://github.com/FuzzingLabs/sui-fuzzer)
- [BitsLab](https://www.movebit.xyz/)

---

## Research & Papers
- [Analyzing Critical Security Vulnerabilities in Move Smart Contracts (2025)](https://link.springer.com/article/10.1007/s10586-025-05439-1)
- [Security Analysis of the Move Language — Numen Cyber](https://www.numencyber.com/blog/security-analysis-of-the-move-language)
- [The Move Prover (CAV 2020)](https://link.springer.com/chapter/10.1007/978-3-030-53291-8_7)

---

## Awesome Lists & Repos
- [MystenLabs/awesome-move](https://github.com/MystenLabs/awesome-move) (Broad Move resources with some security mentions)
- [awesome-move/awesome-move](https://github.com/awesome-move/awesome-move) (General Move awesome list)

