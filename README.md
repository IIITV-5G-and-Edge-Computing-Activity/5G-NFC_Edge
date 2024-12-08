# **NFCare: Proof of Help**

**NFCare** leverages **NFC technology**, **5G connectivity**, **Edge Computing**, and **blockchain attestation** to create a real-time, verifiable system for tracking assistance and building reputation in large-scale events like hackathons, conferences, and relief operations.

---
## **Group Members**
- Aditya Chaplot (202151005)
- Akshat Patel (202151014)
- Kalp Patel (202151109)
- Pratyaksha Tailor (202151118)
- Anmol Wadhwani (202151178)

## **System Overview**

### **1. Request Help**
- Attendees tap their **NFC tags or wristbands** on an **RC522 reader** connected to an **ESP8266 WiFi module**.
- The **5G-integrated backend**, deployed on an **Edge network**, instantly notifies mentors with:
  - User’s name and seating location.
  - Social handle for direct communication.

### **2. Assistance and Attestation**
- Mentors provide help, and attendees tap the mentor’s **ARX Halo NFC badge** to:
  - Generate a **Proof of Help**, signed with the mentor’s **Ethereum address**.
  - The signature and request details are attested using the **Sign Protocol** on the blockchain, creating a tamper-proof record.

### **3. Reputation and Feedback**
- Attendees rate mentors post-assistance.
- Ratings are aggregated on **Edge-deployed MongoDB servers**, calculating a **Reputation Score** based on non-zero ratings, rewarding mentors for their efforts.

---

## **Tech Specifications**

### **Hardware**
- **RC522 RFID Reader**: Reads NFC tags and badges.
- **ESP8266 WiFi Module**: Transmits data to the backend over a **5G-ready network** for low-latency communication.
- **ARX Halo NFC Chips**: Securely embed Ethereum addresses for signature generation.

### **Network and Infrastructure**
- **5G Integration**: Ensures seamless data transmission even in high-density or remote areas.
- **Edge Computing**: Reduces latency by processing help requests and ratings closer to the event location, enabling real-time responsiveness.

### **Software**
- **Backend**: Node.js with MongoDB for decentralized data management.
- **Blockchain**: **Sign Protocol** for on-chain attestation of "Proof of Help."
- **Frontend**: JavaScript and HTML for user interaction.

---

## **Key Features**
- **Low-Latency Communication**: **Edge computing and 5G** ensure real-time help request handling, even in large-scale events.
- **Scalable and Affordable**: NFC tags and wristbands are cost-effective and widely adopted at events.
- **Decentralized Validation**: Blockchain attestation provides verifiable records of interactions.
- **Reputation System**: Mentor performance is transparently tracked and incentivized through ratings.
- **Resilient Connectivity**: 5G ensures uninterrupted operation in urban or remote areas.

---

**NFCare harnesses the power of **5G** and **Edge Computing** to deliver a scalable, verifiable, and real-time "Proof of Help" system, redefining how collaboration is tracked and rewarded.**
