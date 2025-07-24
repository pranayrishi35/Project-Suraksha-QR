# Project-Suraksha-QR
Project Suraksha QR: A Multi-Layered Security Framework for UPI
Project Suraksha QR is a high-fidelity, interactive prototype demonstrating a next-generation security architecture designed to combat UPI QR code fraud in India. This project moves beyond simple transaction monitoring to create a multi-layered, intelligent defense system that protects users from sophisticated social engineering scams.

The core mission is to shift the burden of security from the end-user to the technology, building an empathetic system that intervenes intelligently at the moment of highest risk.

Key Features & Innovations
This prototype simulates a complete, secure ecosystem with two main defense layers:

1. Proactive Trust Layer: QR Verification & Rating
A simulation of a centralized system where merchants can be verified.

Verified Badge: Legitimate merchants are displayed with a "Verified Merchant" badge and a rating, providing an immediate visual cue of trust to the user.

Trust-Based Risk Scoring: The AI risk engine automatically lowers the risk for transactions with highly-rated, verified merchants, ensuring a frictionless experience for safe payments.

2. Reactive Intelligence Layer: The Real-time Transaction Risk Engine (RTRE)
A secure, server-side API (simulated in the prototype) that analyzes every transaction for signs of fraud using a combination of transactional data and behavioral biometrics.

Intelligent Interventions: Based on the calculated risk score, the system deploys a range of context-aware interventions:

Soft Stop: A "Categorization Challenge" for medium-risk payments to make the user pause and reflect.

Hard Stop: A "Direct Challenge" for high-risk payments, forcing the user to confront the potential danger.

Time-Lock Protocol: For critical-risk transactions that a user still attempts to approve, a mandatory 30-minute "cooling-off" period is activated. This is designed to break the spell of urgency created by scammers.

Three-Factor Verification (3FV): After the cooling-off period, the user must pass a final, multi-step verification process involving the bank, email, and SMS OTPs before the payment is processed.

Technology & Security
This prototype is built with modern web technologies (HTML, Tailwind CSS, JavaScript) and demonstrates a secure, production-ready architecture.

Client-Server Simulation: The core risk engine logic is architected as a secure, server-side API to prevent client-side tampering.

MITM Defense: The API simulation includes request signing to protect against Man-in-the-Middle attacks.

Hardened Frontend: The application includes a strong Content Security Policy (CSP) to mitigate XSS and other injection vulnerabilities.
