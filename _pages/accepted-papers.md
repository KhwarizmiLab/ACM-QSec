---
permalink: /accepted-papers/
title: "Accepted Papers"
author_profile: false
redirect_from: 
  - /papers/
  - /papers.html
---

<script>
function toggleAbstract(element) {
    const abstract = element.nextElementSibling.nextElementSibling;
    const indicator = element.querySelector('.expand-indicator');
    
    if (abstract.classList.contains('show')) {
        abstract.classList.remove('show');
        indicator.textContent = '▸';
    } else {
        abstract.classList.add('show');
        indicator.textContent = '▾';
    }
}
</script>

The following papers have been accepted for presentation at the **ACM Workshop on Quantum Security and Privacy (QSec)**. Click on paper titles to view abstracts.

---

<div class="paper-container">
    <a href="#" class="paper-title" onclick="toggleAbstract(this); return false;">
        Securing Quantum Computer Reset with One-Time Pads
        <span class="expand-indicator">▸</span>
    </a>
    <div class="paper-authors">
        Chuanqi Xu (<em>Yale University</em>); Jamie Sikora (<em>Virginia Polytechnic Institute and State University</em>); Jakub Szefer (<em>Northwestern University</em>)
    </div>
    <div class="paper-abstract">
        The rapid expansion of cloud-based access to quantum computers has significantly democratized their usage, enabling a more diverse range of users to explore and utilize quantum computing technologies. However, this increased accessibility also introduces security and privacy concerns. Cloud-based access and sharing of quantum computers require secure means to isolate different users, such as through the use of reset operations. However, current reset operations, including direct thermalization and fast reset instructions, are vulnerable to information leakage due to imperfections in quantum computer operations. To counteract these vulnerabilities, our work proposes multiple implementations of the one-time pad (OTP) defense mechanism. These implementations, specifically random execution, dynamic circuit, and control gate, involve applying Pauli or control gates randomly before executing standard reset operations. We analyze and compare these implementations in detail, demonstrating their effectiveness in mitigating state leakage. This work offers innovative approaches to enhancing the security of reset operations and the safety of cloud-based quantum computers.
    </div>
</div>

<div class="paper-container">
    <a href="#" class="paper-title" onclick="toggleAbstract(this); return false;">
        Pulse-to-Circuit Characterization of Stealthy Crosstalk Attack on Multi-Tenant Superconducting Quantum Hardware
        <span class="expand-indicator">▸</span>
    </a>
    <div class="paper-authors">
        Syed Emad Uddin Shubha (<em>Louisiana State University</em>); Tasnuva Farheen (<em>Louisiana State University</em>)
    </div>
    <div class="paper-abstract">
        Hardware crosstalk in multi-tenant superconducting quantum computers constitutes a significant security threat, enabling adversaries to inject targeted errors across tenant boundaries. We present the first end-to-end framework for mapping physical pulse-level attacks to interpretable logical error channels, integrating density-matrix simulation, quantum process tomography (QPT), and a novel isometry-based circuit extraction method. Our pipeline reconstructs the complete induced error channel and fits an effective logical circuit model, revealing a fundamentally asymmetric attack mechanism: one adversarial qubit acts as a driver to set the induced logical rotation, while a second, the catalyst, refines the attack's coherence. Demonstrated on a linear three-qubit system, our approach shows that such attacks can significantly disrupt diverse quantum protocols, sometimes reducing accuracy to random guessing, while remaining effective and stealthy even under realistic hardware parameter variations. We further propose a protocol-level detection strategy based on observable attack signatures, showing that stealthy attacks can be exposed through targeted monitoring and providing a foundation for future defense-in-depth in quantum cloud platforms.
    </div>
</div>

<div class="paper-container">
    <a href="#" class="paper-title" onclick="toggleAbstract(this); return false;">
        Assessing the Viability of Quantum-Resistant IKEv2 over Constrained and Internet-Scale Networks
        <span class="expand-indicator">▸</span>
    </a>
    <div class="paper-authors">
        Geoff Twardokus (<em>Rochester Institute of Technology</em>); William Joslin (<em>Rochester Institute of Technology</em>); Hanif Rahbari (<em>Rochester Institute of Technology</em>); William Layton (<em>National Security Agency</em>)
    </div>
    <div class="paper-abstract">
        Within 1–2 decades, quantum computers may become powerful enough to break current public-key cryptography, driving authorities such as the IETF and NIST to push for adopting quantum-resistant cryptography (QRC) in ecosystems like Internet Protocol Security (IPsec). However, IPsec struggles to adopt QRC, primarily due to the limited ability of Internet Key Exchange Protocol Version 2 (IKEv2), which sets up IPsec sessions, to tolerate the large public keys and digital signatures of QRC. Many IETF RFCs have been proposed to integrate QRC into IKEv2, but their performance and interplay remain largely untested in practice. In this paper, we measure the performance of these RFCs over constrained links by developing a flexible, reproducible measurement testbed for IPsec with quantum-resistant IKEv2 proposals. By deploying our testbed in lossy wireless links and on the internationally distributed FABRIC testbed for Internet scenarios, we reveal that performance bottlenecks arise with quantum-resistant IKEv2 in connections that experience high round-trip times, non-trivial packet loss, or other constraints. Our results, including the revelation of a 400–1000-fold (or greater) increase in data overhead over high-loss wireless links, expose the shortcomings and opportunities of today's RFCs and call for further attention and development in this vital area of post-quantum network security.
    </div>
