# Survey on Security and Privacy Neuromorphic Computing
This repository extends from our recent work "Emerging Threats and Countermeasures in Neuromorphic Systems: A Survey". By designing and analyzing Memristor Devices for Neuromorphic Computing, Spiking Neural Networks (SNNs), Physically Unclonable Functions (PUFs), True Random Number Generators (TRNGs), we are investigating the relationship between In Memory Computing Systems and their hardware and software security.

> #### **Emerging Threats and Countermeasures in Neuromorphic Systems: A Survey**  
> 
>Neuromorphic computing mimics brain-inspired mechanisms through spiking neurons and energy-efficient processing, offering a pathway to efficient in-memory computing (IMC). However, these advancements raise critical security and privacy concerns. As the adoption of bio-inspired architectures and memristive devices increases, so does the urgency to assess the vulnerability of these emerging technologies to hardware and software attacks. Emerging architectures introduce new attack surfaces, particularly due to asynchronous, event-driven processing and stochastic device behavior.
> 
> The integration of memristors into neuromorphic hardware and software implementations of spiking neural networks (SNNs) enables diverse opportunities for advanced computing architectures, including security-aware applications. This survey systematically analyzes the security landscape of neuromorphic systems, covering attack methodologies, side-channel vulnerabilities, and countermeasures. We focus on both hardware and software security concerns relevant to SNNs, as well as hardware security primitives such as Physical Unclonable Functions (PUFs) and True Random Number Generators (TRNGs) for cryptographic and secure computation.
> 
> By addressing attack methodologies and countermeasure strategies jointly, this survey maps the current threat landscape and provides a foundation for developing secure and trustworthy neuromorphic architectures.

