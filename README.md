# Sentinel-Main

## Problem Statement
Modern cybersecurity teams face an overwhelming volume of threats, making it difficult for analysts to quickly identify vulnerabilities, verify manipulated media (like deepfakes), triage alerts, and react to live network attacks in real-time without constantly context-switching between multiple disjointed tools.

## Project Description
Sentinel-Main (also known as Sentinel-X 2.0) is a comprehensive, advanced AI-driven cybersecurity command center and threat intelligence dashboard. Designed with a cyberpunk aesthetic, it acts as a unified platform for modern security monitoring and analysis. It features real-time simulated attack tracking, active threat mapping, a built-in interactive attack simulation test site, and deep integration with AI to automatically analyze code vulnerabilities, authenticate manipulated media, fact-check malicious payloads, and provide an interactive SOC chatbot assistant.

## Google AI Usage

### Tools / Models Used
- Google Gemini 1.5 Pro (`@google/genai` API)

### How Google AI Was Used
Google's Gemini 1.5 Pro model serves as the core intelligence engine within the dashboard to power our complex analysis suites:
- **Interactive Security Chatbot:** Acts as a virtual SOC analyst, allowing users to query security logs, understand active threat vectors, and receive instant mitigation strategies.
- **Deepfake & Media Authenticator:** Analyzes user-uploaded image or video frames to detect generative artifacts, metadata inconsistencies, and visual manipulations.
- **Code Vulnerability Scanner (SAST):** Performs deep static application security testing on user-provided application code to identify OWASP vulnerabilities and auto-generate secured code alternatives.
- **Fact-Checker & Payload Analyzer:** Evaluates the credibility of domains, investigates social engineering payloads, and detects potential phishing campaigns.

## Proof of Google AI Usage
Attach screenshots in a `/proof` folder:
- <!-- Add your AI proof screenshot link here, e.g., [AI Proof](./proof/ai-proof.png) -->
- [AI Integration Proof 1](./proof/ai-proof-1.png)
- [AI Integration Proof 2](./proof/ai-proof-2.png)

## Screenshots
Add project screenshots:
- <!-- Add your project screenshot link here, e.g., [Dashboard](./screenshots/dashboard.png) --><img width="1891" height="918" alt="Screenshot 2026-03-31 160329" src="https://github.com/user-attachments/assets/df453ac8-8563-470e-8f6a-d54dba824f8e" />
<img width="1919" height="863" alt="Screenshot 2026-03-31 160604" src="https://github.com/user-attachments/assets/17ea1c56-2977-4bfd-90f3-9f3adac02830" />
<img width="1889" height="558" alt="Screenshot 2026-03-31 160417" src="https://github.com/user-attachments/assets/27c04474-28d8-4978-a601-3f8349677442" />
<img width="1879" height="816" alt="Screenshot 2026-03-31 160359" src="https://github.com/user-attachments/assets/86241ac1-9920-43e5-aef9-db5838a22fe7" />

- [Dashboard Overview](./screenshots/dashboard.png)
- [Analytics Page](./screenshots/analytics.png)

## Demo Video
Upload your demo video to Google Drive and paste the shareable link here(max 3 minutes). [Watch Demo](#)

## Installation Steps

```bash
# Clone the repository
git clone <your-repo-link>

# Go to project folder
cd sentinel-main

# Install dependencies
npm install

# Run the project
npm run dev
```