</div>

<div class="paper-container">
    <a href="#" class="paper-title" onclick="toggleAbstract(this); return false;">
        I Know What You Are Reading: Evaluating Readout Crosstalk in Cloud-based Quantum Computers 🏆 <span class="best-paper-award">Best Paper Award</span>
        <span class="expand-indicator">▸</span>
    </a>
    <div class="paper-authors">
        Yizhuo Tan (<em>Yale University</em>); Jakub Szefer (<em>Northwestern University</em>)
    </div>
    <div class="paper-abstract">
        Frequency-multiplexing is a technique used for achieving resource-efficient readout in superconducting-based quantum computers. By enabling multiple resonators to share a common feed line, it significantly reduces the number of required cables and passive components. However, this gain in scalability introduces increased readout crosstalk. The readout crosstalk is not only a reliability issue, but also a possible security issue. Prior work has explored readout crosstalk in experimental systems not publicly available. This work builds on the prior findings and evaluates readout crosstalk in commercial, cloud-based quantum computers. In the process, this work also reconstructs the likely architecture for the shared readout feed lines and shows which qubit readout resonators likely share a feed line. This work finally shows that crosstalk-induced errors occurring during readout can be exploited by adversaries to infer the state of co-located victim qubits, leading to unintended information leakage.
    </div>
</div>

<div class="paper-container">
    <a href="#" class="paper-title" onclick="toggleAbstract(this); return false;">
        A Lightweight Unified Keccak Module for Efficient Hashing in ML-KEM and ML-DSA
        <span class="expand-indicator">▸</span>
    </a>
    <div class="paper-authors">
        Suraj Mandal (<em>Indian Institute of Technology Kanpur</em>); Debapriya Basu Roy (<em>Indian Institute of Technology Kanpur</em>)
    </div>
    <div class="paper-abstract">
        One of the major modules used in post-quantum cryptographic (PQC) algorithms is Keccak or SHA-3. For generating the coefficients of the public vector, secret vector, and error vector, different sampler functions receive the output of the Keccak function directly. For PQC hardware implementations, Keccak plays a critical role in terms of being a major contributor to both area and timing overhead. This motivates us to design a unified Keccak module that can be shared between both CRYSTALS-Kyber and CRYSTALS-Dilithium. In this work, we have designed a unified Keccak module that efficiently generates the hash computations of CRYSTALS-Kyber (ML-KEM) and CRYSTALS-Dilithium (ML-DSA), which are current standard for post-quantum secure key encapsulation and digital signature algorithm respectively. Compared to the state-of-the-art unified Keccak implementations, we have achieved a 43% improvement in area overhead, resulting in a better area-time product (ATP) than the existing works.
    </div>
</div>

<div class="paper-container">
    <a href="#" class="paper-title" onclick="toggleAbstract(this); return false;">
        Authenticating Quantum Circuits Through Localized Noise Fingerprints
        <span class="expand-indicator">▸</span>
    </a>
    <div class="paper-authors">
        Gabrielle MacNeil (<em>University of New Hampshire</em>); Sandeep Sunkavilli (<em>University of New Hampshire</em>); Qiaoyan Yu (<em>University of New Hampshire</em>)
    </div>
    <div class="paper-abstract">
        Quantum computing promises to outperform classical systems, yet today's Noisy Intermediate-Scale Quantum (NISQ) devices remain limited by gate errors, decoherence, and hardware variability. These challenges are compounded by the lack of built-in mechanisms to verify that quantum circuits execute as intended, especially in an untrusted quantum computer. In this work, we define quantum noise as a diagnostic signal rather than a nuisance. We propose a novel authentication method that utilizes Total Variation Distance (TVD) calculated using quantum noise. TVD compares a quantum circuit output distribution with a trusted quantum noise fingerprint. TVD offers a localized, interpretable metric for detecting structural tampering, such as gate reordering or injection. To support fine-grained verification, we introduce the concept of diagnostic ancilla qubits, non-invasive observers embedded in the circuit that store local noise signatures for post-execution analysis. While still a forward-looking concept, this proposal enables circuit-level verification. Our approach combines gate-level noise modeling with lightweight integrity checks, offering a promising path toward secure and tamper-evident quantum computation.
    </div>
</div>