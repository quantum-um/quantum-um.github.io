---
title: Seminars
#feature_text: |
#  A demo of Markdown and HTML includes
feature_image: "https://picsum.photos/2560/600?image=873"
#excerpt: "A demo of Markdown and HTML includes"
aside: false
---

### Information
Valid until the end of the 2022/23 academic year

**Hour**:
14h00 (14pm WET)

**Room**:
0.05 (Department of Informatics)

---

**Date:**
3 March 2023

**Speakers:**
Inês Dias and Vitor Fernandes
[slides]

**Title:**
Towards quantum concurrency (Part 1)

**Abstract:**
In the classical setting, concurrency speeds up the execution of programs, which decreases their
execution time [1].  Currently, quantum computers must handle fault-tolerant hardware [2]. This
faulty-hardware is prone to noise, which affects the superposition time of qubits (the superposition
time of qubits is in the order of a few milliseconds [3]).

We then aim to bring the benefits of concurrency to the quantum setting. In order to study to what
extent concurrency can help to mitigate noise in quantum programming, our goal is to define and
implement the semantics of a concurrent quantum language, which will in turn allow to simulate
quantum concurrent programs.  To do that, we based our work on a concurrent imperative language
developed by Brookes [4].  In fact, our concurrent quantum language is an extension of said
language, by adding basic quantum features to it.

In this talk, we focus on the language developed by Brookes.  We present its syntax and operational
semantics. Additionally, we discuss the use of Parsec [5], a package of Haskell, in order to build a
parser for this language, and also the implementation of its operational semantics in
Haskell. Furthermore, we briefly discuss the syntax and the operational semantics of the quantum
concurrent language.


**References:**

[1] Cantrill, Bryan, and Jeff Bonwick. "Real-world concurrency." Communications of the ACM 51.11 (2008): 34-39.

[2] Nielsen, Michael A., and Isaac Chuang. "Quantum computation and quantum information." (2002): 558-559.

[3] Zhang, Yu, et al. "Optimizing quantum programs against decoherence: delaying qubits into quantum superposition." 2019 International Symposium on Theoretical Aspects of Software Engineering (TASE). IEEE, 2019.

[4] Stephen Brookes. Full abstraction for a shared-variable parallel language. Information
and Computation, 127(2):145–163, 1996. URL: https://www.sciencedirect.com/science/
article/pii/S0890540196900565, doi:https://doi.org/10.1006/inco.1996.0056.

[5] Daan Leijen, Paolo Martini, and Antoine Latter. parsec: Monadic parser combinators, 2023. [[link](https://hackage.haskell.org/package/parsec)]


---

**Date:**
24 February 2023

**Speaker:**
Henrique Faria
[slides]

**Title:**
Multi-Party Computations: Providing a Post-Quantum Solution (Part 1)

**Abstract:**
In recent years, the development of quantum computers led the world in a search for post-quantum
resistant algorithms. During the last round of the National Institute of Standards and Technology's
Post-Quantum Cryptography contest (NIST-PQC)[1] it was concluded that the proposed quantum-resistant
digital signatures lacked variability, thus requiring further candidates. During the NIST-PQC's
third round, NIST withdrew PICNIC, a Multi-Party Computation (MPC) candidate, from the schemes to be
standardized due to concerns with its security. However, NIST stated that upon further research and
development, MPC schemes could provide promising candidates for standardization. The fact is that
during the NIST-PQC's contest duration, several MPC schemes that improved upon PICNIC's performance
and security appeared [2,3]. A big problem with their implementations is that these often detach
themselves from the original scheme leading to doubts about their security. To solve this issue, the
toolchain Jasmin-EasyCrypt[4,5] emerged allowing one to link optimized implementations to the
original scheme's security claims. In this talk, we will detail what an MPC scheme is and how the
Jasmin-EasyCrypt toolchain can provide high-speed high-assurance software implementations with
proofs over these concrete implementations instead of proofs over a theoretical scheme.

**References:**

[1] Status Report on the Third Round of the NIST Post-Quantum Cryptography Standardization Process. Gorjan Alagic, Daniel Apon, David Cooper, Quynh Dang, Thinh Dang, John Kelsey, Jacob Lichtinger, Yi-Kai Liu, Carl Miller, Dustin Moody, Rene Peralta, Ray Perlner, Angela Robinson, Daniel Smith-Tone.

[2] Banquet: Short and Fast Signatures from AES. Carsten Baum, Cyprien Delpech de Saint Guilhem, Daniel Kales, Emmanuela Orsini, Peter Scholl and Greg Zaverucha. In: Cryptology ePrint Archive, Paper 2021/068.

[3] LegRoast: Efficient post-quantum signatures from the Legendre PRF. Ward Beullens, Cyprien Delpech de Saint Guilhem. In: Cryptology ePrint Archive, Paper 2020/128.

[4] Jasmin: High-Assurance and High-Speed Cryptography. José Bacelar Almeida, Manuel Barbosa, Gilles Barthe, Arthur Blot, Benjamin Grégoire, Vincent Laporte, Tiago Oliveira, Hugo Pacheco, Benedikt Schmidt, Pierre-Yves Strub. In: CCS’17.

[5] [[https://github.com/EasyCrypt/easycrypt](https://github.com/EasyCrypt/easycrypt)].

---

**Date:** 17 February 2023

**Speaker:**
Andrea D'Urbano
[[slides]({{ site.url }}/slides/Resource theory of LOSR - a primer.pdf)]

**Title:**
Resource theory of local operations and shared randomness - a primer

**Abstract:**
In [1], Schmidt et al. presented a method to analyse and formalise scenarios involving multiple
parties sharing a common cause but no cause-effect relationship. This scenario could prove to be
useful to quantify the advantage, if any, in using quantum resources in distributed quantum
information processing, and in particular secure multi-party computation. The resource-theory
discussion in [1] and the general framework presented in [2] and [3], allow to describe the
nonclassicality in such scenarios, taking into account the causal structure of the experiment. We
will describe this approach and try to apply the methodologies presented in [3] to the easiest and
the most fundamental example of quantum multi-party computation: quantum secret sharing [4].

**References:**

[1] Schmid, David, Denis Rosset, and Francesco Buscemi. "The type-independent resource theory of local operations and shared randomness." Quantum 4 (2020): 262.

[2] Wolfe, Elie, et al. "Quantifying Bell: The resource theory of nonclassicality of common-cause boxes." Quantum 4 (2020): 280.

[3] Zjawin, Beata, et al. "Quantifying EPR: the resource theory of nonclassicality of common-cause assemblages." arXiv preprint arXiv:2111.10244 (2021).

[4] Hillery, Mark, Vladimír Bužek, and André Berthiaume. "Quantum secret sharing." Physical Review A 59.3 (1999): 1829.