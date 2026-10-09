## Hi, I'm Fernando

I'm a software engineer who builds systems, from mobile apps and real-time C++ to LLM inference and embedded vehicle networks, and secures them.

- Active-duty U.S. Coast Guard electronics technician
- B.S. Software Engineering, Western Governors University (WGU)
- Next: WGU M.S. Computer Science (starting January 2027), then M.S. Cybersecurity and Information Assurance

My portfolio has two tracks that tell one story: build real systems, then break and defend them.

### Software engineering

| Project | What it shows | Status |
|---|---|---|
| **[fleet-ops-ios](https://github.com/fernandojcardenas/fleet-ops-ios)** | SwiftUI + Firebase fleet-maintenance app, live on the App Store and used daily by a rental business. It has Firestore security rules hardened to a staff allowlist with 28 emulator tests, a STRIDE threat model, and CI with a secrets scan and iOS build. | ✅ Shipped |
| **[maritime-tracker](https://github.com/fernandojcardenas/maritime-tracker)** | Real-time vessel tracking in C++20 on public AIS data, with a live browser map. A fuzzed decoder for untrusted radio messages, live ingest, a Kalman-filter tracker, anomaly detection, COLREGs collision risk and a benchmarked spatial index, served over its own WebSocket server and shipped as a Docker image. Every result is measured on real Norwegian and Danish traffic and re-checked in CI. | ✅ Done |
| **[llm-inference-cpp](https://github.com/fernandojcardenas/llm-inference-cpp)** | LLM inference engine written from scratch in C++20 for open-weights models on a laptop CPU. Hardened, fuzzed model loading (safetensors and GGUF); a tokenizer whose token ids match Hugging Face on 4.5 million inputs; a forward pass that matches PyTorch layer by layer; a KV cache, sampling and a chat CLI; a thread pool + AVX2/NEON matmul; 8-bit/4-bit quantization; and an OpenAI-compatible chat completions server (streaming, request limits, Docker image), checked against llama.cpp on the same machine, weights and API shape. | ✅ Done (7 of 7 milestones) |
| **[vehicle-network-security-lab](https://github.com/fernandojcardenas/vehicle-network-security-lab)** | Security lab for heavy-vehicle networks (SAE J1939, the CAN protocol of trucks and ground vehicles) in C++20. A passive, fuzzed decoder checked against real truck traffic and an independent implementation; a simulated truck on a bit-accurate CAN bus that runs live on Linux SocketCAN; a passive intrusion detector that catches five attack types on real Kenworth traffic with no false alarms; and SecOC-style message authentication (HMAC-SHA256, anti-replay) that rejects spoof, replay and forgery outright. Next: a hardened embedded-Linux gateway (SELinux, default-deny firewall) booted in CI. No hardware needed. | 🔨 In progress (M4 of 6) |

### Cybersecurity

| Project | What it shows | Status |
|---|---|---|
| **[owasp-top10-ci-pipeline](https://github.com/fernandojcardenas/owasp-top10-ci-pipeline)** | Flask app with 7 seeded OWASP Top 10 (2021) vulnerabilities, each exploited and fixed with a documented write-up, plus a SAST/SCA/DAST pipeline on every push | ✅ Done |
| **[flagship2-cloud-security-pipeline](https://github.com/fernandojcardenas/flagship2-cloud-security-pipeline)** | Terraform AWS baseline with six seeded CIS misconfigurations, each fixed with a write-up and a regression test. Checkov (plus two custom rules), tfsec, gitleaks and a deploy to a local AWS emulator run on every push, with no AWS account needed. | ✅ Done |
| Hardened DevSecOps platform | A Kubernetes platform my own services deploy onto: hosts hardened to DISA STIGs with Ansible and measured with OpenSCAP, SBOMs, scanned and signed container images, and admission policies that block anything unsigned or non-compliant | Planned, 2026–2027 |
| RMF as code | NIST SP 800-53 controls and a machine-readable (OSCAL) system security plan validated in CI, plus a remediation tracker web app (Java/Spring Boot, PostgreSQL) fed by real scanner findings from my own projects | Planned, 2027 |
| Detection engineering | Detections written, tested and versioned as code, including a Windows Server / Active Directory lab | Planned, 2028 |
| AI/LLM security | Red-teaming an LLM app served by my own inference engine against the OWASP Top 10 for LLM applications | Planned, 2028 |

Connect with me on [LinkedIn](https://www.linkedin.com/in/fernandoelicardenas).

