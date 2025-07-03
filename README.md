# Awesome-ZKP-Security ![awesome](https://awesome.re/badge.svg)

A curated list of awesome ZKP Security resources, papers, tutorials, and tools. Inspired by [Awesome-Smart-Contract-Security](https://github.com/saeidshirazi/Awesome-Smart-Contract-Security).

If you want to add a new resource, please submit a pull request to improve this file. Thank you!

## Table of Contents

- [ZKPs](#zkps)
- [Blogs](#blogs)
- [Audits](#audits)
- [Talks](#talks)
- [CTFs and Puzzles](#ctfs-and-puzzles)
- [Misc](#misc)
- [Papers](#papers)
- [Tools](#tools)

## ZKPs

### Curated Lists for ZKPs

- [Xor0v0/awesome-zero-knowledge-proofs-security](https://github.com/Xor0v0/awesome-zero-knowledge-proofs-security)
- [sCrypt-Inc: Awesome zero knowledge proofs](https://github.com/sCrypt-Inc/awesome-zero-knowledge-proofs)
- [matter-labs: Awesome zero knowledge proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
- [ventali/awesome-zk](https://github.com/ventali/awesome-zk)
- [zkp.science](https://zkp.science)
- [Zero-Knowledge Proofs Starter Pack](https://ethresear.ch/t/zero-knowledge-proofs-starter-pack/4519)
- [gakonst/awesome-starknet](https://github.com/gakonst/awesome-starknet)
- [Zero Knowledge Canon by a16z](https://a16zcrypto.com/zero-knowledge-canon/)
- [ZKP Knowledge Base by Delendum Research](https://kb.delendum.xyz/)

### Courses

- [Zero Knowledge Proofs MOOC](https://zk-learning.org/)
- [MIT's Modern Zero Knowledge Cryptography](https://zkiap.com/)
- [0xParc's Circom and Halo2 learning groups](https://learn.0xparc.org/)

### Books

- [The MoonMath Manual to zk-SNARKs](https://leastauthority.com/community-matters/moonmath-manual): minimal experience in cryptography required
- [A Graduate Course in Applied Cryptography](http://toc.cryptobook.us/book.pdf) (Dan Boneh and Victor Shoup, 2023)
- [Proofs, Arguments, and Zero-Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf) (Justin Thaler, 2022)
- [Building Cryptography Proofs from Hash Functions](https://github.com/hash-based-snargs-book/hash-based-snargs-book/blob/main/snargs-book.pdf) (Alessandro Chiesa and Eylon Yogev, 2024)

## Blogs

- [zkSecurity's Blog](https://www.zksecurity.xyz/blog/)
- [0xParc's Blog](https://0xparc.org/blog)
- [Trail of Bits' Blog](https://blog.trailofbits.com/)
- [OZ's Security Insights Blog](https://blog.openzeppelin.com/tag/security-insights)
- [Veridise's Blog](https://veridise.medium.com/)
- [Zellic's Blog](https://www.zellic.io/blog/)
- [David Wong's Blog](https://www.cryptologie.net/)

### Specific blog posts / Vulnerability Disclosures

- [The State of Security Tools for ZKPs](https://www.zksecurity.xyz/blog/posts/zksecurity-tools/) (Jun 2, 2024)
- [Detecting boomerang values in zero-knowledge circuits using tag analysis](https://www.zksecurity.xyz/blog/posts/boomerang/) (Aug 25, 2023)
- [The zero-knowledge attack of the year might just have happened, or how Nova got broken](https://www.zksecurity.xyz/blog/posts/nova-attack/) (Jul 2, 2023)
- [Do in secret. Assert in public. Don't under-constrain your prover's witness computation in ZK programs](https://www.zksecurity.xyz/blog/posts/underconstrain-bugs/) (Jun 1, 2023)
- [Ecne: Automated Verification of ZK Circuits](https://0xparc.org/blog/ecne) (May 12, 2022)
- [What Is a ZK Audit?](https://www.zellic.io/blog/what-is-a-zk-audit/) (Jan 25, 2024)
- [ZK-SNARKS & The Last Challenge Attack: Mind Your Fiat-Shamir!](https://blog.openzeppelin.com/the-last-challenge-attack) (Dec 14, 2023)
- [The Frozen Heart vulnerability in PlonK](https://blog.trailofbits.com/2022/04/18/the-frozen-heart-vulnerability-in-plonk/) (Apr 18, 2022)
- [The Frozen Heart vulnerability in Bulletproofs](https://blog.trailofbits.com/2022/04/15/the-frozen-heart-vulnerability-in-bulletproofs/) (Apr 15, 2022)
- [Coordinated disclosure of vulnerabilities affecting Girault, Bulletproofs, and PlonK](https://blog.trailofbits.com/2022/04/13/part-1-coordinated-disclosure-of-vulnerabilities-affecting-girault-bulletproofs-and-plonk/) (Apr 13, 2022)
- [It pays to be Circomspect](https://blog.trailofbits.com/2022/09/15/it-pays-to-be-circomspect/) (Sep 15, 2022)
- [Disarming Fiat-Shamir footguns](https://blog.trailofbits.com/2024/06/24/disarming-fiat-shamir-footguns/) (Jun 24, 2024)
- [Zcash Counterfeiting Vulnerability Successfully Remediated](https://electriccoin.co/blog/zcash-counterfeiting-vulnerability-successfully-remediated/) (Feb 5, 2019)
- [Security Vulnerabilities in ZK](https://zkv.xyz/security-vulnerabilities-in-zk/) (Sep 1, 2023)
- [Circom-Pairing: A Million-Dollar ZK Bug Caught Early](https://medium.com/veridise/circom-pairing-a-million-dollar-zk-bug-caught-early-c5624b278f25) (Jan 3, 2023)
- [Developing securely on Aleo blockchain: Common Vulnerability Patterns](https://medium.com/veridise/developing-securely-on-aleo-blockchain-common-vulnerability-patterns-a99070e3ebe2) (Jun 26, 2024)
- [Satisfiability Modulo Finite Fields: Unlocking SMT for ZK Verification](https://medium.com/veridise/satisfiability-modulo-finite-fields-unlocking-smt-for-zk-verification-3709b0b2b48e) (Aug 17, 2023)
- [ZK Vulnerabilities: Sharp rocks hidden in deep water](https://medium.com/veridise/zk-vulnerabilities-sharp-rocks-hidden-in-deep-water-7cad8d4c2dfa) (May 2, 2023)
- [Medjai: Protecting Cairo code from Bugs](https://medium.com/veridise/medjai-protecting-cairo-code-from-bugs-d82ec852cd45) (Jul 22, 2022)
- [Patch Thursday -- Uncovering a ZK-EVM Soundness Bug in zkSync Era](https://medium.com/chainlight/uncovering-a-zk-evm-soundness-bug-in-zksync-era-f3bc1b2a66d8) (Nov 2, 2023)
- [Common Vulnerabilities in ZK Proof](https://blog.oxor.io/common-vulnerabilities-in-zk-proof-5ba7620dfa2f) (Oct 30, 2023)
- [ChainLight saved zkSync Era from $1.9B exploit](https://blockworks.co/news/exploit-bug-zksync-matter-labs) (Nov 3, 2023)
- [ZKPs for Engineers: A look at the Dark Forest ZKPs](https://blog.zkga.me/df-init-circuit) (Sep 29, 2020)
- [Facebook: Critical bugs in Facebook/Polygon Winterfell library](https://github.com/google/security-research/security/advisories/GHSA-8fhq-pf83-pv93) (Apr 12, 2023)
- [Vulnerabilities patched in Aztec 2.0](https://medium.com/aztec-protocol/vulnerabilities-found-in-aztec-2-0-9b80c8bf416c) (Sep 16, 2021)
- [00 PLONK Bug](https://github.com/cryptosubtlety/00/blob/main/00.pdf) (15 Dec 2021)
- [Aztec: Disclosure of recent vulnerabilities](https://hackmd.io/@aztec-network/disclosure-of-recent-vulnerabilities) (Jan 11, 2022)
- [Tornado.cash got hacked. By us.](https://tornado-cash.medium.com/tornado-cash-got-hacked-by-us-b1e012a3c9a8) (Oct 12, 2019)
- [Filecoin -- one PoREP vulnerability found by Trapdoor Tech](https://trapdoortech.medium.com/filecoin-one-porep-vulnerability-found-by-trapdoor-tech-7fc7beb4557b) (May 7, 2020)
- [Formal Verification of ZK Constraint Systems](https://delendum.xyz/writings/2022-09-04-formal-verification-zk-constraint-systems.html) (Sep 4, 2022)
- [Groth16 Malleability](https://github.com/geometryxyz/groth16-malleability) (Last updated: Aug 1, 2022)
- [SP1 Security Update (2 vulns disclosure)](https://blog.succinct.xyz/sp1-security-update-1-27-25/) (Jan 27, 2025)
- [Solana says zero-knowledge proofs were root of mid-April bug](https://blockworks.co/news/solana-bug-patch-zero-knowledge-proofs) ([fix](https://github.com/anza-xyz/agave/pull/5883)) (May 5, 2025)

## Audits

- [Collection of security reviews of ZK Protocols](https://github.com/nullity00/zk-security-reviews)
- [zksecurity audit reports](https://www.zksecurity.xyz/reports/)
- [openzeppelin audit reports](https://blog.openzeppelin.com/tag/security-audits)
- [veridise audit reports](https://veridise.com/past-security-audits/)

- [ZKP MOOC Lecture 15: Secure ZK Circuits with Formal Methods](https://www.youtube.com/watch?v=av7Wq742GIA)
- [zkStudyClub: Zero-Knowledge Proofs Security, in Practice -- JP Aumasson, Taurus](https://www.youtube.com/watch?v=l_pIrHVz87I)
- [0xParc: (Workshop) ZK Security Research](https://www.youtube.com/watch?v=nYifGRRikh8)
- [Are Your Zero-Knowledge Proofs Correct? by Jon Stephens | Devcon Bogotá](https://www.youtube.com/watch?v=ettgm3ZVYOk)
- [Shankara Pailoor - Picus: Push button zk circuit verification](https://www.youtube.com/watch?v=4iDhdEmwnlQ)
- [Introduction to ZK Security Research | David Theodore | PROGCRYPTO](https://www.youtube.com/watch?v=P2OVtcsSZSQ)
- [ZK7: Security of ZKP projects: same but different - JP Aumasson - Taurus](https://www.youtube.com/watch?v=be9pbCKNB28)
- [ZK9: Fuzzy Knowledge Fuzzing SNARK circuit primitives – Innokentii Sennovskii (Aztec Network)](https://www.youtube.com/watch?v=ItVUCP1El2E)
- [ZK10: ZK Vulnerabilities and Attacks - Stefanos Chaliasos](https://www.youtube.com/watch?v=CNxNe9-UySs)
- [ZK11: Insights from and on Taxonomy of ZKP Vulnerabilities - Gyumin Roh](https://www.youtube.com/watch?v=Gfa4BIMMXhk)
- [ETH Seoul 2023: Opinionated Survey of ZKP Security by Gyumin Roh, KALOS/HAECHI LABS](https://www.youtube.com/watch?v=L8PqEaX74VU)
- [ZKProof 6: Exploiting a Vulnerable Implementation of the Fiat-Shamir Transform in a KZG-based SNARK ](https://www.youtube.com/live/CH3Kvssyyds?si=uiR3-UdYN8wFgYJh)
- [ZKProof 6: Why Verifying the Verifier Opens Up Longer-Term ZK Innovation - Ben Livshits (Matter Labs)](https://www.youtube.com/live/JUls9DWQuic?si=82_0U-ObhW5PCJ7j)
- [ZKProof 6: Practical Formal Verification for Arithmetic Circuits - Marcin Kostrzewa (Reilabs)](https://www.youtube.com/live/pidYRNKplZE?si=qAgi_XQQS4cQPWif)
- [ZKProof 6: SoK: Understanding Security Vulnerabilities in SNARKs - Stefanos Chaliasos (Imperial College London)](https://www.youtube.com/watch?v=6-aeTlREYZo)
- [ETHCC\[7\]: Analysis and Auditing of ZKP Vulnerabilities](https://ethcc.io/archive/Analysis-and-Auditing-of-ZKP-Vulnerabilities)
## Talks


## CTFs and Puzzles

- [ZKHACK's puzzles](https://zkhack.dev/puzzles/)
- [RareSkills' puzzles](https://github.com/RareSkills/zero-knowledge-puzzles)
- [Ingonyama's CTF](https://github.com/ingonyama-zk/zkctf-2023-writeups)
- [StarknetCC-CTF](https://github.com/pscott/StarknetCC-CTF)
- [CRYPTOHACK](https://cryptohack.org/challenges/zkp/)

## Misc

- [zk-bug-tracker](https://github.com/0xPARC/zk-bug-tracker)
- [ZK-EVM Audit education sessions](https://www.notion.so/scrollzkp/zkEVM-Audit-Education-Session-11-15-11-22-86d60daceadb438f85908817f7082611)
- [ZK Podcast](https://zeroknowledge.fm/episodes/)
- [ZK Bugs Dataset with reproducible vulns](https://github.com/zksecurity/zkbugs/)

## Advisories

- [Plonky3 -- Missing final polynomial degree check in FRI verifier](https://github.com/Plonky3/Plonky3/security/advisories/GHSA-f69f-5fx9-w9r9)

## Papers

- [SoK: What don't we know? Understanding Security Vulnerabilities in SNARKs](https://arxiv.org/pdf/2402.15293)
- [Zero-Knowledge Proof Vulnerability Analysis and Security Auditing](https://eprint.iacr.org/2024/514.pdf)
- [The Ouroboros of ZK: Why Verifying the Verifier Unlocks Longer-Term ZK Innovation](https://eprint.iacr.org/2024/768.pdf)
- [CLAP: a Semantic-Preserving Optimizing eDSL for Plonkish Proof Systems](https://arxiv.org/pdf/2405.12115)
- [An SMT-LIB Theory of Finite Fields](https://ceur-ws.org/Vol-3725/paper3.pdf)
- [Weak Fiat-Shamir Attacks on Modern Proof Systems](https://eprint.iacr.org/2023/691.pdf)
- [Practical Security Analysis of Zero-Knowledge Proof Circuits](https://www.cs.utexas.edu/~isil/zkap.pdf)
- [Automated Detection of Under-Constrained Circuits in Zero-Knowledge Proofs](https://dl.acm.org/doi/pdf/10.1145/3591282)
- [Certifying Zero-Knowledge Circuits with Refinement Types](https://eprint.iacr.org/2023/547.pdf)
- [Bounded Verification for Finite-Field-Blasting (In a Compiler for Zero Knowledge Proofs)](https://link.springer.com/content/pdf/10.1007/978-3-031-37709-9_8.pdf)
- [Automated Analysis of Halo2 Circuits](https://eprint.iacr.org/2023/1051.pdf)
- [Formal Verification of Zero-Knowledge Circuits](https://arxiv.org/pdf/2311.08858)
- [SMT Solving over Finite Field Arithmetic](https://arxiv.org/pdf/2305.00028)
- [Compositional Formal Verification of Zero-Knowledge Circuits](https://eprint.iacr.org/2023/1278.pdf)
- [Satisfiability Modulo Finite Fields](https://link.springer.com/content/pdf/10.1007/978-3-031-37703-7_8.pdf)
- [Leo: A Programming Language for Formally Verified, Zero-Knowledge Applications](https://docs.zkproof.org/pages/standards/accepted-workshop4/proposal-leo.pdf)
- [SNARKProbe: An Automated Security Analysis Framework for zkSNARK Implementations](https://link.springer.com/chapter/10.1007/978-3-031-54773-7_14)
- [Scalable Verification of Zero-Knowledge Protocols](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a133/1Ub23QzVaWA)
- [The Last Challenge Attack: Exploiting a Vulnerable Implementation of the Fiat-Shamir Transform in a KZG-based SNARK](https://eprint.iacr.org/2024/398)
- [fAmulet: Finding Finalization Failure Bugs in Polygon zkRollup](https://arxiv.org/pdf/2410.12210)
- [Fuzzing Processing Pipelines for Zero-Knowledge Circuits](https://arxiv.org/pdf/2411.02077)
- [How to Prove False Statements: Practical Attacks on Fiat-Shamir](https://eprint.iacr.org/2025/118)
- [MTZK: Testing and Exploring Bugs in Zero-Knowledge (ZK) Compilers](https://www.ndss-symposium.org/wp-content/uploads/2025-530-paper.pdf)
- [zkFuzz: Foundation and Framework for Effective Fuzzing of Zero-Knowledge Circuits](https://arxiv.org/pdf/2504.11961)
- [ConsCS: Effective and Efficient Verification of Circom Circuits](https://www.computer.org/csdl/proceedings-article/icse/2025/056900a737/251mHhOXS9i)
- [AC4: Algebraic Computation Checker for Circuit Constraints](https://arxiv.org/pdf/2403.15676)
- [Automated Verification of Consistency in Zero-Knowledge Proof Circuits](https://eprint.iacr.org/2025/916.pdf)
- [Towards Fuzzing Zero-Knowledge Proof Circuits (Short Paper)](https://arxiv.org/pdf/2504.14881)

## Tools

If the link points to a paper, then it means that the tool is not open-sourced.

| Tool                                                                                       | Layer           | DSL / Target | Analysis                      |
|--------------------------------------------------------------------------------------------|-----------------|--------|-------------------------------------|
| [Circomspect](https://github.com/trailofbits/circomspect)                                  | Circuit         | Circom | Static Analysis                     |
| [ZKAP](https://github.com/whbjzzwjxq/ZKAP)                                                 | Circuit         | Circom | Static Analysis                     |
| [halo2-analyzer](https://github.com/quantstamp/halo2-analyzer)                             | Circuit         | halo2  | Static Analysis / Symbolic Analysis |
| [Coda](https://github.com/Veridise/coda)                                                   | Circuit         | Circom | Formal Verification (Coq)           |
| [Picus](https://github.com/Veridise/Picus)                                                 | Circuit         | Circom, GNARK (R1CS) | Formal Verification   |
| [Ecne](https://github.com/franklynwang/EcneProject)                                        | Circuit         | Circom (R1CS) | Formal Verification          |
| [SNARKProbe](https://github.com/BARC-Purdue/SNARKProbe)                                    | Circuit/Backend | R1CS   | Fuzzing                             |
| [circom_civer](https://github.com/costa-group/circom_civer)                                | Circuit         | Circom | Formal Verification                 |
| [gnark-lean-extractor](https://github.com/reilabs/gnark-lean-extractor)                    | Circuit         | Gnark  | Formal Verification (Lean)          |
| [fAmulet](https://arxiv.org/pdf/2410.12210)                                                | Circuit/zk(E)VM|  Polygon zkEVM | Fuzzing                      |
| [zkwasm-fv](https://github.com/CertiKProject/zkwasm-fv)                                    | Circuit/zk(E)VM | zkWasm | Formal Verification (Coq)           |
| [MTZK](https://sites.google.com/view/mtzk)                                                 | Frontend        | ZoKrates, Noir, Cairo, Leo | Fuzzing (Metamorphing Testing)|
| [Circuzz](https://arxiv.org/pdf/2411.02077)                                                | Frontend        | Circom, Corset, GNARK, Noir| Fuzzing (Metamorphing Testing)|
| [aztec_fuzzing](https://github.com/FuzzingLabs/aztec_fuzzing)                              | Frontend        | Noir    | Fuzzing (Generation-based)         |
| [sierra_analyzer](https://github.com/FuzzingLabs/sierra-analyzer)                          | Circuit         | Cairo   | Static Analysis / Symbolic Execution |
| [Pilspector](https://github.com/Schaeff/pilspector/)                                       | Circuit         | PIL     | Symbolic Analysis                  |
| [zkFuzz](https://github.com/Koukyosyumei/zkFuzz)                                           | Circuit         | Circom  | Fuzzing                            |
| [CIVER](https://github.com/costa-group/circom_civer)                                       | Circuit         | Circom  | Formal Verification (SMT)          |
| [garden](https://github.com/formal-land/garden)                                            | Circuit         | Circom  | Formal Verification (Coq)          |
