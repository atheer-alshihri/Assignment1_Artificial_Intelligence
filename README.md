# Assignment1_Artificial_Intelligence
Assignment_Design and Implementation of an AI Driven Adoptive Honeypot for Cyber Threat Detection
Cyber threats continue to evolve in complexity and frequency, traditional
security solutions such as firewalls and intrusion detection systems are often
insufficient to detect and mitigate advanced persistent threats. Honeypots have emerged
as a valuable tool in cybersecurity, designed to lure attackers and study their behavior
by simulating vulnerable systems. However, conventional honeypots suffer from
limitations such as static configurations and predictable responses, making them less
effective against sophisticated adversaries.
This paper proposes the design and implementation of an adaptive honeypot system
powered by artificial intelligence (AI), capable of dynamically adjusting its behavior in
response to attacker interactions. The system leverages a high-interaction applicationlevel
honeypot deployed on VMware Workstation, with backend data collection and
visualization facilitated by the Modern Honeypot Network (MHN) platform. Dionaea
honeypots were used to capture malware samples and log attack vectors, while machine
learning models—specifically reinforcement learning—were proposed to enhance
deception techniques based on real-time threat data.
Simulation and deployment were conducted using both local virtual machines and
cloud environments via Google Cloud Platform (GCP), offering scalability and
flexibility. Evaluation metrics focused on attacker engagement time, system
adaptability, and detection precision. Results demonstrated that the adaptive honeypot
outperformed static models in terms of maintaining attacker interaction and collecting
richer behavioral data.
Future work will focus on integrating advanced machine learning algorithms for real-time threat classification, personalized deception strategies based on attacker profiling, and automated incident response mechanisms. These advancements aim to establish a more robust, intelligent, and proactive defense layer in modern cybersecurity infrastructures.
