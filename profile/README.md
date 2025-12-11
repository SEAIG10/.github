# 💬 LOCUS: AI-Driven Household Context-Awareness for Predictive Cleaning
> 25-2 Hanyang University Software Engineering Project
![Image](https://github.com/user-attachments/assets/17f12668-e4a5-44db-935b-c54b75bd7609)
## Blog
[LOCUS Blog](https://bit.ly/4pV3u68)
## 📄 Documentation
### Software Engineering Paper
- [LOCUS_SE Paper (PDF)](https://github.com/SEAIG10/Document/blob/main/LOCUS_SE.pdf)
- [LaTeX Source (.tex)](https://github.com/SEAIG10/Document/blob/main/LOCUS_SE.tex)

### AI Technical Documentation
- [LOCUS AI Technical Blog
(Notion)](https://bit.ly/44mHsRG)
- [LOCUS_AI Paper (PDF)](https://github.com/SEAIG10/Document/blob/main/LOCUS_AI.pdf)

## ✔️ Proposal
We propose LOCUS (Learning On-device Context and User-specific Schedules), a Predictive Cleaning System powered by On-device AI.

While hardware for robot vacuums has advanced, software remains "reactive," relying on rigid schedules that fail to address dynamic messes (e.g., crumbs dropped while snacking). LOCUS shifts this paradigm by establishing a "Proactive Partner" system that anticipates cleaning needs based on real-time household contexts.

Our approach focuses on three core innovations:

- Predictive Cleaning: Unlike traditional obstacle avoidance, LOCUS interprets high-level scenarios (e.g., "cooking," "dining") by integrating multi-modal data—visual context (YOLO), audio cues (YAMNet) and spatial data(ARKit). The system utilizes a proprietary TimeSyncBuffer to align these asynchronous sensor streams, feeding them into a GRU-based sequential model to predict contamination probabilities in real-time.

- Strict On-device AI: To eliminate privacy risks associated with cloud-based processing, LOCUS processes all sensitive data (images, voice) locally on the edge. No raw sensor data is transmitted to the cloud, ensuring complete data sovereignty.

- Personalized Federated Learning (FedPer): Recognizing that every home is unique, LOCUS employs the FedPer architecture. This splits the model into a shared 'Base' and a personal 'Head', allowing the AI to learn user-specific lifestyle patterns without exposing private data to the central server.
<br/><br/>



## 🔧 Architecture Design
<img width="1393" height="562" alt="image" src="https://github.com/user-attachments/assets/6db02384-1b1f-42ff-92cc-897346b7459f" />
<br/><br/>


## 🎥 Vidoes
[🔗 Click below Image 👇 🔗](유튜브 링크)
<br/>
<a href="https://www.youtube.com/watch?v=iMFx_97CZnE">
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/24cbe0f4-61b5-4900-985a-be9bd5b87b37" />
</a>
<br/><br/>

## PPT
[LOCUS.pdf](https://github.com/SEAIG10/Document/blob/main/LOCUS_PPT.pdf)


## 👫🏻 Team Members
| Name | Organization | Email |
|-------|-------|-------|
| Hanyeong Ko | Hanyang University Dept. of Information Systems Seoul, South Korea | lilla9907@hanyang.ac.kr |
| Junhyung Kim | Hanyang University Dept. of Information Systems Seoul, South Korea | combe4259@hanyang.ac.kr |
| Dayeon Lee | Hanyang University Dept. of Sports Science Seoul, South Korea | ldy21@hanyang.ac.kr |
| Seunghwan Lee | Hanyang University Dept. of Information Systems Seoul, South Korea | shlee5820@hanyang.ac.kr |
<br/>
