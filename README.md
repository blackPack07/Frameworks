# 🚀 Multi-Tool Test Automation & Performance Engineering Portfolio

## 📌 Overview
Welcome to my centralized test engineering portfolio. This repository serves as a showcase of production-ready test automation and performance testing frameworks that I have built. Coming from a functional UI and API automation background, this project documents my journey in mastering diverse testing methodologies, setting up quality gates, establishing performance SLAs, and generating stakeholder-friendly metrics.

Rather than scattering my work across isolated repositories, this unified ecosystem highlights my adaptability across different programming languages (JavaScript, Python) and testing tools.

---

## 📂 Repository Architecture
The repository is modularly structured by tool. Each directory contains self-contained frameworks with their own configurations and documentation:

```text
📂 Frameworks (Root)
│
├── 📂 performance-k6/          # JavaScript-based API Load Testing (Grafana k6)
│   ├── gtm.js                 # Baseline API validation
│   ├── RampUpDown.js          # Traffic curves & scaling simulations
│   ├── Thresholds.js          # SLA enforcement & quality gates
│   └── TrafficDistribution.js # Advanced VU scenario distribution
│
├── 📂 performance-locust/      # Python-based Distributed Load Testing (Locust)
│   ├── locustfile.py          # User behavior & task sets
│   └── EncDecription.py/      # Custom cryptographic utilities for secure test data
│
└── 📂 functional-ui-api/       # (Future Slot for Playwright / Selenium / RestAssured)

---
## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
