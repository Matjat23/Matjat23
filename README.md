# Hi, I'm Matty

I'm a software and automation engineer and an MSc student in High-Performance Computer Systems at Chalmers University of Technology in Gothenburg, Sweden. Right now I'm on a one-year internship at Amerden in St. Augustine, Florida, where I build software for Automatic Guided Vehicles (AGVs) and work hands-on with the automation hardware. I like turning complex ideas into tools people can actually use.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Matty%20Jatta-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matty-jatta-b11880199/)
[![Website](https://img.shields.io/badge/Website-My%20American%20Year-e8784a?style=flat)](https://matjat23.github.io)

## Projects

**[Maja](https://github.com/Matjat23/maja)** is my personal AI assistant. She runs fully on my laptop with a local LLM (Llama 3.1 through Ollama), keeps my notes and tasks, answers questions from my own documents with the source file and page, listens and talks back (faster-whisper and Piper), wakes up on "Hey Maja", sends reminders and can look through the webcam with a vision model. It has unit tests and CI on GitHub Actions. The long-term goal is a small robot version of her for my desk.

**[My American Year](https://matjat23.github.io)** ([code](https://github.com/Matjat23/Matjat23.github.io)) is a website I built to document my year in the US, one chapter per city, with the goal of visiting 100 cities. It is a single page in plain HTML, CSS and JavaScript with an interactive map (D3), video loops, a photo viewer and a language switch for English, Swedish and French. Behind it is a small Python pipeline that resizes my photos, strips GPS data and makes WebP thumbnails and share images for every chapter.

**[Kamarat](https://github.com/Matjat23/kamarat)** ([try it](https://kamarat-hackathon.web.app)) is my entry for the #BuildHybridAI 2026 hackathon. I have lived in Senegal, France, Sweden and the US, and every move came with letters I did not fully understand. The usual fix is to paste the letter into a chatbot, together with your name, your ID number and your address. Kamarat splits the work between two models instead. In desktop Chrome, Gemini Nano runs on your own device, finds the personal details and my code swaps them for labels like `[NAME_1]` (without Nano, rule-based checks do this). You see side by side what will be shared and approve it. Only then does Gemini in the cloud explain what the letter asks of you, and every point quotes the sentence it comes from, which my code checks is really in the letter. Deadlines are worked out by the code, not the AI, with weekends and business days per country. On 44 made-up letters in many languages and formats, the rule-based check kept 207 of 208 personal details out of the shared text. It is not legal advice. It shows you exactly what leaves your device and where every answer comes from. Built with React, Vite and Firebase AI Logic.

**[spotlight.io](https://github.com/Matjat23/spotlight-ai)** is a photo and video search tool my team (Isak Rodung, Joshua Shiley and I) built in one weekend at the AI4Good Hackathon 2026, where we took 3rd place. It helps the nonprofit Dreams Come True find moments in their archive by describing them in plain words. Local models describe every photo and video frame (Qwen2.5-VL), and search combines CLIP image vectors, MiniLM text vectors and BM25 keywords with Reciprocal Rank Fusion. Whisper makes what is said in videos searchable. Everything runs on one laptop, staff accept or correct every AI suggestion, and faces only become anonymous groups, because the photos are of children and their families.

**MediCall** is a Flutter app that connects elderly patients at home with mobile care teams, built with Stanford Biodesign Digital Health and Sahlgrenska University Hospital.

I also won my track at the SSEN 2026 Hackathon at Chalmers, and my bachelor's thesis used regression on crash data (CISS) to study gender differences in traffic safety.

## Work

At Amerden I write software for AGV systems in C#, C++ and Python, configure vehicles with Kollmorgen NDC8 and work with PLCs. Before that I spent two summers as a data analyst at Göteborg Energi, working with Python, Power BI and Microsoft Fabric.

## Tools I use

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PLC](https://img.shields.io/badge/PLC-555555?style=for-the-badge)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## About me

I speak French, Swedish, English and Wolof. I care about accessible design, clear documentation and learning by building, and I'm involved in women in tech communities like Chalmers Women's Association. Outside of tech I run (two half-marathons so far), hike, read and collect cities.
