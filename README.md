# NETWORK-INTRUSION DETECTION SYSTEM(NIDS)
The project proposes collecting network traffic, pre-processing it, selecting useful features, training an ML classification model, and then using that model to detect suspicious traffic and generate alert.
## Features
### Real-Time Network Monitoring
- Captures live network packets using Scapy.
- Extracts network traffic features automatically.
- Continuously analyzes incoming traffic.
  ### Intrusion Detection

Detects the following traffic categories:

| Class | Description |
|---|---|
| Normal | Legitimate network traffic |
| DoS | Denial of Service attacks |
| Probe | Network scanning and reconnaissance |
| R2L | Remote-to-Local attacks |
| U2R | User-to-Root privilege escalation attacks |

### Machine Learning Models
The system compares predictions from:
- Random Forest Classifier
- Linear Support Vector Machine (SVM)