Mantained by [**Pablo Sorrentino**](https://github.com/SorrentinoPablo), member of the Security and Privacy Research Group from the [University of Groningen (RUG)](https://www.rug.nl/), supervised by [**Tamalika Banerjee**](https://research.rug.nl/en/persons/tamalika-banerjee/) and [**Fatih Turkmen**](https://www.cs.rug.nl/~turkmen/). 

---
## Citation

If you find this repository useful for your research, please cite our work:
- [1] `Pablo Sorrentino, Stjepan Picek, Ihsen Alouani, Nikolaos Athanasios Anagnostopoulos, Francesco Regazzoni, Lejla Batina, Tamalika Banerjee, Fatih Turkmen. (2025). Emerging Threats and Countermeasures in Neuromorphic Systems: A Survey. ACM Computing Surveys (under review).`

- Bibtex:

```bibtex
@article{sorrentino2025neuromorphic,
  title={{Emerging Threats and Countermeasures in Neuromorphic Systems: A Survey}},
  author={Sorrentino, Pablo and
          Picek, Stjepan and
          Alouani, Ihsen and
          Anagnostopoulos, Nikolaos Athanasios and
          Regazzoni, Francesco and
          Batina, Lejla and
          Banerjee, Tamalika and
          Turkmen, Fatih},
  journal={ACM Computing Surveys},
  year={2025},
  note={under review}
}
```
---
Our goal is to offer a living resource for researchers and practitioners, reflecting the latest developments and evaluations in the field. Please
- Star this repository to show support
- Create a PR if you notice missing papers in this collection of academic papers
- Share with the research community

For any questions or support, please reach out through: p.f.a.sorrentino@rug.nl

## Contents / Key Topics
- [Introduction](#Introduction)
  - [Neuromorphic Computing](#Neuromorphic-Computing)
  - [Spiking Neural Networks](#Spiking-Neural-Networks)
  - [Types of Threads](#Types-of-Threads)
- [Hardware Vulnerabilities and Countermeasures](#Hardware-Vulnerabilities-and-Countermeasures) 
- [Software Attacks and Defensive Strategies](#Software-Attacks-and-Defensive-Strategies)
- [Emeging Security Applications](#Emeging-Security-Applications)

## Introduction

<details>
<summary> List of Foundational and Survey Papers: </summary>

## *Neuromorphic Computing and Memristors*

| Year | Title | Authors | Venue | Details |
|------|-------|---------|-------|---------|
| 2013 | Reverse Engineering the Cognitive Brain | Gert Cauwenberghs | Proceedings of the IEEE | [Link]()<br>[Talk]()<br>[Code]() |
| 2015 | TrueNorth: Design and Tool Flow of a 65 mW 1 Million Neuron Programmable Neurosynaptic Chip | Filipp Akopyan et al. | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2017 | A Survey of Neuromorphic Computing and Neural Networks in Hardware | Catherine D. Schuman et al. | arXiv | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | Hardware and Software Optimizations for Accelerating Deep Neural Networks: Survey of Current Trends, Challenges, and the Road Ahead | Maurizio Capra et al. | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Neuromorphic Electronics Based on Copying and Pasting the Brain | Donhee Ham et al. | Nature Electronics | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Breaking the von Neumann Bottleneck: Architecture-Level Processing-in-Memory Technology | S. Xu, X. Zou, X. Chen | Science China Information Sciences | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Brain-Inspired Computing Needs a Master Plan | A. Mehonic, A. J. Kenyon | Nature Electronics | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Opportunities for Neuromorphic Computing Algorithms and Applications | Catherine D. Schuman et al. | Nature Computational Science | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Toward a Formal Theory for Computing Machines Made Out of Whatever Physics Offers | Herbert Jaeger, Beatriz Noheda, Wilfred G. van der Wiel | Nature Reviews Physics | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | System Model of Neuromorphic Sequence Learning on a Memristive Crossbar Array | Sebastian Siegel et al. | IEEE TNNLS | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Brain-Inspired Methods for Achieving Robust Computation in Heterogeneous Mixed-Signal Neuromorphic Processing Systems | Dmitrii Zendrikov, Sergio Solinas, Giacomo Indiveri | Nature Electronics | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Memristive Memory Enhancement by Device Miniaturization for Neuromorphic Computing | Anouk S. Goossens et al. | Advanced Electronic Materials | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Tunability of Voltage Pulse–Mediated Memristive Functionality by Varying Doping Concentration in SrTiO₃ | A. S. Goossens, Tamalika Banerjee | Journal of Applied Physics | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Electrochemical-Memristor-Based Artificial Neurons and Synapses: Fundamentals, Applications, and Challenges | Shaochuan Chen et al. | Advanced Functional Materials | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Memristors on the Edge of Chaos | Leon O. Chua | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Hardware Implementation of Memristor-Based Artificial Neural Networks | Fernando Aguirre et al. | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Memristor-Based Spiking Neural Networks: Cooperative Development of Neural Network Architecture/Algorithms and Memristors | Huihui Peng, Lin Gan, Xin Guo | Advanced Intelligent Systems | [Link]()<br>[Talk]()<br>[Code]() |

## *Spiking Neural Networks*
| Year | Title | Authors | Venue | Details |
|------|-------|---------|-------|---------|
| 2011 | Simulation of a Memristor-Based Spiking Neural Network Immune to Device Variations | Damien Querlioz, Olivier Bichler, Christian Gamrat | IEEE Transactions on Circuits and Systems I | [Link]()<br>[Talk]()<br>[Code]() |
| 2014 | Nengo: A Python Tool for Building Large-Scale Functional Brain Models | Trevor Bekolay et al. | Frontiers in Neuroinformatics | [Link]()<br>[Talk]()<br>[Code]() |
| 2015 | Memory and Information Processing in Neuromorphic Systems | Giacomo Indiveri, Shih-Chii Liu | Proceedings of the IEEE | [Link]()<br>[Talk]()<br>[Code]() |
| 2015 | Spiking Deep Networks with LIF Neurons | Eric Hunsberger, Chris Eliasmith | arXiv | [Link]()<br>[Talk]()<br>[Code]() |
| 2018 | Programming Spiking Neural Networks on Intel’s Loihi | Min Lin, Qiang Chen, Shuicheng Yan | IEEE Computer Architecture Letters | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Spiking Neural Networks Based on Two-Dimensional Materials | Juan B. Roldán | Materials Today Physics | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Exploring Neuromorphic Computing Based on Spiking Neural Networks: Algorithms to Hardware | Nitin Rathi et al. | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | SpikingJelly: An Open-Source Machine Learning Infrastructure Platform for Spike-Based Intelligence | Wei Fang et al. | Science China Information Sciences | [Link]()<br>[Talk]()<br>[Code]() |

## *Types of Threads*
| Year | Title | Authors | Venue | Details |
|------|-------|---------|-------|---------|
| 1997 | On the Importance of Checking Cryptographic Protocols for Faults | Dan Boneh, Richard A. DeMillo, Richard J. Lipton | EUROCRYPT | [Link]()<br>[Talk]()<br>[Code]() |
| 2001 | Electromagnetic Analysis: Concrete Results | Karine Gandolfi, Christophe Mourtel, Francis Olivier | CHES | [Link]()<br>[Talk]()<br>[Code]() |
| 2003 | The EM Side-Channel(s) | Dakshi Agrawal et al. | CHES | [Link]()<br>[Talk]()<br>[Code]() |
| 2003 | Private Circuits: Securing Hardware Against Probing Attacks | Yuval Ishai, Amit Sahai, David Wagner | CRYPTO | [Link]()<br>[Talk]()<br>[Code]() |
| 2004 | Correlation Power Analysis with a Leakage Model | Eric Brier, Christophe Clavier, Francis Olivier | CHES | [Link]()<br>[Talk]()<br>[Code]() |
| 2006 | Threshold Implementations Against Side-Channel Attacks and Glitches | Svetla Nikova, Christian Rechberger, Vincent Rijmen | CHES | [Link]()<br>[Talk]()<br>[Code]() |
| 2019 | Spectre Attacks: Exploiting Speculative Execution | Paul Kocher et al. | IEEE Symposium on Security and Privacy | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | Meltdown: Reading Kernel Memory from User Space | Moritz Lipp et al. | USENIX Security Symposium | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Understanding Security Threats in Emerging Neuromorphic Computing Architecture | Chidhambaranathan Rajamanikkam et al. | IEEE Computer Society | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | SoK: Deep Learning-Based Physical Side-Channel Analysis | Stjepan Picek et al. | IEEE Transactions on Information Forensics and Security | [Link]()<br>[Talk]()<br>[Code]() |

</details>

## Hardware Vulnerabilities and Countermeasures [[Back to Top](#survey-on-security-and-privacy-neuromorphic-computing)]

| Year | Title | Authors | Type | Target / Leakage | Venue | Details |
|------|-------|---------|------|------------------|-------|---------|
| 2024 | IMCE: An In-Memory Computing and Encrypting Hardware Architecture for Robust Edge Security | Hanyong Shao et al. | Side-Channel | IMC architecture / power leakage | IEEE Transactions on Computers | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Error Detection and Correction Codes for Safe In-Memory Computations | Luca Parrini et al. | Fault Injection | IMC memory arrays / computation faults | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | FTC: A Universal Framework for Fault-Injection Attack Detection and Prevention | Md Rafid Muttaki et al. | Fault Injection | General hardware logic / injected faults | IEEE TIFS | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | CoMeT: Count-Min-Sketch-Based Row Tracking to Mitigate RowHammer at Low Cost | F. Nisa Bostanci et al. | Fault Injection | DRAM rows / disturbance errors | IEEE S&P | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | ProtFe: Low-Cost Secure Power Side-Channel Protection for General and Custom FeFET-Based Memories | Taixin Li et al. | Side-Channel | FeFET memories / power leakage | IEEE TVLSI | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | UnTrustZone: Systematic Accelerated Aging to Expose On-Chip Secrets | Jubayer Mahmod, Matthew Hicks | Fault Injection | Aging-induced degradation / reliability leakage | USENIX Security | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | S-Tune: SOT-MTJ Manufacturing Parameters Tuning for Securing the Next Generation of Computing | Muhtasim Alam Chowdhury et al. | Hardware Trojan | Spintronic devices / parametric manipulation | IEEE Trans. on Magnetics | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Era of Sentinel Tech: Charting Hardware Security Landscapes Through Post-Silicon Innovation, Threat Mitigation and Future Trajectories | Mamidipaka B. R. Srinivas, Konguvel Elango | Hardware Trojan | Post-silicon hardware components | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | NEUROSEC: FPGA-Based Neuromorphic Audio Security | Murat Isik et al. | Side-Channel | FPGA-based SNN / timing & power leakage | IEEE ISCAS | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | On the Layout-Oriented Investigation of Power Attack Hardness of Spintronic-Based Logic Circuits | Pegah Iranfar et al. | Side-Channel | Spintronic logic / power leakage | IEEE Trans. on Magnetics | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Mercury: An Automated Remote Side-Channel Attack to NVIDIA Deep Learning Accelerator | Xiaobei Yan et al. | Side-Channel | GPU accelerator / timing & power leakage | IEEE S&P | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Hardware Trojans in eNVM Neuromorphic Devices | Lingxi Wu et al. | Hardware Trojan | eNVM neuromorphic devices / malicious circuitry | IEEE TETC | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Side-Channel Attack Analysis on In-Memory Computing Architectures | Ziyu Wang et al. | Side-Channel | IMC architectures / power & timing leakage | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | AI Attacks AI: Recovering Neural Network Architecture from NVDLA Using AI-Assisted Side-Channel Attack | Naina Gupta et al. | Side-Channel | NVDLA accelerator / power & EM leakage | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Understanding and Characterizing Side Channels Exploiting Phase-Change Memories | Md Hafizul Islam Chowdhury et al. | Side-Channel | PCM devices / resistance & power leakage | IEEE Trans. on Computers | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | DeepSteal: Advanced Model Extractions Leveraging Efficient Weight Stealing in Memories | Adnan Siraj Rakin et al. | Side-Channel | On-chip memories / access-pattern leakage | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | A Survey of Neuromorphic Computing-in-Memory: Architectures, Simulators, and Security | Felix Staudigl et al. | Side-Channel | Neuromorphic IMC platforms / multiple leakages | ACM Computing Surveys | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Enhancing Security of Memristor Computing System Through Secure Weight Mapping | Minhui Zou et al. | Side-Channel | Memristive weights / power leakage | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | NeuroHammer: Inducing Bit-Flips in Memristive Crossbar Memories | Felix Staudigl et al. | Fault Injection | Memristive crossbars / disturbance faults | IEEE TDSC | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Hardware Functional Obfuscation with Ferroelectric Active Interconnects | Tongguang Yu et al. | Hardware Trojan | Ferroelectric interconnects / logic obfuscation | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Logic Locking Using Emerging 2T/3T Magnetic Tunnel Junctions for Hardware Security | Divyanshu et al. | Hardware Trojan | MTJ-based logic / structural locking | IEEE TVLSI | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | SCARE: Side-Channel Attack on In-Memory Computing for Reverse Engineering | Sina Sayyah Ensan et al. | Side-Channel | IMC arrays / power & timing leakage | IEEE TIFS | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | BlockHammer: Preventing RowHammer at Low Cost by Blacklisting Rapidly-Accessed DRAM Rows | A. G. Yağlikçi et al. | Fault Injection | DRAM rows / row disturbance | IEEE S&P | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Understanding Security Threats in Emerging Neuromorphic Computing Architecture | Chidhambaranathan Rajamanikkam et al. | Side-Channel | Neuromorphic hardware / architectural leakage | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Emerging Topics in Hardware Security | Mark Tehranipoor | Hardware Trojan | Hardware supply chain / post-silicon threats | IEEE Design & Test | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Deep Learning Side-Channel Attack Against Hardware Implementations of AES | Takaya Kubota et al. | Side-Channel | AES hardware / power leakage | IEEE TIFS | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | Novel Hybrid CMOS/Memristor Implementation of the AES Algorithm Robust Against DPA | Massoud Masoumi | Side-Channel | AES on memristive hardware / power leakage | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2019 | More Practical Single-Trace Attacks on the Number Theoretic Transform | Peter Pessl, Robert Primas | Side-Channel | Cryptographic accelerators / power leakage | CHES | [Link]()<br>[Talk]()<br>[Code]() |
| 2019 | CSI NN: Reverse Engineering of Neural Network Architectures Through Electromagnetic Side Channel | Lejla Batina et al. | Side-Channel | Neural accelerators / EM leakage | CHES | [Link]()<br>[Talk]()<br>[Code]() |
| 2019 | Exploiting the Switching Dynamics of HfO₂-Based ReRAM Devices for Reliable Analog Memristive Behavior | F. Cüppers et al. | Side-Channel | ReRAM devices / switching dynamics | IEEE TED | [Link]()<br>[Talk]()<br>[Code]() |
| 2017 | Correlation Power Analysis Attack Against STT-MRAM Based Cryptosystems | Abhishek Chakraborty et al. | Side-Channel | STT-MRAM cryptosystems / power leakage | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |

## Software Attacks and Defensive Strategies [[Back to Top](#survey-on-security-and-privacy-neuromorphic-computing)]

| Year | Title | Authors | Type | Target / Leakage | Venue | Details |
|------|-------|---------|------|------------------|-------|---------|
| 2025 | Side-Channel Analysis of Integrate-and-Fire Neurons Within Spiking Neural Networks | Matthias Probst, Manuel Brosch, Georg Sigl | SCA/FIA | Neuron dynamics / timing & power leakage | DATE | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Sneaky Spikes: Uncovering Stealthy Backdoor Attacks in Spiking Neural Networks with Neuromorphic Data | Gorka Abad et al. | Backdoor | Temporal spike patterns / poisoned triggers | IEEE S&P | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Moving Target Defense Through Approximation for Low-Power Neuromorphic Edge Intelligence | Ayesha Siddique, Khaza Anuarul Hoque | Adversarial | Model approximation / attack surface randomization | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Watermarking Neuromorphic Brains: Intellectual Property Protection in Spiking Neural Networks | Hamed Poursiami, Ihsen Alouani, Maryam Parsa | Inference | Model ownership / watermark leakage | IEEE TIFS | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Securing on-Chip Learning: Navigating Vulnerabilities and Potential Safeguards in Spiking Neural Network Architectures | Najmeh Nazari et al. | SCA/FIA | On-chip learning dynamics / fault sensitivity | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | HyperTheft: Thieving Model Weights from TEE-Shielded Neural Networks via Ciphertext Side Channels | Yuanyuan Yuan et al. | Inference | Encrypted execution / ciphertext leakage | IEEE S&P | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Securing Spiking Neural Networks with Genetic XOR Encryption on RRAM-based Neuromorphic Accelerator | Kwunhang Wong et al. | Inference | Encrypted weights / key-dependent leakage | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Spikewhisper: Temporal Spike Backdoor Attacks on Federated Neuromorphic Learning over Low-Power Devices | Hanqing Fu et al. | Backdoor | Federated SNNs / temporal spike triggers | USENIX Security | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | On the Need of Neuromorphic Twins to Detect Denial-of-Service Attacks on Communication Networks | Holger Boche et al. | Adversarial | Network-level DoS / event saturation | IEEE Communications Magazine | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Enhancing the Robustness of Spiking Neural Networks with Stochastic Gating Mechanisms | Jianhao Ding et al. | Adversarial | Spike gating / adversarial noise robustness | IEEE TNNLS | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | SCANN: Side Channel Analysis of Spiking Neural Networks | Karthikeyan Nagarajan et al. | SCA/FIA | Spike timing & activity / information leakage | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Attacking the Spike: On the Transferability and Security of Spiking Neural Networks to Adversarial Examples | Nuo Xu et al. | Adversarial | Spike-based inference / adversarial transferability | IEEE TNNLS | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Cybersecurity Regulation of Smart Mobility Hardware Systems: Case Assessment for Spin-Based MTJ Devices | Divyanshu Divyanshu et al. | Inference | System-level regulation & leakage risks | IEEE Design & Test | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Improving Reliability of Spiking Neural Networks through Fault Aware Threshold Voltage Optimization | Ayesha Siddique, Khaza Anuarul Hoque | SCA/FIA | Voltage thresholds / fault resilience | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Analysis of Power-Oriented Fault Injection Attacks on Spiking Neural Networks | Karthikeyan Nagarajan et al. | SCA/FIA | Power perturbations / induced faults | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Fault Injection Attacks in Spiking Neural Networks and Countermeasures | Karthikeyan Nagarajan et al. | SCA/FIA | Neuron state corruption / fault models | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Efficiency Attacks on Spiking Neural Networks | Sarada Krithivasan et al. | Adversarial | Energy consumption / spike amplification | IEEE TNNLS | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Toward Robust Spiking Neural Network Against Adversarial Perturbation | Ling Liang et al. | Adversarial | Input perturbations / spike robustness | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | SNN-RAT: Robustness-Enhanced Spiking Neural Network Through Regularized Adversarial Training | Jianhao Ding et al. | Adversarial | Adversarial training / spike regularization | IEEE TNNLS | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | Adversarial Machine Learning Attacks and Defense Methods in the Cyber Security Domain | Ishai Rosenberg et al. | Adversarial | ML pipelines / generic adversarial threats | ACM Computing Surveys | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | HIRE-SNN: Harnessing the Inherent Robustness of Energy-Efficient Deep Spiking Neural Networks by Training With Crafted Input Noise | Souvik Kundu et al. | Adversarial | Noise-aware training / robustness | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | Is Spiking Secure? A Comparative Study on the Security Vulnerabilities of Spiking and Deep Neural Networks | Alberto Marchisio et al. | Adversarial | SNN vs DNN robustness comparison | DATE | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | NeuroAttack: Undermining Spiking Neural Networks Security Through Externally Triggered Bit-Flips | Valerio Venceslai et al. | SCA/FIA | External perturbations / bit-flip faults | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | TBT: Targeted Neural Network Attack With Bit Trojan | Adnan Siraj Rakin et al. | Backdoor | Bit-level trojans / targeted misclassification | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2019 | Parametric Noise Injection: Trainable Randomness to Improve Deep Neural Network Robustness Against Adversarial Attack | Zhezhi He et al. | Adversarial | Trainable noise / adversarial defense | IEEE TCAD | [Link]()<br>[Talk]()<br>[Code]() |
| 2015 | Robustness of Spiking Deep Belief Networks to Noise and Reduced Bit Precision of Neuro-Inspired Hardware Platforms | Evangelos Stromatias et al. | Adversarial | Quantization & noise robustness | Neural Computation | [Link]()<br>[Talk]()<br>[Code]() |
| 2015 | Are Neuromorphic Architectures Inherently Privacy-Preserving? An Exploratory Study | Ayana Moshruba | Inference | Data privacy / information leakage | arXiv | [Link]()<br>[Talk]()<br>[Code]() |

## Emeging Security Applications [[Back to Top](#survey-on-security-and-privacy-neuromorphic-computing)]

| Year | Title | Authors | Venue | Details |
|------|-------|---------|-------|---------|
| 2024 | Defense Method Against Adversarial Example Attacks Using Thermal Noise of a CMOS Image Sensor | Yuki Rogi et al. | Secure Sensing | Sensor noise / adversarial robustness | IEEE Sensors Journal | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Efficient Implementation of Mahalanobis Distance on Ferroelectric FinFET Crossbar for Outlier Detection | Musaib Rafiq, Yogesh Singh Chauhan, Shubham Sahay | IMC + Crypto | Crossbar computing / anomaly detection | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | A Robust Deep Learning Attack-Immune MRAM-Based Physical Unclonable Function | Mohammad Javad Adel et al. | PUF | MRAM PUF / ML-attack resilience | IEEE Transactions on Magnetics | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Resilience Evaluation of Memristor-Based PUF Against Machine Learning Attacks | Hebatallah M. Ibrahim, Heorhii Skovorodnikov, Hoda Alkhzaimi | PUF | Memristive PUF / ML robustness | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | In Situ Cryptography in a Neuromorphic Vision Sensor Based on Light-Driven Memristors | Lingxiang Hu et al. | IMC + Crypto | Near-sensor cryptography / memristive vision | Nature Electronics | [Link]()<br>[Talk]()<br>[Code]() |
| 2024 | Algorithmically-Enhanced Design of Spintronic-Based Tunable True Random Number Generator for Dependable Stochastic Computing | Amir Bahador, Mohammad Hossein Moaiyeri, Reza Ghaderi | TRNG | Spintronic TRNG / stochastic computing | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Hardware Security Primitives Using Passive RRAM Crossbar Array: Novel TRNG and PUF Designs | Simranjeet Singh et al. | PUF/TRNG | Passive RRAM crossbars / entropy source | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | True Random Number Generator Based on the Variability of the High Resistance State of RRAMs | Maryam Akbari et al. | TRNG | RRAM HRS variability / entropy | IEEE Transactions on Electron Devices | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Attack Resilient True Random Number Generators Using Ferroelectric-Enhanced Stochasticity in 2D Transistor | Yu-Chieh Chien et al. | TRNG | Ferroelectric devices / entropy enhancement | IEEE Transactions on Electron Devices | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Physical Unclonable Functions (PUF) for IoT Devices | Abdulaziz Al-Meer, Saif Al-Kuwari | PUF | IoT authentication / device identity | IEEE IoT Journal | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | PUF-Phenotype: A Robust and Noise-Resilient Approach to Aid Group-Based Authentication With DRAM-PUFs Using Machine Learning | Owen Millwood et al. | PUF | DRAM-PUF / ML-assisted authentication | IEEE TIFS | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | A Unified Multibit PUF and TRNG Based on Ring Oscillators for Secure IoT Devices | Iluminada Baturone, Roberto Román, Ángel Corbacho | PUF/TRNG | Ring-oscillator entropy / IoT security | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2023 | Suppression of Crosstalk in Row–Column Actuator Array Using Regulation of Ferroelectric Polarization | Jin Soo Park et al. | IMC + Crypto | Crossbar arrays / interference mitigation | IEEE Transactions on Electron Devices | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Memristor-Based Security Primitives Robust to Malicious Attacks for Highly Secure Neuromorphic Systems | Jungyeop Oh et al. | PUF/TRNG | Memristive primitives / neuromorphic security | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | In-Memory Unified TRNG and Multi-Bit PUF for Ubiquitous Hardware Security | Sachin Taneja, Viveka Konandur Rajanna, Massimo Alioto | PUF/TRNG | In-memory entropy generation | IEEE Journal of Solid-State Circuits | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | All-in-One, Bio-Inspired, and Low-Power Crypto Engines for Near-Sensor Security Based on Two-Dimensional Memtransistors | Akhil Dodda et al. | IMC + Crypto | Near-sensor crypto / memtransistors | Nature Electronics | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Using Memristor Arrays as Physical Unclonable Functions | Florian Frank et al. | PUF | Memristor arrays / device identity | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2022 | Clones of the Unclonable: Nanoduplicating Optical PUFs and Applications | E. Marakis et al. | PUF | Optical PUF cloning / physical security | Nature Communications | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | A Survey on the Security of PUFs | Shuqin Su et al. | PUF | PUF threats & countermeasures | ACM Computing Surveys | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | A Novel Physical Unclonable Function (PUF) Using 16×16 Pure-HfOx Ferroelectric Tunnel Junction Array for Security Applications | Junsu Yu et al. | PUF | FTJ array / device-level entropy | IEEE Transactions on Electron Devices | [Link]()<br>[Talk]()<br>[Code]() |
| 2021 | RRAM Random Number Generator Based on Train of Pulses | Binbin Yang et al. | TRNG | RRAM pulse variability / entropy | IEEE Transactions on Electron Devices | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | Application of the Quasi-Static Memdiode Model in Cross-Point Arrays for Large Dataset Pattern Recognition | Fernando Leonel Aguirre et al. | IMC + Crypto | Cross-point IMC / pattern recognition | IEEE TCAS-I | [Link]()<br>[Talk]()<br>[Code]() |
| 2020 | True Random Number Generator for Reliable Hardware Security Modules Based on a Neuromorphic Variation-Tolerant Spintronic Structure | Abdolah Amirany, Kian Jafari, Mohammad Hossein Moaiyeri | TRNG | Spintronic TRNG / HSM security | IEEE Transactions on Magnetics | [Link]()<br>[Talk]()<br>[Code]() |
| 2018 | Memristor Technology: Synthesis and Modeling for Sensing and Security Applications | Heba Abunahla, Baker Mohammad | Secure Sensing | Memristor modeling / sensing security | IEEE Access | [Link]()<br>[Talk]()<br>[Code]() |
| 2018 | Advancing Hardware Security Using Polymorphic and Stochastic Spin-Hall Effect Devices | Satwik Patnaik et al. | PUF/TRNG | Spin-Hall devices / polymorphic security | IEEE Transactions on Nanotechnology | [Link]()<br>[Talk]()<br>[Code]() |
| 2018 | A Bio-Inspired Physically Transient/Biodegradable Synapse for Security Neuromorphic Computing Based on Memristors | Bingjie Dang et al. | Secure Sensing | Transient memristors / hardware security | Advanced Functional Materials | [Link]()<br>[Talk]()<br>[Code]() |
