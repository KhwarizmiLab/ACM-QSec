---
permalink: /schedule/
title: "Schedule"
author_profile: false
redirect_from: 
  - /program/
  - /schedule.html
  - /program.html
---

<div class="schedule-container">
    <div class="schedule-header">
        <div class="schedule-date">October 17, 2025</div>
        <h1 class="schedule-title">QSec Workshop Schedule</h1>
        <div class="schedule-location">Room 201C at the Taipei International Convention Center (TICC)</div>
    </div>

    <div class="time-block invited-talk">
        <div class="time-header">
            <div class="time-slot">9:00 AM - 10:00 AM</div>
            <div class="session-title">Keynote</div>
        </div>
        <div class="session-content">
            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('keynote-abstract'); return false;">
                    "From Shor to Standards --- The Evolution of PQC and the Road Ahead for Quantum-Era Threats"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Ruben Niederhagen</span> (Academia Sinica &amp; University of Southern Denmark)
                    <button class="bio-toggle" onclick="toggleBio('keynote-bio'); return false;">View Bio</button>
                </div>
                <div id="keynote-abstract" class="paper-abstract" style="display:none;">
                    This talk traces the journey from the early academic roots of post-quantum cryptographic schemes, through the crucible of the NIST competition, to the 2024 standards that now guide worldwide PQC migration. It examines the dual challenge of defending against both quantum and classical adversaries, highlights lessons learned from the design of long-horizon cryptographic primitives, and explores how today’s standardization choices will shape decades of secure communication. Looking ahead, the talk outlines the key research, engineering, and policy challenges that must be addressed to ensure a safe, efficient, and enduring transition to quantum-resistant security.
                </div>
                <div id="keynote-bio" class="speaker-bio" style="display:none;">
                    <strong>Speaker Bio:</strong> Ruben Niederhagen is Associate Research Fellow at Academia Sinica in Taiwan and Associate Professor at the University of Southern Denmark in Denmark. He obtained his PhD at Eindhoven University of Technology in the Netherlands in 2012. His research fields are Applied and Embedded Cryptography as well as Cryptanalytic Implementations. He is a co-submitter to the NIST Post-Quantum Cryptography Standardization process of two algorithms: the hash-based signature scheme SPHINCS+, which was standardized by NIST as SLH-DSA, and the code-based key-encapsulation mechanism Classic McEliece, which made it to the last round.
                </div>
            </div>
        </div>
    </div>

    <div class="time-block invited-talk">
        <div class="time-header">
            <div class="time-slot">10:00 AM - 10:20 AM</div>
            <div class="session-title">Short Invited Talk #1</div>
        </div>
        <div class="session-content">
            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract5'); return false;">
                    "Emerging Threats to Quantum Cybersecurity: From Malware to SWAP-Based Side-Channel Attacks"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Siyi Wang</span> (Nanyang Technological University)
                    <button class="bio-toggle" onclick="toggleBio('bio5'); return false;">View Bio</button>
                </div>
                <div id="abstract5" class="paper-abstract">
                    The rise of quantum computing brings not only transformative opportunities but also unprecedented security risks. This talk explores emerging threats that challenge the reliability of quantum systems, spanning from local to cloud-based environments. It begins with MalaQ, the first malware targeting quantum computers, which exploits the classical–quantum interface to degrade performance or even crash circuits on real quantum hardware. Moving to shared quantum infrastructures, I will present a SWAP-based side-channel attack that leverages crosstalk in multi-tenant cloud-based quantum devices. Contrary to prior assumptions, this attack remains effective over long distances, enabling adversaries to disrupt computations or extract sensitive information on IBM quantum devices. Together, these results highlight the urgent need to rethink the security of emerging quantum infrastructures and to develop robust defenses against future quantum cyber threats.
                </div>
                <div id="bio5" class="speaker-bio">
                    <strong>Speaker Bio:</strong> Dr. Wang Siyi is a Postdoctoral Researcher at Nanyang Technological University, Singapore, specializing in quantum computing and cybersecurity. She has contributed extensively to quantum arithmetic, cryptanalysis, and quantum cloud security. Her team proposed MalaQ, the first malware targeting ion-trapped quantum computers, and recently introduced a SWAP-based side-channel attack that demonstrates crosstalk vulnerabilities on multi-tenant quantum devices. Her work has been recognized with awards including Best Student Presentation at Yale's Quantum Computer Cybersecurity Symposium, Best Paper at IFIP/IEEE VLSI-SoC, and Best Poster at ACM AsiaCCS.
                </div>
            </div>
        </div>
    </div>

    <div class="time-block break-block">
        <div class="time-header">
            <div class="time-slot">10:20 AM - 11:00 AM</div>
            <div class="session-title">☕ Coffee Break</div>
        </div>
        <div class="session-content">
            <p>Networking and refreshments</p>
        </div>
    </div>

    <div class="time-block">
        <div class="time-header">
            <div class="time-slot">11:00 AM - 12:00 PM</div>
            <div class="session-title">Paper Session I</div>
        </div>
        <div class="session-content">

            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract4'); return false;">
                    "I Know What You Are Reading: Evaluating Readout Crosstalk in Cloud-based Quantum Computers"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Yizhuo Tan</span> (Yale University); 
                    <span class="speaker-name">Jakub Szefer</span> (Northwestern University)
                </div>
                <div id="abstract4" class="paper-abstract">
                    Frequency-multiplexing is a technique used for achieving resource-efficient readout in superconducting-based quantum computers. By enabling multiple resonators to share a common feed line, it significantly reduces the number of required cables and passive components. However, this gain in scalability introduces increased readout crosstalk. The readout crosstalk is not only a reliability issue, but also a possible security issue. Prior work has explored readout crosstalk in experimental systems not publicly available. This work builds on the prior findings and evaluates readout crosstalk in commercial, cloud-based quantum computers. In the process, this work also reconstructs the likely architecture for the shared readout feed lines and shows which qubit readout resonators likely share a feed line. This work finally shows that crosstalk-induced errors occurring during readout can be exploited by adversaries to infer the state of co-located victim qubits, leading to unintended information leakage.
                </div>
            </div>

            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract6'); return false;">
                    "Authenticating Quantum Circuits Through Localized Noise Fingerprints"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Gabrielle MacNeil</span> (University of New Hampshire); 
                    <span class="speaker-name">Sandeep Sunkavilli</span> (University of New Hampshire); 
                    <span class="speaker-name">Qiaoyan Yu</span> (University of New Hampshire)
                </div>
                <div id="abstract6" class="paper-abstract">
                    Quantum computing promises to outperform classical systems, yet today's Noisy Intermediate-Scale Quantum (NISQ) devices remain limited by gate errors, decoherence, and hardware variability. These challenges are compounded by the lack of built-in mechanisms to verify that quantum circuits execute as intended, especially in an untrusted quantum computer. In this work, we define quantum noise as a diagnostic signal rather than a nuisance. We propose a novel authentication method that utilizes Total Variation Distance (TVD) calculated using quantum noise. TVD compares a quantum circuit output distribution with a trusted quantum noise fingerprint. TVD offers a localized, interpretable metric for detecting structural tampering, such as gate reordering or injection. To support fine-grained verification, we introduce the concept of diagnostic ancilla qubits, non-invasive observers embedded in the circuit that store local noise signatures for post-execution analysis. While still a forward-looking concept, this proposal enables circuit-level verification. Our approach combines gate-level noise modeling with lightweight integrity checks, offering a promising path toward secure and tamper-evident quantum computation.
                </div>
            </div>

            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract2'); return false;">
                    "Securing Quantum Computer Reset with One-Time Pads"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Chuanqi Xu</span> (Yale University); 
                    <span class="speaker-name">Jamie Sikora</span> (Virginia Polytechnic Institute and State University); 
                    <span class="speaker-name">Jakub Szefer</span> (Northwestern University)
                </div>
                <div id="abstract2" class="paper-abstract">
                    The rapid expansion of cloud-based access to quantum computers has significantly democratized their usage, enabling a more diverse range of users to explore and utilize quantum computing technologies. However, this increased accessibility also introduces security and privacy concerns. Cloud-based access and sharing of quantum computers require secure means to isolate different users, such as through the use of reset operations. However, current reset operations, including direct thermalization and fast reset instructions, are vulnerable to information leakage due to imperfections in quantum computer operations. To counteract these vulnerabilities, our work proposes multiple implementations of the one-time pad (OTP) defense mechanism. These implementations, specifically random execution, dynamic circuit, and control gate, involve applying Pauli or control gates randomly before executing standard reset operations. We analyze and compare these implementations in detail, demonstrating their effectiveness in mitigating state leakage. This work offers innovative approaches to enhancing the security of reset operations and the safety of cloud-based quantum computers.
                </div>
            </div>

        </div>
    </div>

    <div class="time-block break-block">
        <div class="time-header">
            <div class="time-slot">12:00 PM - 1:30 PM</div>
            <div class="session-title">🍽️ Lunch Break</div>
        </div>
        <div class="session-content">
            <p>Lunch and networking opportunity</p>
        </div>
    </div>

    <div class="time-block invited-talk">
        <div class="time-header">
            <div class="time-slot">1:30 PM - 1:50 PM</div>
            <div class="session-title">Short Invited Talk #2</div>
        </div>
        <div class="session-content">
            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract1'); return false;">
                    "CHEQ: Towards Enabling Circuit Integrity Checking in Quantum Controllers"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Barbora Hrda</span> (TU Munich)
                    <button class="bio-toggle" onclick="toggleBio('bio1'); return false;">View Bio</button>
                </div>
                <div id="abstract1" class="paper-abstract">
                    Rapid advances in quantum computing hardware and software are bringing closer the promise of new discoveries and breakthroughs that these machines will enable. To fully utilize and trust quantum computers, however, users need assurances about the confidentiality and integrity of quantum circuits they execute on quantum computers. While existing research has begun to address the issues of quantum circuit confidentiality, there is a lack of quantum computer architecture or hardware designs for ensuring and checking the integrity of quantum circuits. This gap in existing research and design of quantum computers is addressed in this talk. It outlines the design of CHEQ, our FPGA enabled Circuit Hashing Engine for Quantum controllers. By providing circuit integrity measurements to users through CHEQ, quantum computing systems can become more resilient to security threats that aim to attack circuit integrity. Combined with other prior work on confidentiality, the new CHEQ integrity assurance in quantum computers can enable complete circuit protection, and thus protection of future discoveries and breakthroughs generated by quantum computers.
                </div>
                <div id="bio1" class="speaker-bio">
                    <strong>Speaker Bio:</strong> Barbora Hrdá is a doctoral candidate at the Technical University of Munich and a researcher at the Fraunhofer Institute for Applied and Integrated Security in Munich, Germany. She also collaborates with the Computer Architecture and Security Lab (CASLAB) led by Prof. Szefer at Northwestern University. Her research focuses on methods that ensure confidentiality and integrity of data processing on quantum computers and quantum computing platforms.
                </div>
            </div>
        </div>
    </div>

    <div class="time-block break-block">
        <div class="time-header">
            <div class="time-slot">1:50 PM - 2:00 PM</div>
            <div class="session-title">Short Break</div>
        </div>
        <div class="session-content">
            <p>&nbsp;</p>
        </div>
    </div>

    <div class="time-block">
        <div class="time-header">
            <div class="time-slot">2:00 PM - 3:00 PM</div>
            <div class="session-title">Paper Session II</div>
        </div>
        <div class="session-content">
            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract3'); return false;">
                    "Pulse-to-Circuit Characterization of Stealthy Crosstalk Attack on Multi-Tenant Superconducting Quantum Hardware"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Syed Emad Uddin Shubha</span> (Louisiana State University); 
                    <span class="speaker-name">Tasnuva Farheen</span> (Louisiana State University)
                </div>
                <div id="abstract3" class="paper-abstract">
                    Hardware crosstalk in multi-tenant superconducting quantum computers constitutes a significant security threat, enabling adversaries to inject targeted errors across tenant boundaries. We present the first end-to-end framework for mapping physical pulse-level attacks to interpretable logical error channels, integrating density-matrix simulation, quantum process tomography (QPT), and a novel isometry-based circuit extraction method. Our pipeline reconstructs the complete induced error channel and fits an effective logical circuit model, revealing a fundamentally asymmetric attack mechanism: one adversarial qubit acts as a driver to set the induced logical rotation, while a second, the catalyst, refines the attack's coherence. Demonstrated on a linear three-qubit system, our approach shows that such attacks can significantly disrupt diverse quantum protocols, sometimes reducing accuracy to random guessing, while remaining effective and stealthy even under realistic hardware parameter variations. We further propose a protocol-level detection strategy based on observable attack signatures, showing that stealthy attacks can be exposed through targeted monitoring and providing a foundation for future defense-in-depth in quantum cloud platforms.
                </div>
            </div>

            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract7'); return false;">
                    "Assessing the Viability of Quantum-Resistant IKEv2 over Constrained and Internet-Scale Networks"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Geoff Twardokus</span> (Rochester Institute of Technology); 
                    <span class="speaker-name">William Joslin</span> (Rochester Institute of Technology); 
                    <span class="speaker-name">Hanif Rahbari</span> (Rochester Institute of Technology); 
                    <span class="speaker-name">William Layton</span> (National Security Agency)
                </div>
                <div id="abstract7" class="paper-abstract">
                    Within 1–2 decades, quantum computers may become powerful enough to break current public-key cryptography, driving authorities such as the IETF and NIST to push for adopting quantum-resistant cryptography (QRC) in ecosystems like Internet Protocol Security (IPsec). However, IPsec struggles to adopt QRC, primarily due to the limited ability of Internet Key Exchange Protocol Version 2 (IKEv2), which sets up IPsec sessions, to tolerate the large public keys and digital signatures of QRC. Many IETF RFCs have been proposed to integrate QRC into IKEv2, but their performance and interplay remain largely untested in practice. In this paper, we measure the performance of these RFCs over constrained links by developing a flexible, reproducible measurement testbed for IPsec with quantum-resistant IKEv2 proposals. By deploying our testbed in lossy wireless links and on the internationally distributed FABRIC testbed for Internet scenarios, we reveal that performance bottlenecks arise with quantum-resistant IKEv2 in connections that experience high round-trip times, non-trivial packet loss, or other constraints. Our results, including the revelation of a 400–1000-fold (or greater) increase in data overhead over high-loss wireless links, expose the shortcomings and opportunities of today's RFCs and call for further attention and development in this vital area of post-quantum network security.
                </div>
            </div>

            <div class="paper-item">
                <a href="#" class="paper-title" onclick="toggleAbstract('abstract8'); return false;">
                    "A Lightweight Unified Keccak Module for Efficient Hashing in ML-KEM and ML-DSA"
                </a>
                <div class="paper-authors">
                    <span class="speaker-name">Suraj Mandal</span> (Indian Institute of Technology Kanpur); 
                    <span class="speaker-name">Debapriya Basu Roy</span> (Indian Institute of Technology Kanpur)
                </div>
                <div id="abstract8" class="paper-abstract">
                    One of the major modules used in post-quantum cryptographic (PQC) algorithms is Keccak or SHA-3. For generating the coefficients of the public vector, secret vector, and error vector, different sampler functions receive the output of the Keccak function directly. For PQC hardware implementations, Keccak plays a critical role in terms of being a major contributor to both area and timing overhead. This motivates us to design a unified Keccak module that can be shared between both CRYSTALS-Kyber and CRYSTALS-Dilithium. In this work, we have designed a unified Keccak module that efficiently generates the hash computations of CRYSTALS-Kyber (ML-KEM) and CRYSTALS-Dilithium (ML-DSA), which are current standard for post-quantum secure key encapsulation and digital signature algorithm respectively. Compared to the state-of-the-art unified Keccak implementations, we have achieved a 43% improvement in area overhead, resulting in a better area-time product (ATP) than the existing works.
                </div>
            </div>
        </div>
    </div>

    <div class="time-block closing-block">
        <div class="time-header">
            <div class="time-slot">3:00 PM</div>
            <div class="session-title">Closing</div>
        </div>
        <div class="session-content">
            <p>Workshop wrap-up and future directions</p>
        </div>
    </div>
</div>

<script>
function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    var titleElement = event.target;
    
    if (abstract.style.display === 'none' || abstract.style.display === '') {
        abstract.style.display = 'block';
        titleElement.classList.add('expanded');
    } else {
        abstract.style.display = 'none';
        titleElement.classList.remove('expanded');
    }
}

function toggleBio(id) {
    var bio = document.getElementById(id);
    var button = event.target;
    
    if (bio.style.display === 'none' || bio.style.display === '') {
        bio.style.display = 'block';
        button.textContent = 'Hide Bio';
    } else {
        bio.style.display = 'none';
        button.textContent = 'View Bio';
    }
}
</script>