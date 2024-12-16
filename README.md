# Interstella Arena
Project Duration: November 2023 - January 2024
## Overview
Interstella Arena is a multiplayer 3D space shooter game designed to deliver an immersive and tactical combat experience. This project involved significant enhancements to the core gameplay systems to address initial challenges with control responsiveness, multiplayer synchronization, and scalability.

![image](https://github.com/user-attachments/assets/14699bb5-1cfa-42ac-b8e7-eebaf30fee28)

## Key Enhancements
### Responsive Controls and Combat Mechanics
<b>Problem </b>: The initial prototype suffered from unresponsive controls and inefficient combat mechanics during multiplayer sessions. <br>
<b>Solution </b>: Enhanced core gameplay systems using C#. This involved refining input handling and synchronization logic to ensure responsive player controls, resulting in smooth tactical combat with weapon systems and an improved player experience.
### Server-Client Synchronization
<b>Problem</b>: Server-client desynchronization led to inconsistent game states across players, affecting hit registration accuracy. <br>
<b>Solution</b>: Implemented an authoritative server architecture featuring:
<li> Lag Compensation </li>
<li>Client-Side Interpolation</li>
<li>Collider Rollback</li>  
<br>
These features ensure accurate hit detection by aligning the server's historical game state with the client's perspective at the time of firing, thereby improving hit registration accuracy and consistency. <br>

### Scalable Player Progression System
<b> Problem</b>: The player progression system required a scalable backend capable of supporting over 10,000 concurrent users. <br>
<b>Solution</b>: Architected a serverless infrastructure with adaptive capacity and partition key design to handle high throughput. This setup ensures sub-100ms response times and 99.9% availability for leaderboard updates.
## Technologies Used
<b>Programming Language</b>: C# <br>
<b>Infrastructure</b>: AWS Serverless architecture

## Notes on Source Code Availability
This project builds upon a previous game development tutorial as its foundation. Due to company policies regarding source code regulations, certain parts of the project are not included in this repository. The uploaded sections focus on demonstrating the core concepts and techniques implemented during development.
## Conclusion
The improvements made to Interstella Arena have significantly enhanced the gameplay experience by ensuring responsive controls, consistent hit registration, and a scalable backend for player progression. These advancements provide a robust framework for future development while adhering to company policies on source code sharing.

## Reference
<li>https://www.youtube.com/watch?v=VW3PkEF1Fzk&list=PLHcOLPSLOK7PNvLAdnqicE_BeqoNH7Zwz</li>
<li>https://www.youtube.com/watch?v=latgsgYKLFk</li>
<li>https://www.youtube.com/watch?v=63USal9QwCk&t=1s</li>

