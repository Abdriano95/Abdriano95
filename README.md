<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Abdulla Mehdi, Gothenburg, Sweden. BSc in Informatics, aiming for IT security." width="100%">
</picture>

**I have a BSc in Informatics and I am aiming for IT security. My thesis finds personal data in Swedish text with a language model that runs locally.**

I graduated from the University of Borås in June 2026. My thesis project, Aegis, is a Python pipeline that classifies personal data and sensitive personal data under the GDPR in Swedish free text. A fellow student and I built it in layers: regex with checksums for identifiers like personal identity numbers, spaCy for names, places and organisations, and a language model running locally via Ollama for the sensitive categories the first two layers cannot judge, because the text is not allowed to leave the organisation. The degree also included a Cybersecurity course, where I picked up the basics of networks, firewalls and IPS/IDS. Outside the thesis most of my code is C# and .NET, with ASP.NET Core APIs on EF Core and clients in Blazor, .NET MAUI and WPF.

I have been at Volvo Cars since 2021, with study leave from September 2023 to June 2026 for the degree. On the engine assembly line I am an assembly technician and a trained mentor for new colleagues, and since August 2026 also deputy team leader. That role is about keeping the shift running: I lead the morning meeting, plan and follow up the day's work, and when an alarm or a stop comes in on the line I deal with it and bring in maintenance if the fault needs them.

On TryHackMe I have finished the Complete Beginner Introduction module and am working through the rest of the Complete Beginner path, with SOC Level 1 as the goal. Next to it I am reading Computer Security Fundamentals. Open to SOC analyst, security analyst and similar roles in IT security, in the Västra Götaland region or remote.

[![Email](https://img.shields.io/badge/Email-abdulla.mehdi%40proton.me-6D4AFF?logo=protonmail&logoColor=white)](mailto:abdulla.mehdi@proton.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdulla--mehdi-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulla-mehdi)
[![Website](https://img.shields.io/badge/Web-abdullamehdi.com-24292F)](https://abdullamehdi.com)

Swedish and English (fluent), Arabic (native).

## Selected work

| Project | What it is and what to look at |
|---|---|
| **[Aegis](https://github.com/Abdriano95/aegis)**<br><sub>Python · thesis</sub> | Bachelor's thesis with Johanna Gull. Finds personal data (GDPR art. 4) and sensitive personal data (art. 9) in Swedish free text in layers: regex with checksums, spaCy NER and a local LLM via Ollama. Every finding records which layer and rule produced it. F1 86.9% on 159 synthetic test texts. [Thesis in DiVA](https://urn.kb.se/resolve?urn=urn:nbn:se:hb:diva-36126) |
| **Viskan VEA**<br><sub>Python · .NET 8 · NDA</sub> | Collaboration with Viskan Systems, an e-commerce company in Borås, in a team of eight. I was test lead and a backend and ML developer: an ML training pipeline in Python and FastAPI, the VEA.Campaign microservice in .NET 8, and Docker and Kubernetes with CI. The code is under NDA. |
| **[MeTube](https://github.com/Abdriano95/MeTube)**<br><sub>C# · .NET 9 · group</sub> | Video platform with a Blazor WebAssembly client and an ASP.NET Core Web API (EF Core, JWT, Azure Blob Storage). In 2026 I replaced the plain-text passwords with salted PBKDF2 hashes from ASP.NET Core's `PasswordHasher` and moved the JWT key to configuration, with tests. |
| **[VIBE](https://github.com/Abdriano95/VIBE-ConcertBookingApp)**<br><sub>C# · .NET 8 and 9</sub> | Concert booking with a .NET MAUI app and an ASP.NET Core Web API on SQL Server. BCrypt password hashing, a global exception middleware and 41 passing xUnit tests. |
| **[Prompt router](https://github.com/Abdriano95/c1tai1-lab2-prompt-router)**<br><sub>Python · LangChain · course lab</sub> | An agent workflow that checks each prompt for personal data with regex rules and masks it, then picks which LLM answers based on how sensitive the prompt is. |
| **[Käll-Koll på läget](https://github.com/Jozelle/KallkollPaLaget)**<br><sub>React · TypeScript · hackathon</sub> | Detective browser game about source criticism, built by five people in two days at Borås Tech Challenge 2026. I built most of the drag-and-drop evidence board. |
| **[Bilverkstad](https://github.com/Abdriano95/Bilverkstad-CarWorkshopManagementSystem)**<br><sub>C# · WPF · group of two</sub> | Car workshop management system in WPF with MVVM, a layered structure and EF Core, built in six weeks with 272 pull requests. |

## Awards and mentoring

- **Borås Tech Challenge 2026:** Best Student Contribution for Käll-Koll på läget ([news](https://www.hb.se/om-hogskolan/aktuellt/nyhetsarkiv/2026/maj/spel-som-gor-skillnad-i-boras-tech-challenge-2026/))
- **Borås Tech Challenge 2025:** Best Student Contribution and Best Pitch for the Unity game The Samaritan ([game](https://abdriano.itch.io/the-samaritan), [news](https://www.hb.se/om-hogskolan/aktuellt/nyhetsarkiv/2025/maj/samhallsnytta-i-fokus-nar-arets-vinnare-av-boras-tech-challenge-utsags/))
- Student mentor at the university's programming club from 2024 to 2026, with weekly C# and Python drop-ins.

## Stack

**Security:** cybersecurity basics (networks, firewalls, IPS/IDS) from the Cybersecurity course, OWASP Top 10 (self-study), Linux (Fedora), TryHackMe (Complete Beginner path, Complete Beginner Introduction module done)<br>
**C# and .NET:** ASP.NET Core Web API, Entity Framework Core, SQL Server, Blazor WebAssembly, .NET MAUI, WPF, xUnit, Moq<br>
**Python:** spaCy, Ollama, LangChain, FastAPI, pytest<br>
**Other:** Docker, Kubernetes, GitHub Actions, Azure Blob Storage, React, TypeScript, Unity, Git
