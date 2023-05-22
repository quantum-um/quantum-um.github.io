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
26 May 2023

**Speaker:**
Tomás Carneiro

**Title:**
iQbricks: Integration of a fully-featured quantum language in the framework Qbricks

**Abstract:**
Quantum Computing has noticeably grown over the last two decades, making it a revolutionary field of
investigation in the current era of technological research.  Such a growth has been leading to an
increasing demand in research by several big enterprises such as IBM, Google and Microsoft, paving
the way for a richer ecosystem and untold benefits among the Quantum Computing community.
Verification is a crucial aspect of software development, as it ensures that a program performs as
intended and reduces the risk of introducing errors. This is especially important in the field of
Quantum Computing, where the complexity of programs is high and the behavior of quantum systems is
often counterintuitive. Verification of quantum programs can help detect errors that may lead to
incorrect results, which is of utmost importance when dealing with quantum algorithms and quantum
simulations. As a result, having a formal verification framework for quantum programs can greatly
benefit the development of reliable and accurate quantum software. Qbricks is a verification
framework for building quantum programs, and corresponds to the framework on which this project has
been integrated.  During the course of this thesis, iQbricks – an intuitive and user-friendly
language to build and formally verify quantum programs – was developed, along with a framework to
translate and generate verifiable Qbricks programs from iQbricks.  This project’s main achievements
were: (1) the design and implementation of a high-level programming language for describing quantum
circuits in an intuitive and user-friendly way and (2) the implementation of a translator, embedded
in Qbricks’ framework, that converts iQbricks programs to Qbricks ones.  The developed framework was
evaluated against two different quantum algorithms: the Quantum Fourier Transform and Grover’s
algorithm.  This project was accompanied by an internship at the Commissariat à l’énergie atomique
et aux énergies alternatives (CEA) - LSL, where this implementation was developed in direct
involvement with Qbricks’ team of investigators.

---
**Date:**
19 May 2023

**Speaker:**
Mario Silva (Université de Lorraine)
[[slides]({{ site.url }}/slides/ApresentacaoINL.pdf)]

