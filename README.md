## Hi, I'm Fernando

I'm a software engineer who builds systems, from mobile apps to radio receivers and firmware, and secures them.

- Active-duty U.S. Coast Guard electronics technician
- B.S. Software Engineering, Western Governors University (WGU)
- Next: WGU M.S. Computer Science (starting January 2027), then M.S. Cybersecurity and Information Assurance

My portfolio has two tracks that tell one story: build real systems, then break and defend them.

### Software engineering

| Project | What it shows | Status |
|---|---|---|
| **[fleet-ops-ios](https://github.com/fernandojcardenas/fleet-ops-ios)** | SwiftUI + Firebase fleet-maintenance app, live on the App Store and used daily by a rental business. It has Firestore security rules hardened to a staff allowlist with 28 emulator tests, a STRIDE threat model, and CI with a secrets scan and iOS build. | ✅ Shipped |
| **[maritime-tracker](https://github.com/fernandojcardenas/maritime-tracker)** | Real-time vessel tracking in C++20 on public AIS data, with a live browser map. A fuzzed decoder for untrusted radio messages, live ingest, a Kalman-filter tracker, anomaly detection, COLREGs collision risk and a benchmarked spatial index, served over its own WebSocket server and shipped as a Docker image. Every result is measured on real Norwegian and Danish traffic and re-checked in CI. | ✅ Done |
| vessel-anomaly-ml | Learned vessel-trajectory anomaly model trained on public AIS data, measured against maritime-tracker's rule-based detector | Planned, 2027 |
| secure-sensor-node | ESP32-S3 sensor node with secure boot, flash encryption and signed OTA updates | Planned, 2028 |

### Cybersecurity

| Project | What it shows | Status |
|---|---|---|
| **[owasp-top10-ci-pipeline](https://github.com/fernandojcardenas/owasp-top10-ci-pipeline)** | Flask app with 7 seeded OWASP Top 10 (2021) vulnerabilities, each exploited and fixed with a documented write-up, plus a SAST/SCA/DAST pipeline on every push | ✅ Done |
| **[flagship2-cloud-security-pipeline](https://github.com/fernandojcardenas/flagship2-cloud-security-pipeline)** | Terraform AWS baseline with six seeded misconfigurations, exploit-and-fix write-ups, and a Checkov/tfsec/gitleaks/Prowler pipeline | 🚧 In progress |
| Detection engineering | Detections written, tested and versioned as code | Planned, 2028 |
| AI/LLM security | Red-teaming an LLM feature against the OWASP Top 10 for LLM applications | Planned, 2028 |

Connect with me on [LinkedIn](https://www.linkedin.com/in/fernandoelicardenas).

