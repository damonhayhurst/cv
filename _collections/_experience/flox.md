---
company: Flox
role: Full Stack Web Developer
from: 2020-04-01
to: 2020-11-01
tags: [WebRTC, Architecture, Containerisation, Usability]
tags: [VueJs, PlotlyJs, Python, WebRTC, Flask, GCP]
---

<!--action-points-->

- Designed and developed the web architecture, from concept to GCP production instance, that displayed live and historic video feeds and associated data and alerts from chicken sheds in a 'media player-like' interface
- Implemented WebRTC infrastructure, including private TURN servers, to retrieve and display live camera feeds
- Developed microservices and REST APIs using Python and Flask to process real-time data, schedule jobs, and push alerts via text, email, and WhatsApp.  
- Containerized the system architecture using Docker and automated the build process for production deployment.  
- Collaborated with the computer vision team to define and implement a testing framework using Pytest, ensuring system reliability.  

<!--full-description-->

Flox is an agri-tech start-up company bringing computer vision and machine learning to the poultry sector.

I built software that interfaced with Flox's machine learning technology. This technology would analyse camera streams from a chicken shed, send real-time alerts and show the farmer what is going on in the sheds. I used Python and Flask to create microservices and REST APIs that would run scheduled jobs and create, update and push real time alerts to the the database, the web interface and the farmer (through text, email, Whatsapp). I worked intensively with WebRTC (including creating private TURN servers) to retrieve the camera displays and display them within a 'media player-like' interface. I utilised Vuetify and PlotlyJs to display this live and historic data. I was solely responsible for the web architecture and developed it from concept to deployed GCP production instance in an intensive three month project.

Alongside the CTO, I helped create, build and support the system architecture. I was heavily responsible for containerising the bulk of the architecture, using Docker, and automating the the build process for production deployment. I mapped out the testing framework and spec for the entire system working closely with Pytest. I communicated with the computer vision team to support them in implementing this spec and other issues related to system architecture.