**Title:**
[A Programming Language Characterizing Quantum Polynomial Time](https://link.springer.com/chapter/10.1007/978-3-031-30829-1_8)

**Abstract:**
We introduce a first-order quantum programming language, named FOQ, whose terminating programs are
reversible. We restrict FOQ to a strict and tractable subset, named PFOQ, of terminating programs
with bounded width, that provides a first programming language-based characterization of the quantum
complexity class FBQP. We finally present a tractable semantics-preserving algorithm compiling a
PFOQ program to a quantum circuit of size polynomial in the number of input qubits.

---
**Date:**
28 April 2023

**Speaker:**
Alexandra Alves
[[slides]({{ site.url }}/slides/nrqae.pdf)]

**Title:**
Noise Resilient Quantum Amplitude Estimation

**Abstract:**
Quantum amplitude estimation (QAE) is a key routine offering a quadratic quantum speed-up. Notable
applications include numerical integration, machine learning, estimating expectation values of
observables, and database searching. However, owing to experimental issues, present-day quantum
devices struggle to realize this potential. Algorithm design plays a pivotal role in overcoming this
issue. In this talk, I will present and discuss several QAE algorithms, with an emphasis on their
susceptibility to noise.

---

**Date:**
14 April 2023

**Speaker:**
Rodrigo Coelho
[[slides]({{ site.url }}/slides/Presentation_Quantum.pdf)]

**Title:**
The effect of Data Re-Uploading in Variational Q-Learning

**Abstract:**
A Reinforcement Learning (RL) agent learns by interacting with the surrounding environment in a
feedback loop, with only a reward signal guiding its actions [1]. However, state-of-the-art RL
algorithms are extremely data-hungry and often not efficiently learnable. Variational Quantum
Circuits (VQCs) allow for implementations that require minimal quantum resources, making them
suitable for near-term applications [2]. Recently, research has shown that VQCs can be used as
function approximators in RL algorithms, reducing the total number of trainable parameters of
parameterized models for some environments [3] [4]. Furthermore, by repeating simple data encoding
gates multiple times, a technique named data re-uploading, these quantum models can access
increasingly rich frequency spectra [5]. This project’s primary goal is to study the effect of data
re-uploading in VQC’s applied to Q-Learning [6], a RL algorithm.

**References:**

[1] R. S. Sutton and A. G. Barto, Reinforcement learning: An introduction. MIT press, 2018.

[2] M. Cerezo, A. Arrasmith, R. Babbush, S. C. Benjamin, S. Endo, K. Fujii, J. R. McClean, K. Mitarai,
X. Yuan, L. Cincio et al., “Variational quantum algorithms,” Nature Reviews Physics, vol. 3, no. 9,
pp. 625–644, 2021.

[3] A. Skolik, S. Jerbi, and V. Dunjko, “Quantum agents in the gym: a variational quantum algorithm
for deep q-learning,” Quantum, vol. 6, p. 720, 2022.

[4] S. Y.-C. Chen, C.-H. H. Yang, J. Qi, P.-Y. Chen, X. Ma, and H.-S. Goan, “Variational quantum
circuits for deep reinforcement learning,” IEEE Access, vol. 8, pp. 141 007–141 024, 2020.

[5] M. Schuld, R. Sweke, and J. J. Meyer, “Effect of data encoding on the expressive power of variational
quantum-machine-learning models,” Physical Review A, vol. 103, no. 3, p. 032430, 2021.

[6] C. J. Watkins and P. Dayan, “Q-learning,” Machine learning, vol. 8, pp. 279–292, 1992.

---

**Date:**
14 April 2023

**Speaker:**
Ioannis Kolotouros (University of Edinburgh)
[[slides]({{ site.url }}/slides/AQC_PQC_Talk.pdf)]

**Title:**
Adiabatic quantum computing with parameterized quantum circuits

**Abstract:**
Adiabatic quantum computing is a universal model for quantum computing. Standard error correction
methods require overhead that makes their application prohibitive for near-term devices. To mitigate
the limitations of near-term devices, a number of hybrid approaches have been pursued in which a
parameterized quantum circuit prepares and measures quantum states and a classical optimization
algorithm minimizes an objective function that encompasses the solution to the problem of
interest. In this work, we propose a different approach starting by analyzing how a small
perturbation of a Hamiltonian affects the parameters that minimize the energy within a family of
parameterized quantum states. We derive a set of equations that allow us to compute the new minimum
by solving a constrained linear system of equations obtained by measuring a series of observables on
the unperturbed system. We then propose a discrete version of adiabatic quantum computing which can
be implemented with NISQ devices while at the same time is insensitive to the initialization of the
parameters and to other limitations hindered in the optimization part of variational quantum
algorithms. We also derive a lower bound on the number of discrete steps needed to guarantee
success. We compare our proposed algorithm with the Variational Quantum Eigensolver on two classical
optimization problems, namely MaxCut and Number Partitioning, and on a quantum spin-configuration
problem, the Transverse-Field Ising Chain model, and confirm that our approach demonstrates superior
performance.

---

**Date:**
31 March 2023

**Speaker:**
Leander Reascos
[[slides]({{ site.url }}/slides/leander.pdf)]

**Title:**
Quantum simulation of spin systems on quantum computers

**Abstract:**
Quantum computing has shown great promise in simulating quantum systems [1, 2]. Therefore, this
project focuses on simulating and studying the properties of spin systems, specifically their
chirality. These systems have multiple applications in various fields, including skyrmions,
spintronics, and high-temperature superconductors [3]. The aim is to measure scalar spin chirality
non-destructively using various algorithms based on different techniques, such as the Hadamard test,
Linear combination of unitaries (LCU) [4], and quantum phase estimation. These algorithms use
indirect measurement to avoid disrupting the state and measure expectation values or eigenvalues
[5].

**References:**

[1] S. Lloyd, “Universal quantum simulators,” vol. 273,
no. 5278, pp. 1073–1078, 1996. [Online]. Available:
https://www.science.org/doi/10.1126/science.273.5278.1073

[2] A. J. Daley, I. Bloch, C. Kokail, S. Flannigan, N. Pearson, M. Troyer, and
P. Zoller, “Practical quantum advantage in quantum simulation,” vol. 607,
no. 7920, pp. 667–676, 2022, number: 7920 Publisher: Nature Publishing
Group. [Online]. Available: https://www.nature.com/articles/s41586-022-
04940-6

[3] X. G. Wen, F. Wilczek, and A. Zee, “Chiral spin states and
superconductivity,” vol. 39, no. 16, pp. 11 413–11 423, 1989. [Online].
Available: https://link.aps.org/doi/10.1103/PhysRevB.39.11413

[4] A. M. Childs and N. Wiebe, “Hamiltonian simulation using linear combina-
tions of unitary operations,” arXiv preprint arXiv:1202.5822, 2012.

[5] K. Mitarai and K. Fujii, “Methodology for replacing indirect measurements
with direct measurements,” Physical Review Research, vol. 1, no. 1, p.
013006, 2019.



---

**Date:**
24 March 2023

**Speaker:**
André Sequeira

**Title:**
Quantum Reinforcement Learning

**Abstract:**
In the context of Quantum Reinforcement Learning (QRL), provably efficient exploration [1] and a
quadratic separation in gradient estimation were recently established for QRL models with oracle
access to environment dynamics [2]. However, once oracle access is removed, even though
Parameterized Quantum Circuits (PQCs) are being used as versatile QRL models, only empirical
advantage relative to a contrived set of classical models was established thus far [3,4]. This work
introduces quantum policy gradients using PQCs and presents the quantum-enhanced natural policy
gradient algorithm. Numerical results are reported, showcasing an improved performance in a series
of classical control benchmarking environments. In addition, regret improvements for natural policy
gradients [5] are discussed using the quantum fisher information [6].

**References:**

[1] - Provably Efficient Exploration in Quantum Reinforcement Learning with Logarithmic Worst-Case Regret - H.Zhong et.al 2023

[2] - Quantum policy gradient algorithms - S.Jerbi et.al 2022

[3] - Policy gradients using variational quantum circuits - A.Sequeira et.al 2022

[4] - Parameterized quantum policies for reinforcement learning - S.Jerbi et.al

[5] - On the theory of policy gradients - optimality, approximation and distribution shift - A.Agarwal et.al 2020

[6] - Fisher information in noisy intermediate-scale quantum applications - J.Meyer 2021

---

**Date:**
10 March 2023

**Speaker:**
José Diogo Guimarães
[[slides]({{ site.url }}/slides/presentation_technique_INL_noise-assisted.pdf)]

**Title:**
Noise-assisted digital quantum simulation of open systems

**Abstract:**
Quantum systems are inherently open and subject to environmental noise, which can have both
detrimental and beneficial effects on their dynamics. In particular, noise has been observed to
enable novel functionalities in bio-molecular systems, making the simulation of their dynamics an
important target for digital and analog quantum simulation. However, current quantum devices are
typically noisy, limiting their computational capabilities. In this work, we propose a novel
approach that leverages the intrinsic noise of a quantum device to reduce the quantum computational
resources required for simulating open quantum systems. We achieve this by combining quantum noise
characterization methods with quantum error mitigation techniques, which allow us to transform and
control the intrinsic noise in a quantum circuit. Specifically, we selectively enhance or reduce
decoherence rates in the quantum circuit to achieve the desired simulation of open system
dynamics. We describe our methods in detail and report on the results of noise characterization and
quantum error mitigation on real and emulated IBM Quantum computers. We also provide estimates of
the experimental resource requirements for our techniques. We believe that this approach can pave
the way for new simulation techniques in Noisy Intermediate-Scale Quantum (NISQ) devices, where
their intrinsic noise can be harnessed to assist quantum computations.


---

**Date:**
3 March 2023

**Speakers:**
Inês Dias and Vitor Fernandes
[[slides]({{ site.url }}/slides/tqc.pdf)]

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
[[slides]({{ site.url }}/slides/pqc-pt1.pdf)]

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