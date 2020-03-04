## [Home](./) | [People](./people) | [**Research**](./research) | [Publication](./publication) | [About](./about) 

## Low-Power Computing 
Power efficiency has become a top priority for both high-performance computing systems (e.g., data center) and resource-constrained embedded systems (e.g., mobile/IoT device). The adverse effects of high-power consumption include an enormous emission of environmentally hostile carbon oxide, system reliability and lifetime degradation due to power-induced thermal effects, and operational cost of cloud and IoT service. To tackle this problem, our work adopts a cross-layer approach: 

*	Circuit-layer: We perform careful and detailed dynamic voltage and frequency scaling (DVFS) with an unprecedented consideration of their effects in circuit robustness to timing violations [DAC'20, TC'18, DATE'17, ICCD'16, ESL'19, CDOES+ISSS'19]. We also design approximate circuits with less power consumption [DATE'17].  

*	Architecture-layer: We propose novel computer architecture design to enable low-power processing of emerging workloads. We design FeFET-based Ternary Content Addressable Memory (TCAM) and Bloom filter to save 30% more energy on AMD GPU [DATE'18, GLSVLSI'20] for neural networks. 

*	System-layer: We propose a novel workload-aware frequency scaling approach for embedded systems [ESL'19]. 

## Big data and Machine Learning Processing
The continuous growth of big data regime and machine learning applications has posed an overwhelming increase in computing demand. How to enable high-performance/low-power/real-time processing of such emerging workloads, without sacrificing the quality of service (QoS), has, therefore, become a crucial question to computing industry. We adopt a software-hardware codesign approach to tackle this problem:

*	We design novel processing-in-memory platforms that can significantly reduce the computation overhead in deep neural networks [DATE'18, GLSVLSI'20]. 

*	We design novel detect-and-bypass hardware that can reduce redundant computations and energy consumption in deep neural networks and multimedia applications [NanoArch'19, ICESS'19]. 

*	We design novel approximate computing platforms through the use of dynamic-voltage-frequency-scaling (DVFS) for multimedia applications [DATE'17, TC'18, DAC'20]. 

## Secure/Dependable Computing Systems
Cyber-security in the digital age is a first-class concern. The ever-increasing use of digital devices, unfortunately, is facing significant challenges, due to the serious effects of security vulnerabilities, which can lead to medical data leakage, adversarial control of nuclear power plants or car hijacking. This challenge is even more pronounced in battlefields when IoT systems are more likely to be targeted by cyber-criminals or hostiles. To identify vulnerabilities in digital systems, we adopt a fuzzing-based approach to:  

*	Identify vulnerabilities from a large set of real-world software such as Google fuzzer-test-suite [ICSE'18, USENIX Security '19, TSE'19, TDSC'19]. Over 100 previously unknown vulnerabilities are discovered and are reported to the US National Vulnerability Database with unique CVE assignments. 

*	Identify vulnerabilities from industrial control system (ICS) software/protocol: 10 previously unknown vulnerabilities are discovered and 6 of which have been assigned unique CVE identifiers in the US National Vulnerability Database. [EMSOFT'19, DAC'20]
