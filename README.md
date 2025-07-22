PASTA Threat Model – Sneaker Company App

Overview
This project presents a full threat model for a sneaker resale mobile application using the PASTA (Process for Attack Simulation and Threat Analysis) framework. The model walks through each stage, from defining business requirements to recommending security controls, with a focus on data protection and real-world vulnerability scenarios.

Objective
To analyze the app’s architecture and identify risks related to user authentication, data storage, transaction handling, and integration with third-party services. The goal is to implement layered controls that reduce the chances of breaches or abuse.

Technologies Analyzed
SQL – Handles storage and retrieval of sensitive data like user accounts and sales records.
API – Connects internal processes and external platforms such as payment gateways.
PKI (RSA/AES) – Enables encrypted data exchange and secure communication.
SHA-256 – Hashes confidential values including passwords and card numbers.

Threats and Vulnerabilities
Threats: Social engineering, malware infection, injection attacks, session hijacking.
Vulnerabilities: Insecure coding practices, broken authentication, weak query protections, poor API token handling.

Security Controls Recommended
1. Parameterized SQL Queries
2. Multi-Factor Authentication (MFA)
3. Secure API Authentication & Validation
4. Employee Security Awareness Training

 Reflection
This exercise helped me understand how each technology introduces different risks, and how threat modeling guides practical mitigation strategies. Building this model step by step strengthened my confidence in identifying realistic threats and structuring defenses that reflect both technical and human factors.
