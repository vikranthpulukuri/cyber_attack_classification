# cyber_attack_classification

In the rapidly evolving landscape of cyber threats, traditional methods of detecting 
cyber-attacks, which often rely solely on network traffic analysis, may fall short in 
addressing the complexities of modern attacks. This project, Integrating Network 
Traffic and System Information for Enhanced Cyber Attack Classification, bridges this 
gap by combining insights from both network traffic and system-level metrics to 
improve the accuracy and scope of Intrusion Detection Systems (IDS). 

The proposed methodology involves creating a comprehensive dataset using 
cybersecurity tools like Wireshark, CIC-Flowmeter, Performance Monitor and 
Metasploit, and combining network data (like source port, destination port, protocol) 
with system metrics (like memory utilization, CPU utilization) through temporal 
alignment. Pre-processed data is then used to train machine learning models such as 
Decision Trees, Random Forest, XGBoost, K Nearest Neighbors, and Naïve Bayes for 
multi-class classification, including normal and attack scenarios. Initial results indicate 
good accuracy level of 86.59% for XGBoost, with further work planned on 
implementing deep learning models to improve detection rates not just by considering 
the values of features but also the attack patterns using temporal data. 

This research addresses gaps in the literature by combining multiple data sources and 
utilizing updated datasets, offering a novel approach to tackling modern cyber threats.
