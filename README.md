<p align="center">
  <img src="assets/banner.svg" alt="Hi, I'm Matty" width="100%">
</p>

I'm a software and automation engineer and an MSc student in High-Performance Computer Systems at Chalmers University of Technology in Gothenburg, Sweden. Right now I'm on a one-year internship at Amerden in St. Augustine, Florida, where I build software for Automatic Guided Vehicles (AGVs) and work hands-on with the automation hardware. I like turning complex ideas into tools people can actually use.

<p align="center">
  <a href="https://www.linkedin.com/in/matty-jatta-b11880199/"><img src="https://img.shields.io/badge/LinkedIn-Matty%20Jatta-db2777?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://matjat23.github.io"><img src="https://img.shields.io/badge/Website-My%20American%20Year-9333ea?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
</p>

<p align="center"><img src="assets/divider.svg" alt="" width="60%"></p>

## Right now

- Building Katty for the #BuildHybridAI 2026 hackathon
- Writing software for automated guided vehicles at Amerden in Florida
- Visiting 100 US cities for My American Year
- Back at Chalmers in Gothenburg in fall 2027

<p align="center"><img src="assets/divider.svg" alt="" width="60%"></p>

## Work

At Amerden I write software for AGV systems in C#, C++ and Python, configure vehicles with Kollmorgen NDC8 and work with PLCs. Before that I spent two summers as a data analyst at Göteborg Energi, working with Python, Power BI and Microsoft Fabric.

<p align="center"><img src="assets/divider.svg" alt="" width="60%"></p>

## Projects

### Maja
My personal AI assistant. She runs fully on my laptop with a local LLM (Llama 3.1 through Ollama), answers questions from my own documents with the source file and page, and listens and talks back with faster-whisper and Piper.

She also keeps my notes and tasks, wakes up on "Hey Maja", sends reminders and can look through the webcam with a vision model. It has unit tests and CI on GitHub Actions. The long-term goal is a small robot version of her for my desk.

[Code](https://github.com/Matjat23/maja)

### spotlight.io
A photo and video search tool my team (Isak Rodung, Joshua Shiley and I) built in one weekend at the AI4Good Hackathon 2026, where we took 3rd place. We built it for the nonprofit Dreams Come True and tested it on their photos: staff describe a moment in plain words and find it in their archive, on one laptop with no cloud.

Local models describe every photo and video frame (Qwen2.5-VL), and search combines CLIP image vectors, MiniLM text vectors and BM25 keywords with Reciprocal Rank Fusion. Whisper makes what is said in videos searchable. Staff accept or correct every AI suggestion, and faces only become anonymous groups, because the photos are of children and their families.

[Code](https://github.com/Matjat23/spotlight-ai)

### Katty
Your buddy in a new country. Katty explains an official notice, like a letter from a migration agency, a tax office or a university, after hiding your personal details on your own device. My entry for the #BuildHybridAI 2026 hackathon. I have lived in Senegal, France, Sweden and the US, and every move came with letters I did not fully understand.

In desktop Chrome, Gemini Nano runs on your device, finds names, ID numbers and addresses, and my code swaps them for labels like `[NAME_1]` (without Nano, rule-based checks do this). You see side by side what will be shared and approve it. Only then does Gemini in the cloud explain what the letter asks of you, and every point quotes the sentence it comes from, which my code checks is really in the letter. Deadlines are worked out by the code, not the AI.

On 44 made-up test letters in many languages, the rule-based check kept 207 of 208 personal details out of the shared text. It is not legal advice. Built with React, Vite and Firebase AI Logic.

<p align="center">
  <img src="assets/katty-home.jpg" alt="Katty home screen" width="260">
  <img src="assets/katty-check.jpg" alt="Katty showing which personal details in a test letter stay hidden" width="260">
</p>

[Code](https://github.com/Matjat23/kamarat) · [Live](https://kamarat-hackathon.web.app)

### Closer
An app for my partner and me while we live in Florida and Sweden, to keep the small daily rituals of a shared home going. An arc on the home screen runs from St. Augustine to Gothenburg with a heart moving along it as the days until I am home go by, and two small characters that look like us show what the other one is doing right now.

We also use it for a shared streak, a Sunday check-in with our own questions, a shared calendar and a wish list. It is a React and Vite web app on Firebase (Firestore, Google sign-in, security rules that only let the two of us in), installed on our phones. The code is private.

### My American Year
A website I built to document my year in the US, one chapter per city, with the goal of visiting 100 cities. It is a single page in plain HTML, CSS and JavaScript with an interactive map (D3), video loops, a photo viewer and English, Swedish and French. A small Python pipeline resizes my photos, strips GPS data and makes WebP thumbnails and share images for every chapter.

<a href="https://matjat23.github.io"><img src="assets/my-american-year.jpg" alt="My American Year start page" width="100%"></a>

[Code](https://github.com/Matjat23/Matjat23.github.io) · [Live](https://matjat23.github.io)

### MediCall
A Flutter app that connects elderly patients at home with mobile care teams, built with Stanford Biodesign Digital Health and Sahlgrenska University Hospital.

<p align="center"><img src="assets/divider.svg" alt="" width="60%"></p>

## Awards and thesis

I won my track at the SSEN 2026 Hackathon at Chalmers, and my bachelor's thesis used regression on crash data (CISS) to study gender differences in traffic safety.

<p align="center"><img src="assets/divider.svg" alt="" width="60%"></p>

## Tools I use

<p align="center">
  <img src="https://img.shields.io/badge/Python-be185d?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-7e22ce?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/C++-c026d3?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/JavaScript-a21caf?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript">
  <img src="https://img.shields.io/badge/SQL-9d174d?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PLC-86198f?style=for-the-badge" alt="PLC">
  <img src="https://img.shields.io/badge/React-db2777?style=for-the-badge&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Firebase-9333ea?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase">
  <img src="https://img.shields.io/badge/FastAPI-be185d?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Flutter-7e22ce?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Ollama-c026d3?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/Power_BI-a21caf?style=for-the-badge&logo=powerbi&logoColor=white" alt="Power BI">
  <img src="https://img.shields.io/badge/Microsoft_Fabric-9d174d?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft Fabric">
  <img src="https://img.shields.io/badge/Git-86198f?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

<p align="center"><img src="assets/divider.svg" alt="" width="60%"></p>

## About me

I speak French, Swedish, English and Wolof. I care about accessible design, clear documentation and learning by building, and I'm involved in women in tech communities like Chalmers Women's Association. Outside of tech I run (two half-marathons so far), hike, read and collect cities.
