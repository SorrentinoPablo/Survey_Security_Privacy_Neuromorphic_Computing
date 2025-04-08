# Survey Security Privacy Neuromorphic Computing
This repository extends from our recent work, "Emerging Threats and Countermeasures in Neuromorphic Systems: A Survey" By designing and analyzing Memristor Devices for Neuromorphic Computing, Spiking Neural Networks (SNNs), Physically Unclonable Functions (PUFs), True Random Number Generators (TRNGs), we are investigating the relationship between In Memory Computing Systems and their hardware and software security.

## Contents / Key Topics
- [Research Papers and Studies](#Research-Papers-and-Studies)
- [Neuromorphic Computing](#Neuromorphic-Computing)
- [Spiking Neural Networks](#Spiking-Neural-Networks)
- [Types of Threads](#Types-of-Threads)
- [Hardware Vulnerabilities and Countermeasures](#Hardware-Vulnerabilities-and-Countermeasures)
- [Software Attacks and Defensive Strategies](#Software-Attacks-and-Defensive-Strategies)
- [Emeging Security Applications](#Emeging-Security-Applications)
- [Collaboration and Contribution](#Collaboration-and-Contribution)

## Research Papers and Studies

* "True Random Number Generator Based on the Variability of the High Resistance State of RRAMs" - Maryam Akbari et al., 2023
* "Truenorth: Design and tool flow of a 65 mw 1 million neuron programmable neurosynaptic chip" - Filipp Akopyan et al., 2015
* "True Random Number Generator for Reliable Hardware Security Modules Based on a Neuromorphic Variation-Tolerant Spintronic Structure" - Abdolah Amirany, Kian Jafari, and Mohammad Hossein Moaiyeri, 2020
* "Algorithmically-Enhanced Design of Spintronic-Based Tunable True Random Number Generator for Dependable Stochastic Computing" - Amir Bahador, Mohammad Hossein Moaiyeri, and Reza Ghaderi, 2024
* "CSI NN: Reverse Engineering of Neural Network Architectures Through Electromagnetic Side Channel" - Lejla Batina et al., 2019
* "A Unified Multibit PUF and TRNG Based on Ring Oscillators for Secure IoT Devices" - Iluminada Baturone, Roberto Román, and Ángel Corbacho, 2023
* "Nengo: a Python tool for building large-scale functional brain models" - Trevor Bekolay et al., 2014
* "On the Need of Neuromorphic Twins to Detect Denial-of-Service Attacks on Communication Networks" - Holger Boche et al., 2024
* "On the importance of checking cryptographic protocols for faults" - Dan Boneh, Richard A DeMillo, and Richard J Lipton, 1997
* "CoMeT: Count-Min-Sketch-based Row Tracking to Mitigate RowHammer at Low Cost" - F. Nisa Bostanci et al., 2024
* "Correlation Power Analysis with a Leakage Model" - Eric Brier, Christophe Clavier, and Francis Olivier, 2004
* "Hardware and Software Optimizations for Accelerating Deep Neural Networks: Survey of Current Trends, Challenges, and the Road Ahead" - Maurizio Capra et al., 2020
* "Reverse engineering the cognitive brain" - Gert Cauwenberghs, 2013
* "Correlation power analysis attack against STT-MRAM based cryptosystems" - Abhishek Chakraborty, Ankit Mondal, and Ankur Srivastava, 2017
* "Electrochemical-Memristor-Based Artificial Neurons and Synapses Fundamentals, Applications, and Challenges" - Shaochuan Chen et al., 2023
* "Attack Resilient True Random Number Generators Using Ferroelectric-Enhanced Stochasticity in 2D Transistor" - Yu-Chieh Chien et al., 2023
* "S-Tune: SOT-MTJ manufacturing parameters tuning for securing the next generation of computing" - Muhtasim Alam Chowdhury et al., 2024
* "Understanding and Characterizing Side Channels Exploiting Phase-Change Memories" - Md Hafizul Islam Chowdhuryy et al., 2023
* "Memristors on ‘edge of chaos’" - Leon O. Chua, 2024
* "Exploiting the switching dynamics of HfO2-based ReRAM devices for reliable analog memristive behavior" - F. Cüppers et al., 2019
* "A bio-inspired physically transient/biodegradable synapse for security neuromorphic computing based on memristors" - Bingjie Dang et al., 2018
* "Enhancing the Robustness of Spiking Neural Networks with Stochastic Gating Mechanisms" - Jianhao Ding et al., 2024
* "SNN-RAT: Robustness-enhanced Spiking Neural Network through Regularized Adversarial Training" - Jianhao Ding et al., 2022
* "Cybersecurity Regulation of Smart Mobility Hardware Systems: Case Assessment for Spin-Based MTJ Devices" - Divyanshu Divyanshu et al., 2023
* "Logic Locking Using Emerging 2T/3T Magnetic Tunnel Junctions for Hardware Security" - Divyanshu Divyanshu et al., 2022
* "All-in-one, bio-inspired, and low-power crypto engines for near-sensor security based on two-dimensional memtransistors" - Akhil Dodda et al., 2022
* "SpikingJelly: An open-source machine learning infrastructure platform for spike-based intelligence" - Wei Fang et al., 2023
* "Using Memristor Arrays as Physical Unclonable Functions" - Florian Frank et al., 2022
* "Spikewhisper: Temporal Spike Backdoor Attacks on Federated Neuromorphic Learning over Low-power Devices" - Hanqing Fu et al., 2024
* "Electromagnetic Analysis: Concrete Results" - Karine Gandolfi, Christophe Mourtel, and Francis Olivier, 2001
* "Tunability of voltage pulse mediated memristive functionality by varying doping concentration in SrTiO3" - A. S. Goossens and T. Banerjee, 2023
* "Memristive Memory Enhancement by Device Miniaturization for Neuromorphic Computing" - Anouk S. Goossens et al., 2023
* "AI Attacks AI: Recovering Neural Network architecture from NVDLA using AI-assisted Side Channel Attack" - Naina Gupta, Arpan Jati, and Anupam Chattopadhyay, 2023
* "Neuromorphic electronics based on copying and pasting the brain" - Donhee Ham et al., 2021
* "Parametric Noise Injection: Trainable Randomness to Improve Deep Neural Network Robustness Against Adversarial Attack" - Zhezhi He, Adnan Siraj Rakin, and Deliang Fan, 2019
* "In situ cryptography in a neuromorphic vision sensor based on light-driven memristors" - Lingxiang Hu et al., 2024
* "Spiking deep networks with LIF neurons" - Eric Hunsberger and Chris Eliasmith, 2015
* "Resilience evaluation of memristor based PUF against machine learning attacks" - Hebatallah M. Ibrahim, Heorhii Skovorodnikov, and Hoda Alkhzaimi, 2024
* "Memory and Information Processing in Neuromorphic Systems" - Giacomo Indiveri and Shih-Chii Liu, 2015
* "On the Layout-Oriented Investigation of Power Attack Hardness of Spintronic-Based Logic Circuits" - Pegah Iranfar et al., 2024
* "Private Circuits: Securing Hardware against Probing Attacks" - Yuval Ishai, Amit Sahai, and David Wagner, 2003
* "NEUROSEC: FPGA-Based Neuromorphic Audio Security" - Murat Isik et al., 2024
* "Toward a formal theory for computing machines made out of whatever physics offers" - Herbert Jaeger, Beatriz Noheda, and Wilfred G. Van Der Wiel, 2023
* "Spectre Attacks: Exploiting Speculative Execution" - Paul Kocher et al., 2019
* "Efficiency attacks on spiking neural networks" - Sarada Krithivasan et al., 2022
* "Deep learning side-channel attack against hardware implementations of AES" - Takaya Kubota et al., 2021
* "HIRE-SNN: Harnessing the Inherent Robustness of Energy-Efficient Deep Spiking Neural Networks by Training With Crafted Input Noise" - Souvik Kundu, Massoud Pedram, and Peter A. Beerel, 2021
* "ProtFe: Low-Cost Secure Power Side-Channel Protection for General and Custom FeFET-Based Memories" - Taixin Li et al., 2024
* "Toward robust spiking neural network against adversarial perturbation" - Ling Liang et al., 2022
* "Programming spiking neural networks on Intel’s Loihi" - Min Lin, Qiang Chen, and Shuicheng Yan, 2018
* "Network in network" - Min Lin, Qiang Chen, and Shuicheng Yan, 2013
* "Meltdown: reading kernel memory from user space" - Moritz Lipp et al., 2020
* "UnTrustZone: Systematic Accelerated Aging to Expose On-chip Secrets" - Jubayer Mahmod and Matthew Hicks, 2024
* "Clones of the Unclonable: Nanoduplicating Optical PUFs and Applications" - E. Marakis et al., 2022
* "Is spiking secure? a comparative study on the security vulnerabilities of spiking and deep neural networks" - Alberto Marchisio et al., 2020
* "Novel Hybrid CMOS/Memristor Implementation of the AES Algorithm Robust Against Differential Power Analysis Attack" - Massoud Masoumi, 2020
* "Physical unclonable functions (PUF) for IoT devices" - Abdulaziz Al-Meer and Saif Al-Kuwari, 2023
* "Brain-inspired computing needs a master plan" - A. Mehonic and A. J. Kenyon, 2022
* "PUF-Phenotype: A Robust and Noise-Resilient Approach to Aid Group-Based Authentication With DRAM-PUFs Using Machine Learning" - Owen Millwood et al., 2023
* "Are neuromorphic architectures inherently privacy-preserving? an exploratory study" - Ayana Moshruba,
* "System model of neuromorphic sequence learning on a memristive crossbar array" - Sebastian Siegel et al., 2023



### *Neuromorphic Computing*
* "Opportunities for neuromorphic computing algorithms and applications" - Catherine D. Schuman et al., 2022
* "A Survey of Neuromorphic Computing and Neural Networks in Hardware" - Catherine D. Schuman et al., 2017
* "Brain-inspired methods for achieving robust computation in heterogeneous mixed-signal neuromorphic processing systems" - Dmitrii Zendrikov, Sergio Solinas, and Giacomo Indiveri, 2023
* "Breaking the von Neumann bottleneck: architecture-level processing-in-memory technology" - S. Xu X. Zou and X. Chen, 2021
* "Memristor-based spiking neural networks: cooperative development of neural network architecture/algorithms and memristors" - Huihui Peng, Lin Gan, and Xin Guo, 2024
* "Hardware implementation of memristor-based artificial neural networks" - Fernando Aguirre et al., 2024

### *Spiking Neural Networks*
* "Exploring Neuromorphic Computing Based on Spiking Neural Networks: Algorithms to Hardware" - Nitin Rathi et al., 2023
* "Spiking neural networks based on two-dimensional materials" - Juan B Roldan, 2022
* "Simulation of a memristor-based spiking neural network immune to device variations" - Damien Querlioz, Olivier Bichler, and Christian Gamrat, 2011

### *Types of Threads*
* "SoK: Deep Learning-based Physical Side-channel Analysis" - Stjepan Picek et al., 2023
* "Understanding Security Threats in Emerging Neuromorphic Computing Architecture" - Chidhambaranathan Rajamanikkam et al., 2021
* "Threshold Implementations Against Side-Channel Attacks and Glitches" - Svetla Nikova, Christian Rechberger, and Vincent Rijmen, 2006
* "The EM Side—Channel(s)" - Dakshi Agrawal et al., 2003
  
### *Hardware Vulnerabilities and Countermeasures*
* "IMCE: An In-Memory Computing and Encrypting Hardware Architecture for Robust Edge Security" - Hanyong Shao et al., 2024
* "SCARE: Side Channel Attack on In-Memory Computing for Reverse Engineering" - Sina Sayyah Ensan et al., 2021
* "Deepsteal: Advanced model extractions leveraging efficient weight stealing in memories" - Adnan Siraj Rakin et al., 2022
* "Understanding Security Threats in Emerging Neuromorphic Computing Architecture" - Chidhambaranathan Rajamanikkam et al., 2021
* "More practical single-trace attacks on the number theoretic transform" - Peter Pessl and Robert Primas, 2019
* "Error Detection and Correction Codes for Safe In-Memory Computations" - Luca Parrini et al., 2024
* "A Survey of Neuromorphic Computing-in-Memory: Architectures, Simulators, and Security" - Felix Staudigl et al., 2022
* "Securing Against Side-Channel Attacks With Wide-Range In Situ Random Voltage Dithering on Async-Logic AES Engine" - Jun-Sheng Ng et al., 2024
* "FTC: A universal framework for fault-injection attack detection and prevention" - Md Rafid Muttaki et al., 2024
* "Enhancing security of memristor computing system through secure weight mapping" - Minhui Zou et al., 2022
* "Hardware functional obfuscation with ferroelectric active interconnects" - Tongguang Yu et al., 2022
* "Mercury: An automated remote side-channel attack to nvidia deep learning accelerator" - Xiaobei Yan et al., 2023
* "Blockhammer: Preventing rowhammer at low cost by blacklisting rapidly-accessed dram rows" - A Giray Yağlikçi et al., 2021
* "Hardware Trojans in eNVM Neuromorphic Devices" - Lingxi Wu et al., 2023
* "Side-channel attack analysis on in-memory computing architectures" - Ziyu Wang et al., 2023
* "Understanding Security Threats in Emerging Neuromorphic Computing Architecture" - Chidhambaranathan Rajamanikkam et al., 2021
* "NeuroHammer: Inducing bit-flips in memristive crossbar memories" - Felix Staudigl et al., 2022
* "Emerging topics in hardware security" - Mark Tehranipoor, 2021
* "NVM-Flip: Non-Volatile-Memory BitFlips on the System Level" - Felix Staudigl et al., 2024
* "Era of Sentinel Tech: Charting Hardware Security Landscapes Through Post-Silicon Innovation, Threat Mitigation and Future Trajectories" - Mamidipaka B. R. Srinivas and Konguvel Elango, 2024


### *Software Attacks and Defensive Strategies*
* "Sneaky Spikes: Uncovering Stealthy Backdoor Attacks in Spiking Neural Networks with Neuromorphic Data" - Gorka Abad et al., 2024
* "Moving Target Defense Through Approximation for Low-Power Neuromorphic Edge Intelligence" - Ayesha Siddique and Khaza Anuarul Hoque, 2024
* "Improving Reliability of Spiking Neural Networks through Fault Aware Threshold Voltage Optimization" - Ayesha Siddique and Khaza Anuarul Hoque, 2023
* "Adversarial Machine Learning Attacks and Defense Methods in the Cyber Security Domain" - Ishai Rosenberg et al., 2021
* "TBT: Targeted Neural Network Attack With Bit Trojan" - Adnan Siraj Rakin, Zhezhi He, and Deliang Fan, 2020
* "Analysis of power-oriented fault injection attacks on spiking neural networks" - Karthikeyan Nagarajan et al., 2022
* "Side-Channel Analysis of Integrate-and-Fire Neurons Within Spiking Neural Networks" - Matthias Probst, Manuel Brosch, and Georg Sigl, 2025
* "Watermarking Neuromorphic Brains: Intellectual Property Protection in Spiking Neural Networks" - Hamed Poursiami, Ihsen Alouani, and Maryam Parsa, 2024
* "Securing on-Chip Learning: Navigating Vulnerabilities and Potential Safeguards in Spiking Neural Network Architectures" - Najmeh Nazari et al., 2024
* "SCANN: Side Channel Analysis of Spiking Neural Networks" - Karthikeyan Nagarajan et al., 2023
* "Fault Injection Attacks in Spiking Neural Networks and Countermeasures" - Karthikeyan Nagarajan et al., 2022
* "HyperTheft: Thieving Model Weights from TEE-Shielded Neural Networks via Ciphertext Side Channels" - Yuanyuan Yuan et al., 2024
* "Attacking the Spike: On the Transferability and Security of Spiking Neural Networks to Adversarial Examples" - Nuo Xu et al., 2023
* "Securing Spiking Neural Networks with Genetic XOR Encryption on RRAM-based Neuromorphic Accelerator" - Kwunhang Wong et al., 2024
* "Neuroattack: Undermining spiking neural networks security through externally triggered bit-flips" - Valerio Venceslai et al., 2020
* "Robustness of spiking Deep Belief Networks to noise and reduced bit precision of neuro-inspired hardware platforms" - Evangelos Stromatias et al., 2015




### *Emeging Security Applications*
* "Defense Method Against Adversarial Example Attacks using Thermal Noise of a CMOS Image Sensor" - Yuki Rogi et al., 2024
* "Memristor Technology: Synthesis and Modeling for Sensing and Security Applications" - Heba Abunahla and Baker Mohammad, 2018
* "Efficient Implementation of Mahalanobis Distance on Ferroelectric FinFET Crossbar for Outlier Detection" - Musaib Rafiq, Yogesh Singh Chauhan, and Shubham Sahay, 2024
* "Advancing hardware security using polymorphic and stochastic spin-hall effect devices" - Satwik Patnaik et al., 2018
* "Suppression of crosstalk in row–column actuator array using regulation of ferroelectric polarization" - Jin Soo Park et al., 2023
* "Memristor-Based Security Primitives Robust to Malicious Attacks for Highly Secure Neuromorphic Systems" - Jungyeop Oh et al., 2022
* "A novel physical unclonable function (PUF) using 16 × 16 pure-HfOx ferroelectric tunnel junction array for security applications" - Junsu Yu et al., 2021
* "RRAM Random Number Generator Based on Train of Pulses" - Binbin Yang et al., 2021
* "Efficient Implementation of Mahalanobis Distance on Ferroelectric FinFET Crossbar for Outlier Detection" - Musaib Rafiq, Yogesh Singh Chauhan, and Shubham Sahay, 2024
* "A robust deep learning attack immune MRAM-based physical unclonable function" - Mohammad Javad Adel et al., 2024
* "Application of the Quasi-Static Memdiode Model in Cross-Point Arrays for Large Dataset Pattern Recognition" - Fernando Leonel Aguirre et al., 2020
* "A Survey on the Security of PUFs" - Shuqin Su et al., 2021
* "In-Memory Unified TRNG and Multi-Bit PUF for Ubiquitous Hardware Security" - Sachin Taneja, Viveka Konandur Rajanna, and Massimo Alioto, 2022
* "Hardware security primitives using passive rram crossbar array: Novel TRNG and PUF designs" - Simranjeet Singh et al., 2023


## Collaboration and Contribution
We encourage contributions from the community. For any questions or support, please reach out through: sorrentino.pablo.fa@gmail.com 
