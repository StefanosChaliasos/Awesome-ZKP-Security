# Awesome-ZKP-Security ![awesome](https://awesome.re/badge.svg)

A curated list of awesome ZKP Security resources, papers, tutorials, and tools. Inspired by [Awesome-Smart-Contract-Security](https://github.com/saeidshirazi/Awesome-Smart-Contract-Security).

If you want to add a new resource, please submit a pull request to improve this file. Thank you!

# Table of Contents

- [ZKPs](#zkps)
- [Blogs](#blogs)
- [Podcasts](#podcasts)
- [Disclosures](#disclosures)
- [Audits](#audits)
- [Talks](#talks)
- [CTFs and Puzzles](#ctfs-and-puzzles)
- [Papers](#papers)
- [Tools](#tools)

# ZKPs

Curated Lists for ZKPs

- [Xor0v0/awesome-zero-knowledge-proofs-security](https://github.com/Xor0v0/awesome-zero-knowledge-proofs-security)
- [sCrypt-Inc: Awesome zero knowledge proofs](https://github.com/sCrypt-Inc/awesome-zero-knowledge-proofs)
- [matter-labs: Awesome zero knowledge proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
- [ventali/awesome-zk](https://github.com/ventali/awesome-zk)
- [zkp.science](https://zkp.science)
- [Zero-Knowledge Proofs Starter Pack](https://ethresear.ch/t/zero-knowledge-proofs-starter-pack/4519)
- [gakonst/awesome-starknet](https://github.com/gakonst/awesome-starknet)
- [Zero Knowledge Canon by a16z](https://a16zcrypto.com/zero-knowledge-canon/)
- [ZKP Knowledge Base by Delendum Research](https://kb.delendum.xyz/)

Courses

- [Zero Knowledge Proofs MOOC](https://zk-learning.org/)
- [MIT's Modern Zero Knowledge Cryptography](https://zkiap.com/)
- [0xParc's Circom and Halo2 learning groups](https://learn.0xparc.org/)

Books

- [The MoonMath Manual to zk-SNARKs](https://leastauthority.com/community-matters/moonmath-manual): minimal experience in cryptography required
- [A Graduate Course in Applied Cryptography](http://toc.cryptobook.us/book.pdf) (Dan Boneh and Victor Shoup, 2023)
- [Proofs, Arguments, and Zero-Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf) (Justin Thaler, 2022)
- [Building Cryptography Proofs from Hash Functions](https://github.com/hash-based-snargs-book/hash-based-snargs-book/blob/main/snargs-book.pdf) (Alessandro Chiesa and Eylon Yogev, 2024)

# Blogs

- [zkSecurity's Blog](https://www.zksecurity.xyz/blog/)
- [0xParc's Blog](https://0xparc.org/blog)
- [Trail of Bits' Blog](https://blog.trailofbits.com/)
- [OZ's Security Insights Blog](https://blog.openzeppelin.com/tag/security-insights)
- [Veridise's Blog](https://veridise.medium.com/)
- [Zellic's Blog](https://www.zellic.io/blog/)
- [David Wong's Blog](https://www.cryptologie.net/)

Specific blog posts / Vulnerability Disclosures

- [The State of Security Tools for ZKPs](https://www.zksecurity.xyz/blog/posts/zksecurity-tools/)
- [Detecting boomerang values in zero-knowledge circuits using tag analysis](https://www.zksecurity.xyz/blog/posts/boomerang/)
- [The zero-knowledge attack of the year might just have happened, or how Nova got broken](https://www.zksecurity.xyz/blog/posts/nova-attack/)
- [Do in secret. Assert in public. Don't under-constrain your prover's witness computation in ZK programs](https://www.zksecurity.xyz/blog/posts/underconstrain-bugs/)
- [Ecne: Automated Verification of ZK Circuits](https://0xparc.org/blog/ecne)
- [What Is a ZK Audit?](https://www.zellic.io/blog/what-is-a-zk-audit/)
- [ZK-SNARKS & The Last Challenge Attack: Mind Your Fiat-Shamir!](https://blog.openzeppelin.com/the-last-challenge-attack)
- [The Frozen Heart vulnerability in PlonK](https://blog.trailofbits.com/2022/04/18/the-frozen-heart-vulnerability-in-plonk/)
- [The Frozen Heart vulnerability in Bulletproofs](https://blog.trailofbits.com/2022/04/15/the-frozen-heart-vulnerability-in-bulletproofs/)
- [Coordinated disclosure of vulnerabilities affecting Girault, Bulletproofs, and PlonK](https://blog.trailofbits.com/2022/04/13/part-1-coordinated-disclosure-of-vulnerabilities-affecting-girault-bulletproofs-and-plonk/)
- [It pays to be Circomspect](https://blog.trailofbits.com/2022/09/15/it-pays-to-be-circomspect/)
- [Disarming Fiat-Shamir footguns](https://blog.trailofbits.com/2024/06/24/disarming-fiat-shamir-footguns/)
- [Zcash Counterfeiting Vulnerability Successfully Remediated](https://electriccoin.co/blog/zcash-counterfeiting-vulnerability-successfully-remediated/)
- [Security Vulnerabilities in ZK](https://zkv.xyz/security-vulnerabilities-in-zk/)
- [Circom-Pairing: A Million-Dollar ZK Bug Caught Early](https://medium.com/veridise/circom-pairing-a-million-dollar-zk-bug-caught-early-c5624b278f25)
- [Developing securely on Aleo blockchain: Common Vulnerability Patterns](https://medium.com/veridise/developing-securely-on-aleo-blockchain-common-vulnerability-patterns-a99070e3ebe2)
- [Satisfiability Modulo Finite Fields: Unlocking SMT for ZK Verification](https://medium.com/veridise/satisfiability-modulo-finite-fields-unlocking-smt-for-zk-verification-3709b0b2b48e)
- [ZK Vulnerabilities: Sharp rocks hidden in deep water](https://medium.com/veridise/zk-vulnerabilities-sharp-rocks-hidden-in-deep-water-7cad8d4c2dfa)
- [Medjai: Protecting Cairo code from Bugs](https://medium.com/veridise/medjai-protecting-cairo-code-from-bugs-d82ec852cd45)
- [Patch Thursday — Uncovering a ZK-EVM Soundness Bug in zkSync Era](https://medium.com/chainlight/uncovering-a-zk-evm-soundness-bug-in-zksync-era-f3bc1b2a66d8)
- [Common Vulnerabilities in ZK Proof](https://blog.oxor.io/common-vulnerabilities-in-zk-proof-5ba7620dfa2f)
- [ChainLight saved zkSync Era from $1.9B exploit](https://blockworks.co/news/exploit-bug-zksync-matter-labs)
- [ZKPs for Engineers: A look at the Dark Forest ZKPs](https://blog.zkga.me/df-init-circuit)
- [Facebook: Critical bugs in Facebook/Polygon Winterfell library](https://github.com/google/security-research/security/advisories/GHSA-8fhq-pf83-pv93)
- [Vulnerabilities patched in Aztec 2.0](https://medium.com/aztec-protocol/vulnerabilities-found-in-aztec-2-0-9b80c8bf416c)
- [00 PLONK Bug](https://github.com/cryptosubtlety/00/blob/main/00.pdf)
- [Aztec: Disclosure of recent vulnerabilities](https://hackmd.io/@aztec-network/disclosure-of-recent-vulnerabilities)
- [Tornado.cash got hacked. By us.](https://tornado-cash.medium.com/tornado-cash-got-hacked-by-us-b1e012a3c9a8)
- [Filecoin —one PoREP vulnerability found by Trapdoor Tech](https://trapdoortech.medium.com/filecoin-one-porep-vulnerability-found-by-trapdoor-tech-7fc7beb4557b)
- [Formal Verification of ZK Constraint Systems](https://delendum.xyz/writings/2022-09-04-formal-verification-zk-constraint-systems.html)
- [Groth16 Malleability](https://geometry.xyz/notebook/groth16-malleability)

# Audits

- [Collection of security reviews of ZK Protocols](https://github.com/nullity00/zk-security-reviews)
- [zksecurity audit reports](https://www.zksecurity.xyz/reports/)
- [openzeppelin audit reports](https://blog.openzeppelin.com/tag/security-audits)
- [veridise audit reports](https://veridise.com/past-security-audits/)

# Talks

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

# CTFs and Puzzles

- [ZKHACK's puzzles](https://zkhack.dev/puzzles/)
- [RareSkills' puzzles](https://github.com/RareSkills/zero-knowledge-puzzles)
- [Ingonyama's CTF](https://github.com/ingonyama-zk/zkctf-2023-writeups)
- [StarknetCC-CTF](https://github.com/pscott/StarknetCC-CTF)
- [CRYPTOHACK](https://cryptohack.org/challenges/zkp/)

# Misc

- [zk-bug-tracker](https://github.com/0xPARC/zk-bug-tracker)
- [ZK-EVM Audit education sessions](https://www.notion.so/scrollzkp/zkEVM-Audit-Education-Session-11-15-11-22-86d60daceadb438f85908817f7082611)
- [ZK Podcast](https://zeroknowledge.fm/episodes/)

# Papers

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

# Tools

| Tool                                                                                       | Layer           | DSL    | Analysis                            |
|--------------------------------------------------------------------------------------------|-----------------|--------|-------------------------------------|
| [Circomspect](https://github.com/trailofbits/circomspect)                                  | Circuit         | Circom | Static Analysis                     |
| [ZKAP](https://github.com/whbjzzwjxq/ZKAP)                                                 | Circuit         | Circom | Static Analysis                     |
| [halo2-analyzer](https://github.com/quantstamp/halo2-analyzer)                             | Circuit         | halo2  | Static Analysis / Symbolic Analysis |
| [Coda](https://github.com/Veridise/coda)                                                   | Circuit         | Circom | Formal Verification (Coq)           |
| [Picus](https://github.com/Veridise/Picus)                                                 | Circuit         | Circom | Formal Verification                 |
| [SNARKProver](https://github.com/BARC-Purdue/SNARKProbe)                                   | Circuit/Backend | R1CS   | Fuzzing                             |
| [circom_civer](https://github.com/costa-group/circom_civer)                                | Circuit         | Circom | Formal Verification                 |
| [gnark-lean-extractor](https://github.com/reilabs/gnark-lean-extractor)                    | Circuit         | Gnark  | Formal Verification (Lean)          |
